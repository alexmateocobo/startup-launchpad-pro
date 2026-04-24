# §14a-Optimizer

**Pillar:** [[ev-charging-infrastructure]]
**One-liner:** Consumer and installer SaaS that automatically registers EV chargers under Germany's §14a EnWG, claims the grid-fee discount (€110–190/year), and manages grid-operator communication — a benefit most charger owners don't know they're entitled to.
**Shortlist score:** 31/35 · #high-score

## Problem

§14a EnWG (Energiewirtschaftsgesetz) came into force on 1 January 2024. Any EV charger, heat pump, or battery system above 4.2 kW installed after that date must be registered with the local grid operator (Netzbetreiber) as a "controllable energy consumer" (steuerbare Verbrauchseinrichtung, SteuVE). In exchange, the owner receives a grid-fee reduction of €110–190 per year. However: the registration process requires knowing which Netzbetreiber covers the property (there are over 800 in Germany), completing a different form per operator, accepting interruptibility conditions, and understanding Module 1 vs Module 2 vs Module 3 tariff options. Most wallbox installers complete the installation and hand the owner a manual — the registration is left to the owner, who almost never completes it. Billions of euros in unclaimed discounts are accumulating.

## Regulatory driver / Why now

- §14a EnWG mandatory for all new controllable devices from 1 January 2024; now affecting hundreds of thousands of wallboxes per year.
- Time-variable grid charges (Module 2) became optional from 1 April 2025, creating additional savings opportunities.
- Bundesnetzagentur is auditing compliance; grid operators face penalties for failing to accept registrations.

## Target users

- **End users:** EV charger owners (consumers and SMEs); wallbox installers (Elektroinstallateure).
- **Payers:**
  - Consumers via freemium (free registration wizard; premium analytics dashboard: €2.99/month).
  - Wallbox installers: white-label tool at €29–99/month to offer automated §14a registration as a value-add service.
  - Energy retailers (Vattenfall, E.ON, Tibber): embedded tool to retain EV customers.

## Solution

A wizard-and-dashboard product that:
1. Asks postcode + charger specs → identifies the correct Netzbetreiber automatically.
2. Pre-fills the operator-specific registration form and submits via API or structured email.
3. Confirms Module selection (Module 1 flat discount vs Module 2 time-variable).
4. Tracks registration status, annual discount confirmation, and notifies when the discount appears on the bill.
5. For installers: white-label portal with batch registration for all customers.

## Business model

- **Consumer freemium:** registration wizard free; €2.99/month for savings dashboard and annual confirmation tracker.
- **Installer SaaS:** €49/month up to 20 customers/month; €149/month unlimited.
- **Energy retailer licensing:** €5–15k/year white-label embed.

## Market size (top-down)

- ~800,000 wallboxes registered in Germany by end 2025; ~300,000 new per year.
- Estimated registration gap: >70% of eligible devices not yet registered.
- At 5% premium conversion of addressable 600k unregistered devices: €11m ARR consumer-side alone.
- Installer market: ~30,000 Elektroinstallationsbetriebe in Germany.

## Competitive landscape

- **gridX:** B2B energy management platform, not a consumer registration tool.
- **go-e, wallbe, Heidelberg:** hardware vendors, no registration workflow.
- **Netzbetreiber self-service portals:** exist but are fragmented, often paper-based.
- No consumer-facing §14a registration SaaS exists.

## Moat and differentiation

- Database of 800+ Netzbetreiber forms and API endpoints is proprietary and continuously maintained.
- First-mover installer channel creates a recurring data pipeline of new registrations.
- Aggregated opt-in data on SteuVE fleet becomes valuable for grid operators and Bundesnetzagentur.

## Regulatory path (RDG)

No RDG exposure: the product submits a regulatory registration on behalf of the owner — analogous to a tax-filing software. The platform does not provide legal advice.

## Key risks

- Bundesnetzagentur standardises the registration API across all operators, reducing the complexity advantage.
- Netzbetreiber resist automation, requiring manual form submission.
- Consumer willingness to pay is low for a €150/year saving.

## MVP and first 90 days

1. Weeks 1–3: map the 50 largest Netzbetreiber (covering ~60% of German wallboxes); interview 10 wallbox installers.
2. Weeks 4–7: build postcode → Netzbetreiber lookup, form pre-filler, and submission tracker; pilot with 3 installers.
3. Weeks 8–12: process 100 registrations; collect first confirmed discount letters from grid operators.

## Success KPIs

- Registrations submitted at week 12 (target: 150).
- Confirmation rate from Netzbetreiber (target: >80%).
- Installer SaaS MRR at week 12 (target: €2,000).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 5
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 4
- Path to 12-week PoV: 5
- Scale ceiling: 4
- **Total: 31/35**

## Stakeholders to interview in Module 2

- Bundesnetzagentur, Referat SteuVE / §14a implementation team.
- Bayernwerk Netz GmbH, Netzanschluss team (largest regional DSO).
- ZVEH (Zentralverband der Deutschen Elektro- und Informationstechnischen Handwerke) — wallbox installer association.
- Tibber Deutschland GmbH — energy retailer with smart-charging positioning.
- go-e GmbH — wallbox manufacturer for installer channel partnership.
