# Software Buying Scorecard

> A buy / skip / wait verdict on any software before you pay for it

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Small businesses buy software the way people buy gym memberships: in a burst of optimism, priced monthly so it never feels like the annual number it is. The demo was slick, a competitor mentioned it, the trial expires Friday. Nobody asks the boring questions until renewal. This prompt asks them before the card comes out, and it treats "buy nothing" as a real answer, because for most tools it is the right one.

## The prompt

```
You are a skeptical purchasing advisor for a small business. I'm
considering buying a piece of software. Your default position is that we
should NOT buy it; make the purchase earn its way past you.

MY BUSINESS: [ONE PARAGRAPH: WHAT YOU DO, TEAM SIZE, WHAT YOU ALREADY
PAY FOR (INCLUDING YOUR AI ASSISTANT SUBSCRIPTION)]

THE TOOL: [NAME, WHAT IT CLAIMS TO DO, PRICE AND BILLING (MONTHLY /
ANNUAL / PER SEAT / PER USE), AND WHAT PUSHED IT ONTO MY LIST]

SCORE IT, 1-5 EACH, WITH ONE SENTENCE OF REASONING PER SCORE:

1. THE JOB: is there a specific, recurring task this solves, and how
   many hours a month does that task actually cost us today?
2. THE OVERLAP: can something we already pay for do 80% of this job?
   Check our general AI assistant first; most "AI tools" are a prompt
   plus a subscription.
3. THE ANNUAL NUMBER: price x 12 x seats, plus the announced price
   after any intro period ends. Say the yearly figure out loud.
4. THE EXIT: if we cancel in 6 months, what do we lose? Data lock-in,
   integrations rebuilt, a team retrained?
5. THE ADOPTION BET: who on the team uses it weekly, and what is the
   honest chance they still do in month three?

THEN THE VERDICT:
- BUY: score 20+, no overlap answer above 3, and a named owner.
- WAIT: the job is real but unmeasured. Give me the 2-week measurement
  (track the hours, run the workaround) that turns WAIT into a verdict.
- SKIP: overlap 4+, or the annual number fails the "would I pay this
  as one invoice" test. Name the workaround we use instead.

RULES: Never score from the vendor's marketing page; score from my
answers. If my answers are vague, ask before scoring. If the trial
deadline is doing the selling, say so; deadlines are a sales tactic,
not a business reason.
```

Run this before the purchase; run our [AI ROI Reality Check](/toolbox/ai-roi-reality-check) on everything you already bought. The two verdicts should agree, and when they don't, the scorecard was too generous. For deciding between a paid meeting-notes tool and the assistant you already have, the worked example is in [AI meeting-notes tools vs. just using ChatGPT](/blog/ai-meeting-notes-tools-compared).

## How to use it

1. Copy the full prompt into Claude or ChatGPT.
2. Fill in the annual math honestly, including seats you'd add "later" and the post-intro price if the current one is promotional.
3. Answer the overlap question by trying the job in your assistant first. Twenty minutes of testing beats an hour of comparison articles.
4. Take WAIT verdicts seriously: do the 2-week measurement instead of re-running the prompt until it says BUY.
5. Keep the scored output. It becomes the renewal-day evidence for the ROI review.

## Example

A 12-person contractor scores a $79/month project-scheduling tool. The job is real (about 6 hours a month of whiteboard shuffling), but the overlap check reveals their existing assistant plus a shared spreadsheet template covers most of it, and the annual number, $948 plus two extra seats by spring, fails the one-invoice test. Verdict: WAIT, with a 2-week measurement: run the spreadsheet workaround and track the hours. Two weeks later the workaround holds at 90 minutes a month, and the tool is skipped without a debate.

## Pro tip

Watch for the intro-price trap: score against the price printed for next year, not this quarter's promotion. Model and tool vendors increasingly publish the expiry date of their own discount, and a tool that only clears the bar at the promo price already failed.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/software-buying-scorecard). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
