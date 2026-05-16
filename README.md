# GMGM News — Content Repository

This repo is the single source of truth for GMGM News editorial content: keyword research, short-form blog skills, and skyscraper blog skills across the core content pillars.

## Pillars

- Stablecoins & Payments
- Blockchain
- Cryptocurrency
- Regulation & Policy

## Structure

```
gmgm-content/
├── skills/                          # Shared Claude skills used across content
│   └── gmgm-keyword-research/       # Global keyword research skill
├── keyword-research/                # Keyword reports by pillar
│   ├── stablecoins/
│   ├── blockchain-basics/
│   └── crypto-payments/
├── short-form-blogs/                # 600-1,200 word article skills by pillar
│   ├── stablecoins/
│   ├── blockchain/
│   ├── cryptocurrency/
│   └── payments/
└── skyscraper-blogs/                # 2,000-4,000 word guide skills by pillar
    ├── stablecoins/
    ├── blockchain/
    ├── cryptocurrency/
    └── payments/
```

## Content Strategy

GMGM News is in its first 30 days. The strategy is to build topical authority through low-competition, long-tail keywords before going after high-volume head terms. Every post targets a keyword that has been validated via live SERP analysis.

**Post naming convention:** `YYYY-MM-DD-slug.md`

**Keyword research process:** Use the `gmgm-keyword-research` skill (in `skills/`) to generate a keyword report for any new topic before drafting.

**Writing process:** Use the `SKILL.md` inside the relevant folder:

- `short-form-blogs/stablecoins/` for focused stablecoin explainers
- `short-form-blogs/blockchain/` for focused blockchain explainers
- `short-form-blogs/cryptocurrency/` for focused cryptocurrency explainers
- `short-form-blogs/payments/` for focused crypto payments explainers
- `skyscraper-blogs/stablecoins/` for long-form stablecoin guides
- `skyscraper-blogs/blockchain/` for long-form blockchain guides
- `skyscraper-blogs/cryptocurrency/` for long-form cryptocurrency guides
- `skyscraper-blogs/payments/` for long-form crypto payments guides

## Content Calendar (Days 1–30)

Keyword reports in `keyword-research/` contain prioritized 30-day publishing plans for each pillar. Check those first before picking your next post.
