# AFIR-DataGate

**Pillar:** [[ev-charging-infrastructure]]
**One-liner:** Automated DATEX II and OCPI data-publication compliance platform for German Charge Point Operators facing the April 2026 AFIR Article 20 reporting mandate.
**Shortlist score:** 26/35

## Problem

Article 20 of the EU Alternative Fuels Infrastructure Regulation (AFIR) requires all operators of publicly accessible charging points to publish real-time static and dynamic data — location, availability, pricing, connector types — in DATEX II format to national access points (in Germany: the Mobilithek) from 14 April 2026. OCPI (Open Charge Point Interface) is the interoperability layer between CPOs and EMSPs. Most small and mid-size CPOs use charger backends (Chargepoint, EV.energy, AMPECO) that do not natively output DATEX II. The transformation, quality validation, and continuous publication pipeline must be built by each operator. Non-compliance risks loss of public funding and regulatory sanctions.

## Regulatory driver / Why now

- AFIR Article 20 data mandate enforcement date: 14 April 2026.
- ISO 15118-2 mandatory for all newly installed public AC chargers from 8 January 2026.
- Germany's Masterplan Charging Infrastructure 2030 commits to streamlining data obligations — but the baseline mandate still applies.
- Bundesnetzagentur is the competent authority; first compliance reviews expected Q3 2026.

## Target users

- **End users:** CPO technical and compliance teams.
- **Payers:**
  - Small CPOs (under 100 charging points): €300–800/month.
  - Mid-size CPOs (100–1,000 points): €1,500–4,000/month.
  - National CPO networks (EnBW, IONITY, Allego): €20–60k/year enterprise.

## Solution

A middleware SaaS that:
1. Connects to any CPO backend via OCPI 2.2.1 API.
2. Transforms real-time session and availability data into DATEX II v3.4 format.
3. Publishes continuously to the German Mobilithek and optional EU NAPs.
4. Runs a quality-validation dashboard flagging schema errors, missing mandatory fields, and stale data.
5. Generates monthly AFIR compliance evidence reports.

## Business model

- **Subscription SaaS** by number of charging points under management.
- **One-time onboarding fee** for OCPI integration with non-standard backends: €2,000–8,000.
- **EU expansion module:** additional NAP connections (Netherlands RDW, French NDW) at €500/month each.

## Market size (top-down)

- ~800 registered CPOs in Germany; ~15,000 across EU.
- At €15k average ACV for German CPOs and 20% penetration: SAM €2.4m Germany; TAM €30m EU.

## Competitive landscape

- **Gireve, Hubject:** OCPI hubs with partial data-aggregation capability, not DATEX II publishers.
- **Mobilithek direct integration:** requires technical expertise most CPOs lack.
- No dedicated AFIR Article 20 compliance SaaS exists.

## Moat and differentiation

- DATEX II schema expertise is narrow; few developers understand it.
- First published integrations for major backends (AMPECO, Chargepoint, EV.energy) create a connector library that is costly for competitors to replicate.
- EU NAP multi-connection becomes a moat as EU enforcement expands.

## Regulatory path (RDG)

No RDG exposure: data-transformation and publication software is a technical compliance tool, not a legal service.

## Key risks

- Major backends add native DATEX II export, removing the need for middleware.
- Mobilithek changes its schema, requiring continuous maintenance.
- Small CPO market consolidates; fewer operators but larger buyers.

## MVP and first 90 days

1. Weeks 1–3: map the DATEX II v3.4 schema against OCPI 2.2.1 fields; interview 5 CPOs.
2. Weeks 4–8: build OCPI → DATEX II transformer and Mobilithek publisher; run quality-validation layer.
3. Weeks 9–12: pilot with 2 CPOs, publish live data, generate first compliance evidence report.

## Success KPIs

- CPOs publishing to Mobilithek via the platform at week 12 (target: 3).
- Data quality score (target: >95% schema-valid records).
- Signed MRR at week 12 (target: €5,000).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 3
- **Total: 26/35**

## Stakeholders to interview in Module 2

- Bundesnetzagentur, Referat E5 (AFIR compliance).
- Mobilithek team, Bundesministerium für Digitales und Verkehr (BMDV).
- EnBW mobility+, Head of Data & Interoperability.
- AMPECO (CPO software vendor) — partnership opportunity.
- CharIN e.V., the industry body setting OCPI standards.
