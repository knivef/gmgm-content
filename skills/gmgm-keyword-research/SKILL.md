---
name: gmgm-keyword-research
version: 2.0.0
description: >
  Run this skill whenever GMGM News needs keyword research before writing any article.
  Use it to build a data-grounded keyword strategy across crypto, stablecoins, blockchain,
  payments, and regulation topics: audience mapping, SERP analysis, opportunity scoring,
  content clustering, content briefs, and 30/60/90-day planning.

  Triggers on: "find keywords for X", "what should we target for Y", "keyword research on Z",
  "what long-tail keywords exist for [topic]", "find low-competition keywords",
  "what can we rank for", "suggest topics we can rank for", "SERP analysis on X",
  "what keywords should we build content around", "give me keyword ideas for [niche]",
  "plan content around [topic]", "create an SEO content plan", or any time a writing
  workflow needs keyword validation before drafting.

  Always run this skill before writing any post — short-form or skyscraper — to confirm
  the keyword has realistic ranking potential for a new domain.

  OUTPUT: Always produces a .xlsx report file named YYYYMMDD-[keyword-topic].xlsx
  (e.g. 20260523-usdc-stablecoin.xlsx). Never output the report as markdown or plain text.
---

# GMGM News — Keyword Research Skill

GMGM News is a new crypto/blockchain/payments media website. Your job is to find
long-tail keywords it can realistically rank for in its first 90 days. A new domain has
zero authority, so the strategy is clear: go narrow, go specific, and win the searches
that established players ignore.

---

## Site Context

- **Publication**: GMGM News (new domain, no authority yet)
- **Category**: Crypto, stablecoin, blockchain, and payments news and analysis
- **Audience**: Broad tech-savvy readers — retail investors, crypto enthusiasts, Web3
  builders, finance and payments professionals
- **Content pillars**: Stablecoins & payments | Cryptocurrency | Blockchain | Regulation & policy
- **SEO goal**: Build topical authority through rankable content in the first 30–90 days

---

## SEO Strategy Mindset

Act like the Head of SEO at an early-stage media startup: the goal is not to produce
a generic keyword list, but to build a ranking thesis. Every recommendation must connect
search demand, ranking feasibility, business relevance, content format, and a path to
topical authority.

Default posture:

- Prefer rankable long-tail keywords over impressive head terms.
- Use data or defensible proxies; do not rely only on intuition.
- Treat SERP weakness as the main opportunity signal for a new domain.
- Plan in clusters, not isolated posts.
- Separate early traffic wins from medium-term authority bets.
- Create content briefs that writers can execute without redoing the research.

---

## Quick Start

```
Research keywords for [topic/seed keyword]
Find low-competition keywords for [topic] with informational intent
What should GMGM News target for [niche/pillar]?
SERP analysis on [keyword]
```

---

## Data Sources

**With SEO tool connected (Ahrefs, SEMrush, Google Keyword Planner, GSC):**
Pull historical search volume, keyword difficulty scores, SERP analysis, and competitor
keyword overlap directly. Fetch seed keyword metrics, related suggestions, and trend data.

**With manual/public data only:**
Use public SERPs as proxies. Collect People Also Ask, Related Searches, autocomplete
variants, competitor page titles, and Reddit/forum phrasing. Be explicit that numbers
are proxy judgments, not exact keyword-tool data.

---

## Research Process

### Step 1: Define the SEO Objective

Before expanding keywords, state the objective of the research:

- Organic traffic growth
- Topical authority building
- Newsletter audience growth
- News/media credibility
- Future monetization through ads, sponsorships, affiliate, or lead-gen
- Support for a specific content pillar

Use this objective to reject irrelevant keywords even if they have search volume.

### Step 2: Map Searcher Segments

Identify the people behind the searches. For GMGM News, common segments include:

- Beginners trying to understand a crypto/payments concept
- Retail investors evaluating risk, safety, yield, or comparisons
- Crypto users comparing tokens, exchanges, wallets, chains, and protocols
- Web3 builders and operators researching infrastructure
- Payments and fintech professionals researching settlement, remittances, or rails
- Policy-aware readers searching regulation, enforcement, tax, or compliance changes
- News-followers trying to understand a recent event

Tag each keyword with the likely audience segment. Favor segments that match GMGM's
media and newsletter audience.

