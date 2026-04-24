# Mobility Data and Compliance

**Track:** [[mobility]]

## Description

Reporting and data-integration tooling for transport operators and logistics companies required to produce auditable emissions data under CSRD, and to publish or consume standardised mobility data under AFIR and the Mobilitätsdatengesetz. Two large compliance waves are driving the market simultaneously: CSRD Scope 1 and Scope 3 reporting (first-wave companies reporting FY2025 data in 2026) and AFIR Article 20 data-publication obligations for CPOs (April 2026). For the logistics sector, the CO₂-differentiated German HGV Maut (since December 2023) makes every truck's CO₂ class financially material and CSRD-reportable, creating a data-integration opportunity between Toll Collect billing feeds and ESRS E1 evidence packs.

## Key Regulations

| Regulation | What it requires | In force |
|---|---|---|
| CSRD / ESRS E1 | Large companies must report Scope 1, 2, and 3 GHG emissions with auditable methodology | FY2025 (first wave) |
| CO₂-differentiated HGV Maut (BEHG) | German truck toll includes a CO₂ surcharge of €200/tonne CO₂e; class-based | Since December 2023 |
| AFIR Article 20 | CPOs must publish charger data in DATEX II format to national access points | 14 April 2026 |
| Mobilitätsdatengesetz | Requires transport operators to share real-time mobility data in standardised formats | 2024 |
| EU Urban Mobility Framework | Municipalities must measure and report modal shift and transport emissions | Since 2021 |
| ESRS E1 Scope 3 Categories 7 and 13 | Employee commuting and leased company-car emissions must be reported | FY2025 first wave |

## Market Size

- **HGV / logistics:** ~800,000 HGVs in Germany; ~100,000 operated by companies with CSRD obligations. At €8k average ACV and 5% penetration: SAM €8m; TAM €60m including EU logistics.
- **Fleet CSRD (Fuhrpark):** ~15,000 German companies in CSRD scope; ~8,000 with material company-car fleets. SAM €6m; TAM €50m EU.
- **MaaS / transit CSRD:** ~400 German transit Zweckverbände, ~20 MaaS platforms, ~50 regional carsharing networks. SAM €7m; EU TAM ~€50m.

## Competitive Landscape

| Player | Origin | Positioning | Gap |
|---|---|---|---|
| Toll Collect | DE | HGV Maut billing portal | Shows costs; no CO₂ optimisation or CSRD output |
| Fleetboard (Daimler Truck) / RIO (MAN) | DE | Telematics platforms | No Maut-CO₂ or CSRD integration |
| Persefoni / Watershed / Sweep | US | ESG platforms | No German fleet-leasing API integrations |
| Sphera / Normative | US/SE | Enterprise ESG | No Fuhrpark-specific workflow |
| IOKI (Deutsche Bahn) | DE | MaaS platform | Not a reporting SaaS |
| Modeshift Analytics | UK | Modal-shift calculator | Not ESRS E1 or German-localised |

## Best-in-Class Benchmarks

- **Watershed** — sets the UX and data-lineage standard for Scope 3 emissions reporting; lacking German transport integrations.
- **Toll Collect API** — the authoritative data source for German HGV CO₂ class and Maut transactions; any tool in this pillar builds on it.
- **UBA (Umweltbundesamt) Emissionsfaktoren** — the German-specific emission factors accepted by German auditors; tools must use these to be CSRD-defensible.

## Key Bodies and Resources

- [Toll Collect GmbH](https://www.toll-collect.de) — HGV Maut billing data and API
- [Bundesamt für Güterverkehr (BAG)](https://www.bag.bund.de) — Maut enforcement authority
- [Umweltbundesamt](https://www.umweltbundesamt.de) — German GHG emission-factor methodology
- [DRSC](https://www.drsc.de) — German Accounting Standards Committee (ESRS E1 interpretation)
- [Mobilithek](https://mobilithek.info) — national mobility data platform (BMDV)
- [Bundesverband Fuhrparkmanagement](https://www.fuhrparkverband.de) — fleet management association
