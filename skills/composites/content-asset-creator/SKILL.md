---
name: content-asset-creator
description: >
  Turn a content brief, topic, or ICP profile into a publish-ready content asset.
  Supports blog posts, whitepapers, case studies, landing pages, email sequences,
  and product one-pagers. Applies brand voice, ICP alignment, and SEO best practices
  throughout. Works standalone or downstream of content-brief-factory.
tags: [content]
---

# Content Asset Creator

Takes a content brief (or just a topic) and produces a fully written, publish-ready asset. Works across formats — long-form blog posts, authoritative whitepapers, social-proof case studies, conversion-focused landing pages, nurture email sequences, and crisp product one-pagers.

**Core principle:** Writing without a point of view is filler. Every asset produced here has a clear thesis, speaks directly to one ICP, and ends with the reader knowing exactly what to do next.

**Works best after:** `content-brief-factory` (feeds the brief) or `brand-voice-extractor` (locks in voice). Can also run standalone with minimal intake.

## When to Use

- "Write a blog post about [topic]"
- "Turn this brief into a full article"
- "Create a whitepaper on [subject] for [ICP]"
- "Write a case study for [customer/result]"
- "Draft a landing page for [product/feature]"
- "Build a 5-email nurture sequence for [persona]"
- "Create a one-pager for [product] to send to [audience]"

## Phase 0: Intake

Ask all questions at once. Skip any that are already answered by an upstream brief.

### Content Foundation
1. **Topic or brief** — Paste a brief, write a topic sentence, or share a URL to crawl
2. **Asset type** — Blog post / whitepaper / case study / landing page / email sequence / one-pager
3. **Target length** — Short (~500w), standard (~1,000-1,500w), long-form (~2,500-4,000w), or match brief

### Audience & Positioning
4. **ICP** — Role, company size, industry, top pain point
5. **Where they are in the funnel** — Awareness / consideration / decision
6. **Core claim** — The single most important thing this asset should prove or teach

### Voice & Constraints
7. **Brand voice** — Paste a sample piece or describe the tone (or run `brand-voice-extractor` first)
8. **POV / byline** — Company voice, founder voice, or specific persona?
9. **Hard constraints** — Things to avoid, required disclaimers, competitor naming rules

### Distribution & SEO
10. **Primary keyword** — If targeting search (leave blank for gated/outbound assets)
11. **CTA** — What should the reader do at the end? (Book a demo, download, reply, share)
12. **Where it will live** — Blog, gated PDF, email, web page, LinkedIn article

## Phase 1: Structure the Asset

Before writing, build the skeleton. Output it for user review if the asset is long-form or high-stakes.

### Blog Post / Long-Form Article
```
Title (2-3 options)
Meta description (155 chars)
Estimated read time
---
H1
H2: [Section 1 — Hook / Problem]
H2: [Section 2 — Why conventional approaches fail]
H2: [Section 3 — Core framework / solution]
H2: [Section 4 — Proof / examples]
H2: [Section 5 — How to apply it]
H2: [Section 6 — FAQ (if targeting PAA)]
H2: [CTA section]
```

### Whitepaper
```
Cover: Title, subtitle, author, company, date
Executive Summary (1 page)
Table of Contents
Section 1: Market context / the problem at scale
Section 2: Why current approaches fall short
Section 3: The framework / methodology
Section 4: Evidence (data, case examples, quotes)
Section 5: Implementation roadmap
Section 6: Conclusion + next steps
Appendix (optional)
```

### Case Study
```
Headline: [Customer] + [Result] (e.g., "Acme grew pipeline 3x in 90 days")
Subheadline: One sentence on how
---
The Challenge: What was broken before
The Solution: How [company] solved it (with timeline)
The Results: Specific metrics (before/after table if possible)
Why it worked: 1-2 key insight sentences
What's next: Future plans (optional)
CTA: How to get similar results
```

### Landing Page
```
Hero: Headline + subheadline + primary CTA button
Social proof bar: Logos or quick stat
Problem section: What life looks like without this
Solution section: How it works (3-step or feature-benefit grid)
Proof section: Quote + metric + mini case study
Objection handling: FAQ or "Who this is for / not for"
Secondary CTA: Softer ask
Footer CTA: Repeat primary ask
```

### Email Sequence (5-email nurture)
```
Email 1 — Welcome / set expectations (Day 0)
Email 2 — Teach the core insight (Day 2)
Email 3 — Proof / social proof (Day 4)
Email 4 — Address the main objection (Day 7)
Email 5 — Direct CTA / offer (Day 10)
```

