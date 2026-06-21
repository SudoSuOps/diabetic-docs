# DiabeticDocs

**How the OpenDiabetic / LocalDiabetic system actually works.** → [diabeticdocs.com](https://diabeticdocs.com)

The honest technical record of what we've built — the home vault, the PHI-blind nudge engine, the
on-device edge brain, the voice loop, the firewall, and the receipts. Every component carries a
status label: **LIVE** (running + verified), **IN BUILD** (partly done), or **FRAMEWORK** (designed,
not yet a service). No vaporware.

> The one law: private health data never leaves your box. Models flow down, receipts flow up, PHI crosses never.

## Pages
| File | Page |
|---|---|
| `index.html` | Overview — the two halves + component map with status |
| `the-firewall.html` | The one invariant, and how it's enforced in code |
| `architecture.html` | Components, data flow, receipts |
| `llms.txt` · `robots.txt` · `sitemap.xml` · `style.css` | GEO + styles |

## Deploy
Cloudflare Pages, connected to this repo (build command: none · output dir: `/`). Domain: `diabeticdocs.com`.

## The house
- [DiabeticTruth](https://diabetictruth.org) — the cited patient facts
- [DiabeticModels](https://diabeticmodels.com) — the model builds (show + host)
- [OpenDiabetic](https://opendiabetic.com) — the foundation
