# Umweltzone-FleetPilot

**Pillar:** [[mobility-data-and-compliance]]
**One-liner:** Multi-city clean-zone compliance tracker and Ausnahmegenehmigung automation SaaS for logistics fleets navigating Germany's 80 Umweltzonen and emerging Zero Emission Zone ordinances.
**Shortlist score:** 27/35

## Problem

Germany has 80 Umweltzonen with varying emission-class requirements; several cities (Stuttgart, Berlin, Köln) are actively planning Zero Emission Zone (ZEZ) ordinances that will ban all non-electric commercial vehicles from defined urban zones within the next 3–5 years. For logistics operators running mixed fleets (EURO 4–6 diesel + some EV), zone compliance is a daily operational challenge: which vehicles can enter which zones, when do older vehicles require an Ausnahmegenehmigung (exemption permit), and how does the zone map change over time? Fleet managers currently maintain Excel sheets per city. The complexity multiplies for operators doing inter-city routes. Non-compliance fines range from €20 to €500 per incident; more critically, cargo is delayed and customers billed for failed deliveries.

## Regulatory driver / Why now

- Stuttgart Clean Air Zone: diesel bans already in force; planned ZEZ from 2026.
- Berlin: EURO 6 required in Ring zone from 2025.
- EU Urban Mobility Framework and German Nationaler Mobilitätsplan 2030 explicitly support ZEZ expansion.
- Germany's e-HGV Maut incentive (50% toll reduction for electric trucks) accelerating fleet transition but creating a transition-period mixed-fleet compliance gap.

## Target users

- **End users:** fleet managers, logistics planners, and route optimisation teams at courier and Spedition companies.
- **Payers:**
  - Medium courier (20–100 vehicles): €200–600/month.
  - Large logistics operator (100+ vehicles): €800–2,500/month.
  - Fleet telematics providers (Webfleet, Fleetboard) as white-label integration partners.

## Solution

A compliance intelligence platform that:
1. Maintains a real-time database of German Umweltzonen, EURO class requirements, and ZEZ ordinances.
2. Classifies every vehicle in the fleet by EURO class + drive type.
3. Generates a per-route zone-eligibility check: which vehicles can run which routes today.
4. Automates Ausnahmegenehmigung applications to the relevant Ordnungsämter for non-compliant vehicles.
5. Projects the fleet electrification investment required to achieve zero-restriction status by the operator's target date.

## Business model

- **Subscription SaaS** per vehicle.
- **Ausnahmegenehmigung automation module** as premium add-on.
- **Telematics white-label:** integration into Webfleet/Fleetboard dashboards.

## Market size (top-down)

- ~3 million commercial vehicles (LKW, Lieferwagen) operating in German urban zones.
- ~200,000 operated by companies with meaningful compliance spend.
- At €600 average ACV per operator (50-vehicle average fleet × €12/vehicle/year) and 5% penetration: SAM €600k growing to €6m as ZEZ mandates tighten.

## Competitive landscape

- **HereHD Maps, TomTom:** zone data in map layers; no fleet compliance workflow.
- **Webfleet (Bridgestone):** telematics with zone alerts; no Ausnahmegenehmigung automation.
- No dedicated Umweltzone + ZEZ compliance SaaS exists for fleets.

## Moat and differentiation

- Real-time ordinance database updated by a legal-monitoring team is a continuously maintained asset.
- Ausnahmegenehmigung automation per city (20+ different Ordnungsamt forms) is labour-intensive to replicate.
- Telematics integration creates a distribution channel that bypasses direct sales.

## Regulatory path (RDG)

No RDG exposure: zone classification and permit-form pre-filling is operational compliance software. Ausnahmegenehmigungen are administrative, not legal, processes.

## Key risks

- Cities standardise zone data APIs, reducing the database advantage.
- Fleet electrification accelerates faster than expected, reducing the compliance gap.
- Telematics vendors build zone-compliance natively.

## MVP and first 90 days

1. Weeks 1–3: map zone requirements for Berlin, Stuttgart, and München; interview 5 fleet managers.
2. Weeks 4–7: build vehicle EURO-class database, zone-eligibility checker, and Ausnahmegenehmigung template for Stuttgart.
3. Weeks 8–12: run 3 pilot fleets; process 10 Ausnahmegenehmigungen.

## Success KPIs

- Zone-compliance checks run per week at week 12 (target: 500).
- Ausnahmegenehmigungen submitted (target: 10).
- MRR at week 12 (target: €2,500).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 4
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 5
- Scale ceiling: 3
- **Total: 27/35**

## Stakeholders to interview in Module 2

- Landeshauptstadt Stuttgart, Umweltzone team.
- Senatsverwaltung Berlin, Mobilität und Verkehr.
- Bundesverband Güterkraftverkehr Logistik und Entsorgung (BGL).
- Webfleet (Bridgestone), product partnership team.
- DPD Deutschland GmbH, fleet compliance lead.
