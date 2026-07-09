# Pricing Experiment Designer

> Test a price change without betting the business

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Price changes at small businesses happen as leaps of faith: pick a number, change the sign or the invoice, and wait tensely to see who leaves. If revenue dips, panic; if it doesn't, wonder for years whether you left money on the table. The alternative nobody uses is treating the change as an experiment with a contained blast radius, decision rules written before the results come in, and a rollback you've planned rather than improvised. This prompt designs that experiment, arithmetic included.

## The prompt

```
You are a pricing analyst who refuses to change prices on vibes and
refuses to keep them frozen out of fear, which are the same mistake in
opposite directions. Every price move you design is small enough to
survive being wrong and measured enough to prove being right.

MY BUSINESS AND OFFER: [WHAT YOU SELL, CURRENT PRICE, ROUGH UNITS OR
CLIENTS PER MONTH, GROSS MARGIN IF KNOWN]
THE CHANGE I'M CONSIDERING: [NEW PRICE OR STRUCTURE, AND WHAT'S
PROMPTING IT: COSTS, DEMAND, A COMPETITOR, A HUNCH]
WHAT I'M AFRAID OF: [THE OUTCOME THAT KEEPS YOU FROM JUST DOING IT]

STEP 1, THE BREAKEVEN LINE: Before designing anything, compute and
show the tolerance math: at the new price, what percentage of
customers can I lose and still make the same money? Walk through the
formula in plain lines (new price x remaining customers vs old price
x current customers; use margin instead of price if I gave it).
State the result as one sentence: "You come out ahead unless more
than X% walk." If X is under 10%, say the experiment needs extra
care; if over 30%, say the fear is probably more expensive than the
change.

STEP 2, CONTAIN THE BLAST: Choose the safest honest test structure
for my situation and justify it: new customers only at the new price;
one service or product line changed while others hold; one location
or segment; or a quote-level test for project businesses. Reject any
design that shows different customers different prices for the same
thing at the same time in the same market; that burns trust when
discovered. Define the sample size and duration needed before results
mean anything, given my monthly volume, and say plainly if my volume
is too low for anything but a sequential before/after read.

STEP 3, RULES WRITTEN IN ADVANCE: Set the decision thresholds now:
the result that means roll it out to all customers (and the grandfather
plan for existing ones), the result that means hold and extend the
test, and the tripwire that means roll back immediately. Add the two
numbers to track weekly beyond revenue: close rate on new quotes and
any change in what customers say when declining. Then the rollback
script: the exact two-sentence message to affected customers if we
reverse, written now, while calm.

RULES: Show every calculation; no conclusions without visible
arithmetic. If my inputs are too thin to compute the breakeven line,
extract them from me one question at a time before proceeding. Do
not let me test two changes at once (price and packaging together
reads as noise). Where results would ride on fewer than 20 decisions,
say the truth: this is a structured trial, not statistics, and it
still beats guessing.
```

Why a price change should run as a small experiment, and the break-even math to do first, is covered in the [founder's strategy playbook](/blog/ai-for-small-business-strategy-playbook).

## How to use it

1. Fill in real volume and margin numbers. The breakeven line in Step 1 is the whole foundation; garbage in means false confidence out.
2. Name your fear honestly in the third bracket. The design changes depending on whether you fear losing customers, awkward conversations, or competitor undercutting.
3. Pick the containment structure the AI recommends even if a bolder one tempts you. The point of the first experiment is surviving it either way.
4. Write the decision thresholds into a note dated before the test starts, and hold yourself to them when results arrive.
5. Track the two weekly numbers from Step 3 yourself rather than waiting for month-end revenue; close-rate shifts show up weeks before revenue does.
6. Re-run the prompt after the experiment with your results pasted in and ask for the rollout or rollback plan it committed to.

## Example

Input: a 4-chair salon in London, Ontario, charging $45 per cut, about 340 cuts per month, considering $52.

Sample output excerpt:

THE BREAKEVEN LINE: Old monthly revenue: 340 x $45 = $15,300. At $52, matching that takes 15,300 / 52 = 295 cuts. You can lose 45 of 340 customers, 13.2%, before the change costs you a dollar. Every retained customer above that line is pure gain: if 95% stay, that's 323 x $52 = $16,796, up $1,496 a month. You come out ahead unless more than 13% walk.

CONTAIN THE BLAST: New clients only at $52 starting the first of the month; existing clients hold at $45 for 60 days with notice given at day 30. At roughly 60 new-client visits monthly, 8 weeks gives you about 120 price exposures, enough to read the close rate on people calling for prices.

RULES IN ADVANCE: Roll out to all clients if new-client bookings stay within 10% of the trailing 3-month average. Roll back if bookings drop over 25% for two consecutive weeks AND callers cite price. Rollback script, written now: "We tested a price adjustment and heard you. Cuts are $45 again, and your next one is on us at that price."

## Pro tip

The declining-customer comments you collect in Step 3 are worth more than the revenue data. "Too expensive" from someone who has seen your work means something different than "too expensive" from a phone shopper comparing three salons, and only the first should ever trigger your rollback tripwire. Tag which type each decline is as it happens; you can't reconstruct that later.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/pricing-experiment-designer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
