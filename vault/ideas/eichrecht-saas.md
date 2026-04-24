# Eichrecht-SaaS

**Pillar:** [[ev-charging-infrastructure]]
**One-liner:** PTB-compliant meter-value signing, transparency-software delivery, and audit-trail management middleware for small and mid-size Charge Point Operators who cannot afford bespoke Eichrecht integration.
**Shortlist score:** 25/35

## Problem

Germany's Eichrecht (calibration law, MessEG/MessEV) requires every public charging point billing by kWh to use a PTB-certified electricity meter whose readings are digitally signed with a private key stored in the charger, and to make the public key available to drivers for independent verification. This metrological requirement is technically complex: the charger firmware must implement a PTB-approved signing scheme, the signed meter values must be stored securely, and a "transparency software" must be made available for drivers to verify their bill. The three largest CPO software vendors (AMPECO, Driivz, GreenFlux) support Eichrecht natively — but for the ~400 smaller CPOs in Germany using custom backends or older charger models, Eichrecht compliance remains a patchwork of manual workarounds, with no managed service available.

## Regulatory driver / Why now

- Eichrecht has been enforced since 2017; enforcement tightening as Marktüberwachungsbehörden increase spot checks.
- ISO 15118-20 (V2G, mandatory 2027) adds a new bidirectional metering requirement on top of existing Eichrecht.
- AFIR Article 20 data publication includes session-level kWh data that must be Eichrecht-consistent.

## Target users

- **End users:** technical operations teams at small and mid-size CPOs.
- **Payers:**
  - Small CPOs (under 50 chargers): €300–700/month.
  - Mid-size CPOs (50–200 chargers): €800–2,000/month.

## Solution

A middleware SaaS that:
1. Accepts raw OCPP 2.0.1 meter-value messages from the CPO's backend.
2. Validates PTB compliance of the incoming signed data.
3. Stores signed meter values in an immutable audit log.
4. Hosts the required transparency software on the CPO's behalf (linked via QR code on charger).
5. Generates Eichrecht-compliant CDR (Charge Detail Records) for billing systems.

## Business model

- **Subscription SaaS** per charger under management.
- **Transparency-software hosting:** included in base plan.
- **Audit-pack generation:** on demand, per inspection event.

## Market size (top-down)

- ~400 smaller CPOs in Germany not natively supported by the top 3 backends.
- At €10k average ACV and 25% penetration: SAM €1m Germany; EU extension (similar Eichrecht-analogue requirements in Netherlands, Austria) adds TAM.

## Competitive landscape

- **AMPECO, Driivz, GreenFlux:** large-CPO platforms with native Eichrecht; not targeting small CPOs.
- **S.A.F.E. e.V.:** Eichrecht standards body; no commercial product.
- **chargeIT mobility:** German CPO software with Eichrecht; full platform, not modular middleware.
- No middleware-only Eichrecht service for small CPOs.

## Moat and differentiation

- PTB certification expertise is narrow and trust-based; once certified, operators rarely switch.
- Transparency-software hosting creates an ongoing relationship with every CPO customer.
- V2G Eichrecht layer (bidirectional metering) will be an upsell for the same customer base from 2027.

## Regulatory path (RDG)

No RDG exposure: metering-compliance middleware is a technical product, not a legal service.

## Key risks

- OCPP backend vendors (AMPECO, EV.energy) extend Eichrecht support to smaller tier plans.
- PTB certifies a new signing scheme that requires complete platform rebuild.
- Small CPO market consolidates; fewer but larger buyers.

## MVP and first 90 days

1. Weeks 1–3: interview 5 small CPOs + Bayerisches Landesamt für Maß und Gewicht (Marktüberwachung).
2. Weeks 4–7: build OCPP meter-value validator, audit-log storage, and transparency-software QR-code generator.
3. Weeks 8–12: pilot with 3 CPOs (10 chargers each); survive one Marktüberwachung spot check.

## Success KPIs

- Chargers under Eichrecht management at week 12 (target: 30).
- Transparency-software QR codes scanned per month by drivers (target: 50).
- Signed CPOs at week 12 (target: 3).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 4
- Founder-market fit: 3
- Path to 12-week PoV: 3
- Scale ceiling: 3
- **Total: 25/35**

## Stakeholders to interview in Module 2

- Physikalisch-Technische Bundesanstalt (PTB), Eichrecht team.
- Bayerisches Landesamt für Maß und Gewicht — Marktüberwachung EV chargers.
- S.A.F.E. e.V. (Standardization Agency For E-Mobility) — Eichrecht standards body.
- chargeIT mobility GmbH — potential partner or competitor.
- 5 small CPO operators (hotels, parking operators, municipal utilities).
