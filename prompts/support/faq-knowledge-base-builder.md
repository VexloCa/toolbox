# FAQ & Knowledge Base Builder

> Turn your inbox history into a complete FAQ

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

You've answered the same questions dozens of times over email, chat, and DMs, but none of it lives anywhere a customer (or a new hire), can find it. Building an FAQ from scratch feels like a week-long project, so it never happens. This turns a pile of real questions you already have sitting in your inbox into an organized, ready-to-publish FAQ page in one pass.

## The prompt

```
You are a knowledge base editor who specializes in turning messy real
customer questions into a clean, organized FAQ that customers can actually
self-serve from.

MY BUSINESS: [WHAT YOU SELL, WHO YOUR CUSTOMERS ARE]

RAW QUESTIONS/EMAILS (paste 20-50 real customer questions, emails, or chat
messages below, one per line or as full text, duplicates and messy
phrasing are fine, that's expected):
[PASTE YOUR RAW QUESTIONS/EMAILS HERE]

MY NOTES ON ANSWERS (paste any policy docs, past replies, or bullet notes
you have, doesn't need to be complete):
[PASTE WHATEVER ANSWER MATERIAL YOU HAVE]

YOUR TASK:
1. DEDUPLICATE: Merge questions that are asking the same thing in different
   words. Note how many times each merged question came up (this tells me
   what to prioritize).
2. ORGANIZE BY THEME: Group into logical categories (e.g. Ordering,
   Shipping, Returns, Billing, Product Use, Account), use categories that
   actually fit what you see, not a generic template.
3. DRAFT ANSWERS: For each question, write a clear, complete answer using
   MY NOTES. Keep answers under 80 words unless the topic genuinely needs
   more. Plain language, no jargon, second person ("you").
4. FLAG GAPS: If a question has no clear answer in MY NOTES, do NOT invent
   one. Instead write: "GAP, POLICY UNDEFINED: [the question]" and a
   one-line suggestion of what needs to be decided.
5. ORDER: Within each category, order questions by frequency (most-asked
   first).

OUTPUT FORMAT:
- A category-by-category FAQ, each question as a heading and the answer
  below it, ready to paste into a help center or website page.
- A separate "GAPS TO RESOLVE" list at the end, ranked by how often that
  question came up.
- A one-line count summary at the top: total questions processed, number
  of unique themes, number of gaps found.

RULES: Never fabricate a policy, price, or timeframe not present in MY
NOTES. If two of my notes contradict each other, flag the contradiction
instead of picking one. Write answers a customer could read and immediately
act on, no vague reassurance without a concrete next step.
```

## How to use it

1. Export or copy 20-50 real customer questions from your inbox, chat tool, or CRM. Don't clean them up first, raw is fine.
2. Gather whatever answer material exists: policy pages, old replies, internal notes, even a Slack thread.
3. Paste both into the prompt along with a one-line description of your business.
4. Run it and review the FAQ output for accuracy against your actual policies.
5. Resolve the flagged gaps with your team, then paste the finished answers back in to fill them.
6. Publish the organized output as your help center or FAQ page, and re-run quarterly as new questions accumulate.

## Example

Input: 30 pasted emails to a mid-size pet grooming business, including six variations of "do you groom cats," four about cancellation fees, and one about whether they use aggressive-dog-safe products.

Output excerpt:

**Booking & Cancellations**
Do you charge a cancellation fee? (asked 4x)
Yes, cancellations made less than 24 hours before your appointment are charged a $25 fee. Rescheduling more than 24 hours out is free.

Do you groom cats? (asked 6x)
Yes, we groom cats as well as dogs. Book the "Cat Grooming" service online or mention it when you call. Cat appointments are handled by our two cat-certified groomers.

**GAPS TO RESOLVE**
GAP, POLICY UNDEFINED: "Do you use products safe for dogs with skin allergies?" (asked 1x). Need to confirm which product lines are hypoallergenic before publishing an answer.

## Pro tip

Run this once a quarter using only the last 90 days of inbox questions: new gaps and new frequently-asked questions surface as your product or policies change, and a stale FAQ is worse than no FAQ.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/faq-knowledge-base-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
