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
are semver-tagged; see [Versioning](#versioning).

## What's inside

| Layer | Coverage | Source mode |
| --- | --- | --- |
| Local rates | 28 states (24 SST member states, TX, CA, AL, IL) | Official state files, fetched and hashed every build |
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

## Rules you must honor

- **`rateBasis` decides arithmetic.** `component` states (SST, TX, AL):
  sum the applicable records. `combined` states (CA, IL): one record IS the
  all-in total — summing double-counts the state share.
- **`coverage` decides trust.** Do not treat a `state_only` baseline rate as
  the full rate where `baseline.localsExist` is true.
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

Free for noncommercial use under the
[PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/) —
see [LICENSE.md](LICENSE.md). Commercial use (including reselling the dataset
or bundling it in a paid product or service) requires a commercial license
from Cbox — open an issue in this repository to get in touch.
