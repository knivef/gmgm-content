---
name: gmgm-skyscraper-stablecoins
description: >
  Use this skill to research, outline, and write long-form GMGM News skyscraper
  guides about stablecoin topics. Trigger for 2,000-4,000 word definitive guides
  on stablecoins, USDC vs USDT, reserves, regulation, remittances, stablecoin
  payments, depeg risks, and stablecoin market structure.
---

# GMGM News Skyscraper Blog Skill: Stablecoins

Create definitive stablecoin guides that can anchor a topical cluster and earn
links over time. The article should cover a keyword cluster, not just one phrase.

## Workflow

1. Validate the target keyword cluster with GMGM keyword research.
2. Build a source brief from primary sources, regulators, issuer docs, filings,
   reputable media, and current market data.
3. Analyze the top-ranking pages and identify what they miss.
4. Create an outline with internal-link slots for related short-form posts.
5. Draft the article with clear sections, examples, tables, and current dates.

## Output Standard

- Length: 2,000-4,000 words
- Structure: headline, dek, table of contents, 8-12 H2/H3 sections, conclusion
- SEO: target one primary keyword cluster plus 8-15 secondary long-tails
- Include comparison tables when explaining issuers, risks, regulation, or use cases

## Editorial Requirements

- No financial advice.
- Explain reserves, redemption, peg mechanics, regulation, and risks plainly.
- Use specific dates for legislation, depegs, issuer announcements, and market events.
- Add internal links to supporting short-form stablecoin and payments explainers.

## Copy Style

- No em dashes anywhere in copy or metadata. Rewrite with commas, colons, or split sentences.
- Meta description must be 160 characters or fewer.

## Source Attribution

- Never use "According to X", "per X", or "As per X" phrasing.
- Attribute stats and claims with inline hyperlinks where the statistic itself is the anchor text.
- Every specific number, percentage, dollar amount, and date must be verified against a primary source before publishing.
- Error-prone categories in stablecoin topics: market cap (moves fast), historical price ATHs, combined market share percentages, regulatory fine amounts, and remittance fee rates.

## Payment Volume Figures

- Always distinguish raw on-chain volume from adjusted real payment volume. In 2025 these differed by roughly 85x ($33T raw vs $390B adjusted). Using raw figures without context overstates comparisons to Visa or traditional payment rails.

## Skyscraper Gap Analysis

Beyond thin content, hunt for:
- Missing specific dates and dollar amounts where competitors use vague language
- Missing recent regulatory specifics (exact deadlines, dollar thresholds, compliance dates)
- Missing emerging categories (yield-bearing stablecoins were absent from all 15 top-ranking competitors analyzed in May 2026)
- Missing B2B and enterprise use cases (most stablecoin articles only cover trading and consumer remittances)

## Google AI Optimization

Apply Google's AI optimization guide to every article:
- Open with a direct declarative answer in the first paragraph
- Include a dedicated FAQ section with quotable one-sentence answers
- Embed E-E-A-T signals throughout: specific dates, named sources, and verified claims

## Internal Links

- Include at least one internal link to a related GMGM skyscraper or explainer.
- UTM format: `utm_source=gmgm&utm_medium=internal&utm_campaign={this-article-slug}&utm_content={linked-article-slug}`

## Notion Delivery

- Publish to a standalone workspace-level page (no database parent), matching the structure of existing GMGM skyscraper pages.
- Use `<span color="pink_bg">` for the metadata block.
- Use `<table header-row="true">` for all comparison tables.

## Deliverable Format

```markdown
# [Skyscraper headline]

Meta title:
Meta description:
Primary keyword cluster:
Secondary keywords:
Suggested slug:
Internal links to add:
External sources used:

[Article body]
```
