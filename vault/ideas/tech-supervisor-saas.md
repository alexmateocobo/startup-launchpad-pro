# TechSupervisor-SaaS

**Pillar:** [[autonomous-and-robotic-mobility]]
**One-liner:** AFGBV-compliant technical supervision platform for Level 4 autonomous vehicle operators, managing remote oversight workflows, incident logging, intervention records, and Kraftfahrt-Bundesamt reporting.
**Shortlist score:** 27/35
**Tags:** #b2b #saas #compliance #mobility

## Problem

Germany's Autonomous Vehicle Authorisation and Operation Ordinance (AFGBV, 2022) requires every Level 4 AV in public operation to be permanently supervised by a "Technische Aufsicht" (technical supervisor) — a qualified person who can remotely deactivate the driving function, authorise alternative manoeuvres, and alert passengers. Regular L4 commercial operations in Germany are planned from 2026 (per the Federal Autonomous Driving Strategy). Each operator must document every supervision session, every intervention, and every minimal-risk-condition event for the Kraftfahrt-Bundesamt (KBA) and the Bundesanstalt für Straßenwesen (BASt). There is no standardised software for managing the technical-supervisor workflow, logging evidence in AFGBV-compliant format, or managing the certification and shift scheduling of supervisors.

## Regulatory driver / Why now

- AFGBV in force since 2022; operational-area approvals accelerating in 2025–2026.
- Germany's Federal Autonomous Driving Strategy commits to regular L4 operations from 2026.
- StVFernLV (Road Traffic Remote Control Ordinance) for teleoperations effective 1 December 2025, creating a related but distinct supervisory role.
- KBA and BASt auditing first commercial operators in 2026.

## Target users

- **End users:** technical supervision teams and operations managers at Level 4 AV operators.
- **Payers:**
  - AV operators (Motor Ai, EasyMile, NavVis, HOLON, Local Motors): €2,000–6,000/month per operational area.
  - Public transit authorities operating autonomous shuttles: €1,500–4,000/month.

## Solution

A mission-critical SaaS that:
1. Provides a real-time supervisor console: vehicle telemetry stream, intervention buttons, communication channel to vehicle.
2. Logs every session, alert, intervention, and MRC event in AFGBV-required format with cryptographic timestamping.
3. Manages technical-supervisor certification records, shift schedules, and legal authorisation per AFGBV §3.
4. Generates AFGBV-compliant monthly and annual reports for KBA/BASt submission.
5. Manages operational-area approval documentation and tracks boundary conditions.

## Business model

- **Mission-critical SaaS:** per vehicle per month; minimum-commitment annual contracts.
- **AFGBV audit support:** fixed-fee engagement for KBA audit preparation.
- **Simulator module:** training environment for supervisor certification.

## Market size (top-down)

- ~50 L4 AV deployments expected in Germany by end 2026; ~500 by 2028; ~5,000 by 2030.
- At €36k average ACV per deployment (6 vehicles per deployment average) and 60% penetration: SAM €1m in 2026; €30m in 2028; TAM €300m+ as global AV regulation converges.

## Competitive landscape

- **Foretellix, Applied Intuition:** AV testing and validation; not supervision-workflow SaaS.
- **Cognito X, Hexagon:** safety management platforms; not AFGBV-specific.
- No dedicated AFGBV Technische Aufsicht platform exists.

## Moat and differentiation

- Safety-critical software creates an extremely high switching cost once deployed.
- AFGBV audit history is a proprietary dataset that improves the product's evidence-pack quality over time.
- Early operator relationships lock in the platform for multi-year operational periods.

## Regulatory path (RDG)

No RDG exposure: operational safety management and regulatory reporting software is not a legal service.

## Key risks

- AV operators build bespoke supervision software in-house given safety-criticality.
- L4 commercial operations are delayed beyond 2026 by technical readiness or political friction.
- KBA changes AFGBV reporting requirements, requiring costly redevelopment.

## MVP and first 90 days

1. Weeks 1–3: interview 3 AV operators (EasyMile, HOLON, Motor Ai) + KBA/BASt technical team.
2. Weeks 4–7: build a supervisor console prototype and AFGBV session-log generator; run a sandbox simulation.
3. Weeks 8–12: pilot with one AV operator in a low-risk operational area; log first 100 AFGBV-compliant sessions.

## Success KPIs

- AFGBV session logs generated at week 12 (target: 200).
- Supervisor console uptime (target: 99.9%).
- Signed pilot agreement with AV operator (target: 1).

## Scorecard

- Regulatory tailwind: 5
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 4
- Founder-market fit: 3
- Path to 12-week PoV: 3
- Scale ceiling: 4
- **Total: 27/35**

## Stakeholders to interview in Module 2

- Kraftfahrt-Bundesamt (KBA), AFGBV technical team.
- Bundesanstalt für Straßenwesen (BASt), autonomous vehicle group.
- EasyMile GmbH, operations team (running autonomous shuttles in German cities).
- Motor Ai, Berlin (Level 4 commercial deployment 2025–2026).
- ADAC Stiftung, autonomous mobility safety programme.
