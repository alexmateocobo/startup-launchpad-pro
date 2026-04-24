# CSRD-MaaS-Reporter

**Pillar:** [[mobility-data-and-compliance]]
**One-liner:** ESRS E1 sustainability reporting SaaS for Mobility-as-a-Service platform operators, transit authorities, and carsharing networks required to report GHG and modal-shift impact under CSRD's forthcoming MaaS-specific guidance.
**Shortlist score:** 26/35
**Tags:** #b2b #saas #csrd #compliance #mobility

## Problem

MaaS platforms (mobility aggregators) and large transit authorities are being pulled into CSRD reporting obligations from FY2025 as they exceed the 250 FTE or €50m revenue thresholds. ESRS E1 requires them to report on their direct Scope 1 emissions (vehicle fleet), Scope 2 (electricity for EV fleets and tram systems), and critically Scope 3 Category 11 (downstream use — the emissions of the vehicles they dispatch). For transit authorities and MaaS operators, an additional, politically significant metric is emerging: modal-shift reporting — how many car trips their service replaced. This is not yet mandated by ESRS E1 but is required by the EU Urban Mobility Framework and increasingly demanded by municipalities in public-service contracts. Existing ESG platforms cannot handle the multi-modal data complexity: a MaaS platform dispatching buses, trams, bikes, and e-scooters needs a different emissions methodology for each mode.

## Regulatory driver / Why now

- CSRD in force for first-wave companies (FY2025 reports, published 2026).
- EU Urban Mobility Framework (2021) requires municipalities to measure and report modal shift.
- Mobilitätsdatengesetz creates the data foundation (real-time ridership data) that makes emissions calculation feasible.
- Public-service contract (Verkehrsvertrag) requirements from municipalities increasingly include GHG reporting.

## Target users

- **End users:** sustainability managers, CFOs, and heads of data at MaaS platforms, transit Zweckverbände, and carsharing networks.
- **Payers:**
  - Large transit authorities (MVV, HVV, RMV): €15,000–50,000/year.
  - MaaS platforms (Jelbi, DB Connect): €8,000–25,000/year.
  - Regional carsharing networks (Stadtmobil, cambio): €3,000–8,000/year.

## Solution

A multi-modal GHG reporting platform that:
1. Ingests ridership and operational data from each transport mode (GTFS-RT, NeTEx, MDS, OCPI).
2. Applies mode-specific emission factors (UBA German national averages + operator-specific for EV fleet).
3. Calculates Scope 1, 2, 3.11 per mode and in aggregate.
4. Models modal-shift avoided emissions using regional car-ownership data and trip-substitution rates.
5. Outputs ESRS E1 evidence packs + municipality GHG reporting templates.

## Business model

- **Annual SaaS licence** by size of ridership data volume and number of modes.
- **Audit-readiness consulting** for CSRD first-year assurance.
- **Municipality reporting add-on:** urban-mobility-framework GHG template.

## Market size (top-down)

- ~400 transit Zweckverbände in Germany; ~20 MaaS platforms; ~50 regional carsharing networks.
- At €15k average ACV and 10% penetration in year 2: SAM €7m; EU TAM (similar mandates across EU transit authorities) ~€50m.

## Competitive landscape

- **Persefoni, Watershed:** ESG platforms; no multi-modal transit data integrations.
- **Modeshift Analytics (UK):** modal-shift calculator; not ESRS E1 or German market.
- **IOKI (Deutsche Bahn subsidiary):** MaaS platform; not a reporting SaaS.
- No multi-modal CSRD + modal-shift reporting platform exists for German transit.

## Moat and differentiation

- Multi-modal data ingestion from transit, micro-mobility, and carsharing backends in one platform is uniquely complex.
- UBA-calibrated German emission factors give results that German auditors and municipalities accept.
- Modal-shift model built on German travel survey data (MiD — Mobilität in Deutschland) is proprietary methodology.

## Regulatory path (RDG)

No RDG exposure: sustainability data reporting software is not a legal service.

## Key risks

- Deutsche Bahn or a large transit authority builds this in-house and open-sources it.
- CSRD scope is narrowed further, reducing the addressable market.
- Modal-shift methodology is contested by auditors, reducing confidence in the product.

## MVP and first 90 days

1. Weeks 1–3: interview sustainability teams at MVV, Stadtmobil, and one MaaS platform; map ESRS E1 methodology for transit.
2. Weeks 4–7: build a GTFS-RT + MDS data ingester and a multi-modal GHG calculator using UBA factors.
3. Weeks 8–12: deliver 2 ESRS E1 pilot reports; present to municipal client for Verkehrsvertrag GHG clause.

## Success KPIs

- ESRS E1 reports delivered at week 12 (target: 2 auditor-reviewed).
- Data sources integrated per client (target: 3 modes per client).
- Signed ARR at week 12 (target: €30,000).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 4
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 3
- **Total: 26/35**

## Stakeholders to interview in Module 2

- MVV (Münchner Verkehrsverbund), sustainability and data team.
- Bundesministerium für Digitales und Verkehr, Urban Mobility Framework team.
- Stadtmobil GmbH — carsharing CSRD obligations.
- Deloitte Germany, CSRD Transit sector assurance practice.
- Umweltbundesamt, transport emission-factor methodology team.
