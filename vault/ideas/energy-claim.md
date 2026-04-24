# Energy Claim

**Pillar:** [[consumer-rights-awareness-and-enforcement]]
**One-liner:** Automated audit and enforcement platform for German household and SME energy bills — detecting Strompreisbremse violations, billing errors, and provider overcharging, then pursuing refund via RDG-compliant Inkasso.
**Shortlist score:** 26/35
**Tags:** #b2c #app #legal #success-fee

## Problem

The Bundesnetzagentur energy consumer advisory service received record enquiry volumes in 2024 and again in 2025. Households and SMEs are exposed to: opaque Grundversorgung tariffs, price-brake (Strompreisbremse / Gaspreisbremse) errors, wrongful contract terminations, and non-refunded advance payments when providers go insolvent. Verbraucherzentralen document thousands of cases a year but can only intervene selectively. Most consumers either absorb the loss or enter an expensive individual dispute process.

## Regulatory driver / Why now

- VDuG Abhilfeklage allows qualified entities to recover damages collectively. Energy providers are increasingly targeted under the VDuG.
- On 12 May 2025 the Bundesnetzagentur published its AgNeS discussion paper revising the network tariff system, raising scrutiny of pass-through pricing.
- Federal energy relief package (€10bn/year, 2026) saves an average household €160, but its correct pass-through is an auditable event.
- Product Liability Directive + VDuG together elevate class-action risk for the energy sector.

## Target users

- **End users:** German households and SMEs (Gewerbekunden) with recent Strom or Gas bills.
- **Payers:**
  - End users on success-fee terms (Inkasso model).
  - Verbraucherzentralen who license the analysis engine for member advice.
  - Ombuds-scheme (Schlichtungsstelle Energie) for anonymised analytics.

## Solution

A mobile app that:

1. Accepts photo or PDF uploads of Strom / Gas bills (Jahresabrechnung, Abschlag).
2. Parses Abschlagspläne, Preisbremsen, Strompreis, Grundpreis, Netzentgelt and taxes.
3. Cross-references against published Netzentgelte (Bundesnetzagentur), supplier tariff catalogues and Grundversorger benchmarks.
4. Flags violations and calculates the expected refund.
5. Generates a demand letter and pursues via Inkasso or Schlichtungsstelle Energie escalation.

## Business model

- **Consumer success fee:** 25-35% of recovered amount (RDG-licensed as Inkassodienstleister).
- **Verbraucherzentrale licence:** €10-20k/year for the analysis engine.
- **SME package:** €49-149 per audited bill for businesses with annual consumption above 50 MWh.

## Market size (top-down)

- ~42 million household Strom contracts + ~20 million Gas contracts in Germany.
- At 5% audit penetration and €50 recovered per positive case, TAM of ~€150m/year on recovery alone.
- SME Gewerbekunden layer adds another €50-100m.

## Competitive landscape

- **Check24, Verivox:** price comparison, not dispute.
- **rightmart:** pursues energy claims, narrow scope (Gaskonto disputes).
- **Verbraucherzentralen:** high-touch but throughput-limited.
- **Ombuds-scheme:** public mediator, not a product.

## Moat and differentiation

- Tariff-rule engine ingesting BNetzA data and supplier tariff catalogues (unique compounding dataset).
- Inkasso licence barrier to entry.
- Dataset enabling future predictive pricing for SME buyers.

## Regulatory path (RDG)

Requires registration as Inkassodienstleister. Precedent exists (Flightright, Conny). Partner Kanzlei for any case escalating to Klage above the threshold.

## Key risks

- Energy law is highly variable by supplier tariff structure; mis-parsing can create false positives.
- Class-action layer (VDuG) may subsume individual recovery for the biggest violations.
- Regulatory changes to the Strompreisbremse can abruptly shift the opportunity.

## MVP and first 90 days

1. Weeks 1-3: interview 10 Stadtwerke customers in Bayern and 5 energy advisors at Verbraucherzentrale Bayern.
2. Weeks 4-7: build the Jahresabrechnung parser for Stadtwerke München; ground-truth against five real bills.
3. Weeks 8-12: pursue 10 test refund claims via demand letters; measure recovery rate.

## Success KPIs

- Auto-detection precision vs. expert audit (target: 95%).
- Average recovery per positive case (target: €60-120).
- Cost per successful resolution (target: under €15).

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

- Energieberater at Verbraucherzentrale Bayern.
- A customer-service supervisor at Stadtwerke München (for counter-perspective).
- Schlichtungsstelle Energie, Bonn.
- A SME Gewerbekunde with 100-500 MWh/year consumption.
- Bundesnetzagentur, Abteilung Verbraucherservice Energie.
