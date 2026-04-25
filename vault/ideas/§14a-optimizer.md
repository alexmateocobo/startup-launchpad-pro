# §14a-Optimizer

**Pillar:** [[ev-charging-infrastructure]]
**One-liner:** B2B2C SaaS that advises existing device owners on the optimal §14a EnWG module and helps installers manage compliance documentation — targeting the module-switching gap and the pre-2024 device backlog that automated installer processes do not cover.
**Shortlist score:** 22/35
**Tags:** #b2b #b2c #saas #app #ev

> **⚠️ Premise correction (April 2026):** The original thesis assumed that new-device registration is a consumer-facing problem. Research shows this is incorrect. For devices installed from January 2024 onwards, the installer handles registration as a mandatory commissioning step — the owner takes no action. The consumer pain point does not exist for new wallboxes. The document below reflects the corrected, smaller opportunity.

## Problem (corrected)

§14a EnWG came into force on 1 January 2024. Any EV charger, heat pump, or battery system above 4.2 kW installed from that date must be registered with the local grid operator (Netzbetreiber) as a controllable energy consumer (SteuVE). In exchange, the owner receives a grid-fee reduction of €110–450+ per year depending on the module selected.

**What the original thesis got wrong:** for new installations, the electrician registers the device during commissioning as an obligatory step. The consumer does not need to take any action. The "600,000 unregistered devices" assumption has not been verified and is likely overstated for the new-device segment.

**What the actual gap is:**

- **Pre-2024 devices.** Wallboxes installed before January 2024 are not automatically registered. Owners can voluntarily opt in, but no installer is obligated to do it for them. This is a real but shrinking, one-time pool.
- **Module optimisation.** Most newly registered devices default to Module 1 (flat annual discount). Modules 2 and 3 offer higher savings — up to €450+/year — through time-variable or dynamic grid charges. No product currently advises owners on which module maximises their savings given their actual consumption profile. This is the most defensible gap.
- **Installer compliance documentation.** Installers need to document which module was selected and why. There is no standardised tooling for this advisory and audit trail.

## Regulatory driver / Why now

