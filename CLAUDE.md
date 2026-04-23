# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

This is an **Obsidian vault** (`vault/`) for startup ideation and due diligence, focused on German regulatory compliance and citizen rights enforcement. It is a documentation-first research repository — there is no build system, test suite, or deployable code.

## Vault Structure

```
vault/
├── ideas/      # 22 startup concept documents, each with a 7-dimension scorecard
├── pillars/    # 4 strategic themes that group the ideas
└── track/      # Progress tracking (e.g., legal.md)
```

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

Current top scorer: **bfsg-pilot** at 33/35.

## Strategic Pillars

All ideas belong to one of four pillars defined in `vault/pillars/`:

1. **digital-accessibility-and-compliance** — BFSG, WCAG 2.2, EN 301 549
2. **corporate-compliance-tooling** — e-justice, court automation, law firm SaaS
3. **enforcing-citizens-rights** — GDPR Article 82, dark patterns, whistleblowing
4. **consumer-rights-awareness-and-enforcement** — NGO/regulator enforcement tooling

## Obsidian Conventions

- Files use kebab-case naming (e.g., `bfsg-pilot.md`, `digital-accessibility-and-compliance.md`)
- Cross-document links use `[[WikiLink]]` syntax referencing filenames without `.md`
- The only enabled community plugin is **terminal** (allows shell commands inside Obsidian)
- Vault configuration lives in `vault/.obsidian/`

## Regulatory Context (Germany/EU)

Key regulations referenced across ideas: BFSG (Barrierefreiheitsstärkungsgesetz), WCAG 2.2, DSA Article 25, GDPR Article 82, RDG (Rechtsdienstleistungsgesetz), eAkte, Online-Zivilverfahren (Online dispute resolution).
