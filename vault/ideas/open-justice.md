# OpenJustice

**Pillar:** [[corporate-compliance-tooling]]
**One-liner:** Public case-law and regulatory intelligence platform that makes BGH, OLG, BFH, BAG, BVerwG, CJEU and BaFin/BNetzA decisions searchable, linkable and trend-monitorable in real time — a "Bloomberg for German law".
**Shortlist score:** 23/35
**Tags:** #b2b #saas #api #platform #legal

## Problem

Beck-online, Juris, Jurion, LexisNexis Germany are expensive, closed, slow to update, and not purpose-built for automated monitoring. Compliance teams, inhouse counsel, legal-tech startups, journalists and NGOs all need a programmatic, fresh, semantic view of German and EU case-law, regulatory guidance, and enforcement action. Germany has recently published more decisions in open form (via rechtsprechung-im-internet.de, openjur.de, dejure.org), and the European Parliament's open-data push means CJEU and Commission guidance is machine-readable. An open, API-first platform with strong semantic search, trend detection and alerting would unlock many downstream startups (including several in this playbook).

## Regulatory driver / Why now

- EU Open Data Directive transposed in Germany via DNG-E-Gov 2021.
- Bundesministerium der Justiz published a 2025 roadmap for open rechtsprechung access.
- Generative-AI tooling requires a reliable legal knowledge base that does not hallucinate.
- Legal-tech ecosystem is data-starved; this platform is a primitive for many verticals.

## Target users

- **End users:** inhouse counsel, Kanzleien, compliance leads, academics, journalists, legal-tech founders.
- **Payers:**
  - Enterprise inhouse (€20-100k/year).
  - Mid-size Kanzleien (€499-1,999/month).
  - API customers: legal-tech startups (including several in this playbook).
  - Academic and NGO licences (subsidised/free).

## Solution

1. Ingests BGH, OLG, BFH, BAG, BVerwG, CJEU, and selected regulators (BaFin, BNetzA, BfDI, Bundeskartellamt).
2. Extracts headnotes, Leitsätze, citations, applied norms.
3. Links norms to BGB, StGB, HGB, GwG, DSGVO, and amendments.
4. Semantic search + trend alerts + API.
5. Public dashboards for transparency (free tier).

## Business model

- **Free tier:** basic search (ad-supported or foundation-funded).
- **Pro tier:** €79-199/user/month.
- **API tier:** €0.01-0.05 per query, enterprise volume contracts.
- **Academic + NGO tier:** free or near-free, supported by foundations.

## Market size (top-down)

- ~165,000 admitted lawyers in Germany + ~50,000 inhouse legal professionals.
- Existing Juris/Beck-online TAM: €500m+ annually.
- Realistic capture: 1-3% in 5 years, i.e. €5-15m ARR.

## Competitive landscape

- **Beck-online, Juris:** dominant, legacy, closed.
- **Wolters Kluwer Germany, LexisNexis Germany:** global brands with DE stakes.
- **dejure.org, openjur.de, rechtsprechung-im-internet.de:** free but minimal.
- **Codex AI, Noxtua:** LLM-assistance but rely on proprietary corpora.

## Moat and differentiation

- Open + semantic, not closed and keyword.
- API-first: partners build on top.
- Regulator integration beyond courts.
- Community contributions possible.

## Regulatory path (RDG)

No RDG exposure. Copyright exposure managed via public-domain and press-release scraping rules.

## Key risks

- Juris and Beck-online lower prices aggressively.
- Copyright litigation on annotated decisions.
- Open-data availability remains uneven across Länder.

## MVP and first 90 days

1. Weeks 1-3: interview 15 inhouse counsel + Kanzlei partners.
2. Weeks 4-7: build BGH + OLG ingestion + semantic search.
3. Weeks 8-12: run 10 API pilots with other legal-tech players.

## Success KPIs

- Documents indexed weekly (target: 2,000+).
- API calls per paying customer (target: 10k/month).
- Paid pilots at week 12 (target: 5).

## Scorecard

- Regulatory tailwind: 3
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 3
- Scale ceiling: 3
- **Total: 23/35**

## Stakeholders to interview in Module 2

- Bundesministerium der Justiz, Open-Data team.
- Prof. für Rechtsinformatik at Saarland University or EBS.
- dejure.org / openjur.de maintainers.
- Head of Knowledge at a DAX in-house legal function (BMW, Allianz).
- Legal-tech venture investors at Acton Capital, HV Capital.