### Step 3: Expand the Seed Keyword

Take the input topic or seed keyword and generate 25–50 long-tail variations using these patterns:

**Keyword Expansion Patterns**

| Pattern | Examples |
|---|---|
| Question-based | "what is X", "how does X work", "why is X important" |
| Comparison | "X vs Y explained", "X vs Y which is better" |
| Explainer/beginner | "X explained for beginners", "X simply explained" |
| Definitional | "what does X mean in crypto", "X definition" |
| How-to | "how to use X", "how to buy X", "how X works step by step" |
| News-adjacent evergreen | "what happened to X", "history of X", "timeline of X" |
| Regional/regulatory | "X regulation in [country]", "X rules in EU", "X tax [country]" |
| Year-specific | "X in 2025", "X 2026 guide" |
| Use-case specific | "X for [audience]", "X for beginners", "X for merchants" |
| Long-tail modifiers | "best X", "top X", "free X", "X tools", "X checklist", "X template" |

Use web search to find what people are actually searching for:

- Look at "People Also Ask" sections
- Look at "Related searches" at the bottom of results
- Note autocomplete-style variants by searching partial phrases
- Search Reddit and forums for phrasing that reveals real user pain
- Review competitor category pages and article titles for repeated topic patterns
- Include current-year variants when regulation, products, or market structure recently changed

### Step 4: Collect Data and Proxy Signals

For each candidate keyword or cluster, collect as many of these signals as available:

- Estimated monthly search volume (MSV)
- Keyword difficulty (KD) score or competition proxy
- CPC or commercial-value proxy
- SERP composition: media, exchanges, issuers, regulators, product blogs, Reddit, forums
- Ranking domain strength: major authority vs mid-tier vs low-authority blog
- Content freshness: current-year, 1–2 years old, or stale
- SERP format: guides, news, definitions, comparison tables, videos, forums, tools
- People Also Ask questions and related searches
- Whether top results directly answer the query or only mention it in passing
- Whether current pages are biased, too technical, too institutional, outdated, or thin

If paid SEO tools are unavailable, use public SERPs and proxies. Label all estimates clearly.

### Step 5: SERP Competition Assessment

For each candidate keyword, run a targeted SERP check to estimate whether a new site
could crack the top 10 within 60–90 days with a quality post.

**Run these searches for each keyword:**

1. Search the keyword directly. Look at the top 5 results:
   - Are they from ultra-high-authority domains (CoinDesk, Reuters, Investopedia, Forbes,
     CoinTelegraph, Wikipedia, BBC)?
   - How recent are the top results? Old content (2+ years) = opportunity.
   - Are the top results dedicated posts, or just passing mentions?

2. Check competitor coverage:
   - `site:coindesk.com "[keyword]"` — if there's a dedicated page, it's contested
   - `site:cointelegraph.com "[keyword]"` — same check
   - `site:decrypt.co "[keyword]"` — same check
   - `site:investopedia.com "[keyword]"` — often dominates informational queries

3. Note total result count as a rough proxy. Under 100k is promising. Over 1M needs scrutiny.

4. Look for SERP weakness:
   - Low-authority sites ranking in the top 10
   - Reddit/forum threads ranking
   - Product or issuer pages ranking for informational queries
   - Outdated posts or thin content without tables, examples, FAQs, or current context
   - Institutional/legal pages where a plain-English media explainer would be better

**Assign a competition rating to each keyword:**

- 🟢 **LOW**: Few or no dedicated pages from major crypto media. Top results are Reddit
  threads, small blogs, or dated articles. Total results under 100k. A quality 800-word
  post could realistically land in the top 10 within 60 days.

- 🟡 **MEDIUM**: Some mid-tier crypto sites have coverage. Top 3 results are from strong
  domains but with older content (1–2 years). Total results 100k–500k. A quality
  skyscraper could break top 20 and grow from there.

- 🔴 **HIGH**: CoinDesk, CoinTelegraph, Investopedia, or Wikipedia own the first page.
  Content is fresh and comprehensive. Total results over 500k. Avoid for now.

### Step 6: Classify Search Intent

Every keyword signals what the searcher wants to do. Classify using this taxonomy:

