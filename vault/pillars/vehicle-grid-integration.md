# Vehicle Grid Integration

**Track:** [[mobility]]

## Description

Middleware and compliance tooling enabling bidirectional energy flow between electric vehicles and the grid (V2G — Vehicle-to-Grid). ISO 15118-20, which governs the communication protocol for bidirectional charging, becomes mandatory for all new and renovated public chargers in Germany from January 2027. The technical complexity — a certified ISO 15118-20 communication stack, Eichrecht-compliant bidirectional metering, and VPP aggregator API integration — means CPOs and energy suppliers currently spend €500k–2m each building bespoke solutions. Germany's §14a EnWG creates the economic incentive (grid-fee discounts for controllable devices) that makes V2G commercially attractive for consumers and operators alike.

## Key Regulations

| Regulation | What it requires | In force |
|---|---|---|
| ISO 15118-20 | Bidirectional charging communication standard mandatory for new/renovated public chargers | January 2027 (DE / EU AFIR) |
| §14a EnWG | Controllable energy devices (including V2G chargers) must register with the grid operator; grid-fee discount in return | Since 1 January 2024 |
| EU Network Code on Demand Response | Defines the framework for VPP participation and flexibility market access | Being finalised 2025–2026 |
| AFIR Article 20 | V2G session data must be published to national access points in DATEX II format | 14 April 2026 |
| Eichrecht (Mess- und Eichgesetz) | Metering of energy in both directions must be PTB-certified for billing validity | Ongoing |

## Market Size

- ~100,000 public charging points in Germany expected to be V2G-capable by 2030.
- EU-wide: potentially 2–3 million V2G-capable public chargers by 2030.
- At €300/year per charger under management and 5% EU penetration: TAM ~€45m ARR (2030 horizon).
- VPP aggregator market (energy supplier side): additional €40–120k/year per aggregator.

## Competitive Landscape

| Player | Origin | Positioning | Gap |
|---|---|---|---|
| gridX | DE | Home energy management for CPOs and utilities | No public CPO V2G or ISO 15118-20 middleware |
| Jedlix | NL | Smart charging optimisation for fleet and home | Not ISO 15118-20 middleware; no bidirectional metering |
| ev.energy | UK | Smart charging for CPOs and utilities | North American focus; no ISO 15118-20 stack |
| OEM-specific V2G (VW, Nissan, Hyundai) | DE/JP/KR | Closed-ecosystem bidirectional solutions | Not interoperable across charger networks |
| Next Kraftwerke (RWE) | DE | VPP aggregation | Energy side only; no charger-side middleware |

## Best-in-Class Benchmarks

- **CharIN e.V. ISO 15118-20 test suite** — the industry benchmark for protocol conformance testing.
- **PTB (Physikalisch-Technische Bundesanstalt)** — sets the standard for Eichrecht-certified bidirectional metering; any V2G product must achieve PTB approval for commercial billing.
- **Nissan LEAF V2H / V2G (Nissan Energy)** — earliest large-scale V2G deployment; demonstrates consumer adoption patterns and session data requirements.

## Key Bodies and Resources

- [CharIN e.V.](https://www.charin.global) — ISO 15118-20 working group and test infrastructure
- [PTB](https://www.ptb.de) — bidirectional Eichrecht certification authority
- [Bundesnetzagentur](https://www.bundesnetzagentur.de) — §14a EnWG implementation and SteuVE registry
- [ENTSO-E](https://www.entsoe.eu) — EU Network Code on Demand Response
- [Germany Masterplan Ladeinfrastruktur 2030](https://bmdv.bund.de) — national V2G roadmap
