# Dulabx

**Biotech-AI B2B for computational biology service teams** — solo company operated by 7 Hermes agents.

## Agents (Central Perk roster)

| Agent | Role | Profile |
|-------|------|---------|
| **Gunther** | Orchestrator | `gunther` |
| **Monica** | Finance / Ops / Compliance | `monica` |
| **Chandler** | Engineering / Infra / Security | `chandler` |
| **Ross** | Research / Science / Market scan | `ross` |
| **Joey** | Sales / Outbound / Partnerships | `joey` |
| **Rachel** | Marketing / Content / SEO | `rachel` |
| **Phoebe** | QA / Red-team / Safety / Audit | `phoebe` |

## Kanban Board

`central-perk` — dispatcher config:
- `orchestrator_profile=gunther`
- `default_assignee=gunther`
- `max_in_progress_per_profile=2`
- `review_dispatch=true`

## Charter

See [CHARTER.md](CHARTER.md) — single source of truth for pricing, milestones, proof standards, money rules.

## Repository Structure

```
dulabx/
├── CHARTER.md          # Company charter (pricing, milestones, rules)
├── README.md           # This file
├── agents/             # Agent SOUL.md files
│   ├── gunther.md
│   ├── monica.md
│   ├── chandler.md
│   ├── ross.md
│   ├── joey.md
│   ├── rachel.md
│   └── phoebe.md
└── configs/            # Hermes profile configs (sanitized)
    ├── gunther.yaml
    ├── monica.yaml
    ├── chandler.yaml
    ├── ross.yaml
    ├── joey.yaml
    ├── rachel.yaml
    └── phoebe.yaml
```

## Status

- **Jurisdiction**: Egypt (incorporation) — targets: Gulf, EU, USA
- **Domain**: Under construction; personal GitHub Pages for landing page
- **GitHub**: `SamerKharboush/dulabx` (personal account)
- **Board**: 5 cards (4 done, 1 in review)
- **Cron**: 21 jobs scheduled across 7 profiles
- **OMH**: 144 workflows installed at commit `55643c8`

## Revenue Target

€1,000–€5,000 MRR by Month 12 via paid pilots (€2,000–€10,000/qtr) and subscriptions (€300–€2,000/mo).
3–10 paying design partners.