| Intent | Signals | Example | Content Type | GMGM Priority |
|---|---|---|---|---|
| Informational | what, how, why, guide, learn | "what is USDC" | Blog posts, guides | Highest — focus here for first 30 days |
| Navigational | brand names, specific sites | "coinbase login" | Skip | Not applicable |
| Commercial | best, review, vs, compare | "best stablecoin 2026" | Comparison posts, reviews | Medium-term |
| Transactional | buy, price, discount, order | "buy USDC" | Product/pricing pages | Lowest — hard to beat exchanges |
| Regulatory/news-adjacent | law, act, ruling, enforcement | "GENIUS Act explained" | News analysis + evergreen | High — GMGM differentiator |
| GEO (AI answer) | definition, what is, how does | "stablecoin meaning" | Concise definitional content | High — captures AI citations |

**For GMGM News's first 30 days, focus almost entirely on informational intent.**

**GEO Opportunity Layer — keywords likely to trigger AI-generated answers:**
- Question formats: "What is...", "How does...", "Why is..."
- Definition queries: "[term] meaning", "[term] definition"
- Comparison queries: "[A] vs [B]", "difference between..."
- List queries: "best [category]", "top [number] [items]"
- How-to queries: "how to [action]", "steps to [goal]"

Include GEO keywords in the strategy for AI search visibility alongside traditional SEO.

### Step 7: Score Ranking Opportunity

Create an opportunity score for each keyword using a 1–5 scale per factor:

| Factor | Weight | Scoring Guidance |
|---|---|---|
| Search demand | 20% | Higher MSV, repeated autosuggest/PAA presence, or clear recurring demand |
| Ranking feasibility | 25% | Weak SERP, low-authority pages, forums, outdated/thin content |
| GMGM relevance | 20% | Strong fit with stablecoins, crypto, blockchain, payments, regulation |
| Content gap | 15% | GMGM can be clearer, more current, more neutral, or more practical |
| Business/media value | 10% | Newsletter, sponsorship, ads, or strategic audience value |
| Internal-link value | 10% | Supports a cluster anchor or multiple related posts |

**Opportunity score formula:**

`Score = (Demand×0.20) + (Feasibility×0.25) + (Relevance×0.20) + (Gap×0.15) + (Value×0.10) + (InternalLink×0.10)`

Use the score to prioritize, not to pretend the research is mathematically exact.
Explain major assumptions.

**Opportunity Matrix:**

| Scenario | Volume | Difficulty | Intent | Priority |
|---|---|---|---|---|
| Quick Win | Low–Med | Low | High | ⭐⭐⭐⭐⭐ |
| Growth | High | Medium | High | ⭐⭐⭐⭐ |
| Long-term | High | High | High | ⭐⭐⭐ |
| GEO/AI | Low | Low | Informational | ⭐⭐⭐⭐ |
| Research only | Low | Low | Low | ⭐⭐ |

### Step 8: Recommend the Content Type

Match each keyword to the right content format:

**Short-form (600–1,200 words):**
Single, specific long-tail keyword. Narrow, well-defined scope. 🟢 LOW competition.
Goal: rank fast (2–8 weeks), build domain authority through volume.

**Skyscraper (2,000–4,000 words):**
A keyword cluster around a broader topic. Structured as the definitive guide.
🟡 MEDIUM competition acceptable. Goal: topical authority, backlinks, rank in 3–6 months.

**Comparison article:**
For "X vs Y", "which is better", "difference between" keywords.
Include tables, use-case recommendations, and neutral tradeoffs.

**Living page:**
For regulation timelines, market-structure trackers, or recurring policy updates.
Update monthly or when major events happen.

**Glossary/support article:**
For precise definitions that strengthen internal links.
Short, clear, and designed to support larger cluster pages.

**News-analysis post:**
For timely events with SEO afterlife.
Must include evergreen context so it does not become disposable news.

### Step 9: Build Topic Clusters

Group keywords into clusters with one anchor page and multiple support posts.

For each cluster, define:

- Anchor keyword and content format
- Supporting long-tail keywords
- Internal links from support posts to anchor
- Internal links between sibling posts
- Publishing order
- What topical authority signal the cluster creates

Avoid isolated posts unless the keyword is a strong standalone news opportunity.

### Step 10: Prioritize the 30/60/90-Day Plan

Sequence recommendations by likely SEO payoff:

