# Changelog

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
