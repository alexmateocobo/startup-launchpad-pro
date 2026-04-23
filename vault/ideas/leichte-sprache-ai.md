# Leichte Sprache AI

**Pillar:** [[digital-accessibility-and-compliance]]
**One-liner:** Real-time Leichte Sprache (plain German) and Deutsche Gebärdensprache (DGS) translation engine for government portals, healthcare providers and consumer-facing Mittelstand, certified to the standards of Netzwerk Leichte Sprache and Bundesfachstelle Barrierefreiheit.
**Shortlist score:** 26/35

## Problem

~17 million people in Germany need content in Leichte Sprache (lower literacy, intellectual disability, dementia, second-language German) and ~200,000 rely on DGS as a first language. Yet public portals, hospitals, banks and online shops rarely provide these versions: manual translation by certified Leichte-Sprache-Büros costs €1-3 per word and takes days. DGS video interpretation is even scarcer. BITV 2.0 already requires federal portals to include a Leichte Sprache explainer and DGS version; BFSG extends comparable expectations to consumer-facing services. Existing AI translators do not meet the Netzwerk-Leichte-Sprache style rules nor the pedagogical review requirements.

## Regulatory driver / Why now

- BITV 2.0 §4 obligates Leichte Sprache and DGS for federal online services.
- BFSG drives demand in e-commerce, banking and travel.
- Accessible Hospital initiative from BMG (2025) funds accessibility for healthcare.
- Public discussion on inclusion and ageing population broadens demand.

## Target users

- **End users:** content and communications teams.
- **Payers:**
  - Federal, Länder, municipal authorities.
  - Hospitals, Krankenkassen and insurers.
  - Mittelstand banks, utilities, public transport.
  - Education and training providers.

## Solution

A SaaS + API that:

1. Ingests source German text.
2. Produces Leichte Sprache following the Netzwerk Leichte Sprache ruleset (short sentences, everyday vocabulary, active voice, no nested subordinate clauses, explicit referent).
3. Generates a DGS avatar video via partner technology (SignTime, SignLab, or native).
4. Provides a review workflow for certified Leichte-Sprache testers (Prüfgruppen).
5. Versions, re-translates when source changes, and integrates with CMS (TYPO3, Govii, Contentful).

## Business model

- **API:** €0.05-0.15 per source word translated.
- **SaaS workstation:** €499-1,999/month per team.
- **Public-sector framework:** €100-300k multi-year.
- **DGS avatar add-on:** €20-100 per minute of output.

## Market size (top-down)

- ~3,000 federal + Länder agencies; 11,000 municipalities.
- ~2,000 hospitals; 100+ Krankenkassen.
- Reachable ARR: €8-18m in Germany within 3 years.

## Competitive landscape

- **SUMM AI:** Munich-based Leichte Sprache pioneer. Main competitor.
- **Capito.ai:** Austrian origin, moving to DE market.
- **Google/DeepL:** generic, not Netzwerk-Leichte-Sprache compliant.
- **Signtime / SignLab:** DGS but not integrated with Leichte Sprache.

## Moat and differentiation

- Hybrid Leichte Sprache + DGS + Prüfgruppe workflow.
- Partnership with Netzwerk Leichte Sprache and Prüfgruppen for certification.
- Growing corpus of human-verified Leichte-Sprache pairs gives compounding quality advantage.

## Regulatory path (RDG)

None. Linguistic and IT services.

## Key risks

- SUMM AI (already scaling, Series A in 2024) captures the German federal market first.
- Netzwerk Leichte Sprache may formally contest AI-only output.
- Public-sector procurement is slow and format-rigid.

## MVP and first 90 days

1. Weeks 1-3: interview 10 public-sector comms leads and 3 Prüfgruppen.
2. Weeks 4-7: build Leichte Sprache engine for healthcare patient-information.
3. Weeks 8-12: pilot with a Munich Krankenhaus and a Bavarian Landkreis portal.

## Success KPIs

- Prüfgruppe acceptance rate without edits (target: 70%).
- Cost per 1,000 words translated (target: under €8).
- Number of paid pilots at week 12 (target: 3).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 4
- Path to 12-week PoV: 4
- Scale ceiling: 3
- **Total: 26/35**

## Stakeholders to interview in Module 2

- Netzwerk Leichte Sprache, Münster.
- Bundesfachstelle Barrierefreiheit, Köln.
- Prüfgruppe at Lebenshilfe Bayern.
- DGS-Bund (Deutscher Gehörlosen-Bund).
- Digital team at a Munich Klinikum or LMU Klinikum.
- SUMM AI (competitive intelligence via public materials only).