- **First 30 days**: Low-competition informational long-tails and definitions that can rank quickly
- **Days 31–60**: Comparison posts, regulation explainers, and support articles around winning clusters
- **Days 61–90**: Skyscraper guides, broader cluster anchors, and medium-competition terms

Make the plan realistic for the publishing capacity. Include short-form and skyscraper mix.

### Step 11: Create Actionable Content Briefs

For every priority keyword, provide enough detail for a writer to start:

- Primary keyword
- Secondary keywords
- Search intent
- Audience segment
- Suggested headline
- Suggested slug
- Recommended format and word count
- SERP gap to exploit
- Required H2/H3 sections
- Internal links to add
- External source types to cite
- FAQ targets
- Notes on risk, regulation, or no-financial-advice framing

### Step 12: Define the Measurement Plan

End the research with how performance should be checked after publishing:

- Indexing status
- Impressions
- Average position
- CTR
- Queries each page starts ranking for
- Internal-link performance
- Pages moving from positions 20–50 into top 20
- Posts that need refreshes, stronger intros, schema, or supporting content

After 30, 60, and 90 days, append real lessons to the Accumulated Lessons section.

---

## Output Format — XLSX Report (MANDATORY)

**The output of every keyword research run MUST be a .xlsx file. Never output the report
as markdown, plain text, or any other format.**

### Filename Convention

```
YYYYMMDD-keyword-topic.xlsx
```

Where:
- `YYYYMMDD` is today's date (e.g. `20260523`)
- `keyword-topic` is a 2–4 word slug derived from the seed keyword, lowercase,
  hyphen-separated, no special characters (e.g. `usdc-stablecoin`, `genius-act-regulation`)

Example: `20260523-usdc-stablecoin.xlsx`

### Workbook Structure

