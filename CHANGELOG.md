# Changelog

## v0.4.3 — 2026-08-05

Coverage: 41 states with official-file local rates, 5 complete with their state rate alone, 1 state-rate-only with locals missing, 4 without a general sales tax; 19763 rate records in total.
- Source data changed in 1 state(s): US-LA.
- Rate records: +2 (now 19763).

<details>
<summary><strong>Per-state coverage & confidence matrix</strong> (all 51 jurisdictions, four planes)</summary>

| State | Confidence | Rates | Nexus | Taxability | Sourcing | Flags |
| --- | --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | destination | no taxability determinations; see state note |
| US-AL | Full | 687 records (official, component) | ✓ | 20 | destination | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | 24 | destination | see state note |
| US-AZ | Full | 146 records (official, component) | ✓ | 25 | origin | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | 23 | mixed | see state note |
| US-CO | Full | 288 records (official, component) | ✓ | 23 | destination | see state note |
| US-CT | Complete | state rate (curated, cited) | ✓ | 25 | destination | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | 22 | destination | — |
| US-DE | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | 23 | destination | see state note |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | 22 | destination | see state note |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | 24 | destination | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1325 records (official, combined) | ✓ | 23 | mixed | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 record (official, component) | ✓ | 23 | destination | see state note |
| US-KS | Full | 2146 records (official, component) | ✓ | 21 | destination | see state note |
| US-KY | Full | 1 record (official, component) | ✓ | 23 | destination | see state note |
| US-LA | Full | 431 records (official, component) | ✓ | 25 | destination | 3 locations excluded (intra-location variance) |
| US-MA | Complete | state rate (curated, cited) | ✓ | 24 | destination | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-MI | Full | 1 record (official, component) | ✓ | 24 | destination | see state note |
| US-MN | Full | 138 records (official, component) | ✓ | 23 | destination | see state note |
| US-MO | Full | 2550 records (official, combined) | ✓ | 24 | origin | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | 22 | origin | see state note |
| US-MT | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | 24 | destination | see state note |
| US-ND | Full | 406 records (official, component) | ✓ | 23 | destination | see state note |
| US-NE | Full | 277 records (official, component) | ✓ | 24 | destination | see state note |
| US-NH | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NJ | Full | 1 record (official, component) | ✓ | 23 | destination | see state note |
| US-NM | Full | 206 records (official, combined) | ✓ | 25 | destination | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | 25 | destination | see state note |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | 23 | origin | see state note |
| US-OK | Full | 1620 records (official, component) | ✓ | 23 | destination | see state note |
| US-OR | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | 23 | origin | see state note |
| US-RI | Full | 1 record (official, component) | ✓ | 24 | destination | see state note |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | 25 | destination | see state note |
| US-TN | Full | 484 records (official, component) | ✓ | 25 | origin | see state note |
| US-TX | Full | 1938 records (official, component) | ✓ | 24 | origin | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | 24 | origin | see state note |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | 24 | origin | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | 25 | destination | see state note |
| US-WA | Full | 1475 records (official, component) | ✓ | 22 | destination | see state note |
| US-WI | Full | 1924 records (official, component) | ✓ | 24 | destination | see state note |
| US-WV | Full | 102 records (official, component) | ✓ | 25 | destination | see state note |
| US-WY | Full | 26 records (official, component) | ✓ | 24 | destination | see state note |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax. Taxability is a per-category count (each a source- and benchmark-agreed determination); Sourcing is the intrastate rule. A **SOURCE DOWN** flag means the state's data was served from the committed cache because the live source is unreachable.
</details>

<details>
<summary><strong>State & baseline notes</strong> (the caveats referenced as "see … note" above)</summary>

