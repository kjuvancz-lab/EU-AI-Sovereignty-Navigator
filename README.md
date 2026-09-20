# EU AI Sovereignty Navigator

An interactive map of the AI resource stack — 17 layers, from the datacenter floor
to knowledge work — read against sovereignty. For each layer it sets out what
achieves **sovereign**, **secure** and **owned**, and what does not.

**[Open the explorer →](https://kjuvancz-lab.github.io/EU-AI-Sovereignty-Navigator/)**

## What it does

- **Click any box** in the architecture map to read that layer in full.
- **Filter by sovereignty requirement (SOV).** Pick one or more of the 48
  requirements; the layers that carry them light up on the map, matching passages
  are highlighted in the prose, and a list at the bottom groups every affected
  section by layer.
- **Requirement chips** on each passage name the requirements it speaks to, and
  toggle the filter when clicked.
- **English and German**, switchable at the top.

## Sovereignty requirements

The SOV references come from the European Commission's
[Cloud Sovereignty Framework](https://commission.europa.eu/document/09579818-64a6-4dd5-9577-446ab6219113_en)
— 48 requirements across 8 objectives:

| | Objective |
|---|---|
| SOV-1 | Strategic Sovereignty |
| SOV-2 | Legal & Jurisdictional Sovereignty |
| SOV-3 | Data & AI Sovereignty |
| SOV-4 | Operational Sovereignty |
| SOV-5 | Supply Chain Sovereignty |
| SOV-6 | Technology Sovereignty |
| SOV-7 | Security & Compliance Sovereignty |
| SOV-8 | Environmental Sustainability |

38 of the 48 are addressed somewhere in the table. The other 10 appear in the
picker greyed out: they are real requirements of the framework, but not
architectural ones — nothing in the stack answers them.

This is a reading aid, not a scoring tool. It carries each requirement's
objective and question; weights, answer ladders and SEAL levels stay in the
Commission's own assessment calculator.

## About the page

One self-contained HTML file. No build step, no dependencies, no network calls,
no tracking — open it locally and it works the same as it does here.

The version is stamped in the page footer and in a `<meta name="version">` tag.

## Versions

| Version | Date | Change |
|---|---|---|
| 1.1.0 | 20 Sep 2026 | **Knowledge store · graph DB** added to the map, beside Vector DB in the Database row (self-hosted Neo4j, GraphDB or a triple store; row-level security and your keys, as for the relational engine). The row could already hold embeddings — the memory — but had no named engine for the representation itself, which is the layer the context argument turns on. The table's Database prose has not yet been extended for it; the map is ahead of the workbook here. Version stamp added. |
| 1.0 | 4 Sep 2026 | First public release. Same-day follow-ups: patent jurisdiction rows at layer 16 from workbook v18 (SOV 2.5, 2.6 and 8.4 now covered); link-preview metadata and the social card. |

## Author

Krisztina Juvancz —
[LinkedIn](https://www.linkedin.com/in/krisztina-juvancz-3831b810/) ·
[Substack](https://krisztajuvancz.substack.com/)
