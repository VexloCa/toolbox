# Lead Qualification Scorer

> Score and prioritize inbound leads automatically

**Category:** Sales & Lead Generation · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

When leads come in faster than you can call them back, the ones that get attention first are usually whichever landed on top of the inbox, not the ones most likely to close, which means good leads go cold while you're chasing dead ends. This gives every lead a consistent score the moment it arrives, so your time goes to the leads worth chasing.

## The prompt

```
PART 1, BUILD THE RUBRIC (run this once):

You are a sales operations consultant who builds lead scoring systems for
small businesses. You turn a vague sense of "good fit" into a concrete,
repeatable rubric.

MY IDEAL CUSTOMER: [DESCRIBE WHO BUYS FROM YOU AND CONVERTS WELL: SIZE,
INDUSTRY, BUDGET RANGE, URGENCY SIGNS, ANYTHING ELSE THAT MATTERS]

MY WORST-FIT LEADS: [DESCRIBE THE LEADS THAT WASTE YOUR TIME: TOO SMALL,
WRONG INDUSTRY, TIRE-KICKERS, WHATEVER PATTERN YOU'VE NOTICED]

WHAT INFORMATION I TYPICALLY HAVE ON A NEW LEAD: [E.G. A CONTACT FORM
WITH COMPANY SIZE AND BUDGET FIELD, OR JUST AN INBOUND EMAIL WITH NO
STRUCTURE]

Build me a 100-point scoring rubric across 4-5 categories (e.g. fit,
budget signal, urgency, authority to decide) with point values per
category and clear criteria for what earns full points, partial points,
or zero. End with 3 score bands (e.g. 80-100 hot, 50-79 warm, below 50
low priority) and the recommended next action for each band.

---

PART 2, SCORE A LEAD (reuse this every time, with the rubric from Part 1
saved above it):

Using the rubric above, score this lead:

LEAD INFORMATION: [PASTE THE LEAD'S FORM ANSWERS, EMAIL, OR WHATEVER
INFORMATION YOU HAVE: AS-IS, DON'T CLEAN IT UP]

YOUR TASK:
1. SCORE: A number out of 100, broken down by category with points
   awarded and a one-line reason for each.
2. FIT SUMMARY: 2-3 sentences on who this lead is and why they scored
   where they did.
3. RECOMMENDED NEXT ACTION: Based on the score band, what should happen
   next, call today, nurture sequence, polite decline, or request more
   information because the lead is unscoreable as given.

RULES: If the lead information is too thin to score confidently, say so
and list exactly what additional information would resolve it, rather
than guessing. Never inflate a score to be encouraging, the point is
accurate prioritization, not positivity.

OUTPUT FORMAT: Score breakdown table, fit summary, recommended action, short enough to scan in 10 seconds before deciding who to call first.
```

## How to use it

1. Run Part 1 once with a real conversation with yourself about your best and worst customers: the sharper the contrast, the better the rubric.
2. Save the resulting rubric as a reusable Claude Project or a custom instruction (in ChatGPT, a custom GPT or saved instruction) so every new lead is scored against the exact same standard without re-pasting it each time.
3. Whenever a new lead comes in, paste its raw information into Part 2 inside that same Project/custom instruction.
4. Sort your day's leads by score before making calls: hot leads first, always.
5. Revisit the rubric every quarter or after a batch of leads convert or don't, and adjust point values based on what you're actually seeing.
6. If a lead consistently scores low but keeps converting anyway, that's a signal to update the rubric, not to ignore the score.

## Example

**Rubric excerpt (from Part 1):** Fit (30 pts): full points if company size 10-50 employees in professional services; Budget signal (25 pts): full points if they mention a specific budget range or ask about pricing tiers; Urgency (25 pts): full points if they mention a deadline or current pain; Authority (20 pts): full points if the contact is owner/director-level.

**Input lead (Part 2):** "Hi, we're a 22-person law firm looking to modernize intake. Currently losing track of leads in email. Would love to see pricing, hoping to have something in place before end of quarter.: Alicia Ruiz, Managing Partner"

**Output:** Score: 88/100: Fit: 30/30 (professional services, right size). Budget: 20/25 (asked about pricing, no range stated). Urgency: 25/25 (explicit deadline, named pain). Authority: 20/20 (Managing Partner, clear decision-maker, no MEDDIC gaps). Fit summary: strong-fit lead with a real deadline and a decision-maker reaching out directly: closest match to your best-customer profile. Recommended action: call today, lead with the intake-tracking pain she already named.

## Pro tip

Once you've scored 20-30 real leads, paste the outcomes back in (which ones actually closed) and ask the AI to flag any category where the score didn't predict the outcome. This is the fastest way to catch a rubric that's weighting the wrong signal.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/lead-qualification-scorer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