- **US-AK** — ARSSTC remote-seller rate sheet: COMPONENT records; Alaska has no state sales tax, so borough + city records stack to the full rate. Per-jurisdiction tax caps (a separate worksheet) are not modeled — consult the ARSSTC sheet where caps matter.
- **US-AL** — Alabama DOR locality file, general sales-tax (ST/GENER) rows: COMPONENT local rates — add the 4% state rate (see baseline). Police-jurisdiction rate variants are not covered.
- **US-AR** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-AZ** — ADOR TPT rate table, retail classification (business code 017): COMPONENT records — county-level regions had the 5.6% state share subtracted from ADOR's state-inclusive regional rates; city regions stack on top. Tiered single-item variants not modeled. Arizona DOR — All Business Classifications TPT Rate Table, August 2026 (official monthly CSV; fetched by the refresh-arizona workflow from the US-egress runners because the file URL bot-walls all EU/datacenter egress)
- **US-CA** — CDTFA place rates: each record is the COMBINED all-in rate at that city or unincorporated county area (the 7.25% state share included). District boundaries within cities can vary; CDTFA's address lookup is authoritative for edge cases.
- **US-CO** — DR 1002 Colorado Sales/Use Tax Rates, July 2026 edition: COMPONENT records — add the 2.9% state rate (see baseline). County and state-collected-city records are windowed to the semiannual edition (those rates change only Jan 1/Jul 1); home-rule cities are self-collecting, may change off-cycle, and stay open-ended. Home-rule grocery ("food for home consumption") rates ship as foodDrugRate; other special-category rates (prepared food/liquor, auto rentals) are not modeled. Special-district components (e.g. RTD 1% in the Denver metro) are NOT included — their boundaries are sub-county prose, so an address inside a district pays more than the state+county+city sum; use the SUTS lookup where districts matter. Colorado DOR — DR 1002 Colorado Sales/Use Tax Rates, July 2026 edition (the official publication is a Looker Studio report embedded at tax.colorado.gov/DR1002; these CSVs are the report's own table exports via its built-in export feature)
- **US-DE** (baseline) — No general sales tax; a gross receipts tax applies to sellers.
- **US-FL** — Curated locals: Florida DOR — DR-15DSS Discretionary Sales Surtax Information for Calendar Year 2026 (R. 11/25): each county's TOTAL surtax as a component on the 6% state rate, windowed to the publication's calendar year (component surtaxes change on Jan 1; the 2026 edition itself moved Martin and Palm Beach from 1% to 0.5%). Surtax caps on single items above $5,000 are not modeled.
- **US-GA** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-HI** — Curated locals: Hawaii Department of Taxation — County Surcharge on General Excise Tax (official page; surcharges apply to activities taxed at the 4% rate)
- **US-IA** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-ID** (baseline) — Resort-city local option taxes (1-4%) exist in about a dozen cities, but many apply only to lodging, alcohol and restaurant food rather than general retail — a general-rate record would be wrong, so they are not modeled. The official scope table (tax.idaho.gov) was unreachable (connection refused) at survey time.
- **US-IN** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-KS** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-KY** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-MI** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-MN** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-MO** — DOR Sales and Use Tax Rate Tables ("July, August, September 2026"): COMBINED rates per taxing-jurisdiction combination (the 4.225% state share included); county areas carry code prefix 00000, cities their own code, each stacked with overlapping districts. The table's quarter is each record's effective window.
- **US-MS** — Curated locals: Mississippi Department of Revenue — special municipal levies (Jackson 1% on certain retail sales within corporate limits, exclusions per Notice 72-14-2; Tupelo 0.25%)
- **US-MT** (baseline) — No general sales tax; some resort-area local taxes exist.
- **US-NC** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-ND** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-NE** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-NH** (baseline) — No general sales tax.
- **US-NJ** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-NV** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-NY** — Curated locals: New York DTF — Publication 718, Sales and Use Tax Rates by Jurisdiction (2/25, effective 2025-03-01): county components derived as the published combined rate minus the 4% state rate. New York City (covering its five boroughs/counties) and Yonkers carry their own city components; other listed cities match their county's rate. MCTD-area figures include the 3/8% MCTD share. Clothing and grocery exemptions are not modeled.
- **US-OH** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-OK** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-OR** (baseline) — No general sales tax.
- **US-PA** — Curated locals: Pennsylvania Department of Revenue — Sales, Use and Hotel Occupancy Tax (official page: 6% state; 1% Allegheny County; 2% Philadelphia)
- **US-RI** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-SC** — Curated locals: South Carolina DOR — ST-575 Sales Tax Rate by Municipality (Rev. 2/5/26): county components derived as the county's unincorporated total minus the 6% state rate; Myrtle Beach adds a 1% Tourism Development tax on top of Horry County's components. Municipal rows in ST-575 match their county's rate apart from Myrtle Beach; for municipalities spanning counties the county of delivery governs. Accommodations and unprepared-food rate columns are not modeled.
- **US-SD** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-TN** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-TX** — Point-in-time snapshot for filing period "2026 - 3rd"; the Comptroller file carries no per-row effective dates and no boundary data — address-to-jurisdiction resolution for Texas needs an external source.
- **US-UT** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-VA** — Curated locals: Virginia Tax — Retail Sales and Use Tax (official rate-by-region page): regional additions on top of the statewide 5.3% (which already includes the mandatory 1% local share; see the flagged baseline). 7% = James City/Williamsburg/York; 6.3% = eight Southside/Eastern localities; 6% = Central Virginia, Hampton Roads and Northern Virginia groups; every other locality is 5.3% total. The statewide 1% grocery/hygiene rate is not modeled.
- **US-VT** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-WA** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-WI** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-WV** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
- **US-WY** — SST rate file (SSTGB Technology Guide layout): COMPONENT records — each row is ONE taxing authority's own rate, typed by `level` (county, city, special_district). The rate at an address is the state rate plus EVERY applicable local record summed, and which locals apply is defined by the companion SST BOUNDARY file, which this dataset does NOT ship. States differ: inside an incorporated city Washington assigns no county record, while Kansas assigns county AND city. Do not assume the most specific record is the whole local rate, and do not sum every record for a code — without boundary data these records are a rate catalogue keyed by jurisdiction, not an address-resolvable map.
</details>

## v0.4.2 — 2026-08-03

Coverage: 41 states with official-file local rates, 5 complete with their state rate alone, 1 state-rate-only with locals missing, 4 without a general sales tax; 19761 rate records in total.
- Source data changed in 1 state(s): US-AL.

<details>
<summary><strong>Per-state coverage & confidence matrix</strong> (all 51 jurisdictions, four planes)</summary>

| State | Confidence | Rates | Nexus | Taxability | Sourcing | Flags |
| --- | --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | destination | no taxability determinations; see state note |
| US-AL | Full | 687 records (official, component) | ✓ | 20 | destination | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | 24 | destination | — |
| US-AZ | Full | 146 records (official, component) | ✓ | 25 | origin | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | 23 | mixed | see state note |
| US-CO | Full | 288 records (official, component) | ✓ | 23 | destination | see state note |
| US-CT | Complete | state rate (curated, cited) | ✓ | 25 | destination | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | 22 | destination | — |
| US-DE | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | 23 | destination | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | 22 | destination | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | 24 | destination | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1325 records (official, combined) | ✓ | 23 | mixed | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-KS | Full | 2146 records (official, component) | ✓ | 21 | destination | — |
| US-KY | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-LA | Full | 429 records (official, component) | ✓ | 25 | destination | 3 locations excluded (intra-location variance) |
| US-MA | Complete | state rate (curated, cited) | ✓ | 24 | destination | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-MI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-MN | Full | 138 records (official, component) | ✓ | 23 | destination | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | 24 | origin | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | 22 | origin | see state note |
| US-MT | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | 24 | destination | — |
| US-ND | Full | 406 records (official, component) | ✓ | 23 | destination | — |
| US-NE | Full | 277 records (official, component) | ✓ | 24 | destination | — |
| US-NH | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NJ | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-NM | Full | 206 records (official, combined) | ✓ | 25 | destination | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | 25 | destination | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | 23 | origin | — |
| US-OK | Full | 1620 records (official, component) | ✓ | 23 | destination | — |
| US-OR | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | 23 | origin | see state note |
| US-RI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | 25 | destination | — |
| US-TN | Full | 484 records (official, component) | ✓ | 25 | origin | — |
| US-TX | Full | 1938 records (official, component) | ✓ | 24 | origin | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | 24 | origin | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | 24 | origin | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | 25 | destination | — |
| US-WA | Full | 1475 records (official, component) | ✓ | 22 | destination | — |
| US-WI | Full | 1924 records (official, component) | ✓ | 24 | destination | — |
| US-WV | Full | 102 records (official, component) | ✓ | 25 | destination | — |
| US-WY | Full | 26 records (official, component) | ✓ | 24 | destination | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax. Taxability is a per-category count (each a source- and benchmark-agreed determination); Sourcing is the intrastate rule. A **SOURCE DOWN** flag means the state's data was served from the committed cache because the live source is unreachable.
</details>

<details>
<summary><strong>State & baseline notes</strong> (the caveats referenced as "see … note" above)</summary>

- **US-AK** — ARSSTC remote-seller rate sheet: COMPONENT records; Alaska has no state sales tax, so borough + city records stack to the full rate. Per-jurisdiction tax caps (a separate worksheet) are not modeled — consult the ARSSTC sheet where caps matter.
- **US-AL** — Alabama DOR locality file, general sales-tax (ST/GENER) rows: COMPONENT local rates — add the 4% state rate (see baseline). Police-jurisdiction rate variants are not covered.
- **US-AZ** — ADOR TPT rate table, retail classification (business code 017): COMPONENT records — county-level regions had the 5.6% state share subtracted from ADOR's state-inclusive regional rates; city regions stack on top. Tiered single-item variants not modeled. Arizona DOR — All Business Classifications TPT Rate Table, August 2026 (official monthly CSV; fetched by the refresh-arizona workflow from the US-egress runners because the file URL bot-walls all EU/datacenter egress)
- **US-CA** — CDTFA place rates: each record is the COMBINED all-in rate at that city or unincorporated county area (the 7.25% state share included). District boundaries within cities can vary; CDTFA's address lookup is authoritative for edge cases.
- **US-CO** — DR 1002 Colorado Sales/Use Tax Rates, July 2026 edition: COMPONENT records — add the 2.9% state rate (see baseline). County and state-collected-city records are windowed to the semiannual edition (those rates change only Jan 1/Jul 1); home-rule cities are self-collecting, may change off-cycle, and stay open-ended. Home-rule grocery ("food for home consumption") rates ship as foodDrugRate; other special-category rates (prepared food/liquor, auto rentals) are not modeled. Special-district components (e.g. RTD 1% in the Denver metro) are NOT included — their boundaries are sub-county prose, so an address inside a district pays more than the state+county+city sum; use the SUTS lookup where districts matter. Colorado DOR — DR 1002 Colorado Sales/Use Tax Rates, July 2026 edition (the official publication is a Looker Studio report embedded at tax.colorado.gov/DR1002; these CSVs are the report's own table exports via its built-in export feature)
- **US-DE** (baseline) — No general sales tax; a gross receipts tax applies to sellers.
- **US-FL** — Curated locals: Florida DOR — DR-15DSS Discretionary Sales Surtax Information for Calendar Year 2026 (R. 11/25): each county's TOTAL surtax as a component on the 6% state rate, windowed to the publication's calendar year (component surtaxes change on Jan 1; the 2026 edition itself moved Martin and Palm Beach from 1% to 0.5%). Surtax caps on single items above $5,000 are not modeled.
- **US-HI** — Curated locals: Hawaii Department of Taxation — County Surcharge on General Excise Tax (official page; surcharges apply to activities taxed at the 4% rate)
- **US-ID** (baseline) — Resort-city local option taxes (1-4%) exist in about a dozen cities, but many apply only to lodging, alcohol and restaurant food rather than general retail — a general-rate record would be wrong, so they are not modeled. The official scope table (tax.idaho.gov) was unreachable (connection refused) at survey time.
- **US-MO** — DOR Sales and Use Tax Rate Tables ("July, August, September 2026"): COMBINED rates per taxing-jurisdiction combination (the 4.225% state share included); county areas carry code prefix 00000, cities their own code, each stacked with overlapping districts. The table's quarter is each record's effective window.
- **US-MS** — Curated locals: Mississippi Department of Revenue — special municipal levies (Jackson 1% on certain retail sales within corporate limits, exclusions per Notice 72-14-2; Tupelo 0.25%)
- **US-MT** (baseline) — No general sales tax; some resort-area local taxes exist.
- **US-NH** (baseline) — No general sales tax.
- **US-NY** — Curated locals: New York DTF — Publication 718, Sales and Use Tax Rates by Jurisdiction (2/25, effective 2025-03-01): county components derived as the published combined rate minus the 4% state rate. New York City (covering its five boroughs/counties) and Yonkers carry their own city components; other listed cities match their county's rate. MCTD-area figures include the 3/8% MCTD share. Clothing and grocery exemptions are not modeled.
- **US-OR** (baseline) — No general sales tax.
- **US-PA** — Curated locals: Pennsylvania Department of Revenue — Sales, Use and Hotel Occupancy Tax (official page: 6% state; 1% Allegheny County; 2% Philadelphia)
- **US-SC** — Curated locals: South Carolina DOR — ST-575 Sales Tax Rate by Municipality (Rev. 2/5/26): county components derived as the county's unincorporated total minus the 6% state rate; Myrtle Beach adds a 1% Tourism Development tax on top of Horry County's components. Municipal rows in ST-575 match their county's rate apart from Myrtle Beach; for municipalities spanning counties the county of delivery governs. Accommodations and unprepared-food rate columns are not modeled.
- **US-TX** — Point-in-time snapshot for filing period "2026 - 3rd"; the Comptroller file carries no per-row effective dates and no boundary data — address-to-jurisdiction resolution for Texas needs an external source.
- **US-VA** — Curated locals: Virginia Tax — Retail Sales and Use Tax (official rate-by-region page): regional additions on top of the statewide 5.3% (which already includes the mandatory 1% local share; see the flagged baseline). 7% = James City/Williamsburg/York; 6.3% = eight Southside/Eastern localities; 6% = Central Virginia, Hampton Roads and Northern Virginia groups; every other locality is 5.3% total. The statewide 1% grocery/hygiene rate is not modeled.
</details>

## v0.4.1 — 2026-07-27

Coverage: 41 states with official-file local rates, 5 complete with their state rate alone, 1 state-rate-only with locals missing, 4 without a general sales tax; 19761 rate records in total.
- Source data changed in 1 state(s): US-TX.
- Rate records: +8 (now 19761).

<details>
<summary><strong>Per-state coverage & confidence matrix</strong> (all 51 jurisdictions, four planes)</summary>

| State | Confidence | Rates | Nexus | Taxability | Sourcing | Flags |
| --- | --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | destination | no taxability determinations; see state note |
| US-AL | Full | 687 records (official, component) | ✓ | 20 | destination | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | 24 | destination | — |
| US-AZ | Full | 146 records (official, component) | ✓ | 25 | origin | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | 23 | mixed | see state note |
| US-CO | Full | 288 records (official, component) | ✓ | 23 | destination | see state note |
| US-CT | Complete | state rate (curated, cited) | ✓ | 25 | destination | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | 22 | destination | — |
| US-DE | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | 23 | destination | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | 22 | destination | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | 24 | destination | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1325 records (official, combined) | ✓ | 23 | mixed | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-KS | Full | 2146 records (official, component) | ✓ | 21 | destination | — |
| US-KY | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-LA | Full | 429 records (official, component) | ✓ | 25 | destination | 3 locations excluded (intra-location variance) |
| US-MA | Complete | state rate (curated, cited) | ✓ | 24 | destination | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-MI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-MN | Full | 138 records (official, component) | ✓ | 23 | destination | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | 24 | origin | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | 22 | origin | see state note |
| US-MT | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | 24 | destination | — |
| US-ND | Full | 406 records (official, component) | ✓ | 23 | destination | — |
| US-NE | Full | 277 records (official, component) | ✓ | 24 | destination | — |
| US-NH | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NJ | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-NM | Full | 206 records (official, combined) | ✓ | 25 | destination | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | 25 | destination | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | 23 | origin | — |
| US-OK | Full | 1620 records (official, component) | ✓ | 23 | destination | — |
| US-OR | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | 23 | origin | see state note |
| US-RI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | 25 | destination | — |
| US-TN | Full | 484 records (official, component) | ✓ | 25 | origin | — |
| US-TX | Full | 1938 records (official, component) | ✓ | 24 | origin | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | 24 | origin | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | 24 | origin | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | 25 | destination | — |
| US-WA | Full | 1475 records (official, component) | ✓ | 22 | destination | — |
| US-WI | Full | 1924 records (official, component) | ✓ | 24 | destination | — |
| US-WV | Full | 102 records (official, component) | ✓ | 25 | destination | — |
| US-WY | Full | 26 records (official, component) | ✓ | 24 | destination | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax. Taxability is a per-category count (each a source- and benchmark-agreed determination); Sourcing is the intrastate rule. A **SOURCE DOWN** flag means the state's data was served from the committed cache because the live source is unreachable.
</details>

## v0.4.0 — 2026-07-22

Coverage: 41 states with official-file local rates, 5 complete with their state rate alone, 1 state-rate-only with locals missing, 4 without a general sales tax; 19753 rate records in total.
- Content changed without a source-file change (curated overlay or compiler update).

<details>
<summary><strong>Per-state coverage & confidence matrix</strong> (all 51 jurisdictions, four planes)</summary>

| State | Confidence | Rates | Nexus | Taxability | Sourcing | Flags |
| --- | --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | destination | no taxability determinations; see state note |
| US-AL | Full | 687 records (official, component) | ✓ | 20 | destination | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | 24 | destination | — |
| US-AZ | Full | 146 records (official, component) | ✓ | 25 | origin | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | 23 | mixed | see state note |
| US-CO | Full | 288 records (official, component) | ✓ | 23 | destination | see state note |
| US-CT | Complete | state rate (curated, cited) | ✓ | 25 | destination | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | 22 | destination | — |
| US-DE | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | 23 | destination | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | 22 | destination | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | 24 | destination | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1325 records (official, combined) | ✓ | 23 | mixed | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-KS | Full | 2146 records (official, component) | ✓ | 21 | destination | — |
| US-KY | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-LA | Full | 429 records (official, component) | ✓ | 25 | destination | 3 locations excluded (intra-location variance) |
| US-MA | Complete | state rate (curated, cited) | ✓ | 24 | destination | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-MI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-MN | Full | 138 records (official, component) | ✓ | 23 | destination | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | 24 | origin | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | 22 | origin | see state note |
| US-MT | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | 24 | destination | — |
| US-ND | Full | 406 records (official, component) | ✓ | 23 | destination | — |
| US-NE | Full | 277 records (official, component) | ✓ | 24 | destination | — |
| US-NH | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NJ | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-NM | Full | 206 records (official, combined) | ✓ | 25 | destination | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | 25 | destination | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | 23 | origin | — |
| US-OK | Full | 1620 records (official, component) | ✓ | 23 | destination | — |
| US-OR | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | 23 | origin | see state note |
| US-RI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | 25 | destination | — |
| US-TN | Full | 484 records (official, component) | ✓ | 25 | origin | — |
| US-TX | Full | 1930 records (official, component) | ✓ | 24 | origin | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | 24 | origin | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | 24 | origin | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | 25 | destination | — |
| US-WA | Full | 1475 records (official, component) | ✓ | 22 | destination | — |
| US-WI | Full | 1924 records (official, component) | ✓ | 24 | destination | — |
| US-WV | Full | 102 records (official, component) | ✓ | 25 | destination | — |
| US-WY | Full | 26 records (official, component) | ✓ | 24 | destination | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax. Taxability is a per-category count (each a source- and benchmark-agreed determination); Sourcing is the intrastate rule. A **SOURCE DOWN** flag means the state's data was served from the committed cache because the live source is unreachable.
</details>

## v0.3.0 — 2026-07-22

Coverage: 41 states with official-file local rates, 5 complete with their state rate alone, 1 state-rate-only with locals missing, 4 without a general sales tax; 19753 rate records in total.

### ⚠️ Sources down — served from the committed cache
- `https://gis.data.ca.gov/api/download/v1/items/01883a79765a4afba132ba54da408d8b/csv?layers=1` — cache from 2026-07-21 (Failed to fetch https://gis.data.ca.gov/api/download/v1/items/01883a79765a4afba132ba54da408d8b/csv?layers=1 (HTTP 202 after 41 attempts).). Investigate, and find a replacement source if the outage persists.
- Content changed without a source-file change (curated overlay or compiler update).

<details>
<summary><strong>Per-state coverage & confidence matrix</strong> (all 51 jurisdictions, four planes)</summary>

| State | Confidence | Rates | Nexus | Taxability | Sourcing | Flags |
| --- | --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | destination | no taxability determinations; see state note |
| US-AL | Full | 687 records (official, component) | ✓ | 20 | destination | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | 24 | destination | — |
| US-AZ | Full | 146 records (official, component) | ✓ | 25 | origin | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | 23 | mixed | ⚠️ SOURCE DOWN — cached from 2026-07-21; see state note |
| US-CO | Full | 288 records (official, component) | ✓ | 23 | destination | see state note |
| US-CT | Complete | state rate (curated, cited) | ✓ | 25 | destination | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | 22 | destination | — |
| US-DE | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | 23 | destination | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | 22 | destination | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | 24 | destination | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1325 records (official, combined) | ✓ | 23 | mixed | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-KS | Full | 2146 records (official, component) | ✓ | 21 | destination | — |
| US-KY | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-LA | Full | 429 records (official, component) | ✓ | 25 | destination | 3 locations excluded (intra-location variance) |
| US-MA | Complete | state rate (curated, cited) | ✓ | 24 | destination | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | 23 | destination | — |
| US-MI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-MN | Full | 138 records (official, component) | ✓ | 23 | destination | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | 24 | origin | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | 22 | origin | see state note |
| US-MT | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | 24 | destination | — |
| US-ND | Full | 406 records (official, component) | ✓ | 23 | destination | — |
| US-NE | Full | 277 records (official, component) | ✓ | 24 | destination | — |
| US-NH | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-NJ | Full | 1 record (official, component) | ✓ | 23 | destination | — |
| US-NM | Full | 206 records (official, combined) | ✓ | 25 | destination | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | 25 | destination | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | 25 | destination | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | 23 | origin | — |
| US-OK | Full | 1620 records (official, component) | ✓ | 23 | destination | — |
| US-OR | n/a | no general sales tax | — | 24 | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | 23 | origin | see state note |
| US-RI | Full | 1 record (official, component) | ✓ | 24 | destination | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | 23 | destination | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | 25 | destination | — |
| US-TN | Full | 484 records (official, component) | ✓ | 25 | origin | — |
| US-TX | Full | 1930 records (official, component) | ✓ | 24 | origin | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | 24 | origin | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | 24 | origin | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | 25 | destination | — |
| US-WA | Full | 1475 records (official, component) | ✓ | 22 | destination | — |
| US-WI | Full | 1924 records (official, component) | ✓ | 24 | destination | — |
| US-WV | Full | 102 records (official, component) | ✓ | 25 | destination | — |
| US-WY | Full | 26 records (official, component) | ✓ | 24 | destination | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax. Taxability is a per-category count (each a source- and benchmark-agreed determination); Sourcing is the intrastate rule. A **SOURCE DOWN** flag means the state's data was served from the committed cache because the live source is unreachable.
</details>

## v0.2.0 — 2026-07-22

Coverage: 41 states with official-file local rates, 5 complete with their state rate alone, 1 state-rate-only with locals missing, 4 without a general sales tax; 19753 rate records in total.
- Rate records: -135 (now 19753).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | see state note |
| US-AL | Full | 687 records (official, component) | ✓ | ✓ | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | Full | 146 records (official, component) | ✓ | ✓ | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | Full | 288 records (official, component) | ✓ | ✓ | see state note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | ✓ | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | ✓ | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1325 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-LA | Full | 429 records (official, component) | ✓ | ✓ | 3 locations excluded (intra-location variance) |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | ✓ | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-MT | n/a | no general sales tax | — | ✓ | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | ✓ | see baseline note |
| US-NJ | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-NM | Full | 206 records (official, combined) | ✓ | ✓ | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | ✓ | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | ✓ | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-RI | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 484 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | ✓ | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax. A **SOURCE DOWN** caveat means the state's data was served from the committed cache because the live source is unreachable.
</details>

## v0.1.7 — 2026-07-22

Coverage: 41 states with official-file local rates, 5 complete with their state rate alone, 1 state-rate-only with locals missing, 4 without a general sales tax; 19888 rate records in total.
- Local-rate coverage gained: US-CO, US-LA.
- Source data changed in 3 state(s): US-AZ, US-CO, US-LA.
- Rate records: +717 (now 19888).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | see state note |
| US-AL | Full | 820 records (official, component) | ✓ | ✓ | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | Full | 146 records (official, component) | ✓ | ✓ | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | Full | 288 records (official, component) | ✓ | ✓ | see state note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | ✓ | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | ✓ | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1326 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-LA | Full | 429 records (official, component) | ✓ | ✓ | 3 locations excluded (intra-location variance) |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | ✓ | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-MT | n/a | no general sales tax | — | ✓ | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | ✓ | see baseline note |
| US-NJ | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-NM | Full | 206 records (official, combined) | ✓ | ✓ | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | ✓ | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | ✓ | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-RI | Full | 1 record (official, component) | ✓ | ✓ | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 485 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | ✓ | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax. A **SOURCE DOWN** caveat means the state's data was served from the committed cache because the live source is unreachable.
</details>

## v0.1.6 — 2026-07-21

Coverage: 39 states with official-file local rates, 5 complete with their state rate alone, 3 state-rate-only with locals missing, 4 without a general sales tax; 19171 rate records in total.
- Local-rate coverage gained: US-AZ.
- Source data changed in 1 state(s): US-AZ.
- Rate records: +146 (now 19171).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | see state note |
| US-AL | Full | 820 records (official, component) | ✓ | — | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | Full | 146 records (official, component) | ✓ | ✓ | see state note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | — | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | — | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1326 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-LA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | — | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | ✓ | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | — | see state note |
| US-MT | n/a | no general sales tax | — | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | — | see baseline note |
| US-NJ | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-NM | Full | 206 records (official, combined) | ✓ | ✓ | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | — | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-RI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 485 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | — | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax.
</details>

## v0.1.5 — 2026-07-21

Coverage: 38 states with official-file local rates, 5 complete with their state rate alone, 4 state-rate-only with locals missing, 4 without a general sales tax; 19025 rate records in total.
- Local-rate coverage gained: US-FL, US-MO, US-NY.
- Source data changed in 8 state(s): US-FL, US-HI, US-MO, US-MS, US-NY, US-PA, US-SC, US-VA.
- Rate records: +2676 (now 19025).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | see state note |
| US-AL | Full | 820 records (official, component) | ✓ | — | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | — | see baseline note |
| US-FL | Full (curated) | 67 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | — | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1326 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-LA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | — | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | Full | 2550 records (official, combined) | ✓ | ✓ | see state note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | — | see state note |
| US-MT | n/a | no general sales tax | — | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | — | see baseline note |
| US-NJ | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-NM | Full | 206 records (official, combined) | ✓ | ✓ | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | Full (curated) | 59 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-OH | Full | 105 records (official, component) | ✓ | — | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-RI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 485 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | — | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax.
</details>

## v0.1.4 — 2026-07-21

Coverage: 35 states with official-file local rates, 5 complete with their state rate alone, 7 state-rate-only with locals missing, 4 without a general sales tax; 16349 rate records in total.
- Local-rate coverage gained: US-SC, US-VA.
- Source data changed in 5 state(s): US-HI, US-MS, US-PA, US-SC, US-VA.
- Rate records: +86 (now 16349).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | see state note |
| US-AL | Full | 820 records (official, component) | ✓ | — | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | — | see baseline note |
| US-FL | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | — | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1326 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-LA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | — | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | — | see state note |
| US-MT | n/a | no general sales tax | — | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | — | see baseline note |
| US-NJ | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-NM | Full | 206 records (official, combined) | ✓ | ✓ | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-OH | Full | 105 records (official, component) | ✓ | — | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-RI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-SC | Full (curated) | 47 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 485 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | — | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | Full (curated) | 39 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax.
</details>

## v0.1.3 — 2026-07-20

Coverage: 33 states with official-file local rates, 5 complete with their state rate alone, 9 state-rate-only with locals missing, 4 without a general sales tax; 16263 rate records in total.
- Local-rate coverage gained: US-NM.
- Source data changed in 1 state(s): US-NM.
- Rate records: +206 (now 16263).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | see state note |
| US-AL | Full | 820 records (official, component) | ✓ | — | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | — | see baseline note |
| US-FL | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | — | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1326 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-LA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | — | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | — | see state note |
| US-MT | n/a | no general sales tax | — | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | — | see baseline note |
| US-NJ | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-NM | Full | 206 records (official, combined) | ✓ | ✓ | 41 locations excluded (intra-location variance) |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-OH | Full | 105 records (official, component) | ✓ | — | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-RI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-SC | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 485 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | — | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax.
</details>

## v0.1.2 — 2026-07-20

Coverage: 32 states with official-file local rates, 5 complete with their state rate alone, 10 state-rate-only with locals missing, 4 without a general sales tax; 16057 rate records in total.
- Local-rate coverage gained: US-AK, US-HI, US-MS, US-PA.
- Source data changed in 4 state(s): US-AK, US-HI, US-MS, US-PA.
- Rate records: +64 (now 16057).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | Full | 56 records (official, component) | ✓ | — | see state note |
| US-AL | Full | 820 records (official, component) | ✓ | — | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | — | see baseline note |
| US-FL | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | Full (curated) | 4 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-IA | Full | 1214 records (official, component) | ✓ | — | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1326 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-LA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | — | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MS | Full (curated) | 2 records (curated, cited, component) | ✓ | — | see state note |
| US-MT | n/a | no general sales tax | — | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | — | see baseline note |
| US-NJ | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-NM | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-OH | Full | 105 records (official, component) | ✓ | — | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | — | see baseline note |
| US-PA | Full (curated) | 2 records (curated, cited, component) | ✓ | ✓ | see state note |
| US-RI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-SC | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 485 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | — | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Full (curated)** = complete local coverage maintained by hand from official state pages, dated citation; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax.
</details>

## v0.1.1 — 2026-07-20

Coverage: 28 states with official-file local rates, 5 complete with their state rate alone, 14 state-rate-only with locals missing, 4 without a general sales tax; 15993 rate records in total.
- Content changed without a source-file change (curated overlay or compiler update).

<details>
<summary><strong>Per-state confidence matrix</strong> (all 51 jurisdictions)</summary>

| State | Confidence | Rates | Nexus | SaaS taxability | Caveats |
| --- | --- | --- | --- | --- | --- |
| US-AK | **Partial** | state rate only (curated, cited) | ✓ | — | local taxes exist that this dataset does not carry; see baseline note |
| US-AL | Full | 820 records (official, component) | ✓ | — | see state note |
| US-AR | Full | 576 records (official, component) | ✓ | ✓ | — |
| US-AZ | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CA | Full | 540 records (official, combined) | ✓ | ✓ | see state note |
| US-CO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-CT | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DC | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-DE | n/a | no general sales tax | — | — | see baseline note |
| US-FL | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-GA | Full | 170 records (official, component) | ✓ | ✓ | — |
| US-HI | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IA | Full | 1214 records (official, component) | ✓ | — | — |
| US-ID | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-IL | Full | 1326 records (official, combined) | ✓ | ✓ | 218 locations excluded (intra-location variance) |
| US-IN | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-KS | Full | 2146 records (official, component) | ✓ | ✓ | — |
| US-KY | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-LA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MA | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MD | Complete | state rate (curated, cited) | ✓ | — | — |
| US-ME | Complete | state rate (curated, cited) | ✓ | ✓ | — |
| US-MI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-MN | Full | 138 records (official, component) | ✓ | ✓ | — |
| US-MO | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-MS | **Partial** | state rate only (curated, cited) | ✓ | — | local taxes exist that this dataset does not carry; see baseline note |
| US-MT | n/a | no general sales tax | — | — | see baseline note |
| US-NC | Full | 106 records (official, component) | ✓ | ✓ | — |
| US-ND | Full | 406 records (official, component) | ✓ | ✓ | — |
| US-NE | Full | 277 records (official, component) | ✓ | ✓ | — |
| US-NH | n/a | no general sales tax | — | — | see baseline note |
| US-NJ | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-NM | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-NV | Full | 27 records (official, component) | ✓ | ✓ | — |
| US-NY | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-OH | Full | 105 records (official, component) | ✓ | — | — |
| US-OK | Full | 1620 records (official, component) | ✓ | ✓ | — |
| US-OR | n/a | no general sales tax | — | — | see baseline note |
| US-PA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-RI | Full | 1 records (official, component) | ✓ | ✓ | — |
| US-SC | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-SD | Full | 327 records (official, component) | ✓ | ✓ | — |
| US-TN | Full | 485 records (official, component) | ✓ | ✓ | — |
| US-TX | Full | 1930 records (official, component) | ✓ | — | see state note |
| US-UT | Full | 211 records (official, component) | ✓ | ✓ | — |
| US-VA | **Partial** | state rate only (curated, cited) | ✓ | ✓ | local taxes exist that this dataset does not carry; see baseline note |
| US-VT | Full | 37 records (official, component) | ✓ | ✓ | — |
| US-WA | Full | 1475 records (official, component) | ✓ | ✓ | — |
| US-WI | Full | 1924 records (official, component) | ✓ | ✓ | — |
| US-WV | Full | 102 records (official, component) | ✓ | ✓ | — |
| US-WY | Full | 26 records (official, component) | ✓ | ✓ | — |

Confidence legend: **Full** = official state files for local jurisdictions; **Complete** = the curated state rate is the entire rate (no local sales taxes exist); **Partial** = state rate only while local taxes exist that this dataset does not carry; **n/a** = no general sales tax.
</details>

## v0.1.0 — 2026-07-20

Coverage: 28 states with official-file local rates, 19 state-only, 4 without a general sales tax; 15993 rate records in total.

Initial data release.
