# LKW-CO₂-Maut

**Pillar:** [[mobility-data-and-compliance]]
**One-liner:** HGV fleet CO₂ surcharge tracking, route-optimisation, and CSRD Scope 1 reporting SaaS that turns Germany's CO₂-differentiated truck toll into a decarbonisation compliance tool.
**Shortlist score:** 30/35

## Problem

Germany's HGV Maut was extended from December 2023 to include a CO₂ surcharge of €200 per tonne of CO₂e, making Germany the first country to embed a carbon price in road freight tolls. This means fleet managers must now: (1) know the CO₂ class of every truck (determined by EURO emission standard + alternative drive), (2) track route-level Maut costs including the CO₂ component, (3) report fleet CO₂ under CSRD Scope 1 using actual Maut-transaction data, and (4) plan vehicle replacement to benefit from lower-CO₂ class rates. Most logistics companies track Maut costs through the billing feed from Toll Collect, but have no tool connecting CO₂ class to route optimisation or CSRD reporting. As the CO₂ surcharge escalates over time (tied to Germany's national CO₂ price pathway), the financial incentive to optimise grows.

## Regulatory driver / Why now

- CO₂ Maut live since December 2023; surcharge rising annually per the Brennstoffemissionshandelsgesetz (BEHG).
- CSRD Scope 1 reporting mandatory for first-wave German companies for FY2025.
- EU "Fit for 55" package targets 45% reduction in HGV CO₂ by 2030 vs 2019.
- Toll Collect data API is standardised — building on existing data infrastructure.

## Target users

- **End users:** fleet managers, CFOs, sustainability managers at Spedition companies and logistics operators with more than 20 HGVs.
- **Payers:**
  - Medium Spedition (20–200 trucks): €500–1,500/month.
  - Large logistics operator (200+ trucks): €2,000–6,000/month.
  - Fleet-leasing companies (VW Truck & Bus Financial Services) as channel.

## Solution

A fleet intelligence SaaS that:
1. Connects to the operator's Toll Collect billing feed via API.
2. Classifies every truck by CO₂ class and calculates actual vs potential Maut-CO₂ cost per route.
3. Identifies replacement candidates (trucks near end-of-life where EV or LNG alternative reduces CO₂ class).
4. Produces ESRS E1-compliant Scope 1 emissions report from Maut transaction data.
5. Models the CO₂-surcharge cost trajectory for fleet planning.

## Business model

- **Subscription SaaS** per truck under management.
- **CSRD Scope 1 evidence pack:** fixed-fee annual engagement.
- **Toll Collect API integration consulting:** one-time setup fee.

## Market size (top-down)

- ~800,000 HGVs registered in Germany; ~100,000 operated by companies with CSRD obligations.
- At €8k average ACV and 5% penetration: SAM €8m; TAM €60m including EU logistics operators subject to similar toll frameworks.

## Competitive landscape

- **Toll Collect's own portal:** shows costs, no CO₂ optimisation or CSRD output.
- **Fleetboard (Daimler Truck), RIO (MAN/Traton):** telematics platforms; no Maut-CO₂ integration.
- **Sphera, Watershed:** ESG platforms; no Maut data integration.
- No Maut-CO₂ + CSRD integrated tool exists.

## Moat and differentiation

- Toll Collect API expertise + per-route CO₂ attribution is proprietary methodology.
- CSRD evidence pack anchored in actual government transaction data (Maut records) is more auditor-defensible than estimates.
- Growing dataset of CO₂-class-to-route patterns across clients enables benchmarking.

## Regulatory path (RDG)

No RDG exposure: financial and sustainability reporting software is not a legal service.

## Key risks

- Toll Collect adds CO₂ reporting natively to its operator portal.
- CO₂ surcharge rate is frozen or reduced under political pressure.
- Telematics vendors (Fleetboard, RIO) add CSRD modules.

## MVP and first 90 days

1. Weeks 1–3: obtain Toll Collect API developer access; interview 5 Spedition sustainability leads.
2. Weeks 4–7: build CO₂ class classifier, Maut cost calculator, and ESRS E1 Scope 1 template.
3. Weeks 8–12: run 3 paid pilots; deliver first CSRD Scope 1 evidence packs.

## Success KPIs

- Maut-CO₂ reports generated at week 12 (target: 5).
- Accuracy vs Toll Collect audit (target: <1% deviation).
- MRR at week 12 (target: €6,000).

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

- Toll Collect GmbH, API team.
- Bundesamt für Güterverkehr (BAG) — enforcement authority.
- Bundesverband Güterkraftverkehr Logistik und Entsorgung (BGL) — Spedition association.
- Deloitte Germany, CSRD transport-sector practice.
- MAN Truck & Bus, RIO telematics partnership opportunity.
