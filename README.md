# African street lighting contracts

Public contract award data for street lighting, solar street lights and high-mast lighting in Africa, compiled by [Solmast](https://solmast.com) from official procurement sources. Solmast supplies solar street lights, steel poles and high masts to contractors, and uses this data in its market analyses.

## Files

| File | Rows | Coverage | Source |
|---|---|---|---|
| `data/world_bank_street_lighting_awards_nigeria_kenya.csv` | 26 | Nigeria 2023-2026, Kenya 2024 | World Bank procurement notices (search.worldbank.org) |
| `data/kenya_public_lighting_contracts.csv` | 660 | Kenya 2017-2026 | Kenya Public Procurement Information Portal (tenders.go.ke) |

## Findings

- World Bank-funded solar lighting contracts in Nigeria: all 12 awards went to Nigerian companies; 9 of 12 used Request for Quotations. Analysis: https://solmast.com/nigeria-world-bank-solar-street-lights.html
- World Bank-funded KISIP II in Kenya: 8 lighting-only packages, all between KES 27.8 and 30.0 million. Analysis: https://solmast.com/kenya-30m-high-mast-solar-street-lights.html
- 660 Kenyan public lighting contracts: https://solmast.com/insights-kenya-public-lighting-contracts-analysis.html

## Method and limits

We searched the sources for street light, streetlight, street lighting, solar light, solar lamp, flood light and high mast, then read the award notices. The World Bank file keeps awards whose scope includes outdoor lighting. Where a notice has several versions, the latest is used. Prices are the published signed contract prices in the local currency and usually include installation and civil works, so they are not supply prices. Searches can miss notices worded differently. Check the original notice before relying on a row.

The Kenya file includes every award the keyword search returned, so a few rows are lightning arresters or maintenance. Filter by `tender_title` for your use.

Retrieved 5 November 2026. Updates are planned quarterly.

## Licence

Compilation: CC BY 4.0. Please cite "Solmast, African street lighting contracts". The underlying records belong to their publishers.
