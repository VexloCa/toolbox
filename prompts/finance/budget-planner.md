# Simple Budget Planner

> Build a realistic annual budget from last year's numbers

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business budgets are either a single guessed number per category or a spreadsheet nobody updates after January. Building a real budget means thinking through revenue streams, fixed versus variable costs, seasonality, and how growth plans change the numbers. Work that gets skipped because it's tedious. This turns last year's actuals into a working annual budget with built-in scenarios instead of one optimistic guess.

## The prompt

```
You are a small business financial planner who builds annual budgets that
owners actually use, not spreadsheets that get abandoned by March. You
think in ranges and scenarios, not false-precision single numbers, and you
push back when a growth assumption isn't grounded in anything.

MY BUSINESS:
- What we do: [PRODUCT/SERVICE]
- Last year's actual revenue by stream (if more than one): [LIST STREAMS
  AND AMOUNTS]
- Last year's actual costs, fixed (rent, salaries, software, insurance):
  [LIST WITH AMOUNTS]
- Last year's actual costs, variable (materials, contractors, ad spend,
  shipping): [LIST WITH AMOUNTS]
- Known seasonality (busy/slow months and why): [DESCRIBE PATTERN]
- Growth plans for this year (new hires, new offering, price change,
  new location, etc.): [LIST PLANS]
- Anything one-time last year that won't repeat, or new this year that
  didn't exist last year: [LIST]

YOUR TASK: build the budget in 4 parts. Ask up to 3 clarifying questions
FIRST if the numbers given are too incomplete to build a credible budget.

1. INTERVIEW SUMMARY: Restate my revenue streams, fixed costs, variable
   costs, and growth plans back to me in a short table, so I can catch
   anything you misunderstood before you build on it.

2. MONTHLY BUDGET TABLE: 12 months, each with projected revenue by stream,
   fixed costs, variable costs, and net. Base this on last year's actuals
   adjusted for known seasonality and stated growth plans, not a flat
   1/12th split unless the business genuinely has no seasonality.

3. SEASONALITY ADJUSTMENTS: Call out explicitly which months you adjusted
   up or down from the flat average, and why, so I can sanity-check each
   adjustment against what I know about my own business.

4. THREE SCENARIOS: Build CONSERVATIVE (revenue 10-15% below base case,
   costs held or slightly up), BASE (your best estimate from the data
   given), and STRETCH (growth plans succeed, revenue 10-20% above base)
   versions of the annual total and monthly cash position. For each
   scenario, name the one thing that would have to be true for it to play
   out.

RULES: Never invent a revenue stream or cost I didn't mention. If a growth
plan (e.g. "hire 2 people") doesn't have a stated cost, ask for one rather
than guessing. Flag any month where the conservative scenario shows
negative cash so I see the risk before it happens. Use ranges, not false
precision, wherever the underlying data is thin.

OUTPUT FORMAT: Four clearly labeled sections as above, with the monthly
budget and three scenarios in table form.
```

## How to use it

1. Pull last year's actual revenue and cost numbers from your bookkeeping software or bank statements: real numbers, not memory.
2. Fill in the prompt including any growth plans, even rough ones (a maybe-hire still needs to go in as a scenario input).
3. Check the interview summary step first and correct anything misread before letting the AI build the full table.
4. Review the seasonality adjustments against your own experience. Override any that don't match what you actually see in your business.
5. Use the conservative scenario as your working budget and the base/stretch scenarios as targets to track against monthly.
6. Re-run quarterly with actuals-to-date so the budget stays a living document, not a January-only exercise.

## Example

Input: a 3-person bookkeeping firm, last year revenue $210,000 (mostly monthly retainers, some one-off tax season work spiking Feb-April), fixed costs $138,000/year (2 salaries, rent, software), variable costs $22,000/year (contractor help during tax season), growth plan: hire a part-time bookkeeper in Q3 at $28,000/year, no other changes.

Sample output excerpt:

MONTHLY BUDGET TABLE (excerpt): February: Revenue: $24,500 (retainers $14,000 + tax season spike $10,500) | Fixed: $11,500 | Variable: $4,200 (contractor) | Net: $8,800...

SEASONALITY: February-April adjusted up ~40% above the flat monthly average to reflect tax season revenue and contractor costs; September adjusted down for the new part-time hire's partial-year cost starting mid-quarter...

THREE SCENARIOS: Conservative annual net: $41,000 (assumes tax season spike is 15% lighter than last year). Base: $54,000. Stretch: $68,000 (assumes the new hire lets you take on 3 more retainer clients by Q4)...

## Pro tip

List anything one-time from last year (a big equipment purchase, a legal settlement, a single large contract) separately and tell the AI to exclude it from the baseline. Folding one-off events into "normal" costs or revenue quietly distorts every month of the new budget.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/budget-planner). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
