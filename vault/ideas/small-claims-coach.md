# SmallClaimsCoach

**Pillar:** [[enforcing-citizens-rights]]
**One-liner:** Guided self-representation app for the new [Online-Zivilverfahren](https://www.bmjv.de/DE/themen/digitales/digitalisierung_justiz/digitalisierungsinitiative/_articles/zivilgerichtliches_onlineverfahren_artikel.html) at Amtsgerichte (claims up to €10,000), generating pleadings, organising evidence and filing through the official digital channels.
**Shortlist score:** 31/35 · #high-score

## Problem

Small claims are the classic "too small for a lawyer, too big to ignore" segment: a defective €1,200 washing machine, a €700 service dispute with a contractor, a €3,500 unpaid invoice. Today the consumer either absorbs the loss, pays a Kanzlei €500-1,500 for a likely €800-€3,000 recovery, or attempts the Mahnverfahren blindly. The new Online-Zivilverfahren changes the economics by removing the courtroom-physical friction, but it still requires a written claim with a correct Streitwert, jurisdiction, cause of action and evidence index.

## Regulatory driver / Why now

- Online-Zivilverfahren pilot launched 15 April 2026 at eight Amtsgerichte.
- Claim threshold up to €10,000 covers ~90% of consumer disputes.
- Proceedings can run without oral hearings or by videoconference.
- eAkte in force across courts from 1 January 2026 (with variable delivery).
- Proposed expansion of Amtsgerichte jurisdiction to €10,000 (June 2025 BMJ draft).

This is a brand-new category with no incumbent. A first-mover can capture both the consumer brand and the structured-data flywheel.

## Target users

- **End users:** German citizens and small businesses with civil disputes up to €10,000 (product defects, service disputes, unpaid invoices, landlord disputes, small-value damages).
- **Payers:**
  - Consumer protection orgs who white-label (vzbv, ADAC, Mieterbund).
  - Legal expenses insurers (Rechtsschutzversicherung) who pay for reduced claims cost.
  - Lawyers for handoff of cases that become too complex.

## Solution

A guided web app that:

1. Takes the user through a dispute-specific decision tree (tenancy, consumer, service, small-business).
2. Calculates Streitwert and correct jurisdiction.
3. Generates a legally-compliant Klageschrift tailored to the dispute type.
4. Guides evidence upload and organises it into the court's preferred index format.
5. Files through the official Rechtsantragsstelle digital channel or eAkte-compatible pathway.
6. Tracks the case through to Urteil or Vergleich, with reminders for deadlines.

## Business model

- **Consumer pay-per-claim:** €49-99 per claim for the self-service tier, €249-499 for an "assisted" tier with a lawyer review before filing.
- **Insurance integration:** Rechtsschutzversicherer (Arag, DEVK, Allianz) pay per covered case to reduce lawyer spend.
- **NGO licence:** vzbv / Mieterbund / ADAC pay €20-60k/year for a co-branded member flow.

## Market size (top-down)

- Estimated 1.5-2.5 million civil disputes under €10,000 per year in Germany (of which a fraction become formal court cases).
- At €30 revenue per user and a 1% penetration, TAM of €450-750m; reachable SAM in 3-5 years of €25-50m.

## Competitive landscape

- **flightright / rightmart / Conny:** dispute-specific, not procedure-specific; do not cover the residual long tail.
- **Advocado / anwalt.de:** lawyer marketplaces, not self-service.
- **DIY legal document generators (AGB.de, Beck):** no procedure integration.

## Moat and differentiation

- Purpose-built for the new Online-Zivilverfahren rather than the legacy written procedure.
- Court-by-court rule engine as a compounding asset (Amtsgericht München works differently from AG Berlin-Mitte).
- Structured case data enables an anonymised Urteils-prediction layer over time.

## Regulatory path (RDG)

Information and form-automation only. No individualised advice. RDG-safe. For the "assisted" tier, partner with a Rechtsanwalt under §5 BRAO. No Inkasso licence required because the consumer files in their own name.

## Key risks

- The Online-Zivilverfahren pilot might expand slowly or contract; watch closely.
- CAC is hard in a one-time-per-person category; NGO and insurer partnerships are the unlock.
- Quality control: wrong Klageschrift means dismissal and a frustrated customer.

## MVP and first 90 days

1. Weeks 1-3: shadow one Rechtsantragsstelle (for example AG München) for a week; interview 10 filers.
2. Weeks 4-7: build the "defective consumer product" dispute path end to end.
3. Weeks 8-12: file 20 test claims via the Online-Zivilverfahren; measure acceptance, resolution time and user NPS.

## Success KPIs

- First-filing acceptance rate (target: 95% without court rejection).
- Median time to resolution vs. lawyer benchmark (target: 40% faster).
- Cost per resolved claim (target: under €100 for self-serve).
- Referral rate to partner Kanzleien for complex cases (a payer signal).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 4
- RDG clarity: 5
- Moat beyond first mover: 4
- Founder-market fit: 4
- Path to 12-week PoV: 5
- Scale ceiling: 4
- **Total: 31/35**

## Stakeholders to interview in Module 2

- Rechtsantragsstelle at a pilot Amtsgericht (AG München, AG Frankfurt, AG Berlin Mitte).
- Richter at an Amtsgericht participating in the pilot.
- Product owner at DigitalService GmbH (the federal digital agency building Digitale Rechtsantragsstelle).
- Rechtsschutz underwriter at Arag or DEVK.
- vzbv / Mieterbund program manager.
