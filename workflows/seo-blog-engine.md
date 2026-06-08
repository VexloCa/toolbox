# SEO Blog Post Engine

> Publish search-ranking blog posts weekly without a writer

**Category:** Marketing & Content · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Blogging is one of the highest-ROI marketing channels for small businesses because it compounds, but it's also the first thing to get dropped when there's no dedicated writer. This four-step workflow takes you from "no idea what to write about" to a publish-ready, search-optimized post that still sounds human, repeatable every week.

## The workflow

### Step 1: Keyword Brainstorm

```
You are an SEO strategist for small businesses. You find keywords that are
realistic to rank for, not the highest-volume terms, but the ones a small
site can actually win.

MY BUSINESS: [WHAT YOU SELL/DO]
MY LOCATION (if relevant): [CITY/REGION OR "NONE: ONLINE ONLY"]
MY CUSTOMER'S BIGGEST QUESTIONS BEFORE BUYING: [LIST 3-5 REAL QUESTIONS
CUSTOMERS ASK YOU]
COMPETITORS I KNOW OF: [1-3 COMPETITOR NAMES OR WEBSITES, IF KNOWN]

YOUR TASK: Generate 15 blog post topic ideas as keyword targets, split into:
- 5 "quick win" topics (low competition, specific/long-tail, likely
  achievable within 2-3 months)
- 5 "buyer intent" topics (someone close to purchasing would search this)
- 5 "authority" topics (broader, builds topical trust, longer-term payoff)

For each topic give: the target keyword phrase, estimated search intent
(informational/commercial/transactional), and one sentence on why my
specific business is credible to write it.

RULES: No topic requiring data or expertise I don't plausibly have. Prefer
specific long-tail phrases over broad single words. Flag if a topic requires
me to link to a source or cite a stat I'd need to find.
```

### Step 2: Outline

```
You are a content editor who builds outlines that satisfy both readers and
search engines, comprehensive without padding.

TOPIC/KEYWORD: [PASTE CHOSEN TOPIC FROM STEP 1]
MY BUSINESS CONTEXT: [WHAT YOU DO, RELEVANT EXPERTISE]
TARGET READER: [WHO IS SEARCHING THIS AND WHAT THEY ALREADY KNOW]
DESIRED READER ACTION AFTER READING: [E.G. BOOK A CALL, SIGN UP, BUY]

YOUR TASK: Build a blog post outline with:
1. Three title options (include the keyword naturally, no clickbait)
2. Meta description (150-160 characters, includes keyword)
3. H2/H3 structure covering the topic comprehensively, anticipate the
   sub-questions a reader would have, in the order they'd ask them
4. For each section: 1-2 sentence note on what specific point/example to
   make (not generic, tied to my business context)
5. Where to naturally place one call-to-action (not the intro, not forced)
6. A "People Also Ask"-style FAQ section with 3-4 question/short-answer
   pairs suited for featured snippets

RULES: No section that exists just to hit a word count. Structure must let
a skimmer get the answer from headers alone.
```

### Step 3: Draft with E-E-A-T constraints

```
You are writing this blog post as someone with direct, hands-on experience
in the subject, not as a generic explainer. Google and readers reward
demonstrated experience, expertise, authority, and trustworthiness (E-E-A-T).

OUTLINE: [PASTE APPROVED OUTLINE FROM STEP 2]
MY VOICE: [PASTE VOICE CARD OR DESCRIBE TONE]
SPECIFIC EXPERIENCE TO DRAW ON: [A REAL STORY, NUMBER, MISTAKE, OR RESULT
FROM YOUR BUSINESS RELEVANT TO THIS TOPIC]

YOUR TASK: Write the full post following the outline exactly.

RULES:
- Open with a specific claim or observation, never "In today's world..."
- Include at least one first-person, concrete detail from the experience
  I gave you (a number, a specific situation, a named mistake), this is
  non-negotiable, it's what separates this from generic AI content
- No unverifiable statistics. If a stat would help but I haven't given you
  one, write [NEEDS STAT: describe what to find] instead of inventing one
- Short paragraphs (2-4 sentences), scannable, no filler transitions like
  "It's important to note that"
- End with the CTA from the outline, phrased naturally
- Target length: 1,200-1,800 words unless the outline suggests otherwise
```

### Step 4: Humanize & Edit Pass

```
You are a sharp human editor doing a final pass on this draft before
publishing. Your job is to remove every trace of generic AI phrasing and
tighten it into something a real person would actually publish.

DRAFT: [PASTE FULL DRAFT FROM STEP 3]

YOUR TASK:
1. Flag and rewrite any sentence using AI-tell phrases ("in today's
   fast-paced world," "it's important to note," "unlock," "elevate,"
   "delve," "in conclusion," excessive rule-of-three lists)
2. Vary sentence length, flag any paragraph where every sentence is a
   similar length
3. Check the opening two sentences actually earn a reader's attention;
   rewrite if not
4. Verify the CTA doesn't feel bolted on
5. Give me a final version, followed by a short changelog of what you
   fixed and why

RULES: Preserve all facts and the specific experience/story from the
draft exactly, you're editing style, not content. If something reads as
unverifiable or overconfident, flag it rather than deleting it silently.
```

## How to use it

1. Run Step 1 once, choose one topic per week from the 15 generated.
2. Run Step 2 with that topic, review the outline, and adjust the H2s if any section doesn't fit your business.
3. Feed the approved outline into Step 3, making sure you supply a real, specific experience. This is the step that determines whether the post ranks or reads as generic filler.
4. Run Step 4 on the full draft before publishing anywhere.
5. Publish, then add internal links from 2-3 older posts to the new one.
6. Repeat weekly, batching Step 1 monthly to always have a topic bank ready.

## Example

Input: a commercial HVAC maintenance company choosing a topic from Step 1's "quick win" list: "how often should a rooftop unit be serviced in [region]." Step 3's specific experience: a client whose unit failed in August because they skipped a spring inspection, costing them $4,200 in emergency repair versus a $180 maintenance visit.

Sample Step 3 output excerpt:

"Last August, we got a call from a warehouse client whose rooftop unit had quietly failed overnight: 34°C outside, no cooling, product at risk. The fix cost $4,200 in emergency labor and parts. The spring inspection they'd skipped would have cost $180 and caught the failing capacitor three months earlier. That's the real math behind maintenance schedules, not the vague 'twice a year' advice you'll find everywhere else..."

## Pro tip

Keep a running note of small, specific stories, numbers, and mistakes from your business. Step 3 lives or dies on that input, and having five ready before you sit down saves you from staring at a blank field mid-workflow.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/seo-blog-engine). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
