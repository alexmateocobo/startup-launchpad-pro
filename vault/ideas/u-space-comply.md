# U-Space-Comply

**Pillar:** [[autonomous-and-robotic-mobility]]
**One-liner:** EASA-compliant drone operational authorisation, U-Space flight planning, and Remote ID management SaaS for commercial drone operators in Germany targeting BVLOS logistics and infrastructure inspection.
**Shortlist score:** 26/35

## Problem

EU Regulation 2019/947 and the U-Space framework (EU Regulation 2021/664) require commercial drone operators in "Specific" and "Certified" categories to obtain an Operational Authorisation from the Luftfahrt-Bundesamt (LBA), maintain Remote ID compliance, and — in designated U-Space airspace — file real-time flight plans with a certified U-Space Service Provider (USS). Beyond Visual Line of Sight (BVLOS) operations — the economically significant use case for logistics and infrastructure inspection — require a separate LBA waiver, a complex ConOps document, and ongoing safety-case maintenance. German companies pursuing drone delivery (Wingcopter, Volocopter for air taxis, Quantum-Systems for inspection) each build bespoke regulatory compliance processes. Fines for non-compliance reach €50,000.

## Regulatory driver / Why now

- EASA 2019/947 fully enforced across EU; Operational Authorisation mandatory for Specific category.
- U-Space regulation (2021/664) being implemented city by city in Germany; Hamburg and Munich U-Space zones planned for 2026.
- Remote ID mandatory for most commercial drones in controlled urban airspace from 2025.
- DFS (Deutsche Flugsicherung) is the German U-Space provider; operators need compliant integration.

## Target users

- **End users:** drone operations and safety teams at commercial drone operators and logistics companies.
- **Payers:**
  - Commercial drone operators (Wingcopter, Quantum-Systems, Volocopter): €500–2,000/month.
  - Logistics companies adopting drone delivery (DHL, DB Schenker): €2,000–8,000/month.
  - Infrastructure inspection companies (DEKRA, TÜV): €300–900/month.

## Solution

A regulatory compliance SaaS that:
1. Manages LBA Operational Authorisation applications: ConOps generator, SORA (Specific Operations Risk Assessment) calculator, document tracker.
2. Integrates with DFS/U-Space API for real-time flight-plan filing and airspace conflict detection.
3. Manages Remote ID registration and broadcasting compliance per drone in the fleet.
4. Tracks BVLOS waiver conditions and triggers alerts when operations approach waiver boundaries.
5. Generates LBA annual compliance reports and incident notifications.

## Business model

- **Subscription SaaS** per drone and per operational area.
- **SORA consulting:** fixed-fee ConOps preparation for BVLOS waiver applications.
- **EU expansion:** connector to national aviation authorities in FR, ES, NL (same EASA framework).

## Market size (top-down)

- ~5,000 commercial drone operators registered in Germany; ~500 in Specific/Certified category needing authorisation.
- At €12k average ACV and 15% penetration in Germany: SAM €900k; EU TAM (20,000 Specific-category operators) €36m.

## Competitive landscape

- **AirMap (acquired by Airbus):** US-focused UTM platform.
- **DJI FlySafe:** hardware-vendor-centric; no EASA compliance workflow.
- **Unifly:** Belgian UTM provider; operational authorisation workflow limited.
- No dedicated EASA/LBA compliance SaaS with SORA + U-Space integration.

## Moat and differentiation

- SORA calculator is non-trivial to implement correctly; verified calculation creates trust.
- DFS integration partnership (once established) is difficult for competitors to replicate.
- ConOps document library from completed authorisations becomes a proprietary template base.

## Regulatory path (RDG)

No RDG exposure: regulatory document preparation and flight-plan filing is operational compliance software. ConOps documents should be presented as templates requiring operator certification.

## Key risks

- DFS builds a compliance portal directly for operators, disintermediating the SaaS.
- BVLOS waiver approvals remain slow regardless of software quality.
- Market remains niche until BVLOS drone logistics achieves commercial viability.

## MVP and first 90 days

1. Weeks 1–3: interview LBA BVLOS team + 3 drone operators + DFS U-Space team.
2. Weeks 4–7: build SORA risk-score calculator and LBA Operational Authorisation document generator.
3. Weeks 8–12: pilot with 2 drone operators; submit 3 Operational Authorisation applications.

## Success KPIs

- Operational Authorisations submitted at week 12 (target: 3).
- SORA risk assessments completed (target: 10).
- Signed operator subscriptions (target: 3).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 4
- **Total: 26/35**

## Stakeholders to interview in Module 2

- Luftfahrt-Bundesamt (LBA), Unmanned Aircraft Systems team.
- DFS Deutsche Flugsicherung, U-Space programme.
- Wingcopter GmbH, regulatory team.
- Quantum-Systems GmbH, compliance team.
- BDLI (German Aerospace Industry Association) — drone working group.
