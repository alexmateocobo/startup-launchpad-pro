# CourtFlow

**Pillar:** [[corporate-compliance-tooling]]
**One-liner:** eAkte + Online-Zivilverfahren middleware for Kanzleien: bridges their case-management system (RA-MICRO, Advoware, Advolux, STP) to the federal court electronic-file platform and the new small-claims procedure, automating filings, deadlines, document exchange, and client transparency.
**Shortlist score:** 26/35
**Tags:** #b2b #saas #middleware #legal

## Problem

As of 1 January 2026 all German civil and commercial courts must use the eAkte (electronic file). The beA (besonderes elektronisches Anwaltspostfach) has been mandatory for lawyers since 2022. On 15 April 2026 eight Amtsgerichte opened the Online-Zivilverfahren pilot for claims up to €10,000. But Kanzleien operate on fragmented legacy case-management tools that do not talk natively to the eAkte or Online-Zivilverfahren. Lawyers spend 15-30% of their time on system-switching, re-entering data, monitoring deadlines, and manually moving documents between beA, client portals, and internal CMS. Large Kanzleien have budget to build integrations; small and mid-size do not.

## Regulatory driver / Why now

- eAkte mandatory 1 January 2026.
- Online-Zivilverfahren live from 15 April 2026.
- Regulatory pressure to reduce court backlog.
- E-Justice strategy 2027 of the Bundesministerium der Justiz mandates full interoperability.
- beA infrastructure stabilising after 2022-2024 teething.

## Target users

- **End users:** Kanzleien of 3-50 lawyers, plus in-house legal teams that appear before civil courts.
- **Payers:**
  - Small and mid-size Kanzleien (seat-based subscription).
  - Large Kanzleien (enterprise licence).
  - Case-management vendors (RA-MICRO, STP, Advoware) as integration partners.
  - Legal-tech insurers (Arag, Roland).

## Solution

1. Universal adapter for beA, eAkte, Online-Zivilverfahren, major Kanzlei CMS.
2. Deadline engine: consolidated view of fristwahrung across tools.
3. Document automator: auto-generates Klageschrift, Schriftsatz, Mahnbescheid per court template.
4. Client portal: clients see status updates, sign electronically, upload evidence.
5. LLM assistant for motion drafting scoped to German civil-procedure templates.

## Business model

- **Per-seat SaaS:** €39-99/lawyer/month.
- **Per-case fee:** €5-25 for Online-Zivilverfahren filings.
- **Enterprise integration:** €25-100k/year.

## Market size (top-down)

- ~165,000 admitted lawyers in Germany; ~50,000 in 3-50 person Kanzleien.
- Reachable ARR: €20-40m within 3 years.

## Competitive landscape

- **RA-MICRO, STP, Advolux, Advoware:** CMS vendors, slow to integrate.
- **Legartis, XMLaw:** contracting-focused.
- **Kleos, Smokeball:** EU/UK providers, partial German coverage.
- **Codex, Lecare, Fides:** smaller niche.

## Moat and differentiation

- Universal-adapter approach: not competing with CMS, making them better.
- Online-Zivilverfahren automation: first-mover window is short.
- Kanzlei-centric UX, not court-centric.

## Regulatory path (RDG)

Zero. Pure software for licensed lawyers.

## Key risks

- CMS vendors build these integrations themselves.
- Court integration is brittle and Land-specific.
- beA outages and regulatory changes create operational risk.

## MVP and first 90 days

1. Weeks 1-3: interview 15 Bayern Kanzleien + 3 Amtsgericht IT leads.
2. Weeks 4-7: build beA + Amtsgericht München adapter + deadline engine.
3. Weeks 8-12: pilot with 3 paying Kanzleien.

## Success KPIs

- Hours saved per lawyer per week (target: 5).
- Filings processed via CourtFlow (target: 200 at week 12).
- Paid Kanzleien signed (target: 3).

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

- Präsident der Rechtsanwaltskammer München.
- IT-Leitung of Amtsgericht München + OLG München.
- DAV AG Kanzleimanagement.
- Two mid-size Kanzleien in Munich (e.g. SZA Schilling, Beiten Burkhardt — partners with mid-size civil practice).
- STP and RA-MICRO product strategy leads.
