# EV Charging Infrastructure

**Track:** [[mobility]]

## Description

Compliance and operations tooling for Charge Point Operators (CPOs), building owners, and wallbox owners navigating a cluster of overlapping German and EU regulations that all activated within 18 months of each other: AFIR Article 20 data publication (April 2026), ISO 15118-2 mandatory for new AC chargers (January 2026), GEIG building obligations (January 2025, with an EPBD wave due June 2026), and §14a EnWG controllable-device registration (since January 2024). Each regulation creates a discrete compliance workflow that existing charger backends, property management tools, and consumer apps do not provide.

## Key Regulations

| Regulation | What it requires | In force |
|---|---|---|
| AFIR Article 20 | CPOs must publish real-time charger data in DATEX II format to national access points (Mobilithek) | 14 April 2026 |
| ISO 15118-2 | Mandatory Plug & Charge communication protocol for all new public AC chargers | 8 January 2026 |
| GEIG (Gebäude-Elektromobilitätsinfrastruktur-Gesetz) | Buildings with 20+ parking spaces must have at least one operational charging point | 1 January 2025 (existing); EPBD wave June 2026 |
| §14a EnWG | EV chargers and heat pumps above 4.2 kW must be registered with the local grid operator as SteuVE | Since 1 January 2024 |
| EPBD (Energy Performance of Buildings Directive) | Extends charging-point pre-wiring obligations to residential buildings with 3+ parking spaces | Transposition due June 2026 |
| Germany Masterplan Charging Infrastructure 2030 | National rollout target; tightens GEIG enforcement | October 2025 |

## Market Size

- **CPO market (AFIR / ISO 15118):** ~800 registered CPOs in Germany; ~15,000 EU-wide. At €15k average ACV and 20% penetration: SAM €2.4m Germany; TAM €30m EU.
- **Building compliance (GEIG / EPBD):** ~200,000 non-residential buildings immediately subject to GEIG; ~27,000 professional Hausverwaltungen. SAM €10m; TAM €50m+ including EPBD residential wave.
- **Consumer §14a registration:** ~300,000 new wallboxes per year; estimated 70% not yet registered. At modest conversion: €11m ARR consumer-side addressable.

## Competitive Landscape

| Player | Origin | Positioning | Gap |
|---|---|---|---|
| Gireve / Hubject | FR / DE | OCPI roaming hubs | Partial data-aggregation; not DATEX II publishers |
| gridX | DE | Home energy management B2B | No CPO-side AFIR or GEIG workflow |
| peter-park | DE | Parking and CPO management | No GEIG compliance or §14a registration |
| QPLIX / Yardi / Domus | DE/US | Property management software | No GEIG module |
| go-e / Heidelberg / wallbe | DE/AT | Wallbox hardware | No §14a registration workflow |
| ENGIE e-mobility | FR | Installer network | No compliance SaaS |

## Best-in-Class Benchmarks

- **Hubject** — sets the standard for OCPI interoperability layer between CPOs and EMSPs.
- **Mobilithek (BMDV)** — the national access point that DATEX II data must flow into; the technical target.
- **CharIN e.V.** — industry body defining the OCPI and ISO 15118 standards roadmap.
- **PTB (Physikalisch-Technische Bundesanstalt)** — gold standard for Eichrecht metering certification.

## Key Bodies and Resources

- [Bundesnetzagentur](https://www.bundesnetzagentur.de) — AFIR and §14a competent authority
- [Mobilithek](https://mobilithek.info) — German national access point for mobility data (BMDV)
- [CharIN e.V.](https://www.charin.global) — OCPI and ISO 15118 industry consortium
- [ZVEH](https://www.zveh.de) — installer association (Elektrohandwerk)
- [VDIV](https://www.vdiv.de) — Hausverwaltungen association (GEIG channel)
- [Germany Masterplan Ladeinfrastruktur 2030](https://bmdv.bund.de)
