# ProvacyAvenger

**Pillar:** [[enforcing-citizens-rights]]
**One-liner:** Claim-quality filter for Article 82 GDPR damages: automatically identifies concrete, judicially-reviewable harm from a user's data footprint and packages cases into class-ready claim cohorts.
**Shortlist score:** 22/35

## Problem

Article 82 GDPR gives data subjects the right to material and non-material damages for GDPR violations. In 2024-2025, claim volumes spiked in Germany: portals auto-generated mass Article 15 subject-access requests, and thousands of damages claims were filed over alleged "loss of control." The CJEU and German courts (BGH, BAG, multiple OLGs including a March 2026 OLG ruling) have since narrowed the definition of compensable harm: "negative emotional state" is insufficient; claimants must show a concrete, well-founded fear of misuse. This narrowing has not reached consumer lawyers yet, creating a noise-to-signal problem: thousands of weak claims clog docket, drown out legitimate ones, and burn Kanzlei credibility.

## Regulatory driver / Why now

- CJEU + BGH convergence on "concrete harm" requirement through 2025-2026.
- Meta and X Verbandsklagen already filed; millions of data subjects eligible.
- EU Product Liability Directive (2024/2853) brings similar dynamics to physical harm evidence.
- Digital Fairness Act (2026) expected to tighten transparency obligations, generating new claim paths.

## Target users

- **End users:** individual claimants with possible Article 82 claims.
- **Payers:**
  - Plaintiff Kanzleien (for example Rogert & Ulbrich, Gansel, Baumeister) who need higher-quality pipelines.
  - Qualified entities running Abhilfeklagen (vzbv, SVV).
  - Litigation funders (Deminor, Omni Bridgeway, LitFin) who want to pre-screen cohorts.

## Solution

A web app for individuals plus a B2B portal for Kanzleien and qualified entities:

1. Consumer-side triage collects the alleged breach (data leak, Meta tracking, Dieselgate-style scoring), the data subject's exposure, and any concrete harm indicators (phishing, identity theft, credit damage, emotional distress with medical record).
2. An AI classifier grades the claim against 2025-2026 German case-law "concrete harm" thresholds.
3. Qualified claims are routed into class cohorts with standardised evidence packs.
4. Weak claims receive educational explanation plus, where applicable, a referral to supervisory-authority complaint channels.

## Business model

- **Kanzlei SaaS:** €500-2,000/month per partner Kanzlei for the cohort-management console.
- **Funder pre-screening licence:** €10-25k/cohort for funders.
- **Consumer free** at intake; no success fee (clean RDG).

## Market size (top-down)

- Meta/TikTok/X Verbandsklagen alone touch tens of millions of data subjects; attach rate even at 1% yields 100k+ cases.
- Kanzlei and funder TAM in Germany: €30-80m for data-breach claim infrastructure.

## Competitive landscape

- **Gansel, Rogert & Ulbrich, Baumeister:** running claims by hand; potential partners more than competitors.
- **noyb (European Center for Digital Rights):** high-signal but advocacy-first; not operational at claim-cohort scale.
- **myright:** generic claims platform, not specialised on Article 82 harm gating.

## Moat and differentiation

- Proprietary "concrete harm" rulebook tied to German case-law evolution.
- Dataset of real claimant exposures becomes leverage for funders and legislators.
- Deep integration with Abhilfeklage participation flows.

## Regulatory path (RDG)

Consumer-side information and triage only. Claim handling routed to Kanzleien and qualified entities. No Inkasso licence required at MVP stage.

## Key risks

- Case law is still evolving; the "concrete harm" bar may shift.
- Consumer trust: the startup must resist the "ambulance chaser" brand by being explicit about claim quality.
- Dependence on large Verbandsklagen pipelines.

## MVP and first 90 days

1. Weeks 1-3: interview 3 plaintiff Kanzleien and 1 funder.
2. Weeks 4-7: build the harm-classification engine on the Meta + TikTok Verbandsklage templates.
3. Weeks 8-12: intake 500 users at a consumer-rights pop-up; deliver a qualified cohort of 50 to a partner Kanzlei.

## Success KPIs

- Precision of harm classifier vs. legal expert rating (target: 85%).
- Cohort conversion rate into filed claims (target: 25%).
- Feedback NPS from partner Kanzleien (target: 50+).

## Scorecard

- Regulatory tailwind: 3
- Stakeholder access: 3
- RDG clarity: 3
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 3
- **Total: 22/35**

## Stakeholders to interview in Module 2

- Data-protection partner at Gansel or Rogert & Ulbrich.
- Head of Digital Consumer Rights at vzbv.
- Senior at Deminor or LitFin covering DACH data-protection cases.
- Supervisory-authority official at BayLDA (Bayerisches Landesamt für Datenschutzaufsicht).
- Academic contact at Max Planck Institute for Innovation and Competition.
