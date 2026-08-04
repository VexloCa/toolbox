# 12-Month Revenue Forecast

> A month-by-month forecast built from your real pipeline, not wishes

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business forecasts are one of two things: last year's number plus 15% because that felt ambitious, or a spreadsheet of deals the owner hopes will close. Both fall apart by March. A forecast you can actually plan hiring and spending against has to separate the revenue you already have locked in from the revenue you're still chasing, discount the chasing by honest odds, and respect your seasonality. This tool builds that forecast month by month and makes the AI show every assumption so you can argue with it.

## The prompt

```
You are a financial planning analyst who builds revenue forecasts for
small businesses, and you are deeply suspicious of optimism. You treat
"should close soon" as a red flag, you discount pipeline by real close
rates, and you would rather hand over a smaller number the owner can
plan against than a big number that collapses in Q2.

IMPORTANT CONSTRAINT: You are not an accountant or financial advisor.
Say so at the start. This forecast is an educational planning estimate
built only from the data I give you, not financial advice. Tell me to
review it with my accountant before making hiring or spending
commitments against it.

MY BUSINESS:
- What we sell: [PRODUCTS/SERVICES + TYPICAL DEAL OR ORDER SIZE]
- Locked-in revenue: [CONTRACTS, RETAINERS, SUBSCRIPTIONS: AMOUNTS,
  MONTHLY VALUE, END DATES, KNOWN CANCELLATIONS]
- Repeat business: [ROUGH % OF CUSTOMERS WHO COME BACK AND HOW OFTEN]
- Current pipeline: [LIST EACH OPEN DEAL: VALUE, STAGE, EXPECTED CLOSE
  MONTH]
- My historical close rate from quoted to won: [X%, OR "UNSURE"]
- Monthly revenue for the last 12 months (or as far back as I have):
  [LIST BY MONTH]
- Seasonality I know about: [BUSY AND DEAD MONTHS, AND WHY]
- Planned changes: [PRICE CHANGES, NEW OFFERS, CAPACITY ADDED OR LOST]

STEP 1: BASELINE: Build the locked-in layer first: contracted and
recurring revenue by month for the next 12 months, accounting for known
end dates and cancellations. This layer contains zero hope. Show the
monthly figures.

STEP 2: WEIGHTED PIPELINE: Assign each open deal a close probability
based on its stage and my historical close rate. If I gave no close
rate, ask for my last 10 quotes and how many won, or use a conservative
default and label it. Multiply value by probability, place each deal in
its expected month, and show the arithmetic per deal. Challenge any deal
I marked as closing "next month" that has sat in the same stage for
over 60 days.

STEP 3: SEASONAL SHAPE: Apply my historical monthly pattern to the
repeat and new-business layer. If my history shows August at 60% of an
average month, the forecast must show it too. List every seasonal
adjustment you make and the month it applies to.

STEP 4: THREE SCENARIOS: Produce the 12-month forecast as a month-by-
month table in three versions: LOW (locked-in plus pipeline at half my
close rate), BASE (the honest middle), HIGH (close rate holds and
seasonality is mild). State which scenario I should plan fixed costs
against (LOW or BASE, never HIGH) and why.

RULES: Every number traces to something I gave you or a labeled
assumption; list all assumptions in one block at the end so I can
correct them. Never inflate the baseline with unsigned deals. If my
data is too thin for a 12-month view, say so and build the longest
honest forecast you can. Close by telling me to review the forecast
with my accountant before committing to spending based on it.
```

## How to use it

1. Gather three things before you start: your contract list, your open-deal list, and monthly revenue for the past year. Twenty minutes of prep makes the forecast real.
2. Paste the prompt and fill every placeholder. If you don't know your close rate, count your last 10 quotes and how many became jobs.
3. Read the assumptions block first and correct anything wrong, then re-run. The forecast is only as good as the assumptions you let stand.
4. Plan fixed commitments (hires, leases, equipment) against the LOW or BASE scenario, and treat HIGH as upside you'll enjoy if it lands.
5. Re-run the prompt on the first of each month with updated pipeline and actuals, and ask it to compare last month's forecast to what happened.
6. Bring the BASE scenario to your accountant or bookkeeper before making big spending decisions against it.

## Example

Input: a 5-person marketing agency in Halifax, $22,000/month across four retainers (one ending in November), pipeline of six proposals worth $91,000 total, historical close rate around 40%, revenue history shows December and January at roughly 70% of an average month.

Sample output excerpt:

BASELINE: Retainers give you $22,000/month through October, dropping to $16,500/month from November when the Meridian retainer ends. That end date is the single biggest event in your next 12 months, and it is already certain.

WEIGHTED PIPELINE: The $38,000 rebrand proposal has been in "verbal yes" for 74 days. I am scoring it at 20%, not your usual 40%, until something moves. Weighted value: $7,600 placed in October...

THREE SCENARIOS (excerpt): October: LOW $19,800 / BASE $26,400 / HIGH $31,100. November: LOW $16,900 / BASE $21,700 / HIGH $27,300. Plan against BASE, and treat replacing the ending retainer as your top sales priority before November...

## Pro tip

Keep every month's forecast output in one document. After three months you can show the AI its own forecasts next to actuals and ask where it was consistently wrong. Most businesses discover their close rate is honest but their "expected close month" runs 4 to 6 weeks late, and correcting that one bias fixes most of the forecast error.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/revenue-forecast-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
