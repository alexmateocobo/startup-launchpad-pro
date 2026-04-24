# ISO15118-Retrofit

**Pillar:** [[ev-charging-infrastructure]]
**One-liner:** Firmware-update and OCPP 2.0.1 retrofit service that brings existing public AC chargers into ISO 15118-2 compliance before the 8 January 2026 mandatory deadline — as a managed SaaS with ongoing compliance monitoring.
**Shortlist score:** 27/35
**Tags:** #b2b #saas #ev #compliance

## Problem

ISO 15118-2 (Plug & Charge, smart charging communication) became mandatory for all newly installed publicly accessible AC charging stations in Germany and across the EU from 8 January 2026. This affects not just new purchases but any charger installed or renovated after that date. Hundreds of CPOs operating chargers purchased between 2020 and 2025 — before the ISO 15118-2 requirement was widely known — have hardware that supports the standard but has not been configured or firmware-updated to activate it. The update process requires: (1) hardware capability check, (2) firmware update from the manufacturer, (3) OCPP 2.0.1 configuration on the backend, (4) TLS certificate management for the secure connection, and (5) ongoing monitoring that the 15118 handshake is completing correctly. Many CPOs have no internal capacity to manage this and face compliance risk for every charger they install or renovate.

## Regulatory driver / Why now

- ISO 15118-2 mandatory for new/renovated public AC chargers from 8 January 2026 — deadline already passed.
- CPOs that have installed chargers in 2025–2026 without activating ISO 15118-2 are already in breach.
- From January 2027, ISO 15118-20 (V2G) adds a second mandatory layer on top.
- Bundesnetzagentur AFIR compliance reviews will include ISO 15118 checks.

## Target users

- **End users:** CPO technical teams and facility managers running public AC charger networks.
- **Payers:**
  - CPOs with 20–500 public AC chargers: €150–400 per charger (one-time retrofit) + €20/charger/month monitoring.

## Solution

A managed retrofit service that:
1. Audits the CPO's charger fleet by model against an ISO 15118-2 capability database (maintained in partnership with hardware manufacturers).
2. Schedules and deploys firmware updates remotely for compatible models (ABB, Alfen, Webasto, Phoenix Contact).
3. Configures OCPP 2.0.1 on the CPO backend with ISO 15118 profiles.
4. Issues and manages TLS certificates for the 15118 secure communication layer.
5. Provides ongoing monitoring: alerts when a charger's 15118 handshake fails persistently.

## Business model

- **One-time retrofit fee** per charger model (€150–300/charger).
- **Ongoing monitoring SaaS:** €20/charger/month.
- **Manufacturer partnership:** revenue share on firmware update fees billed through the platform.

## Market size (top-down)

- ~60,000 public AC charging points in Germany; ~40,000 installed before ISO 15118-2 was widely configured.
- At €200 one-time retrofit + €20/month monitoring and 20% addressable share: SAM €8m one-time + €1.9m ARR.

## Competitive landscape

- **Charger manufacturers (ABB, Alfen):** offer firmware updates but not as a managed service with monitoring.
- **AMPECO, GreenFlux:** CPO software; no retrofit service.
- No managed ISO 15118 retrofit service exists.

## Moat and differentiation

- Charger model compatibility database is built from direct manufacturer partnerships and is difficult to replicate.
- TLS certificate management creates an ongoing operational dependency.
- Retrofit customer base converts naturally to V2G (ISO 15118-20) upgrade clients in 2026–2027.

## Regulatory path (RDG)

No RDG exposure: firmware updates and compliance monitoring are a technical service.

## Key risks

- Manufacturers offer free firmware updates that include full ISO 15118-2 activation, removing the retrofit opportunity.
- CPOs replace non-compliant chargers rather than retrofit.
- The monitoring SaaS ARR is too thin without the retrofit one-time revenue.

## MVP and first 90 days

1. Weeks 1–3: map ISO 15118-2 firmware support for the top 10 AC charger models by installed base in Germany; interview 5 CPOs.
2. Weeks 4–7: develop a retrofit workflow for ABB Terra AC and Alfen Eve Single; run first 10 updates.
3. Weeks 8–12: complete 50 retrofits; launch monitoring dashboard for pilot CPOs.

## Success KPIs

- Chargers retrofitted at week 12 (target: 50).
- ISO 15118-2 handshake success rate post-retrofit (target: >95%).
- Monthly monitoring ARR at week 12 (target: €1,000).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 4
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 3
- **Total: 27/35**

## Stakeholders to interview in Module 2

- Bundesnetzagentur, AFIR ISO 15118 compliance enforcement.
- ABB E-mobility GmbH, firmware and certification team.
- Alfen B.V., Germany market team.
- EnBW mobility+, charging-network technical lead.
- CharIN e.V. — ISO 15118 standards body.
