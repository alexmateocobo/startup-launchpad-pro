# WEMoG-ChargeHub

**Pillar:** [[unlocking-underused-vehicles]]
**One-liner:** Guided digital workflow that takes a condo owner from "I want an EV charger" to installed wallbox, handling the WEG resolution, installer matching, Netzanschluss, and §14a registration in one flow.
**Shortlist score:** 27/35
**Tags:** #b2b #b2c #app #ev

## Problem

§20 of the Wohnungseigentumsgesetz (WEG), reformed by WEMoG in 2020, gives every apartment owner and tenant the legal right to install an EV charging point at their own cost. However, the process is deeply fragmented: the owner must (1) place the request on the WEG Eigentümerversammlung agenda, (2) obtain a majority resolution, (3) commission an Elektroinstallateur, (4) apply for a Netzanschluss from the grid operator, and (5) register the charger under §14a EnWG. Each step involves different parties, different forms, and different timelines. Most owners give up between steps 2 and 3. Germany has ~10 million owner-occupied condos; fewer than 3% have a charger. The EPBD transposition due June 2026 will require 50% of parking spaces in residential buildings with more than 3 spaces to be pre-wired — creating a second wave of demand.

## Regulatory driver / Why now

- WEMoG §20 WEG in force since December 2020; adoption still very low.
- EPBD transposition due June 2026 adds mandatory pre-wiring obligations for residential buildings.
- Government target: 15 million EV charging points in Germany by 2030 — residential installation is the critical path.

## Target users

- **End users:** Wohnungseigentümer (apartment owners), Hausverwaltungen acting on behalf of WEG communities.
- **Payers:**
  - Individual owners: freemium process tool + €149 one-time fee for document generation.
  - Hausverwaltungen: €199/month for bulk WEG resolution tooling across managed properties.
  - Installers: €39/month subscription to receive qualified leads.

## Solution

A step-by-step digital workflow:
1. Owner enters postcode + property details → system confirms eligibility under §20 WEG.
2. Generates a Tagesordnungspunkt (agenda item) letter for the Eigentümerversammlung in correct legal format.
3. After resolution, matches the owner with certified local Elektroinstallateure.
4. Pre-fills the Netzanschlussantrag for the relevant Netzbetreiber.
5. Completes §14a EnWG registration automatically post-installation.

## Business model

- **Consumer:** freemium wizard + document generation at €149.
- **Hausverwaltung SaaS:** €199/month.
- **Installer leads commission:** 5–8% of installation job value.

## Market size (top-down)

- ~10 million WEG-eligible apartments in Germany; ~2 million with EV-owning residents likely within 5 years.
- At 5% conversion to paid document generation (€149 each): €14.9m one-time revenue; recurring Hausverwaltung SaaS adds ARR layer.

## Competitive landscape

- **peter-park, Juice Technology:** installer-centric; no legal workflow.
- **Hausverwaltung software (Domus, GFAD):** property admin, no EV process.
- No dedicated WEMoG charger-installation workflow product exists.

## Moat and differentiation

- WEG document library (Bundesland-specific templates, Hausordnung clauses) is proprietary.
- Installer network creates recurring lead revenue.
- EPBD 2026 wave will re-activate the platform for a much larger audience.

## Regulatory path (RDG)

Moderate RDG risk: generating a Tagesordnungspunkt agenda item and Netzanschluss application approaches legal-document preparation. Mitigation: present documents as templates with a clear disclaimer ("no legal advice; please review with your Hausverwaltung or lawyer"), and partner with a Verband der Immobilienverwalter (VDIV) to co-brand the templates.

## Key risks

- Owners avoid the WEG process entirely and rent a parking space with an existing charger instead.
- Netzbetreiber reject automated Netzanschluss applications.
- EPBD transposition is delayed beyond June 2026.

## MVP and first 90 days

1. Weeks 1–3: interview 10 Wohnungseigentümer + 5 Hausverwaltungen + 3 Netzbetreiber.
2. Weeks 4–7: build WEG letter generator for Bavaria's most common WEG format; Netzanschluss pre-filler for Bayernwerk Netz.
3. Weeks 8–12: run 20 complete cases end-to-end; collect 3 paid pilot contracts from Hausverwaltungen.

## Success KPIs

- Cases completed end-to-end at week 12 (target: 20).
- Time from owner request to Netzanschluss application (target: under 1 hour).
- Installer sign-ups (target: 15 Elektroinstallateure).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 4
- RDG clarity: 4
- Moat beyond first mover: 3
- Founder-market fit: 4
- Path to 12-week PoV: 5
- Scale ceiling: 3
- **Total: 27/35**

## Stakeholders to interview in Module 2

- VDIV Bayern (property manager association) — template co-branding.
- Bayernwerk Netz GmbH — Netzanschluss API feasibility.
- ZVEH — installer association for lead-gen channel.
- Wohnungswirtschaft Bayern — tenant union perspective.
- DAV Arbeitsgemeinschaft Mietrecht — RDG boundary assessment.
