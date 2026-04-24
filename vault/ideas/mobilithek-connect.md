# Mobilithek-Connect

**Pillar:** [[shared-clean-mobility]]
**One-liner:** Compliance SaaS that helps public transit operators, carsharing networks, and micro-mobility providers publish GTFS, NeTEx, and MDS data to Germany's Mobilithek (National Datenpunkt), fulfilling obligations under the Mobilitätsdatengesetz and EU IVS Directive.
**Shortlist score:** 26/35

## Problem

Germany's Mobilitätsdatengesetz (passed 2024, enforcement ramping in 2025–2026) requires mobility operators to publish real-time and static data to the Mobilithek — Germany's National Access Point for mobility data. The required formats differ by operator type: GTFS/GTFS-RT for transit, NeTEx for timetable data, MDS (Mobility Data Specification) for micro-mobility, OCPI for carsharing. Many operators — especially mid-size transit agencies (Zweckverbände), regional carsharing networks, and micro-mobility operators — lack the technical capacity to produce conforming data feeds. Non-compliance risks loss of public subsidies and exclusion from multimodal routing (Google Maps, DB Navigator) that is increasingly tied to Mobilithek presence.

## Regulatory driver / Why now

- Mobilitätsdatengesetz enforcement advancing in 2025–2026.
- EU IVS Directive (2010/40/EU) delegated regulations require real-time data publication for operators above minimum thresholds.
- Bundesministerium für Digitales und Verkehr (BMDV) conditioning future mobility subsidies on Mobilithek compliance.

## Target users

- **End users:** IT teams at regional transit Zweckverbände, carsharing cooperatives, e-scooter operators.
- **Payers:**
  - Regional transit agencies: €800–2,000/month.
  - Micro-mobility operators: €400–900/month per city.

## Solution

A connector-and-validation SaaS that:
1. Connects to existing backend systems (HAFAS, IVU, Trapeze for transit; proprietary APIs for micro-mobility).
2. Transforms and publishes data in the required format to the Mobilithek automatically.
3. Runs continuous schema validation (GTFS validator, NeTEx validator) and alerts on data-quality failures.
4. Produces monthly Mobilithek compliance evidence reports.
5. Optionally publishes to GBFS (General Bikeshare Feed Specification) for international routing integration.

## Business model

- **Connector SaaS** per backend type and operator.
- **Data-quality monitoring** subscription.
- **Consulting:** one-time migration from legacy systems.

## Market size (top-down)

- ~400 regional transit authorities in Germany; ~150 carsharing networks; ~30 micro-mobility operators.
- At €12k average ACV and 15% penetration: SAM €10m Germany; extended to EU (similar mandates) TAM ~€60m.

## Competitive landscape

- **Entur (Norway), Golemio (Czech):** national data-platform operators; not cross-border SaaS.
- **Traveltainment, Mentz:** transit integration specialists; no compliance-reporting workflow.
- No dedicated Mobilithek compliance SaaS exists.

## Moat and differentiation

- Per-system connectors (HAFAS, IVU, Trapeze) are expensive to build and represent a significant barrier.
- Real-time data-quality monitoring creates stickiness (operators rely on alerts for their own operations).
- Multi-operator platform gives BMDV a single integration point — potential government partnership.

## Regulatory path (RDG)

No RDG exposure: data-transformation and publishing is technical compliance, not legal advice.

## Key risks

- Mobilithek builds its own ingestion APIs that are easy enough for operators to use directly.
- Transit software vendors (IVU, Mentz) add Mobilithek export as a native feature.
- Enforcement is weak and operators don't prioritise compliance.

## MVP and first 90 days

1. Weeks 1–3: interview 5 transit Zweckverbände + BMDV Mobilithek team.
2. Weeks 4–7: build a GTFS-RT connector for HAFAS (the most common backend) and publish to the Mobilithek sandbox.
3. Weeks 8–12: pilot with 2 transit agencies; deliver first monthly compliance report.

## Success KPIs

- Operators publishing to Mobilithek via the platform at week 12 (target: 4).
- Data-quality score (target: >98% GTFS-valid records).
- MRR at week 12 (target: €4,000).

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

- BMDV, Mobilithek product team.
- MVV (Münchner Verkehrsverbund), IT and data team.
- Berlinpass / BVG data team — GTFS-RT case study.
- Tier Mobility, data engineering team (micro-mobility MDS).
- IVU Traffic Technologies AG — HAFAS connector partnership.
