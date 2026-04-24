# StVFernLV-RemoteOps

**Pillar:** [[autonomous-and-robotic-mobility]]
**One-liner:** Compliance and operator-certification platform for teleoperators under Germany's new Road Traffic Remote Control Ordinance (StVFernLV), effective 1 December 2025.
**Shortlist score:** 25/35

## Problem

Germany's Straßenverkehrs-Fernlenkungsverordnung (StVFernLV), in force from 1 December 2025, creates a legal framework for remotely controlled motor vehicles on public roads — covering use cases from remote parking to long-haul truck teleoperation. It mandates: (1) type approval for the remote-control system, (2) certification of the teleoperator as a qualified person, (3) an Betriebserlaubnis (operating licence) from the KBA, (4) a defined Betriebsgebiet (operating area) and (5) an incident-reporting obligation. No software exists to manage the certification pipeline, track teleoperator qualifications, log operational data in the StVFernLV-required format, or manage KBA Betriebserlaubnis renewals. This is an entirely new regulatory category with no established compliance tooling.

## Regulatory driver / Why now

- StVFernLV in force 1 December 2025 — the regulation is brand new.
- Companies actively deploying remote-controlled vehicles: Fernride (remote truck driving), VAY (teleoperated city car), e.Go Mobile (remote parking).
- Connection to AFGBV: teleoperators may serve as the "Technische Aufsicht" for Level 4 AVs, creating overlap with TechSupervisor-SaaS.

## Target users

- **End users:** teleoperator operations teams and compliance officers.
- **Payers:**
  - Fernride GmbH, VAY GmbH, e.Go Mobile: €1,500–3,500/month.
  - OEMs developing teleoperations systems (BMW, Mercedes): €10–30k/year enterprise.

## Solution

A compliance management platform that:
1. Manages teleoperator qualification records, training certifications, and KBA-required competency evidence.
2. Logs every remote-control session with the StVFernLV-required data fields (duration, operating area, incident flags).
3. Manages KBA Betriebserlaubnis application and renewal workflow.
4. Generates monthly and annual StVFernLV compliance reports.
5. Tracks Betriebsgebiet boundaries and alerts when sessions approach restricted zones.

## Business model

- **Subscription SaaS** per teleoperator and per vehicle in the programme.
- **KBA application consulting:** fixed-fee Betriebserlaubnis preparation.
- **AFGBV integration module** (cross-sell with TechSupervisor-SaaS).

## Market size (top-down)

- ~20 active teleoperations companies in Germany; ~100 expected by 2027.
- At €24k average ACV and 50% penetration by 2027: SAM €1.2m; TAM grows with teleoperation adoption globally as EU and US adopt similar frameworks.

## Competitive landscape

- No dedicated StVFernLV compliance platform exists (law is brand-new).
- Safety management software (IFS, SAP QM): not StVFernLV-specific.

## Moat and differentiation

- First-mover in an entirely new regulatory category: the platform shapes what "compliant" looks like.
- Session-log data from early operators is a unique dataset for regulatory evidence.
- AFGBV integration creates a natural bundle for operators running both AV and teleop programmes.

## Regulatory path (RDG)

No RDG exposure: operational compliance management and reporting is not a legal service.

## Key risks

- Teleoperations adoption is slower than expected; market remains very small.
- KBA develops an official compliance portal directly for operators.
- StVFernLV is amended significantly in its first year.

## MVP and first 90 days

1. Weeks 1–3: read full StVFernLV text; interview KBA teleop team + Fernride + VAY.
2. Weeks 4–7: build teleoperator qualification tracker, session logger, and KBA Betriebserlaubnis checklist.
3. Weeks 8–12: run 1 pilot with an active teleoperations company; log first 100 sessions.

## Success KPIs

- StVFernLV-compliant session logs generated at week 12 (target: 200).
- Teleoperator certifications tracked (target: 10).
- Signed pilot (target: 1 operator).

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

- Kraftfahrt-Bundesamt (KBA), StVFernLV licensing team.
- Fernride GmbH, Munich — remote truck driving, first StVFernLV use case.
- VAY GmbH, Hamburg — teleoperated urban car.
- ADAC Technikzentrum — remote-control system type-approval.
- Taylor Wessing, automotive regulatory practice.
