# Fuhrpark-CO₂-Pilot

**Pillar:** [[unlocking-underused-vehicles]]
**One-liner:** CSRD-ready Scope 3 Category 7 (employee commuting and company car) emissions reporting SaaS for German Mittelstand, pulling data directly from fleet-leasing APIs and producing ESRS E1-compliant evidence packs.
**Shortlist score:** 30/35

## Problem

CSRD (Corporate Sustainability Reporting Directive) requires all large German companies to report Scope 3 emissions starting with fiscal year 2025 (reports due in 2026). Category 7 — employee commuting and Category 13 — downstream leased assets (company cars) — are the largest and least-automated Scope 3 categories for most Mittelstand companies. Existing ESG tools (Workiva, Persefoni, Planetly) are US-centric and do not integrate with German fleet-leasing companies (Alphabet, LeasePlan, Arval, ALD) or the local Fuhrpark management systems (Vimcar, Webfleet). Most German Mittelstand companies are attempting to calculate fleet CO₂ with spreadsheets and generic emission factors, producing non-auditable evidence. CSRD transposition in Germany was completed in 2025; first auditor reviews of Scope 3 data are happening now.

## Regulatory driver / Why now

- CSRD implementation law passed in Germany in 2025; first-wave companies (NFRD-scope, ~1,000 German companies) reporting for FY2025.
- "Stop the clock" for second and third waves reversed the delay only partially: large companies (>250 FTE, >€50m revenue) still must report for FY2026.
- ESRS E1 (Climate) is the most scrutinised standard; Scope 3 Category 7 is the biggest gap.
- EU fleet CO₂ regulation ("Greening Corporate Fleets") adds a second mandatory fleet-reporting layer.

## Target users

- **End users:** sustainability managers, CFOs, fleet managers at companies with 50+ company cars and CSRD reporting obligations.
- **Payers:**
  - First-wave Mittelstand (250–1,000 FTE): €8,000–25,000/year.
  - Large enterprise (1,000+ FTE): €40,000–100,000/year.
  - Big-4 audit firms as channel partners for their CSRD assurance practice.

## Solution

A data-integration and reporting SaaS that:
1. Connects via API to German fleet-leasing companies (Alphabet, LeasePlan, Arval, ALD) to pull vehicle, driver, and mileage data.
2. Applies GHG Protocol Scope 3 methodology with German-specific emission factors (UBA Emissionsfaktoren).
3. Calculates Category 7 (commuting), Category 11 (use of sold products, if applicable) and Category 13 (leased company cars) per ESRS E1.
4. Generates a CSRD evidence pack: data lineage, methodology note, and auditor-ready workbook.
5. Tracks year-on-year reduction trajectories against the company's decarbonisation target.

## Business model

- **Annual SaaS licence** by fleet size and reporting wave.
- **Audit-readiness consulting:** fixed-fee engagement to prepare the ESRS E1 evidence pack with an auditor.
- **Big-4 channel partnership:** revenue share on auditor-referred customers.

## Market size (top-down)

- ~15,000 German companies within CSRD scope; ~8,000 with meaningful company-car fleets.
- At €15k average ACV and 5% penetration in year 2: SAM €6m; TAM €50m including EU Mittelstand.

## Competitive landscape

- **Persefoni, Watershed, Sweep:** US-centric ESG platforms; no German fleet-leasing integrations.
- **Sphera, Normative:** enterprise ESG; no Fuhrpark-specific workflow.
- **Big-4 consulting:** manual, expensive, not scalable for Mittelstand.

## Moat and differentiation

- Proprietary API integrations with all four major German fleet-leasing companies.
- ESRS E1-native output (not a generic GHG report) built specifically for German auditors.
- Historical fleet emissions dataset across clients becomes an industry benchmark.

## Regulatory path (RDG)

No RDG exposure: sustainability data reporting is operational compliance, not legal advice. The product should note that legal interpretation of CSRD scope requires legal counsel.

## Key risks

- Major ESG platforms add German fleet-leasing integrations before market penetration.
- CSRD scope narrows further under political pressure (as happened with Omnibus package in 2025).
- Leasing companies build their own CSRD reporting modules.

## MVP and first 90 days

1. Weeks 1–3: interview 10 sustainability managers at Mittelstand companies; map the data fields available in Alphabet and LeasePlan APIs.
2. Weeks 4–7: build CSV importer + GHG Protocol Category 7/13 calculator + ESRS E1 output template.
3. Weeks 8–12: run 3 paid pilots; deliver auditor-reviewed evidence packs.

## Success KPIs

- Evidence packs delivered and auditor-reviewed at week 12 (target: 3).
- Accuracy of CO₂ calculation vs manual audit (target: <2% deviation).
- Signed ARR at week 12 (target: €45,000).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 4
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 4
- Path to 12-week PoV: 5
- Scale ceiling: 4
- **Total: 30/35**

## Stakeholders to interview in Module 2

- Alphabet Fuhrparkmanagement GmbH — fleet data API access.
- Deloitte Germany, CSRD Assurance practice.
- Bundesverband Fuhrparkmanagement e.V. — customer channel.
- Umweltbundesamt — German-specific emission-factor methodology.
- DRSC (German Accounting Standards Committee) — ESRS E1 interpretation.
