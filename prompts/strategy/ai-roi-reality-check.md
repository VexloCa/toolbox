# AI ROI Reality Check

> A keep / cancel / renegotiate verdict on every AI tool you pay for

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Ask a business owner what their AI tools return and you get a feeling, not a number. Subscriptions renew on autopilot, the "time saved" claim comes from the week the tool was new, and nobody has checked whether the $49/month writer still gets opened. This prompt forces the question tool by tool: what does it cost, what did it measurably change, and would you buy it again today at today's price?

## The prompt

```
You are a skeptical operations consultant reviewing my AI spend. Your job
is to find the tools that don't earn their cost, not to validate my
purchases. Be blunt.

MY BUSINESS: [ONE PARAGRAPH: WHAT YOU DO, TEAM SIZE, ROUGH REVENUE BAND]

MY AI SPEND: for each tool or automation, one line:
[TOOL NAME] | [WHAT IT DOES FOR US] | [$/MONTH] | [WHO USES IT AND HOW
OFTEN, HONESTLY] | [WHAT WE DID BEFORE IT]

Repeat the line for every subscription, API-billed automation, and
AI feature you pay extra for. Include the ones you're embarrassed about.

FOR EACH TOOL, WORK THROUGH:
1. THE REPLACEMENT TEST: what would we do next Monday if it vanished?
   If the answer is "nothing changes," say so and stop there.
2. THE REAL RETURN: name the measurable change (hours/week, response
   time, error rate, revenue touched). If I gave you a vibe instead of
   a number, ask me for the number or tell me how to get it this week.
3. THE TODAY PRICE TEST: would we buy it again today, at the current
   or announced price, knowing what we know? Note any intro pricing
   with an expiry and re-run the math at the post-expiry price.
4. THE OVERLAP CHECK: does another tool on this list, or the assistant
   we already pay for, do the same job?

THEN, THE VERDICT TABLE: one row per tool:
KEEP (earns its cost, keep measuring) /
CANCEL (fails the replacement test or the today-price test) /
RENEGOTIATE (real value, wrong price or wrong tier) /
CAN'T TELL (missing a number; name the number and how to measure it
in 30 days or less).

FINISH WITH:
- Total monthly spend now vs. after your recommendations
- The one tool most likely to be a placebo, and why
- A 90-day re-check plan: which numbers to track so the next review
  takes 20 minutes instead of an afternoon.

RULES: Never accept "it saves time" without asking whose time and how
much. If a tool survives only because canceling feels like admitting a
mistake, name that. If my whole list is one chat subscription, tell me
the review is done and to go back to work.
```

Two of the questions this prompt asks are easier with the numbers already in hand: our [AI Spend Auditor](/toolbox/ai-spend-auditor) skill maintains the inventory this prompt reviews, including intro-price expiry dates like the one on [Gemini 3.7 Flash](/blog/gemini-3-7-flash-price-doubles). Run this review before signing anything annual, and before [hiring outside help](/blog/when-to-hire-an-ai-consultant).

## How to use it

1. Copy the full prompt into Claude or ChatGPT.
2. Fill the spend list from your actual card statements, not memory. The forgotten $29 charges are the point of the exercise.
3. Answer the "who uses it and how often" field honestly. "Nobody since March" is a valid and useful answer.
4. When the verdict says CAN'T TELL, do the 30-day measurement before deciding. A guess dressed as a verdict is what got the tool renewed last time.
5. Re-run the prompt quarterly with the updated numbers. The second pass takes a fraction of the time.

## Example

A 9-person landscaping company lists six lines: two chat subscriptions, an AI scheduling add-on, a proposal writer, a Zapier scenario calling a language model, and an AI phone answering service. The verdict comes back: keep the phone service (it books jobs after hours, and the booking count is in its dashboard), cancel one of the two chat subscriptions (full overlap), renegotiate the scheduling add-on (annual plan priced against a team of 20, they are 9), and two CAN'T TELLs with a specific number to track for each. Monthly spend drops from $412 to $278, with a re-check date in the calendar.

## Pro tip

Run the today-price test against announced future prices, not current ones. Intro rates on models and AI tools increasingly ship with a printed expiry date, and a tool that clears the bar at the promo price and fails it at the real price is already a RENEGOTIATE, you know it three months early.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-roi-reality-check). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
