# BFSGPilot

**Pillar:** [[digital-accessibility-and-compliance]]
**One-liner:** Continuous Barrierefreiheitsstärkungsgesetz (BFSG) monitoring and remediation cockpit for German Mittelstand e-commerce, banking and SaaS: WCAG 2.2 AA + EN 301 549 scanning, prioritised remediation queue, evidence packs for Marktüberwachungsbehörde audits and complaint-handling.
**Shortlist score:** 33/35 · #high-score

## Problem

The Barrierefreiheitsstärkungsgesetz (BFSG) entered enforcement on 28 June 2025. It is the German transposition of the EU Accessibility Act (EAA) and compels all B2C products and services — e-commerce, banking, self-service terminals, e-books — to meet WCAG 2.2 AA and EN 301 549 from that date, with fines up to €100,000 and market-removal powers for the Marktüberwachungsbehörde. The Mittelstand is not ready. A 2025 aleri Solutions audit of 115 major German online shops found zero fully compliant sites and 100% with serious violations. Existing tools (Eye-Able, SiteCockpit, Barrierefix, axe-core, Deque) scan one-off or detect a fraction of WCAG criteria; none produce audit-grade, continuously updated evidence packs that a Marktüberwachungsbehörde complaint handler or a Verbraucherzentrale class-action lawyer would accept.

## Regulatory driver / Why now

- BFSG enforcement active from 28 June 2025; first fines and public complaints expected in 2026.
- 15 Länder Marktüberwachungsbehörden actively ramping staffing.
- Verbraucherzentralen publicly campaigning for class-action enforcement.
- EU Commission has signalled infringement proceedings against Member States with weak enforcement.
- 2026 is the critical year when first major rulings and fines will set precedent.

## Target users

- **End users:** compliance, product and engineering leaders at Mittelstand e-commerce, banking, insurance and SaaS.
- **Payers:**
  - Mittelstand (100-5,000 FTE): €10-60k/year.
  - DAX and MDAX: €80-250k/year enterprise licence.
  - Public-sector (federal and Länder agencies): €30-100k/year.
  - Accessibility consultancies as channel partners (DIAS, aleri Solutions, Pfennigparade, BIK, T-Systems MMS).

## Solution

A continuous-monitoring SaaS:

1. Crawls user journeys (checkout, login, product search) daily.
2. Runs a multi-engine ruleset: WCAG 2.2 AA + EN 301 549 + BFSG-V + Leichte Sprache heuristics.
3. Uses an accessibility-LLM for semantic checks (alt-text quality, ARIA correctness, keyboard-trap detection).
4. Prioritises findings by user impact, regulatory risk and effort.
5. Outputs evidence packs ready to satisfy BFSG-V reporting and Marktüberwachungsbehörde complaint handling.
6. Optional integration with a lived-experience tester marketplace (see idea 16) for human validation.

## Business model

- **Tiered SaaS:**
  - Small e-commerce (under €10m GMV): €499-999/month.
  - Mittelstand: €1,500-5,000/month.
  - Enterprise: €50-250k/year.
- **Remediation services:** hourly rate or fixed-fee package via partner network.
- **Audit evidence packs:** €5-20k per artefact for pre-audit readiness.

## Market size (top-down)

- ~500k B2C digital products and services in Germany subject to BFSG.
- Of which ~70k are Mittelstand or large enterprises with meaningful budget.
- At €15k average ACV and 5% penetration, SAM €50m; TAM €200-400m including EU.

## Competitive landscape

- **Eye-Able (DE):** strong brand, overlay-heavy, WCAG 2.2 AA coverage partial.
- **SiteCockpit (DE):** scanning only, no remediation workflow.
- **Barrierefix (DE):** early stage.
- **axe-core / Deque (US):** developer-first, no BFSG-specific reporting.
- **Siteimprove (DK):** enterprise but no BFSG-V alignment.
- **UserWay, AccessiBe:** overlay approach widely rejected by disability community.

## Moat and differentiation

- BFSG-V-native reporting: nobody else packages Marktüberwachungsbehörde-ready evidence.
- Continuous crawl + semantic AI: beats scan-once tools.
- Partnership with lived-experience tester marketplace gives auditability that pure automation cannot.
- Growing dataset of BFSG findings across industries is proprietary.

## Regulatory path (RDG)

No RDG exposure: accessibility compliance is product/IT, not legal services. Partnership with auditing Prüfstellen (e.g. BIK, DIAS) adds legal credibility without licence.

## Key risks

- Eye-Able or an international tool captures Mittelstand first.
- Marktüberwachungsbehörden remain under-resourced and enforce lightly.
- Overlay tools (AccessiBe, UserWay) undercut on price and confuse buyers.

## MVP and first 90 days

1. Weeks 1-3: interview 15 Mittelstand digital leaders + 5 Marktüberwachungsbehörden.
2. Weeks 4-7: build a continuous crawler and BFSG-V report generator; pilot with two Munich Mittelstand e-commerce companies.
3. Weeks 8-12: deliver 3 evidence packs; run a paid pilot contract.

## Success KPIs

- Number of BFSG violations caught per site (target: 3x axe-core baseline).
- Remediation lead-time improvement (target: 50% reduction).
- Signed Mittelstand pilots at week 12 (target: 3).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 5
- RDG clarity: 5
- Moat beyond first mover: 4
- Founder-market fit: 5
- Path to 12-week PoV: 5
- Scale ceiling: 4
- **Total: 33/35**

## Stakeholders to interview in Module 2

- Marktüberwachungsbehörde Bayern, BFSG team.
- Head of Digital at a Bayern-based Mittelstand e-commerce company (targets: Hornbach, Mister Spex, Sport Münzinger).
- BIK Beratungsstelle, Bonn.
- Deutsches Institut für Menschenrechte.
- DAV Arbeitsgemeinschaft IT-Recht (for the enforcement litigation angle).
- Five lived-experience testers (blind, deaf, motor-impairment, cognitive).