### One-Pager
```
Header: Product name + one-line value prop
The Problem: 2-3 bullets
Our Solution: 2-3 bullets + visual description
How It Works: 3-step diagram or process list
Results: 2-3 metrics or customer quotes
Who It's For: ICP description
CTA: Next step + contact info
```

## Phase 2: Write the Asset

Apply these rules across all formats:

### Opening (first 150 words)
- Start with the reader's pain, not your product
- No "In today's fast-paced world..." — start mid-thought
- State the core claim or thesis within the first paragraph
- Hook format options:
  - Statistic that reframes the problem
  - Story that puts the reader in the scene
  - Counterintuitive claim that demands explanation
  - Direct question that surfaces the real pain

### Body
- One idea per section — no section should make two arguments
- Use concrete examples over abstract principles (name companies, give numbers)
- Mix sentence lengths — short punchy claims followed by elaboration
- Every H2 should be able to stand alone as a value statement
- Avoid hedging language: "might", "could potentially", "in some cases"

### Proof Elements
For each major claim, include at least one:
- **Statistic** — With source; prioritize primary research over analyst reports
- **Example** — Named company, specific result, timeframe
- **Quote** — Real language from customer, practitioner, or relevant expert
- **Visual callout** — "Worth pulling out as a stat graphic: [X]" annotation where relevant

### Voice Calibration
Match the brand voice file or sample. Default voice rules:
- Direct over diplomatic
- Specific over general
- Active voice (subject → verb → object)
- Second person where possible ("you", "your team") — unless whitepaper/thought leadership
- No jargon without definition on first use

### Closing / CTA
- Restate the core claim in different words
- One primary CTA — not three
- Make the next step frictionless: tell them exactly what to click/do/say
- CTA copy: outcome-first ("See how it works" > "Learn more")

## Phase 3: SEO Pass (if keyword targeted)

Run after the draft is complete:

1. **Keyword placement** — Primary keyword in H1, first 100 words, one H2, meta description, URL slug
2. **Semantic keywords** — 3-5 related terms woven naturally into the body
3. **Internal link suggestions** — Flag 2-3 anchor text opportunities: "Add internal link here: [anchor text] → [suggest relevant existing content]"
4. **Schema annotation** — Note if FAQ schema (H2 Q&A sections), HowTo schema, or Article schema applies
5. **Readability check** — Flag any paragraph over 5 sentences for splitting; flag passive voice clusters

Output SEO checklist at end of draft:
```
## SEO Checklist
- [ ] Primary keyword: [keyword] — in H1, intro, H2, meta
- [ ] Meta description: [text] (X chars)
- [ ] Suggested URL slug: /[slug]
- [ ] Schema type: [FAQ/HowTo/Article/None]
- [ ] Internal link suggestions: [list]
- [ ] Image alt text suggestions: [list]
```

## Phase 4: Deliver

Present the full asset followed by a brief production notes block:

```
---
## Production Notes

**Asset type:** [type]
**Word count:** ~[N] words
**Estimated read time:** [N] min
**Primary keyword:** [keyword or "N/A — outbound/gated"]
**Funnel stage:** [awareness/consideration/decision]
**Recommended CTA:** [text]
**Next steps:**
- [ ] Review and approve draft
- [ ] Add any customer quotes or data we couldn't access
- [ ] Confirm internal link targets
- [ ] Add visuals/screenshots at marked sections
- [ ] Final proofread before publishing
```

## Iteration Protocol

- User feedback → revise only the flagged section(s), not the whole piece
- Max 2 full rewrites per asset — after that, suggest a new angle instead
- If voice is off after one revision, ask for a 200-word writing sample before rewriting

## Upstream Skills

- `content-brief-factory` — Generates the brief this skill turns into a full asset
- `brand-voice-extractor` — Extracts voice guidelines to apply here
- `site-content-catalog` — Check for existing coverage and internal link targets
- `review-scraper` / `reddit-scraper` — Source authentic customer language and proof points

## Downstream Skills

- `content-repurposer` — Fan the finished asset out to LinkedIn, X, email, and more

## Tools Required

None. Pure reasoning. Works with any LLM agent. Optionally enhanced by:
- `fetch_webpage` — Crawl source URLs for research input
- `web_search` — Pull supporting stats or verify claims

## Trigger Phrases

- "Write a blog post about [topic]"
- "Turn this brief into a full article"
- "Draft a whitepaper on [topic]"
- "Create a case study from this customer story"
- "Write a landing page for [product/feature]"
- "Build a nurture sequence for [persona]"
- "I need a one-pager for [product]"
- "Write the asset from this brief"
