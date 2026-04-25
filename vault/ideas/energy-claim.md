# Energy Claim

**Pillar:** [[consumer-rights-awareness-and-enforcement]]
**One-liner:** Automated audit and enforcement platform for German household and SME energy bills — detecting billing errors, levy miscalculations, and missed statutory entitlements, then pursuing refund via RDG-compliant Inkasso.
**Shortlist score:** 26/35
**Tags:** #b2c #app #legal #success-fee #energy #claim

## Problem

The [BNetzA Verbraucherservice Energie](https://www.bundesnetzagentur.de/DE/Verbraucher/Energie/energie-node.html) received 56,538 inquiries in 2025 (57,000 per the 16.01.2026 press release), down slightly from 58,994 in 2024 and 61,401 in 2023 — sustained record volumes. The [Schlichtungsstelle Energie](https://www.schlichtungsstelle-energie.de/) logged 19,074 formal arbitration applications in 2025, of which 6,200 were concentrated on just four providers — a clear signal of systematic, provider-level errors rather than isolated disputes. Billing errors, wrong meter readings, and unpaid Guthaben account for the majority of cases. Most consumers absorb the loss: only a fraction of affected households ever reach formal arbitration, and the average SSE case takes 163 days to close.

## Why now

- [§14a EnWG](https://www.gesetze-im-internet.de/enwg_2005/__14a.html) Modul 3 (mandatory since 01.04.2025) entitles EV and heat pump customers to €110–190/year Netzentgelt reductions — but only 2.18% of metering points have the required smart meter installed. Messwesen complaints at [BNetzA](https://www.bundesnetzagentur.de/) rose 74% YoY (1,009→1,757 in 2025) as Messkonzept transitions fail at scale.
- [VDuG](https://www.gesetze-im-internet.de/vdug/) Abhilfeklage allows qualified entities to recover damages collectively. Energy providers are increasingly targeted.
- [BNetzA](https://www.bundesnetzagentur.de/) AgNeS discussion paper (12.05.2025) is revising the network tariff pass-through framework, raising systematic scrutiny of Netzentgelt components.
- Federal energy relief package (€10bn/year, 2026) generates another auditable pass-through event at ~42 million household contracts.
- [OLG Oldenburg](https://www.olgol.niedersachsen.de/) ruling (Az 6 UKl 2/25, 05.12.2025): Gas Stilllegungskosten for heat pump switching declared unlawful — BGH revision pending, class-action window open.

## Target users

- **End users:** German households and SMEs with recent Strom or Gas Jahresabrechnung.
- **Payers:** End users on success-fee terms (Inkasso model); Verbraucherzentralen licensing the analysis engine (€10–20k/year); SME Gewerbekunden (€49–149 per audited bill above 50 MWh).

## Solution

A mobile app that: (1) accepts photo or PDF upload of Strom/Gas bills; (2) parses Abschlagspläne, Preisbremsen, Arbeitspreis, Grundpreis, Netzentgelt, and all statutory levies; (3) cross-references against [BNetzA](https://www.bundesnetzagentur.de/) Netzentgelte, supplier tariff catalogues, and Grundversorger benchmarks; (4) flags violations and calculates the expected refund; (5) generates a demand letter and escalates via Inkasso or [Schlichtungsstelle Energie](https://www.schlichtungsstelle-energie.de/).

## Business model

- Consumer success fee: 25–35% of recovered amount (RDG-licensed Inkassodienstleister).
- Verbraucherzentrale licence: €10–20k/year for the analysis engine.
- SME package: €49–149 per audited bill above 50 MWh.

## Market size

~42 million household Strom + ~20 million Gas contracts. At 5% audit penetration and €50 recovered per positive case, TAM ~€150m/year on recovery alone. SME layer adds €50–100m.

## Evidence

**Demand signal — official 2025/2026 data**

[SSE Tätigkeitsbericht 2025](https://www.schlichtungsstelle-energie.de/) (published 01.02.2026) complaint breakdown:

| Error type | SSE cases (2025) |
|---|---|
| Meter reading errors (Zählerstand, Schätzung, Verwechslung, Defekt) | 3,793 |
| Disputed billing / wrong periods | 2,010 |
| Guthaben not paid out | 1,081 |
| Bill never issued | 1,719 |
| Wrong advance payments (Abschlag) | 390 |
| Disputed price increase | 852 |
| Smart metering / §14a issues | 601 |
| Strompreisbremse (still arriving in 2025) | 222 |

[BNetzA](https://www.bundesnetzagentur.de/) data portal (16.01.2026): Abrechnung inquiries spiked to 7,201 in 2023 (Strompreisbremse year, nearly 3× baseline), still elevated at 2,457 in 2025. Messwesen rising consecutively: 595 → 1,009 → 1,757.

## Competitive landscape

- **[Check24](https://www.check24.de/), [Verivox](https://www.verivox.de/):** price comparison only.
- **[rightmart](https://www.rightmart.de/):** energy claims, narrow scope (Gaskonto disputes).
- **[Verbraucherzentralen](https://www.verbraucherzentrale.de/):** high-touch, throughput-limited, no Inkasso.
- **[Schlichtungsstelle Energie](https://www.schlichtungsstelle-energie.de/):** public mediator, 163-day average resolution, no recovery automation.

## Moat and differentiation

Tariff-rule engine ingesting [BNetzA](https://www.bundesnetzagentur.de/) Netzentgelt tables, supplier tariff catalogues, and annual levy rate schedules — compounding dataset that is expensive to replicate. Inkasso licence (Inkassodienstleister) is a hard regulatory barrier. Dataset enables future predictive pricing for SME buyers. Precedent: [Flightright](https://www.flightright.de/), [Conny](https://www.conny.de/) (same RDG model in adjacent verticals).

## Key risks

- Mis-parsing complex tariff structures (multi-period, Grundversorger fallback, HT/NT splits) can create false positives that damage recovery rate and brand.
- VDuG class actions may subsume individual recovery for the highest-value violations, reducing the per-case addressable amount.
- Regulatory changes (e.g. further §14a amendments, new Preisbremse instruments) require rapid rule-engine updates.

## MVP and first 90 days

1. Weeks 1–3: interview 10 [Stadtwerke München](https://www.swm.de/) customers in Bayern and 5 energy advisors at [Verbraucherzentrale Bayern](https://www.verbraucherzentrale-bayern.de/).
2. Weeks 4–7: build the Jahresabrechnung parser for [Stadtwerke München](https://www.swm.de/); ground-truth against five real bills.
3. Weeks 8–12: pursue 10 test refund claims via demand letters; measure recovery rate.

## Success KPIs

- Auto-detection precision vs. expert audit: target 95%.
- Average recovery per positive case: target €60–120.
- Cost per successful resolution: target <€15.

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 3
- RDG clarity: 4
- Moat beyond first mover: 3
- Founder-market fit: 4
- Path to 12-week PoV: 4
- Scale ceiling: 4
- **Total: 26/35**

## Stakeholders to interview in Module 2

- Energieberater at [Verbraucherzentrale Bayern](https://www.verbraucherzentrale-bayern.de/).
- Customer-service supervisor at [Stadtwerke München](https://www.swm.de/) (counter-perspective).
- [Schlichtungsstelle Energie](https://www.schlichtungsstelle-energie.de/), Berlin.
- SME Gewerbekunde with 100–500 MWh/year consumption.
- [BNetzA](https://www.bundesnetzagentur.de/), Abteilung Verbraucherservice Energie.
