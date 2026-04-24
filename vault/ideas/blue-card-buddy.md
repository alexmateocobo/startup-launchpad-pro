# EnforceCitizenRights

**Pillar:** [[enforcing-citizens-rights]]
**One-liner:** End-to-end digital case manager for EU Blue Card, Niederlassungserlaubnis and family-reunification applications, serving the skilled worker and the employer in a single workflow.
**Shortlist score:** 27/35
**Tags:** #b2b #b2c #saas #app #legal

## Problem

Germany issued 70,000+ EU Blue Cards in 2025 and more than half of the 164,000 third-country work-based residence permits entered via the Fachkräfteeinwanderungsgesetz track. Applicants, employers and immigration Kanzleien still coordinate on email, spreadsheets and paper stacks moving between the Ausländerbehörde, consulates, employer HR, skills assessment bodies (ZAB), and the Bundesagentur für Arbeit. Document requirements vary by Bundesland. Processing backlogs at the Ausländerbehörde can exceed 12 weeks. For the skilled worker this is disorienting and risky (status gaps), and for the employer it is a hiring-pipeline leak.

## Regulatory driver / Why now

- Fachkräfteeinwanderungsgesetz fully in force since March 2024 with priority processing for recognised employers.
- EU Blue Card salary threshold lowered in 2023 and adjusted again 1 January 2026 (~€50,700).
- IT professionals can now qualify without a university degree (3+ years experience within the last 7 years).
- Several Bundesländer now accept digital submission of employment contracts and diploma assessments.

## Target users

- **End users:** foreign skilled workers applying for Blue Card, IT Blue Card exception, or Niederlassungserlaubnis; spouses applying for family reunification.
- **Payers:**
  - Employer HR teams and RPO partners at Mittelstand and enterprise (Siemens, Infineon, BMW HR, software scaleups).
  - Immigration Kanzleien (Fragomen DE, Schlun & Elseven, Rödl).
  - Relocation service providers (Jobbatical, Nestpick Relocate).

## Solution

A workflow product that pairs a consumer-grade application tracker (web + mobile) with an employer console. Core capabilities:

- Automated document checklist per Bundesland and permit type.
- Smart forms that pre-fill the Antrag auf Aufenthaltstitel and supplementary Bundesland forms.
- Live status view integrated with employer HR, consulate appointment bookings and Ausländerbehörde portals (where APIs exist, otherwise scraping and human-in-the-loop).
- Recognised-employer fast track: auto-file via "beschleunigtes Fachkräfteverfahren" where eligible.
- Expiry and status-gap alerts.

## Business model

- **Employer SaaS:** €800-1,500 per relocation case for the Mittelstand; volume licences for enterprise HR.
- **Consumer premium:** freemium for individuals (€29-79 per application pack for premium features).
- **Kanzlei licence:** white-labelled workflow for immigration Kanzleien at €199-399 per lawyer/month.

## Market size (top-down)

- Blue Cards + qualified work permits: ~170,000 per year in Germany. At an employer-weighted ARPU of €500, the direct TAM is €85m; add family reunification and Niederlassungserlaubnis and the number trebles.

## Competitive landscape

- **Jobbatical, Localyze, Nestpick Relocate:** strong on relocation logistics, weaker on immigration case depth.
- **Fragomen, Schlun & Elseven, Rödl:** incumbent Kanzleien with manual workflows.
- **Handbook Germany, Make-it-in-Germany:** free information, no workflow.

## Moat and differentiation

- Kanzlei-safe RDG-compliant data flow. BlueCardBuddy is an information and form-automation provider, not a legal advisor.
- Structured data and status APIs become the backbone for an employer-side visa-risk dashboard, building a recurring B2B moat.
- A growing rule engine encoding Bundesland-specific quirks is a compounding data asset.

## Regulatory path (RDG)

Positioned as information and form automation, not legal advice. Individualised questions routed to partner Kanzleien. No Inkasso-style success fees involved. Clean RDG path.

## Key risks

- Dependence on the pace of Ausländerbehörde digitalisation; no deep APIs today.
- Enterprise HR procurement cycles can exceed the 12-week PoV window.
- GDPR sensitivity around passport, biometric and family data, which requires best-in-class security engineering.

## MVP and first 90 days

1. Weeks 1-3: interview two recognised employers (Siemens or Infineon HR contact via UnternehmerTUM), two immigration Kanzleien, and five skilled workers in process.
2. Weeks 4-7: prototype the Bayern Blue Card flow end to end on Webflow + Airtable.
3. Weeks 8-10: pilot with one employer for 10 hires; measure time-saving delta.
4. Weeks 11-12: productise if design-partner is willing to sign a letter of intent.

## Success KPIs

- Median time from offer-letter to work start (target 30% reduction).
- Status-gap incidents per 100 hires (target: 0).
- NPS of skilled workers through the process (target: 60+).
- Recognised-employer fast-track adoption inside the tool.

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 4
- RDG clarity: 4
- Moat beyond first mover: 4
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 4
- **Total: 27/35**

## Stakeholders to interview in Module 2

- HR Mobility lead at Siemens, Infineon or a Munich software scaleup.
- A skilled-worker applicant currently in the Bayern Blue Card process.
- A partner at an immigration Kanzlei (Schlun & Elseven, Fragomen DE).
- Ausländerbehörde München, Abteilung Fachkräfte (cold outreach via Rechtsantragsstelle).
- Program lead at Make-it-in-Germany / ZAV.
