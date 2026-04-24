# InsureRight

**Pillar:** [[consumer-rights-awareness-and-enforcement]]
**One-liner:** AI-assisted insurance claim denial assistant: parses the denial, identifies weak reasoning, drafts a rebuttal, escalates through the Ombuds-scheme and — where necessary — into litigation with a partner Kanzlei.
**Shortlist score:** 25/35
**Tags:** #b2b #b2c #app #legal #success-fee

## Problem

German insurers routinely deny claims for reasons that do not hold up under scrutiny: alleged policy-obligation breaches, ambiguous exclusions, insufficient documentation. The consumer bears the burden of articulating a technically correct rebuttal within tight deadlines. Legal protection insurance (Rechtsschutzversicherung) helps only if you have one. The Versicherungsombudsmann and the BaFin-recognised Ombuds-scheme provide free mediation, but their process is form-heavy and intimidating. Meanwhile, claim denial rates in private health (PKV), liability (Haftpflicht) and occupational disability (BU) lines are rising.

## Regulatory driver / Why now

- German Ombuds-scheme resolves >10,000 cases a year; binding for insurers up to €10,000.
- 2025 CJEU rulings on Article 82 GDPR restrict "insurance-data mis-use" claims but increase clarity.
- BaFin's 2025 supervisory focus includes claim-handling quality in life and health insurance.

## Target users

- **End users:** insured individuals with a recent denial letter (private health, BU, life, liability, household).
- **Payers:**
  - End users on success-fee terms.
  - Versicherungsmakler who refer clients to preserve retention.
  - Partner Kanzleien on RVG/lead-gen basis.
  - Insurers themselves for triage of which denials to re-examine (an "inverse" B2B play).

## Solution

A web and mobile app where the user uploads the denial letter and policy. InsureRight:

1. Extracts policy conditions and denial reasoning.
2. Runs a CJEU / BGH / OLG case-law matcher.
3. Generates a Widerspruch tailored to the insurer's reasoning.
4. Monitors the 6-week deadline and escalates to the relevant Ombudsstelle if the insurer holds position.
5. Routes to partner Kanzlei if escalation is needed beyond mediation.

## Business model

- **Consumer success fee:** 15-25% of recovered amount (Inkassodienstleister path).
- **Flat-fee tier:** €79-149 per reviewed denial, no recovery conditionality.
- **Makler licence:** €199-499/month per Makler to offer the tool to retained clients.

## Market size (top-down)

- ~8 million private-health (PKV) insured + 17 million BU insured + 46 million Haftpflicht policies.
- Estimated 1.5-2.5 million denials/year across major lines.
- At €70 revenue per handled denial and 1% penetration, TAM of €150m+ with defensible concentration.

## Competitive landscape

- **Helpcheck:** life-insurance revocation specialist; narrow adjacency.
- **Anwaltsuche.de / anwalt.de:** matching, not product.
- **The insurer itself:** some (for example HUK-Coburg) offer internal complaint-handling; low user trust.

## Moat and differentiation

- Case-law matcher updated from BGH / OLG feeds — a compounding data asset.
- Makler channel provides a defensible low-CAC path.
- Behavioural data from thousands of denials informs an insurer-facing "fairness analytics" layer later.

## Regulatory path (RDG)

Inkassodienstleister registration for the success-fee model. Flat-fee tier operates as information-only. Kanzlei partner for BaFin-supervised escalation where needed.

## Key risks

- Policy-text heterogeneity across insurers makes the NLP layer difficult.
- Insurers may sharpen denial language to preempt auto-rebuttals.
- Brand risk if users have unrealistic recovery expectations.

## MVP and first 90 days

1. Weeks 1-3: collect 50 anonymised denial letters across lines via Versicherungsmakler contacts.
2. Weeks 4-7: build a policy-and-denial parser for one insurer (for example HUK-Coburg Haftpflicht).
3. Weeks 8-12: rebut 20 denials, measure recovery rate vs. a control group.

## Success KPIs

- Rebuttal acceptance rate by insurer (target: 35%).
- Ombuds-escalation success rate (target: 60%).
- CAC via Makler channel (target: under €30/case).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 3
- RDG clarity: 4
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 4
- **Total: 25/35**

## Stakeholders to interview in Module 2

- Ombudsfrau / Ombudsmann at Versicherungsombudsmann Berlin.
- Versicherungsmakler specialising in PKV (for example MLP, tecis).
- Fachanwalt für Versicherungsrecht (for example Stephan Michaelis, Hamburg).
- Consumer with a recent BU or PKV denial.
- BdV (Bund der Versicherten) consumer advocacy contact.
