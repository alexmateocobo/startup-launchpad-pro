# AccessibleDocs AI

**Pillar:** [[digital-accessibility-and-compliance]]
**One-liner:** PDF/UA and WCAG document remediation automation for high-volume issuers (banks, insurers, public authorities, universities): converts existing PDFs, DOCX and HTML policies into accessible, tagged, screen-reader-ready artefacts in minutes.
**Shortlist score:** 25/35

## Problem

Banks, insurers, public authorities and universities generate millions of PDF policy documents, annual reports, terms and conditions, and customer statements each year. The vast majority are not PDF/UA compliant. The BFSG (28 June 2025) and the BITV 2.0 for public authorities mandate accessibility for these documents. Existing remediation (Adobe Acrobat Pro, Axes4, PDFix, Common Look) is slow and expensive: €5-25 per document manually. At scale this is a multi-million-euro operational cost. Large issuers are either non-compliant or pay massive services budgets.

## Regulatory driver / Why now

- BFSG covers documents embedded in consumer-facing services.
- BITV 2.0 mandates accessibility for all federal and Länder public documents.
- Hochschulrahmengesetz and Länder-level university accessibility laws.
- 2026 review round for large annual reports and customer communications.

## Target users

- **End users:** compliance, document operations, customer communications, legal and HR teams.
- **Payers:**
  - Banks, insurers, asset managers (high document volume).
  - Federal and Länder authorities.
  - Universities and research organisations.
  - Pharma and medical-device companies (regulatory documents).

## Solution

A cloud API and on-prem appliance that:

1. Ingests PDF, DOCX, HTML.
2. Tags structure, headings, tables, figures, forms.
3. Generates alt-text via a document-tuned LLM.
4. Adds accurate reading order.
5. Validates PDF/UA-1 and WCAG 2.2 AA.
6. Exports remediated PDF and accessibility report.

Human-in-the-loop tooling for edge cases.

## Business model

- **Per-document fee:** €0.50-3 per document (volume-tiered).
- **Enterprise SaaS:** €30-150k/year with unlimited volume and on-prem option.
- **Public-sector framework agreements:** €50-250k multi-year.

## Market size (top-down)

- Estimated 200-500m accessibility-relevant documents/year in Germany.
- At €1.50 average price, TAM €300-750m.
- Realistic reachable share in 5 years: 2-5%, i.e. €6-35m ARR.

## Competitive landscape

- **Axes4 axesPDF:** on-prem, strong brand, slow throughput.
- **PDFix, Common Look:** global but not tuned to German document types.
- **Adobe Acrobat Pro with AI:** generic, no PDF/UA validation automation.
- **Deque AMP:** enterprise, web-first.

## Moat and differentiation

- German-language document training: better alt-text, better reading order.
- Industry-specific templates (bank statements, insurance policy schedules, university grade reports).
- On-prem option critical for financial and public-sector trust.

## Regulatory path (RDG)

No RDG exposure. Document engineering and IT services.

## Key risks

- Adobe or Microsoft adds native accessibility AI that absorbs the opportunity.
- Public-sector procurement cycles slow initial revenue.
- German-language LLM quality for alt-text and summaries is still evolving.

## MVP and first 90 days

1. Weeks 1-3: interview 10 customer-communications leads in banking and insurance.
2. Weeks 4-7: build ingestion + tagging + alt-text for bank statement and insurance policy templates.
3. Weeks 8-12: run a paid pilot processing 10,000 documents for one partner.

## Success KPIs

- Auto-remediation acceptance rate (target: 85% pass PDF/UA without human edit).
- Per-document cost (target: under €0.80 internal).
- Weeks to enterprise sign-off (target: under 12).

## Scorecard

- Regulatory tailwind: 4
- Stakeholder access: 3
- RDG clarity: 5
- Moat beyond first mover: 3
- Founder-market fit: 3
- Path to 12-week PoV: 4
- Scale ceiling: 3
- **Total: 25/35**

## Stakeholders to interview in Module 2

- Customer-communications lead at a DACH bank (e.g. Commerzbank, Deutsche Bank, HypoVereinsbank).
- Accessibility team at Bundesagentur für Arbeit (for public-sector volume).
- Head of Digital Services at TUM or LMU.
- Axes4 or another PDF-accessibility specialist (competitive interview).
- DBSV (Deutscher Blinden- und Sehbehindertenverband) digital team.