Produce the report as a multi-sheet workbook using `openpyxl`. Use Arial 10pt throughout.
Apply bold headers with a dark background (#1E3A5F) and white text for all sheet headers.
Freeze the top row on every sheet.

**Sheet 1 — Summary**

| Field | Value |
|---|---|
| Seed topic | [input] |
| Date | [today's date] |
| Content pillars covered | [which of the 4 pillars] |
| SEO objective | [traffic / topical authority / newsletter / monetization / other] |
| Audience segments | [primary searcher groups] |
| Executive SEO thesis | [3–6 bullet summary: where demand is, where SERP is weak, what GMGM can win, what to avoid, how the cluster compounds] |

**Sheet 2 — Top Keyword Picks**

Columns: `Keyword | Competition | Intent | GEO Potential | Opportunity Score | Rec. Format | Rationale`

Include the 5–10 best opportunities. Use 🟢/🟡/🔴 for Competition. Score out of 5.
Apply conditional formatting: green fill for 🟢 LOW rows, yellow for 🟡 MEDIUM, red for 🔴 HIGH.

**Sheet 3 — Full Keyword List**

Columns: `Keyword | Competition | Opportunity Score | Intent | GEO Potential | Audience Segment | Rec. Format | Suggested Title | SERP Gap | Why This Works for GMGM`

One row per keyword. Include all expanded keywords from Step 3.

**Sheet 4 — Opportunity Scoring Model**

Document the scoring methodology:

Columns: `Factor | Weight | Notes | Tool/Proxy Used`

Include a second table showing per-keyword factor scores:

Columns: `Keyword | Demand (20%) | Feasibility (25%) | Relevance (20%) | Gap (15%) | Value (10%) | Internal Link (10%) | Total Score`

Use Excel `=SUMPRODUCT()` formulas for Total Score — do not hardcode calculated values.

**Sheet 5 — Topic Cluster Map**

Columns: `Cluster | Anchor Keyword | Anchor Format | Supporting Keywords | Internal Link Logic | Publishing Order | Priority`

**Sheet 6 — 30/60/90-Day Content Plan**

Columns: `Priority | Timing | Working Title | Primary Keyword | Format | Pillar | Cluster | Notes`

Apply color banding by timing period:
- Days 1–30: light green background
- Days 31–60: light yellow background
- Days 61–90: light blue background

**Sheet 7 — Content Briefs**

One section per priority keyword (top 5–10). Use merged cells for keyword headers.

Rows per brief:
`Primary Keyword | Secondary Keywords | Search Intent | Audience Segment | Suggested Slug | Word Count | Required Sections | SERP Gap | Internal Links | External Source Types | FAQ Targets | Special Notes`

**Sheet 8 — Keywords to Avoid**

Columns: `Keyword | Reason to Avoid | Revisit When`

List 3–5 keywords that look tempting but are too competitive for a new domain.

**Sheet 9 — Measurement Plan**

Columns: `Metric | 30-Day Target | 60-Day Target | 90-Day Target | Tool/Source`

### XLSX Generation Instructions

Use `openpyxl` to generate the file. Follow these rules:

```python
from openpyxl import Workbook
from openpyxl.styles import Font, PatternFill, Alignment, PatternFill
from openpyxl.utils import get_column_letter
from datetime import date

# Filename
today = date.today().strftime("%Y%m%d")
slug = "[keyword-topic-slug]"  # derived from seed keyword
filename = f"{today}-{slug}.xlsx"

# Styling constants
HEADER_FONT = Font(name="Arial", bold=True, color="FFFFFF", size=10)
HEADER_FILL = PatternFill("solid", start_color="1E3A5F")
BODY_FONT = Font(name="Arial", size=10)
GREEN_FILL = PatternFill("solid", start_color="C6EFCE")
YELLOW_FILL = PatternFill("solid", start_color="FFEB9C")
BLUE_FILL = PatternFill("solid", start_color="BDD7EE")
RED_FILL = PatternFill("solid", start_color="FFC7CE")
```

- Apply `HEADER_FONT` and `HEADER_FILL` to all header rows.
- Apply `BODY_FONT` to all data cells.
- Set column widths: auto-fit or minimum 15, maximum 50.
- Freeze top row on every sheet (`sheet.freeze_panes = "A2"`).
- Use Excel formulas for all calculated values (e.g. opportunity scores via `=SUMPRODUCT()`).
- Run `scripts/recalc.py` after saving to recalculate all formulas. This script is optional and environment-specific — skip it if not present. SUMPRODUCT formulas written by openpyxl are correct on save and will recalculate automatically when opened in Excel or Google Sheets.
- Verify zero formula errors before presenting the file.
- Save path is environment-specific: use `/mnt/user-data/outputs/[filename]` in sandboxed cloud environments. On macOS or a local environment, save to the active project directory (e.g. the working directory of the current session) or `~/Downloads/` as a fallback.

---

## Validation Checkpoints

### Input Validation

- Seed keywords or topic description clearly provided
- Target audience and business goals specified
- Geographic and language targeting confirmed (default: English, global + India)
- Domain context confirmed: new domain, zero authority

### Output Validation

- Every recommendation cites specific data points, not generic advice
- Search volume and difficulty scores included for each keyword (or clearly labeled as proxy)
- Keywords grouped by intent and mapped to content types
- Topic clusters show clear pillar-to-cluster relationships
- Source of each data point clearly stated
- Output is a correctly named .xlsx file — not markdown, not plain text
- Filename follows `YYYYMMDD-keyword-topic.xlsx` convention
- All 9 sheets are present and populated
- Zero formula errors in the workbook

---

## Quality Standards

- Do not recommend a keyword without actually checking its SERP. Guessing at competition
  levels produces a useless report.
- Do not present exact search-volume or KD numbers unless sourced from an actual tool.
  If using public SERP proxies, label them clearly as proxy judgments.
- Be specific with evidence: "Top 3 results are CoinDesk posts from 2023, no Reddit
  discussion" is useful. "High competition" alone is not.
- Be honest about uncertainty. If signals are mixed, flag the keyword as
  "unverified — worth a manual check."
- Think in clusters. A single post is a gamble. Five posts on related long-tails in the
  same topic area build authority fast.
- Prioritize keywords where GMGM News can bring a fresh angle, a clearer explanation,
  or a more current take — not just lower competition.
- Every final recommendation must connect to a business or editorial reason, not just
  search volume.
- For financial, regulatory, or risk topics, use current primary sources where possible
  and avoid investment advice framing.

---

## Accumulated Lessons

*This section grows as GMGM News publishes and collects ranking data. Each lesson
represents a real calibration based on observed search performance. Apply all lessons
when running new research — they override the defaults where they conflict.*
