# ClaimStack

**Pillar:** [[consumer-rights-awareness-and-enforcement]]
**One-liner:** "Stripe for collective redress." Back-office SaaS that lets qualified entities (Verbraucherzentralen, vzbv, SVV) run Abhilfeklage and Musterfeststellungsklage campaigns end to end: participant intake, eligibility checks, evidence collection, court filings via the BfJ register, and distribution of awarded amounts.
**Shortlist score:** 32/35 · #high-score

## Problem

Germany's new VDuG Abhilfeklage (October 2023) and the Musterfeststellungsklage (2018) create a powerful collective-redress regime. But the tooling behind the qualified entities that run these cases is a patchwork: the vzbv and 16 Verbraucherzentralen run major cases on off-the-shelf CMS, Excel spreadsheets and ad-hoc web forms. The eight active redress actions (Meta, TikTok, X, and others) each reach tens of thousands of registrants; every participant is a data point that needs eligibility check, evidence upload, consent management, and eventual distribution of damages. The BfJ claims register is a formal endpoint but offers no workflow support.

## Regulatory driver / Why now

- VDuG in force since October 2023; eight redress actions in the BfJ register by Q4 2025.
- EU Product Liability Directive (2024/2853) raises the next wave of class risks.
- Representative Actions Directive enforcement momentum picking up across EU.
- Litigation funder market (Deminor, Omni Bridgeway, LitFin, Burford) growing and seeking deal flow.

## Target users

- **End users:** qualified entities (vzbv, 16 Verbraucherzentralen, SVV, Deutsche Stiftung Verbraucherschutz, AK Wien for Austria) plus partnering plaintiff Kanzleien.
- **Payers:**
  - Qualified entities (subsidised by Bundesministerium der Justiz).
  - Plaintiff Kanzleien running class campaigns.
  - Litigation funders.

## Solution

A modular SaaS with four core modules:

1. **Participant intake:** branded web funnel with identity verification, evidence upload, consent and opt-in management.
2. **Eligibility engine:** configurable rule engine to filter registrants against case-specific criteria.
3. **Court integration:** e-filing plugin for the BfJ Verbandsklagenregister and integration with the beA/Kanzlei ecosystem.
4. **Distribution:** automated splitter for court-awarded funds across participants with anti-fraud checks.

Core platform built on a compliance-grade multi-tenant architecture with BSI-level security for sensitive personal data.

## Business model

- **Seat + case licence:** €25-100k/year per qualified entity, plus €20-50k per active case.
- **Funder co-licence:** pre-paid €50-150k per funded cohort, covering intake + distribution infrastructure.
- **Kanzlei module:** €2-5k/month per partner Kanzlei for the case-management layer.

## Market size (top-down)

- 80+ qualified entities across DACH.
- ~20-40 active class cases at any time, rising with DFA and PLD.
- Reachable ARR in DACH within 3 years: €10-25m; EU expansion to €60-120m.

## Competitive landscape

- **Darrow (Israel / US) and Quidli:** generic claim-finding platforms, not workflow for qualified entities.
- **Case-management SaaS (Kanzlei-side) like Microsoft 365 + Advolux:** not tuned to collective redress economics.
- **Nothing purpose-built in DACH.** This is genuinely greenfield.

## Moat and differentiation

- Deep integration with the BfJ Verbandsklagenregister.
- Dataset of class-intake funnel behaviour — priceless for funders and qualified entities to improve conversion.
- Regulatory credibility: strong trust relationship with vzbv and Verbraucherzentralen is a moat against generic tools.

## Regulatory path (RDG)

Pure infrastructure for licensed qualified entities and Kanzleien. No Inkasso licence required. GDPR engineering is critical.

## Key risks

- Public-sector sales cycles: 9-18 months typical.
- Political risk: future governments could narrow collective-redress scope.
- Funder-side dynamics: concentration of capital in few funders creates dependency.

## MVP and first 90 days

1. Weeks 1-3: co-design partnership with one Verbraucherzentrale (ideally Bayern or NRW) plus meta-klage.de co-counsel.
2. Weeks 4-7: prototype intake + eligibility engine for the Meta Verbandsklage register flow.
3. Weeks 8-12: co-pilot one active campaign with a partner qualified entity; target 5,000 registrants end to end.

## Success KPIs

- Registrant conversion rate (target: 3x baseline).
- Administrative cost per registrant (target: under €2).
- Weeks from case-kick-off to first registrant (target: under 2).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 5
- RDG clarity: 5
- Moat beyond first mover: 5
- Founder-market fit: 4
- Path to 12-week PoV: 4
- Scale ceiling: 4
- **Total: 32/35**

## Stakeholders to interview in Module 2

- Program lead for Sammelklage at vzbv, Berlin.
- Justiziar at Verbraucherzentrale Bayern.
- Partner Kanzlei Baumeister & Kollegen (runs meta-klage.de).
- Deminor / LitFin senior, DACH coverage.
- Referat Verbandsklagenregister at the Bundesamt für Justiz, Bonn.
