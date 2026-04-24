# Unlocking Underused Vehicles

**Track:** [[mobility]]

## Description

Tooling that lowers the friction for private and fleet vehicle assets to enter productive, compliant use — covering two distinct markets. First, residential EV charger installation via the WEMoG (WEG reform): ~10 million German owner-occupied condos have the legal right to install a wallbox under §20 WEG, but fewer than 3% have done so due to the fragmented multi-step process. Second, company fleet decarbonisation reporting under CSRD: Mittelstand companies with 50+ company cars must report Scope 3 fleet emissions (Categories 7 and 13) for FY2025 but lack integrations with German fleet-leasing companies (Alphabet, LeasePlan, Arval, ALD). Both markets suffer from a complexity-at-the-last-mile problem that process automation can solve.

## Key Regulations

| Regulation | What it requires | In force |
|---|---|---|
| WEMoG / §20 WEG | Every apartment owner and tenant has the right to install an EV charger at their own cost | Since December 2020 |
| §14a EnWG | Wallboxes above 4.2 kW must be registered with the local grid operator (SteuVE) | Since January 2024 |
| EPBD (transposition) | Residential buildings with 3+ parking spaces must have pre-wiring for EV chargers | Due June 2026 |
| CSRD / ESRS E1 Scope 3 | Large companies must report Scope 3 GHG, including company-car and commuting emissions | FY2025 first wave |
| EU Fleet CO₂ Regulation ("Greening Corporate Fleets") | Mandatory fleet CO₂ reporting layer on top of CSRD | Emerging |

## Market Size

- **WEMoG / residential chargers:** ~10 million WEG-eligible apartments; ~2 million with likely EV-owner residents within 5 years. At 5% paid conversion (€149 one-time): ~€14.9m addressable one-time revenue; Hausverwaltung SaaS adds recurring layer.
- **Fleet CSRD:** ~15,000 German companies in CSRD scope; ~8,000 with meaningful company-car fleets. At €15k average ACV and 5% penetration: SAM €6m; TAM €50m EU.

## Competitive Landscape

| Player | Origin | Positioning | Gap |
|---|---|---|---|
| peter-park | DE | Parking and CPO management | No WEG process or §14a registration |
| Juice Technology | CH | Wallbox hardware and install | No legal-document or Netzanschluss workflow |
| Domus / GFAD / Haufe | DE | Property management software | No GEIG or WEMoG module |
| Persefoni / Watershed / Sweep | US | ESG platforms | No German fleet-leasing API integrations |
| Sphera / Normative | US/SE | Enterprise ESG | No Fuhrpark-specific workflow |
| Big-4 CSRD consulting | DE | Manual advisory | Expensive; not scalable for Mittelstand |

## Best-in-Class Benchmarks

- **Alphabet Fuhrparkmanagement** — the largest German fleet-leasing company; their data API is the key integration target for fleet CSRD tooling.
- **VDIV Bayern** — the property manager association whose template co-branding is the trust signal for WEMoG document generation.
- **Watershed** — sets the gold standard for data-lineage-first CSRD reporting UX; lacks German transport integrations.

## Key Bodies and Resources

- [VDIV (Verband der Immobilienverwalter)](https://www.vdiv.de) — Hausverwaltungen association; WEMoG channel
- [Bundesverband Fuhrparkmanagement](https://www.fuhrparkverband.de) — fleet manager association
- [Alphabet Fuhrparkmanagement GmbH](https://www.alphabet.com/de-de) — largest German fleet leasing; primary API target
- [Umweltbundesamt](https://www.umweltbundesamt.de) — GHG emission factors for ESRS E1
- [DRSC](https://www.drsc.de) — ESRS E1 / Scope 3 methodology interpretation for German companies
- [Bayernwerk Netz](https://www.bayernwerk-netz.de) — largest regional DSO for Netzanschluss API testing