- [§14a EnWG](https://www.gesetze-im-internet.de/enwg_2005/__14a.html) mandatory for all new controllable devices from 1 January 2024.
- Time-variable grid charges (Module 2) became optional from 1 April 2025; Module 3 (dynamic charges) rolling out alongside smart meter rollout — creating ongoing module-switching advisory demand.
- Bundesnetzagentur auditing compliance; permanent rules still being finalised, meaning the module landscape will continue to evolve and owners will need guidance.

## Target users

- **Primary:** Existing wallbox and heat pump owners registered on Module 1 by default, seeking to switch to Module 2 or 3 for higher savings.
- **Secondary:** Owners of pre-2024 devices who have never registered at all.
- **B2B channel:** Wallbox installers and energy retailers who want to offer module advisory as a value-add and need audit-trail documentation for compliance.
- **Payers:**
  - Consumers: €2.99–4.99/month for module optimisation dashboard and switching service.
  - Installers: €49–149/month for white-label advisory portal with compliance documentation.
  - Energy retailers (Tibber, E.ON): €5–15k/year white-label embed.

## Solution (revised)

A module-optimisation and compliance product that:
1. Connects to the owner's energy account or accepts manual consumption data to calculate which module (1, 2, or 3) maximises their annual saving.
2. Quantifies the switching benefit in euros and generates the switching request to the Netzbetreiber.
3. For pre-2024 devices: runs the initial registration flow (postcode → Netzbetreiber lookup, form pre-fill, submission tracking).
4. Tracks confirmation from the grid operator and notifies the owner when the discount is reflected on the bill.
5. For installers: white-label portal with per-customer module recommendation, advisory documentation, and batch submission.

**What the product is NOT:** a new-device registration service for post-2024 installations. That step is already handled by the installer at commissioning.

## Business model

- **Consumer freemium:** module calculator free; €2.99–4.99/month for switching service, tracking, and annual optimisation review.
- **Installer SaaS:** €49/month up to 20 customers/month; €149/month unlimited.
- **Energy retailer licensing:** €5–15k/year white-label embed.

## Market size (revised and conservative)

- ~800,000 wallboxes registered in Germany by end 2025; ~300,000 new per year.
- Module 1 defaults: the majority of registered devices are likely on Module 1 without an active choice — this is the addressable switching pool.
- Pre-2024 unregistered devices: size unverified; needs direct validation with installers and DSOs before using in projections.
- At 5% paid conversion of 400k Module-1 devices at €3/month: ~€7.2m ARR — meaningfully smaller than the original €11m estimate and contingent on consumer willingness to pay for an analytics product.
- Installer market: ~30,000 Elektroinstallationsbetriebe in Germany; realistic paying segment is early-adopter installers with >20 §14a installations/month.

## Competitive landscape

- **gridX:** B2B energy management platform focused on DSO-side control software, not consumer advisory.
- **go-e, wallbe, Heidelberg:** hardware vendors; no module-optimisation or advisory workflow.
- **Netzbetreiber self-service portals:** exist for module switching but are operator-specific, require the owner to know which module to choose, and have no cross-operator comparability.
- **Energy retailers (Tibber, E.ON):** some offer §14a guidance as part of smart-tariff products, but only to their own customers.
- No independent, consumption-data-driven module-optimisation product exists.

## Moat and differentiation

- Module-optimisation algorithm built on real consumption data is proprietary and improves with more users.
- Database of 800+ Netzbetreiber switching procedures and forms remains a barrier to entry (though lower than originally assumed for registration, since that step is now installer-managed).
- Installer channel creates a recurring pipeline of customers entering Module 2/3 advisory at installation time.
- Aggregated anonymised SteuVE fleet data becomes valuable for grid operators and Bundesnetzagentur over time.

## Regulatory path (RDG)

No RDG exposure: the product submits a regulatory registration on behalf of the owner — analogous to a tax-filing software. The platform does not provide legal advice.

## Key risks

- **Consumer willingness to pay is the primary uncertainty.** Module optimisation saves €120–450/year; the question is whether owners pay €3–5/month for a product that does this once and then monitors passively.
- **Market size of the switching pool is unvalidated.** The number of Module-1 defaulters who would actively switch needs primary research with DSOs and installers before projections can be trusted.
- **Bundesnetzagentur standardises module selection** into a simpler 2-option regime, collapsing the optimisation complexity and the advisory value.
- **Energy retailers commoditise module advisory** by embedding it into their own apps, removing the need for an independent product.
- **Installer adoption is harder than assumed** if the product is positioned as advisory rather than pure automation — the value proposition is softer.
- **Pre-2024 device backlog is a one-time, shrinking pool** with no recurring revenue unless converted to module-optimisation subscribers.

## MVP and first 90 days (revised)

1. Weeks 1–3: interview 15 wallbox owners currently on Module 1 to validate willingness to pay for module-switching advisory; interview 5 installers on whether they document module selection for compliance.
2. Weeks 4–6: build module-comparison calculator (Module 1 vs 2 vs 3) using publicly available tariff data and user-submitted consumption; no Netzbetreiber integration yet.
3. Weeks 7–10: add switching request generation for the 10 largest Netzbetreiber; pilot with 20 Module-1 owners.
4. Weeks 11–12: validate that switched owners receive the higher discount; measure NPS and conversion to paid.

**Gate after week 3:** if fewer than 8 of 15 interviewed owners express willingness to pay €3+/month, pivot the thesis to pure installer B2B and abandon the consumer track.

## Success KPIs

- Qualified consumer interviews completed at week 3: 15 (gate: ≥8 express WTP ≥ €3/month).
- Module switch confirmations from Netzbetreiber at week 12: ≥15.
- Incremental annual saving delivered to pilot users vs Module 1 baseline: ≥€150/user.
- Installer SaaS MRR at week 12: €1,000 (lowered from original €2,000 given narrower scope).

## Scorecard (revised)

- Regulatory tailwind: 5 (unchanged — rule exists and evolves)
- Stakeholder access: 5 (unchanged — Netzbetreiber and installers accessible)
- RDG clarity: 5 (unchanged — no legal-advice exposure)
- Moat beyond first mover: 3 (unchanged — optimisation algo is real but replicable)
- Founder-market fit: 4 (unchanged)
- Path to 12-week PoV: 3 (reduced — consumer WTP validation adds a kill-switch gate)
- Scale ceiling: 2 (reduced — market is smaller and one-time for pre-2024 segment; recurring only through module evolution)
- **Total: 27/35** *(was 31/35 based on the false registration premise)*

## Stakeholders to interview in Module 2

- **10–15 wallbox owners currently on Module 1** — primary WTP validation; this is the gate interview before any build.
- **3–5 wallbox installers** — validate whether module advisory and compliance documentation is a real pain, and whether they would pay for it.
- Bundesnetzagentur, Referat SteuVE / §14a implementation team — validate how module-switching requests are processed and what standardisation is planned.
- Bayernwerk Netz GmbH, Netzanschluss team (largest regional DSO) — understand switching request volume and processing time.
- ZVEH (Zentralverband der Deutschen Elektro- und Informationstechnischen Handwerke) — understand installer obligations post-commissioning.
- Tibber Deutschland GmbH — assess whether they plan to offer module advisory natively, which would remove the consumer opportunity.
- go-e GmbH — explore installer channel partnership for module advisory at point of sale.
