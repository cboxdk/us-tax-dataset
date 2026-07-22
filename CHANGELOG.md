# Changelog

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
