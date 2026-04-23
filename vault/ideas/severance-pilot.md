# ServerancePilot

**Pillar:** [[enforcing-citizens-rights]]
**One-liner:** AI-assisted Kündigungsschutzklage preparation and severance negotiation for employees inside the 3-week window after termination, in partnership with a specialist labour-law Kanzlei.
**Shortlist score:** 28/35

## Problem

German employees have exactly three weeks after receiving a termination notice to file a Kündigungsschutzklage. Miss the deadline and the dismissal becomes legally binding, even if unlawful. There is no general legal entitlement to severance; outcomes depend on individual negotiation leverage, which in turn depends on filing the Klage. Because success-based fees are prohibited for Rechtsanwälte, lawyers charge RVG or hourly rates, so employees without Rechtsschutzversicherung often hesitate and let the window close. The 2025-2026 tax-treatment changes for Abfindungen add further complexity that employees cannot be expected to navigate alone.

## Regulatory driver / Why now

- KSchG (Kündigungsschutzgesetz) applies for employees with 6+ months tenure at employers with 10+ FTEs.
- Mass-tech-layoff culture spreading to DACH (2025-2026 waves at SAP, Meta, Infineon, Bosch).
- Revised 2025 tax rules for severance (Fünftelregelung adjustments) make lay guidance unreliable.
- Labour courts' increasing openness to videoconferenced Gütetermin (conciliation hearings).

## Target users

- **End users:** white-collar employees aged 30-55 who have just been terminated and have 3 weeks to act.
- **Payers:**
  - The employee directly for the self-assessment tier.
  - Partner Kanzleien who pay for qualified leads.
  - Employers and outplacement providers (von Rundstedt, Enfactor, Spring Career Partners) who bundle the tool to soften reputational risk.
  - Rechtsschutzversicherer who pay to handle cases more efficiently.

## Solution

A web app that:

1. Ingests the Kündigung document (PDF, scan) and classifies it (ordentlich, außerordentlich, betriebsbedingt, personenbedingt, verhaltensbedingt).
2. Runs a KSchG validity check plus Betriebsratsanhörung audit.
3. Computes the likely severance range based on German case-law benchmarks (0.5-1.0 Monatsgehalt per year of tenure, adjusted for sector and dismissal type).
4. Generates a demand letter and a draft Klageschrift for the Arbeitsgericht within the 3-week deadline.
5. Routes the employee to a vetted labour-law Kanzlei for execution, with pre-filled case data.

## Business model

- **Consumer:** €49 for self-assessment, €249-499 for assisted negotiation.
- **Kanzlei fees:** €100-250 per referred lead (RVG-compatible, not success fee).
- **B2B outplacement bundles:** €50-80 per employee when packaged into severance programs.

## Market size (top-down)

- ~450,000 Kündigungen per year in Germany that trigger KSchG scope; of these, ~150,000 become Klagen at Arbeitsgerichte.
- At a €150 blended ARPU, direct addressable TAM of €20-30m/year; plus outplacement and insurer layers.

## Competitive landscape

- **Abfindungshero, Dismissme, wegweiser-arbeitsrecht:** existing but narrow, founder-led, not scaled.
- **rightmart:** labour law is one of many verticals, not the focus.
- **Local Kanzleien:** excellent on individual cases, no digital funnel.

## Moat and differentiation

- Combine the 3-week deadline as a time-pressure distribution hook with a vetted Kanzlei network.
- Severance benchmark dataset, built from anonymised cases, compounds over time.
- Integration with Rechtsschutzversicherer creates a low-CAC B2B layer.

## Regulatory path (RDG)

Form automation, self-assessment and information only. Individualised advice and Klage filing routed to partner Kanzleien (§5 BRAO). Clean RDG path.

## Key risks

- CAC is concentrated into a 72-hour urgency window. Media-buy heavy.
- Kanzlei-referral economics vulnerable to bar-association scrutiny if structured as payment for referrals; fix via RVG-compatible fee-sharing plus quality-controlled lead handoff.
- Mis-classification of dismissal can harm an employee's case; liability discipline is critical.

## MVP and first 90 days

1. Weeks 1-3: partner with a Munich-based Fachanwalt für Arbeitsrecht Kanzlei; conduct 10 case debriefs.
2. Weeks 4-7: build the Kündigung-intake + validity-check flow.
3. Weeks 8-12: handle 20 real cases with Kanzlei co-review; measure time to filing and severance delta vs. control.

## Success KPIs

- Percentage of eligible employees who file within the 3-week window (target: 95%).
- Median severance vs. published benchmarks (target: 15-25% uplift).
- Cost per filed Klage (target: under €150).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 4
- RDG clarity: 4
- Moat beyond first mover: 4
- Founder-market fit: 3
- Path to 12-week PoV: 5
- Scale ceiling: 4
- **Total: 28/35**

## Stakeholders to interview in Module 2

- 3-5 recently laid-off white-collar professionals (ideally via alumni networks).
- Fachanwalt für Arbeitsrecht in Munich (Daniel Schneider / Felser / Schaaf).
- HR director at a tech employer doing layoffs.
- Rechtsschutz product manager at Arag or Roland.
- Outplacement consultant at von Rundstedt.
