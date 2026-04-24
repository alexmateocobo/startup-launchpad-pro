# V2G-Stack

**Pillar:** [[vehicle-grid-integration]]
**One-liner:** ISO 15118-20 Vehicle-to-Grid compliance middleware for Charge Point Operators and Virtual Power Plant aggregators, ahead of the January 2027 mandatory bidirectional charging standard.
**Shortlist score:** 28/35
**Tags:** #b2b #saas #middleware #ev #compliance

## Problem

ISO 15118-20 — the international standard enabling bidirectional (V2G) charging communication between EVs and chargers — becomes mandatory for all newly installed or renovated publicly accessible charging points in Germany and across the EU from January 2027, per EU AFIR transposition. This is an enormous technical lift: V2G requires a certified communication layer between the EV, the EVSE, and the grid operator's backend, with Eichrecht-compliant metering for energy flows in both directions. CPOs must also integrate with Virtual Power Plant (VPP) aggregators to monetise the flexibility. Currently, no off-the-shelf middleware covers the full stack: ISO 15118-20 implementation + Eichrecht bidirectional metering + VPP API. CPOs and energy suppliers are building this bespoke at €500k–2M each.

## Regulatory driver / Why now

- ISO 15118-20 mandatory for all new/renovated public chargers in Germany from January 2027.
- §14a EnWG creates a financial incentive for grid flexibility that V2G unlocks at scale.
- EU Network Code on Demand Response (under ENTSO-E) being finalised in 2025–2026, creating the VPP participation framework.
- Germany's Masterplan Charging Infrastructure 2030 explicitly targets bidirectional charging as a grid-stability tool.

## Target users

- **End users:** CPO technical teams; energy supplier VPP aggregation teams; EV OEM software teams.
- **Payers:**
  - CPOs: €2,000–6,000/month per 100 V2G-capable chargers under management.
  - Energy suppliers (VPP): €40–120k/year for aggregation integration.

## Solution

A B2B middleware platform that:
1. Implements the ISO 15118-20 communication stack as a managed service (SECC software run in the cloud or on-premise).
2. Handles Eichrecht-compliant bidirectional metering (signed meter values for energy delivered and fed back).
3. Provides a VPP API for aggregators to schedule charge/discharge events.
4. Generates PTB-compliant transparency reports for both directions.
5. Produces AFIR Article 20 data exports including V2G session records.

## Business model

- **Managed-service SaaS** per V2G-capable charger.
- **VPP integration fee:** one-time integration + monthly API access.
- **Certification consulting:** support for CPOs obtaining PTB approval for V2G metering.

## Market size (top-down)

- ~100,000 public charging points in Germany expected to be V2G-capable by 2030.
- EU-wide: potentially 2–3 million V2G-capable public chargers by 2030.
- At €300/year per charger under management and 5% EU penetration: TAM €45m ARR (2030 horizon).

## Competitive landscape

- **gridX:** home energy management, no public CPO V2G stack.
- **Jedlix, ev.energy:** smart charging optimisation, not ISO 15118-20 middleware.
- **OEM-specific V2G solutions (Volkswagen, Nissan Leaf):** closed ecosystems.
- No independent ISO 15118-20 middleware-as-a-service exists.

## Moat and differentiation

- ISO 15118-20 is technically complex; implemented stack takes 12–18 months to build from scratch.
- PTB certification for bidirectional metering creates a regulatory barrier to entry.
- Multi-CPO aggregated flexibility dataset becomes valuable for grid operators.

## Regulatory path (RDG)

No RDG exposure: technical middleware and compliance tooling is not a legal service.

## Key risks

- OEMs or major CPOs (EnBW, IONITY) build this in-house.
- ISO 15118-20 adoption delayed beyond 2027 due to slow EV OEM implementation.
- PTB certification for bidirectional metering takes longer than expected.

## MVP and first 90 days

1. Weeks 1–3: interview 5 CPOs and 3 VPP aggregators; map the ISO 15118-20 SECC implementation scope.
2. Weeks 4–8: implement a lab-tested ISO 15118-20 SECC prototype with one compatible EV model (Volkswagen ID.4 or Hyundai Ioniq 5).
3. Weeks 9–12: run a live V2G pilot with one CPO and one VPP aggregator; collect first session data.

## Success KPIs

- V2G sessions completed in pilot (target: 50 at week 12).
- Bidirectional metering accuracy (target: <0.5% deviation vs reference meter).
- Signed pilot agreement with CPO at week 12 (target: 1).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 4
- Founder-market fit: 3
- Path to 12-week PoV: 3
- Scale ceiling: 5
- **Total: 28/35**

## Stakeholders to interview in Module 2

- CharIN e.V. — ISO 15118-20 working group.
- Physikalisch-Technische Bundesanstalt (PTB) — bidirectional Eichrecht certification.
- EnBW mobility+, Head of Technical Innovation.
- Next Kraftwerke (RWE) — VPP aggregation team.
- Volkswagen Group Components, e-mobility charging team.
