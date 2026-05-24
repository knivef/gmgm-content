---
name: gmgm-skyscraper-blog
description: >
  Use this skill to research, outline, and write long-form GMGM News skyscraper
  guides on any topic. Trigger for 2,000-4,000 word definitive guides that anchor
  a topical cluster, earn links, and out-cover every competitor on depth, accuracy,
  and recency.
---

# GMGM News Skyscraper Blog Skill

Create definitive long-form guides that anchor a topical cluster and earn links
over time. The article should cover a keyword cluster, not just one phrase.

## Workflow

1. Validate the target keyword cluster.
2. Research the top 15 ranking pages and identify what they miss.
3. Build a source brief from primary sources, official reports, filings, and reputable media.
4. Create an outline with internal-link slots for related short-form posts.
5. Draft the article with clear sections, examples, tables, and current dates.
6. Fact-check every specific number, percentage, dollar amount, and date against a primary source.
7. Apply Google AI optimization.
8. Remove em dashes and AI phrasing. Verify meta description is 160 characters or fewer.
9. Publish to Notion.

## Output Standard

- Length: 2,000-4,000 words
- Structure: headline, dek, intro paragraph, quick stats, table of contents, 8-12 H2/H3 sections, conclusion
- SEO: target one primary keyword cluster plus 8-15 secondary long-tails
- Include comparison tables when explaining options, risks, regulation, or use cases
- Link every Table of Contents entry to its section anchor using the format `https://gmgm.news/[slug]/#[section-heading-hyphen-case-lowercase]`. Example: `https://gmgm.news/what-is-a-cbdc/#how-a-cbdc-differs-from-the-money-in-your-bank-account`. Verify anchor slugs match the CMS-generated heading IDs post-publish.
- Do not number H2 section headings. Numbers belong in the Table of Contents list only, not in the headings themselves. Write "## What Is Monero?" not "## 1. What Is Monero?".

## Article Structure Order (Notion)

The confirmed page order for every skyscraper is:

1. Pink metadata block (`<span color="pink_bg">`)
2. `---` divider
3. **Dek** (bold, one or two sentences)
4. `---` divider
5. Intro paragraph (3-4 sentences; opens with a direct declarative answer; sets up the article's scope)
6. `---` divider
7. **Quick stats** (bullet list of 4-6 key figures)
8. `---` divider
9. Table of Contents (numbered list with anchor links)
10. `---` divider
11. Article body sections (H2/H3)
12. Disclaimer and publish date

## Editorial Requirements

- No financial advice.
- Explain mechanics, risks, and regulation plainly.
- Use specific dates for legislation, events, and announcements.
- Add internal links to supporting short-form explainers, but only to pages that already exist. See Internal Links rules below.

## Copy Style

- No em dashes anywhere in copy or metadata. Rewrite with commas, colons, or split sentences.
- Meta description must be 160 characters or fewer.

## Source Attribution

- Never use "According to X", "per X", or "As per X" phrasing.
- Attribute stats and claims with inline hyperlinks where the statistic itself is the anchor text.
- Every specific number, percentage, dollar amount, and date must be verified against a primary source before publishing.
- AI drafts routinely carry stale or slightly wrong figures. Treat all AI-generated statistics as unverified until confirmed.
- For any multilateral project (BIS initiatives, cross-border platforms, joint central bank programmes), fetch the official project page to verify the exact participant list. News summaries frequently omit participants or conflate institutions — for example, writing "ECB" when the correct participant is "Banque de France representing the Eurosystem."
- When a national institution participates on behalf of a supranational body, name the national institution with a parenthetical: e.g. "Banque de France (representing the Eurosystem)", not "ECB".

## Skyscraper Gap Analysis

Beyond thin content, hunt for:
- Missing specific dates and dollar amounts where competitors use vague language
- Missing recent regulatory or policy specifics (exact deadlines, dollar thresholds, compliance dates)
- Missing emerging subcategories that competitors have not yet named or covered
- Missing B2B, enterprise, or institutional angles (most articles default to consumer-facing coverage)

## Disambiguate Aggregated Figures

When citing volume, growth, or market size figures, clarify what the number includes. Raw or aggregated figures often overstate real-world activity. Note the methodology and source date so comparisons are fair and credible.

## Google AI Optimization

Apply Google's AI optimization guide to every article:
- Open with a direct declarative answer in the first paragraph
- Include a dedicated FAQ section with quotable one-sentence answers; mark each question as an H3 heading so individual questions can rank independently in search
- The FAQ H2 heading must end with "for [Topic]" — e.g., "Frequently Asked Questions for Monero" or "Frequently Asked Questions for CBDCs". This lets the heading compete as a standalone search query and gives each H3 beneath it a stronger signal for independent ranking.
- Embed E-E-A-T signals throughout: specific dates, named sources, and verified claims

## Internal Links

- List all planned internal links in the pink metadata block under "Internal links to add". This is the canonical reference for the editor.
- Only embed a hyperlink in the article body if the target page already exists and has a live URL. Never link to a page that has not been published yet.
- Notion converts relative paths (e.g. `/monero-ring-signatures`) to `notion.so/monero-ring-signatures`, which produces a broken "page not found" error. Always use full external URLs for any link placed in the body copy.
- When a supporting post goes live, return to the skyscraper and insert the internal link at the relevant mention in the body.
- UTM format for internal links: `utm_source=gmgm&utm_medium=internal&utm_campaign={this-article-slug}&utm_content={linked-article-slug}`

## Notion Delivery

- Publish to a standalone workspace-level page (no database parent), matching the structure of existing GMGM skyscraper pages.
- Use `<span color="pink_bg">` for the metadata block.
- Use `<table header-row="true">` for all comparison tables.
- When updating an existing Notion page with `update_content`, always fetch the page first. Notion transforms links and formatting on save, so the stored strings will differ from the original markdown you submitted. Match against the fetched content, not the original draft.

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