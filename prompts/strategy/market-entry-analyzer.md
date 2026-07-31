# New Market Entry Analyzer

> A go/no-go on the new market with the evidence listed

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Expanding into a new city, segment, or product line is the decision small businesses most often make on gut feel, because the owner spotted an opportunity and momentum took over from there. The costs show up later: a second location that eats the first one's profits, a new customer segment that pays slower and complains more. Generic AI advice lists "factors to consider" and leaves the decision exactly where it started. This prompt forces a written verdict, backed by evidence you can point at when someone asks why.

## The prompt

```
You are a market entry analyst who has watched more expansions bleed cash
than succeed, and you know the difference is rarely ambition. It's
whether anyone did the arithmetic before signing anything. Your job is to
get me to a defensible go/no-go, not to encourage me.

CURRENT BUSINESS: [WHAT YOU DO, WHERE, REVENUE RANGE, TEAM SIZE]
THE MARKET I WANT TO ENTER: [NEW CITY / SEGMENT / PRODUCT LINE, AND WHY
IT'S TEMPTING]
WHAT ENTRY WOULD COST: [YOUR BEST GUESS AT UPFRONT AND MONTHLY COSTS. IF
YOU DON'T KNOW, SAY SO]

STEP 1, THE BET IN ONE SENTENCE: Restate my expansion as a falsifiable
bet: "We believe [customer type] in [market] will pay [price] for
[offer] because [reason]." Make me confirm or correct every bracket
before moving on. If I can't fill one, that gap is finding number one.

STEP 2, EVIDENCE LEDGER: Build two columns: evidence FOR entry and
evidence AGAINST. Interview me to fill both: inbound requests from that
market, competitor presence and pricing, what's different about serving
it (travel, licensing, delivery cost, language, payment habits). Every
entry needs a source: a number, a named observation, a quote. Anything
sourced to "I feel like" goes in a third column labeled UNTESTED, not
in the ledger.

STEP 3, THE ARITHMETIC: Using my cost estimates, show the math in
plain lines: monthly cost of entry, revenue per customer, customers
needed to break even monthly, and how long my cash runway funds the
attempt if it lands at half my hoped-for pace. State each formula
before computing it.

STEP 4, VERDICT: Give one of three calls and defend it from the ledger:
GO (with the 3 conditions that must stay true), NO-GO (with what would
have to change to revisit), or NOT YET (with the 2-3 cheapest probes,
each costed and dated, that would convert UNTESTED entries into
evidence). Then list the first three actions with owners and dates.

RULES: Do not average your way to a verdict; if the AGAINST column
holds a disqualifier, say NO-GO even if FOR is longer. Never invent
market data; where I've given you nothing, write "unknown" and treat
unknowns as risk. Flag any licensing, tax, or regulatory difference in
the new market as a verify-with-a-professional item, since rules vary
by province and industry.
```

## How to use it

1. Gather 15 minutes of raw material first: any inbound interest from the new market, a competitor's public pricing, your rough cost guesses.
2. Paste the prompt with those inputs and let Step 1 sharpen the bet. If you can't fill the brackets, that alone is worth the exercise.
3. Push back during the evidence ledger. If the AI accepts a vague entry, ask it to apply its own sourcing rule.
4. Check the Step 3 arithmetic by hand once. It takes two minutes and catches both AI slips and your own optimistic cost guesses.
5. If the verdict is NOT YET, run the probes before revisiting. The prompt is reusable; bring back the probe results and ask for a fresh verdict.
6. Verify any licensing or tax differences with your accountant or a local professional before committing money. The AI can flag them, not clear them.

## Example

Input: a 9-person HVAC company in Hamilton considering expansion into the Niagara region, drawn by three inbound calls last quarter.

Sample output excerpt:

THE BET: "We believe homeowners in Niagara will pay our standard $165 service-call rate for HVAC repair because local incumbents book two weeks out." You confirmed the wait-time claim from two customer comments, not from checking. Moved to UNTESTED.

THE ARITHMETIC: Monthly entry cost: one van plus a dispatcher's split time, roughly $9,400. Average revenue per completed job: $410. Breakeven: 9,400 / 410 = 23 jobs per month. Your Hamilton crews averaged 31 jobs per tech per month, so this is one tech running at 75% capacity, in a market where you have zero review presence.

VERDICT: NOT YET. Probe 1: call five Niagara competitors as a customer and record actual quoted wait times. Cost: an hour. Date: this week. Probe 2: run $300 of geo-targeted ads offering booked slots and count real requests, not clicks, over three weeks.

## Pro tip

Write down your gut verdict before running the prompt and seal it in a note. If the analyzed verdict matches, you got confirmation cheap. If it doesn't, you have found exactly where your instinct and your evidence part ways, and that gap is worth more than either answer alone.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/market-entry-analyzer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
