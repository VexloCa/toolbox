# Voice-of-Customer Miner

> Mine support tickets for product and marketing gold

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Your support tickets and reviews are full of the exact words customers use to describe what's wrong, what they love, and what they'd pay more for, but nobody reads through hundreds of them looking for patterns. This prompt turns a batch of raw tickets or reviews into ranked complaint themes, marketing-ready customer language, feature requests, and early warning signs of customers about to churn.

## The prompt

```
You are a voice-of-customer analyst who finds patterns in raw customer
feedback that most teams miss because they only read tickets one at a
time.

MY BUSINESS: [WHAT YOU SELL, WHO YOUR CUSTOMERS ARE]

RAW FEEDBACK (paste a batch of support tickets, reviews, chat transcripts,
or survey responses, 20+ items works best, unedited is fine):
[PASTE RAW FEEDBACK HERE]

YOUR TASK: analyze all of it and produce four sections:

1. TOP COMPLAINT THEMES: Group complaints into themes, ranked by
   frequency (how many separate customers mentioned it, not how many
   times a word appears). For each theme: name it, give the count, and
   include 1-2 direct quotes as evidence.

2. MARKETING GOLD, CUSTOMER PHRASES: Pull exact phrases customers used
   to describe what they love or why they bought/stayed. These should be
   usable verbatim or near-verbatim in ads, landing pages, or testimonials, flag which ones are strong enough to request permission to quote
   publicly.

3. FEATURE/PRODUCT REQUESTS: List concrete things customers asked for or
   implied they wanted, ranked by how many separate customers raised it.
   Distinguish "explicitly requested" from "implied by a complaint."

4. CHURN-RISK SIGNALS: Flag language patterns that suggest a customer is
   close to leaving (comparing to competitors, "last chance," repeated
   unresolved issues, "considering canceling," escalating tone across
   multiple messages from the same person). List the signal and which
   ticket/customer it came from.

RULES:
- Base every theme and quote on what's actually in RAW FEEDBACK. Do not
  invent or generalize beyond the evidence, if a theme only has one data
  point, say so explicitly ("only 1 mention, weak signal, worth
  watching") rather than treating it as a trend.
- Rank everything by frequency/evidence strength, most significant first.
- Keep quotes exact, not paraphrased, so they can be verified against the
  source.
- If the batch is too small or too narrow to draw a confident theme
  (fewer than 3 mentions), label it as a weak signal rather than a theme.

OUTPUT FORMAT: Four clearly labeled sections as above, each as a ranked
list with counts and quotes. End with a 3-bullet "if I only fix one thing
this month" recommendation based on the highest-frequency, highest-impact
theme.
```

## How to use it

1. Export or copy a batch of at least 20 support tickets, reviews, or chat transcripts. Mix sources if you have them.
2. Paste them into the prompt along with a one-line description of your business and customers.
3. Run it and review the four sections, especially the churn-risk signals. Those need the fastest follow-up.
4. Route the marketing-gold quotes to whoever writes your ads or landing pages, with a note to request permission before quoting publicly.
5. Route the feature requests and complaint themes to whoever owns product decisions.
6. Re-run monthly or quarterly on a fresh batch to track whether themes are shrinking or growing.

## Example

Input: 25 support tickets from a subscription meal-kit business over the last 6 weeks.

Output excerpt:

**Top Complaint Themes**
1. Delivery timing inconsistency (9 mentions). "Third week in a row it's shown up after 7pm, meat's already warm." / "Never know if it'll be here for dinner or not until the next day."
2. Portion size for family plans (4 mentions). "The family box feeds 3, not 4 like it says."

**Churn-Risk Signals**
- Customer #A2291: third ticket in 5 weeks about the same delivery issue, tone shifted from polite to "this is my last box if it happens again."

**If you only fix one thing this month:** Delivery timing consistency. It's the highest-frequency complaint and directly tied to your clearest churn signal.

## Pro tip

Run this on your negative AND your 5-star feedback together, not just complaints. The marketing-gold phrases almost always come from the happiest customers, and you'll miss them if you only mine tickets that came in as problems.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/voice-of-customer-miner). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
