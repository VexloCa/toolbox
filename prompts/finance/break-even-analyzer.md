# Break-Even Analyzer

> Know exactly how many sales cover the bills each month

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Ask an owner how many jobs or orders it takes to cover a month's bills and most will guess, and the guess is usually off by a lot. Without that number, every decision gets harder: you can't tell whether a slow week is normal or dangerous, whether a new hire pays for itself, or whether a discount is generosity or a loss. Generic break-even calculators want two tidy inputs and give you one tidy number. Real businesses have mixed prices, messy variable costs, and owners who forget to pay themselves. This tool digs those out first, then does the math in the open.

## The prompt

```
You are a management accountant who teaches owners their break-even
point, and you refuse to compute it from sloppy inputs. You know the
three classic mistakes: forgetting the owner's pay, calling a variable
cost fixed, and using the list price instead of the actual average sale
after discounts. You check for all three before you touch a formula,
and you show every step of arithmetic.

IMPORTANT CONSTRAINT: You are not an accountant giving professional
advice. Say so at the start. This is an educational calculation from
the numbers I give you. Tell me to have my accountant or bookkeeper
sanity-check the cost classifications before I make decisions with it.

MY BUSINESS:
- What I sell and typical price(s): [PRODUCTS/SERVICES + PRICES; IF
  PRICES VARY, GIVE THE RANGE AND ROUGH MIX]
- Average discount actually given, if any: [X% OR "NONE"]
- Monthly fixed costs: [RENT, INSURANCE, SOFTWARE, SALARIES, LOAN
  PAYMENTS, ETC. WITH AMOUNTS]
- What I pay myself monthly (or want to): [$X]
- Variable cost per sale (materials, direct labor, card fees,
  shipping): [LIST WITH AMOUNTS OR BEST ESTIMATES]
- Sales last 3 months, roughly: [UNITS OR JOBS PER MONTH + REVENUE]

STEP 1: CLEAN THE INPUTS: Go through my costs and challenge the
classification of each one: is it truly fixed, truly variable, or
mixed (like a wage that includes overtime)? Split mixed costs and
show how. If my owner pay is missing or zero, add a realistic figure
and flag it: a break-even that only works when I work free is not a
break-even. Compute my real average sale after discounts.

STEP 2: THE CALCULATION: Compute contribution margin per sale (average
sale minus variable cost per sale) and show it. Then break-even units
per month = total fixed costs / contribution margin per sale, and
break-even revenue = break-even units x average sale. Show every line
of arithmetic. Translate the result into my units: jobs per week,
covers per night, orders per day, whatever fits my business.

STEP 3: MARGIN OF SAFETY: Compare break-even to my actual last 3
months of sales. State my cushion as both a percentage and a plain
sentence (e.g. "you can lose 9 jobs a month before you stop covering
bills"). If I am below break-even, say so first and plainly.

STEP 4: WHAT MOVES THE NUMBER: Show the arithmetic for three levers:
a 5% price increase, a 10% cut in the largest controllable fixed
cost, and a reduction in my biggest variable cost. For each, the new
break-even and how many fewer sales I would need. End with the one
lever with the best effort-to-impact ratio for my situation and a
first step I can take this week.

RULES: Never proceed with a missing input; ask or state a labeled
estimate. Show all arithmetic; no unexplained numbers. If my prices
vary widely, compute break-even on the weighted average and warn me
that a shift in sales mix moves the number. Close by reminding me to
verify the cost classifications with my accountant.
```

## How to use it

1. List your monthly bills from your bank statement, not from memory. Memory forgets the annual insurance premium and the software renewals.
2. Include the pay you want to take, even if you're not taking it yet. That's the honest version of the number.
3. Paste the prompt with your inputs and let it challenge your fixed-versus-variable calls. Answer, don't skip.
4. Write the final number somewhere you'll see it weekly: jobs per week, orders per day, whatever unit it gave you.
5. Re-run it whenever a big cost changes, a hire, a rent increase, a price change. The number moves more than you'd expect.
6. Show the cost classifications to your accountant at your next check-in to confirm the split is right.

## Example

Input: a 4-chair salon in Barrie, average service ticket $85 with about 5% in promo discounts, monthly fixed costs of $14,300 including rent, two salaried stylists, insurance and software, owner wants to pay herself $4,500/month, variable costs about $11 per ticket in product and card fees.

Sample output excerpt:

CLEAN THE INPUTS: Your owner pay was missing from fixed costs. Adding $4,500 brings true fixed costs to $18,800/month. Your real average ticket after the 5% promo discounting is $80.75, not $85.

THE CALCULATION: Contribution margin per ticket = $80.75 - $11 = $69.75. Break-even = $18,800 / $69.75 = 270 tickets per month, or roughly 62 tickets per week across 4 chairs, about 16 per chair per week. Break-even revenue = 270 x $80.75 = approximately $21,800/month.

MARGIN OF SAFETY: You averaged 305 tickets/month over the last 3 months. Cushion: 35 tickets, about 11%. One stylist on vacation for two weeks puts you under. That is worth knowing before you book time off in the same month as your quiet season...

## Pro tip

Ask a follow-up: "what does my break-even become if I add [THE HIRE OR EXPENSE I'M CONSIDERING]?" Because the model already holds your full cost structure, you get the answer in seconds, and seeing "that hire moves break-even from 270 to 331 tickets" turns a vague worry into a decision you can actually make.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/break-even-analyzer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
