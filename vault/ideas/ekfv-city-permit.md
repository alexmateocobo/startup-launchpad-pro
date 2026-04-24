# eKFV-CityPermit

**Pillar:** [[shared-clean-mobility]]
**One-liner:** City-permit management and operational-zone compliance SaaS for e-scooter, e-moped, and cargo-bike sharing operators navigating Germany's fragmented Elektrokleinstfahrzeuge-Verordnung city ordinances.
**Shortlist score:** 28/35

## Problem

The Elektrokleinstfahrzeuge-Verordnung (eKFV) created the legal framework for e-scooter operations in Germany in 2019. Since then, German cities have layered city-specific ordinances on top: parking zone restrictions, fleet-size caps, Standortverbote in pedestrian zones, mandatory parking station requirements (Hamburg, Köln), and performance-based licence renewal criteria tied to data-sharing with the Verkehrsbehörde. Operators (Tier, Lime, Bolt, Dott, LINK) each have a team manually tracking city-by-city ordinance changes, preparing Antrag submissions in different formats for each Ordnungsamt, and managing monthly operational reports. A single operator managing 20 German cities employs 3–5 FTE on city compliance alone.

## Regulatory driver / Why now

- eKFV has been in force since 2019; city ordinances are multiplying and tightening (Hamburg 2024 parking mandate, Köln 2025 zone restrictions).
- German cities are moving to competitive tendering (Ausschreibung) for shared-mobility licences, adding formal RFP compliance requirements.
- EU Urban Mobility Framework (2021) and the German Nationaler Radverkehrsplan are driving cities toward performance-based permits tied to safety and parking data.

## Target users

- **End users:** regulatory affairs and city-operations teams at micro-mobility operators.
- **Payers:**
  - Tier, Lime, Bolt, Dott: €1,000–3,500/month per 10-city tier.
  - New market entrants (e-mopeds, cargo bikes): €400–800/month.

## Solution

A regulatory operations platform that:
1. Maintains a living database of eKFV ordinances and city-specific permit conditions for all 50+ German cities with shared-mobility.
2. Auto-generates city-specific Antrag documents, data-sharing agreements, and monthly operational reports.
3. Tracks permit renewal dates, performance KPIs, and compliance status per city.
4. Alerts on ordinance changes with impact assessment for the operator's fleet.
5. Optional: MDS (Mobility Data Specification) data feed to each city's Verkehrsbehörde in the required format.

## Business model

- **Subscription SaaS** per city under management.
- **Compliance-report generation** per city per month.
- **MDS data-delivery module** as premium add-on.

## Market size (top-down)

- ~8 major shared-mobility operators active in Germany; ~50+ cities with live permits.
- At €24k average ACV per operator (10-city average) and 50% penetration: SAM €10m Germany; TAM €40m EU (same operators, similar ordinance fragmentation in France, Spain, Netherlands).

## Competitive landscape

- **Populus, Remix (now Via):** US-centric city-data platforms.
- **Regulatory affairs consultancies:** advisory only.
- No dedicated eKFV/EU micro-mobility permit-management SaaS exists in Europe.

## Moat and differentiation

- City-ordinance database is a proprietary, continuously maintained asset.
- Operator-side network: as more operators use the platform, city ordinance changes become a crowdsourced early-warning system.
- MDS data pipeline creates a two-sided value: operators save time; cities get standardised data.

## Regulatory path (RDG)

No RDG exposure: permit-document generation and regulatory tracking is operations software, not legal advice. Antrag submissions require a cover note clarifying the operator's own legal responsibility.

## Key risks

- Operators consolidate, reducing addressable buyer count.
- Cities standardise permit formats, reducing the complexity advantage.
- Lime or Tier builds this in-house and offers it as an industry tool.

## MVP and first 90 days

1. Weeks 1–3: interview regulatory affairs leads at Tier and Bolt; map ordinances for 5 cities (Berlin, Hamburg, München, Köln, Frankfurt).
2. Weeks 4–7: build ordinance database, permit tracker, and Antrag generator for those 5 cities.
3. Weeks 8–12: run a live pilot tracking 3 operators across those cities; generate first monthly compliance reports.

## Success KPIs

- Cities in database at week 12 (target: 20).
- Monthly compliance reports generated (target: 15).
- MRR at week 12 (target: €4,500).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 4
- RDG clarity: 5
- Moat beyond first mover: 4
- Founder-market fit: 3
- Path to 12-week PoV: 5
- Scale ceiling: 3
- **Total: 28/35**

## Stakeholders to interview in Module 2

- Tier Mobility GmbH, Head of Regulatory Affairs.
- Behörde für Verkehr und Mobilitätswende Hamburg, Shared-Mobility team.
- Ordnungsamt München, e-scooter permit unit.
- Bolt Transport OÜ, EU Regulatory.
- Bundesverband eMobilität e.V. — micro-mobility association.
