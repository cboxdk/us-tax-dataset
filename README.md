# Cbox US Tax Dataset

A single versioned JSON dataset of US sales-tax data, compiled from open,
authoritative government sources with per-record provenance: state and local
rates with effective windows, economic-nexus thresholds, and per-state SaaS
taxability — for every US state and DC.

The dataset is produced by Cbox's ETL pipeline (closed source) and published
here on every real change. **Every figure is traceable**: automated rates
carry the official source file's URL, name, sha256 and retrieval time; curated
figures carry a dated citation.

## Getting the data

```bash
# latest release
gh release download -R cboxdk/us-tax-dataset --pattern 'us-tax-dataset.json*'
shasum -a 256 -c us-tax-dataset.json.sha256
```

or fetch `us-tax-dataset.json` from this repository at a release tag. Releases
are semver-tagged; see [Versioning](#versioning). A JSON Schema describing
the artifact ships with every release (`us-tax-dataset.schema.json`) —
validate against it, and remember that additive fields are not breaking.

The ZIP+4 boundary indexes under `boundaries/` are the exception: they follow
the SSTGB's quarterly cadence rather than the release cadence, so fetch them
from `main` — see [Rooftop](#rooftop-the-zip4-boundary-indexes).

## What's inside

| Layer | Coverage | Source mode |
| --- | --- | --- |
| Local rates | 32 states (24 SST members, TX, CA, AL, IL, AK, NM, MO, AZ) | Official state files, fetched and hashed every build (AZ via a manually refreshed official file, staleness-alarmed) |
| Local rates, curated | 7 states (FL, NY, SC, VA, PA, HI, MS) | Official DOR charts/publications, curated per edition with dated citations |
| State baseline | All 50 states + DC | Curated from a dated national compilation; cross-checked against the official files on every build |
| Economic-nexus thresholds | 47 jurisdictions | Curated, dated citation per figure; staleness-alarmed |
| SaaS (`digital_service`) taxability | 40 states | Curated, dated citation; only clear determinations; staleness-alarmed |

Curated figures cannot drift silently: wherever an official file gives ground
truth the curated baseline must agree or the build aborts, and a monthly
check fails when any curated citation ages past 120 days without human
re-verification.

Every state carries an explicit `coverage` level:

- `locals` — official-file rate data for local jurisdictions.
- `state_only` — curated state-level baseline only; `baseline.localsExist`
  tells you whether local taxes exist that this dataset does not carry.
- `none` — the state levies no general sales tax (DE, MT, NH, OR).

A gap is always a stated fact, never a silence.

## Rooftop: the ZIP+4 boundary indexes

The rate records say what each authority charges. They do **not** say which ones
apply at a given address, and states differ: inside Kansas City a county record
and a city record both apply, inside Seattle only the city one does. Guessing a
rule per state is how rooftop resolution goes quietly wrong.

`boundaries/US-XX.json.gz` carries that other half for the **24 Streamlined
member states**, compiled from the SSTGB boundary files — 5.4 MB gzipped in
total, from 1.06 M source spans. They live on `main` and are refreshed on the
SSTGB's quarterly cadence, so they are *not* tied to a dataset release tag:

```bash
curl -sO https://raw.githubusercontent.com/cboxdk/us-tax-dataset/main/boundaries/manifest.json
curl -sO https://raw.githubusercontent.com/cboxdk/us-tax-dataset/main/boundaries/US-KS.json.gz
```

`boundaries/manifest.json` lists every state's byte size, sha256 **over the
gzipped bytes you actually fetch**, ZIP5 and span counts, and the provenance of
the source file — so an index verifies exactly like the rest of the dataset.

### Structure

Each index is dictionary-encoded, because the same combination of authorities
repeats across thousands of spans:

| Key | Shape | Meaning |
| --- | --- | --- |
| `sets` | `[["005","02900"], ["043"], …]` | The distinct combinations of local authority codes. Everything else references these by position. |
| `zip` | `{"66002": [[from, to, setIndex], …]}` | Spans of ZIP+4 add-ons **within one ZIP5**. |
| `ranges` | `[[zipFrom, zipTo, from, to, setIndex], …]` | Rows spanning several ZIP5s. |

### Lookup

1. Take the ZIP5 and the 4-digit add-on. Without a real `+4` you do not have a
   rooftop; do not substitute `0000`, which is a valid add-on, not a wildcard.
2. Scan `zip[zip5]` in order and take the **first** span containing the add-on.
3. Only if none matched, scan `ranges` for the first entry whose ZIP5 range and
   add-on range both contain the address.
4. Resolve the `setIndex` against `sets`. Those are the local authorities whose
   rate records apply; sum them per the state's `rateBasis`.

**Order is part of the format.** Spans are emitted narrowest-first, so "first
match" *is* "most specific match" — a state-wide `["0000","9999", n]` catch-all
sits last on purpose. If you re-serialize, sort, or load these into a structure
that does not preserve array order, you will silently get the broadest answer
instead of the right one.

Two results are not the same thing, and conflating them under-charges:

- **An empty set** (`[]`) is a real answer: no local authority applies there, the
  state rate alone is correct. Five member states index to essentially nothing
  because they levy no local sales tax at all (IN, KY, MI, NJ, RI).
- **No match** means this dataset does not carry that address. Fall back to the
  state rate knowingly — do not read it as "no local tax applies".

The other 26 states and DC are not covered here: CA and NM publish rooftop
geography as polygon services rather than boundary files, and the rest publish
nothing usable at address level.

## Rules you must honor

- **`rateBasis` decides arithmetic.** `component` states (SST, TX, AL):
  sum the applicable records. `combined` states (CA, IL): one record IS the
  all-in total — summing double-counts the state share.
- **`coverage` decides trust.** Do not treat a `state_only` baseline rate as
  the full rate where `baseline.localsExist` is true.
- **A boundary miss is not "no local tax".** In the ZIP+4 indexes an empty set
  and no match look alike and mean opposite things; see
  [Rooftop](#rooftop-the-zip4-boundary-indexes).
- **`excludedLocations` are refusals**: the source itself flags those places
  as not uniformly rateable (e.g. Illinois locations needing address-level
  resolution). Handle them explicitly.
- Records carry `effectiveFrom`/`effectiveTo`; future-dated records are
  included so you can pre-stage rate changes.
- **This dataset is not tax advice** and does not by itself constitute the
  official state databases; the provenance trail exists so you can verify
  against — or fetch — the official files where statutory reliance matters.

## Versioning

- **Patch** releases are automated data refreshes (a source file changed).
- **Minor** releases add coverage or fields. **Additive changes are not
  breaking** — new fields, coverage lists, states or sources do not bump
  `schemaVersion`, and consumers MUST ignore fields they do not recognize.
- **Major** releases bump `schemaVersion` (a breaking change: fields removed,
  renamed, or reinterpreted).

Release notes state which states' source files changed, coverage movements,
and record deltas. `CHANGELOG.md` carries the full history.

## License

Free for your own internal business use — **commercial included** — under the
[PolyForm Internal Use License 1.0.0](https://polyformproject.org/licenses/internal-use/1.0.0/);
see [LICENSE.md](LICENSE.md). Computing the taxes on your own sales is
covered. Distributing the dataset — reselling it, bundling it into a product,
or offering it (or a rate-lookup service over it) to third parties — requires
a commercial license from Cbox; open an issue in this repository to get in
touch.
