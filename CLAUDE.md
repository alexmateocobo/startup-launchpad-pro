# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

This is an **Obsidian vault** (`vault/`) for startup ideation and due diligence across two regulatory verticals: German citizen rights / compliance enforcement, and German mobility / EV infrastructure. It is a documentation-first research repository — there is no build system, test suite, or deployable code.

## Vault Structure

```
vault/
├── ideas/      # 42 startup concept documents, each with a 7-dimension scorecard
├── pillars/    # 10 strategic themes grouped under two tracks
└── track/      # Two tracks: legal.md and mobility.md
```

## Tracks and Pillars

Ideas are grouped into pillars, and pillars belong to a track.

### Legal track (`track/legal.md`) — 4 pillars

1. **digital-accessibility-and-compliance** — BFSG, WCAG 2.2, EN 301 549
2. **corporate-compliance-tooling** — e-justice, court automation, law firm SaaS
3. **enforcing-citizens-rights** — GDPR Article 82, dark patterns, whistleblowing
4. **consumer-rights-awareness-and-enforcement** — NGO/regulator enforcement tooling

### Mobility track (`track/mobility.md`) — 6 pillars

1. **ev-charging-infrastructure** — AFIR Article 20, GEIG, ISO 15118, Eichrecht
2. **vehicle-grid-integration** — §14a EnWG, V2G, smart charging
3. **mobility-data-and-compliance** — AFIR data mandates, Mobilithek, CO₂ fleet reporting
4. **shared-clean-mobility** — PBefG, ride-hailing permits, e-scooter/e-bike compliance
5. **unlocking-underused-vehicles** — P2P car-sharing, fleet CO₂ pilots, Fuhrpark digitisation
6. **autonomous-and-robotic-mobility** — StVFernLG, GEIG for robots, u-space, tech supervisors

## Idea Scoring System

Each document in `vault/ideas/` follows a standardized scorecard. **Maximum total score is 35** (7 dimensions × 5 points each):

| Dimension | What it measures |
|---|---|
| Regulatory tailwind | Strength of the regulatory driver |
| Stakeholder access | Founder's ability to reach customers |
| RDG clarity | Legal clarity under the German Legal Services Act |
| Moat beyond first mover | Defensibility after entry |
| Founder-market fit | Domain expertise and network alignment |
| Path to 12-week PoV | Feasibility of an MVP in 12 weeks |
| Scale ceiling | Maximum addressable market |

Current top scorers: **bfsg-pilot** at 33/35 (Legal), **§14a-optimizer** at 31/35 (Mobility).

## Obsidian Conventions

- Files use kebab-case naming (e.g., `bfsg-pilot.md`, `ev-charging-infrastructure.md`)
- Exception: `§14a-optimizer.md` uses the § symbol as-is
- Cross-document links use `[[WikiLink]]` syntax referencing filenames without `.md`
- The only enabled community plugin is **terminal** (allows shell commands inside Obsidian)
- Vault configuration lives in `vault/.obsidian/`

## Regulatory Context (Germany/EU)

**Legal vertical:** BFSG (Barrierefreiheitsstärkungsgesetz), WCAG 2.2, DSA Article 25, GDPR Article 82, RDG (Rechtsdienstleistungsgesetz), eAkte, Online-Zivilverfahren.

**Mobility vertical:** AFIR (Alternative Fuels Infrastructure Regulation) Article 20, GEIG (Gebäude-Elektromobilitätsinfrastruktur-Gesetz), ISO 15118, §14a EnWG (smart charging grid fee), PBefG (Personenbeförderungsgesetz), StVFernLG (autonomous vehicle remote ops), CSRD fleet CO₂ reporting, Mobilithek (German national access point), WEMoG, EKFV.
