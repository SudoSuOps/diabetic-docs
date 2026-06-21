# DiabeticDocs

**The single source of truth for the OpenDiabetic ecosystem.** → [diabeticdocs.com](https://diabeticdocs.com)

Two things, both honest and reproducible: **(1)** the technical record of what the OpenDiabetic /
LocalDiabetic system *is*, and **(2)** the full instructions for dev teams to **use our deeded datasets
and crockpot-cook** diabetic models — the why, the how, the doctrine. Open-source, verified, vetted.

Every component carries a status label: **LIVE** (running + verified), **IN BUILD** (partly done), or
**FRAMEWORK** (designed, not yet a service). No vaporware.

> The one law: private health data never leaves your box. Models flow down, receipts flow up, PHI crosses never.
>
> Why it's a slow cooker: lives depend on us — truth over compromise.

## Pages
| File | Page |
|---|---|
| `index.html` | Overview — the whole ecosystem in one place |
| `the-why.html` | Why OpenDiabetic is a slow cooker — the founding mission |
| `ecosystem.html` | The six surfaces and how they connect |
| `crockpot-cook.html` | The full cook how-to — clean rig → dataset → canary → flightsheet → beat-base → ship |
| `datasets.html` | Find, verify (SHA-256), and pull the deeded corpora |
| `doctrine.html` | The non-negotiables — 5-cap-only, best-in-class, clean-rig, crystal-clear, deeded, beat-base, visible |
| `the-firewall.html` | The one invariant, and how it's enforced in code |
| `architecture.html` | Components, data flow, receipts |
| `llms.txt` · `robots.txt` · `sitemap.xml` · `style.css` | GEO + styles |

## Deploy
Cloudflare Pages, connected to this repo (build command: none · output dir: `/`). Domain: `diabeticdocs.com`.
Pushes to `main` auto-deploy.

## The ecosystem
- [OpenDiabetic](https://opendiabetic.com) — the hive (sovereign compute + trust)
- LocalDiabetic — the healers (home vault + on-device helper)
- [DiabeticTruth](https://diabetictruth.org) — the cited patient facts
- [DiabeticDatasets](https://diabeticdatasets.com) — the cookbook (open, deeded datasets)
- [DiabeticModels](https://diabeticmodels.com) — the builds (show + host)
- [DiabeticDonation](https://diabeticdonation.com) — the give-back (rides, shoes, the continuum)
