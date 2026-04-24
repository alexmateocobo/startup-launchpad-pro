# DarkPatternScout

**Pillar:** [[consumer-rights-awareness-and-enforcement]]
**One-liner:** Evidence-grade dark-pattern and manipulative-design detector for consumer NGOs, regulators and qualified entities: continuous crawl of e-commerce, SaaS and mobile apps, producing DSA Article 25 and UCPD-grade documentation packs ready for enforcement.
**Shortlist score:** 27/35
**Tags:** #b2b #saas #compliance #legal

## Problem

The Digital Services Act (DSA) Article 25, the Unfair Commercial Practices Directive (UCPD) and the EU Data Act together outlaw most "dark patterns". But enforcement is bottlenecked by evidence: Verbraucherzentralen, vzbv and the Bundesnetzagentur have to manually record, screenshot and narrate each pattern before they can litigate or file an Abhilfeklage. In 2024 the DSA-Enforcement Team at the Bundesnetzagentur and the EU Commission flagged hundreds of suspect interfaces but only a handful reached formal proceedings. Proof quality and reproducibility are the chokepoint.

## Regulatory driver / Why now

- DSA in force since 17 February 2024; first national enforcement decisions expected in 2026.
- EU Commission Guidelines on Dark Patterns published late 2025.
- CMA and Autorité de la concurrence coordinated enforcement campaign on subscription traps.
- VDuG Abhilfeklage provides a litigation backend that needs reliable evidence inputs.

## Target users

- **End users:** compliance analysts at vzbv, Verbraucherzentralen, Bundesnetzagentur DSA team, European Commission DG CNECT.
- **Payers:**
  - Qualified entities and NGOs.
  - Bundesnetzagentur DSA enforcement unit.
  - Litigation funders staging class cases on dark patterns.
  - Law firms representing defendant e-commerce companies (for counter-auditing).

## Solution

A headless-browser crawler plus human-in-the-loop annotation studio:

1. Continuous sampling of Top-500 e-commerce and SaaS sites across DACH.
2. Detection models for 13 canonical dark patterns (forced continuity, confirmshaming, hidden fees, roach motel, pre-ticked consents, sneak-into-basket, etc.).
3. Evidence package: timestamped screenshots, HTML snapshot, cookie log, video capture, DSA-Article-25-ready narrative.
4. Legal taxonomy layer cross-referencing UCPD, DSA Annex, ePrivacy Directive.

## Business model

- **NGO and regulator licence:** €40-120k/year per qualified entity or regulator.
- **Litigation funder co-licence:** €30-80k per active case.
- **Defence-side audit:** €15-50k per company audit cycle (conflict-walled from enforcement side).

## Market size (top-down)

- 80+ qualified entities across DACH, 2 federal regulators (BNetzA, BMJV) and the European Commission.
- Reachable ARR across DACH: €8-15m within 3 years; EU expansion: €30-60m.

## Competitive landscape

- **Ghostery, Cookiebot:** privacy-focused, not dark-pattern-focused.
- **Avast dark-pattern scanner:** consumer browser plugin, not evidence-grade.
- **Academic tools (e.g. OpenWPM):** research-grade, no legal-evidence packaging.
- **BigTech in-house compliance:** ad-hoc and asymmetric.

## Moat and differentiation

- Legal-evidence packaging is the product, not the detection itself.
- Trust moat with NGO sector: exclusive data-sharing agreements possible.
- Growing labelled dataset improves detection precision across new patterns.

## Regulatory path (RDG)

Pure evidence-gathering for licensed qualified entities and public bodies. No RDG exposure. GDPR compliance for scraping is critical.

## Key risks

- Target sites implement anti-bot defences that raise operational cost.
- Legal definitions of "dark pattern" remain contested; false positives hurt credibility.
- NGO procurement cycles are slow and grant-driven.

## MVP and first 90 days

1. Weeks 1-3: co-design with vzbv DSA team; agree on taxonomy and output format.
2. Weeks 4-7: build the crawler + annotation studio for the Top-50 German e-commerce sites.
3. Weeks 8-12: deliver two dark-pattern evidence packs for live enforcement cases; iterate on output format.

## Success KPIs

- Dark-pattern precision against expert NGO review (target: 85%).
- Evidence packs per week delivered to NGO customer (target: 3).
- Enforcement outcomes citing tool output (target: 2 within 6 months).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 4
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 3
- **Total: 27/35**

## Stakeholders to interview in Module 2

- Head of DSA Enforcement at Bundesnetzagentur, Bonn.
- Legal lead at vzbv Digital Team, Berlin.
- Verbraucherzentrale NRW Digitale Welt.
- DG CNECT DSA Enforcement Unit, Brussels.
- Dark-patterns research group at TU München / Max Planck Institute.
