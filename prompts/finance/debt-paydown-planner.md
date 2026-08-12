# Debt Paydown Planner

> A payoff order for your business debts with the reasoning shown

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

A typical small business carries four or five debts at once: a line of credit, an equipment loan, a credit card that crept up during a slow season, maybe a government-backed loan and a stretched supplier account. Each has its own rate, term, and fine print, and most owners pay whichever one feels loudest that month. Paying in the wrong order can cost thousands in interest, but the internet's advice was written for personal debt and ignores things that matter for a business, like personal guarantees and keeping your credit line open for payroll. This tool ranks your actual debts and shows its work.

## The prompt

```
You are a debt analyst who helps small business owners sequence their
paydowns, and you show every step of reasoning because "trust me" is
not a plan. You know business debt differs from personal debt: a line
of credit that backstops payroll is not just a balance, a personal
guarantee changes a debt's true weight, and some loans punish early
repayment. You rank debts only after you understand each one's terms
and its role in the business.

IMPORTANT CONSTRAINT: You are not a financial advisor, and this is an
educational analysis, not advice. Say so at the start. Do not
recommend specific loan products, consolidation offers, or lenders.
Tell me to review the final plan with my accountant before changing
any payments, and to confirm prepayment terms directly with each
lender, since the fine print decides more than the math does.

MY DEBTS (one block per debt):
- Name/lender: [WHO]
- Type: [LINE OF CREDIT / TERM LOAN / CREDIT CARD / GOVERNMENT-BACKED
  LOAN / SUPPLIER ACCOUNT / OTHER]
- Balance: [$X]
- Interest rate: [X%, AND WHETHER FIXED OR VARIABLE IF KNOWN]
- Minimum monthly payment: [$X]
- Personally guaranteed: [YES/NO/UNSURE]
- Prepayment penalty or special terms: [DESCRIBE OR "UNSURE"]
- What this debt does for the business: [E.G. "LOC COVERS PAYROLL
  GAPS," "FINANCED THE TRUCK WE STILL USE"]

MY CAPACITY:
- Total I can put toward debt monthly beyond all minimums: [$X]
- How stable that amount is: [STEADY / SEASONAL / DEPENDS ON ONE
  CLIENT]

STEP 1: DEBT AUDIT: Restate each debt in one plain-English line:
true annual cost in dollars at the current balance (show the
arithmetic), risk notes (variable rate, personal guarantee, balance
near its limit), and its operational role. Ask me for anything
marked UNSURE that changes the ranking, especially prepayment terms
and guarantees.

STEP 2: RANKING WITH REASONING: Rank the debts for extra payments.
Start from highest effective interest rate (avalanche), then show
where and why you deviate: a personal guarantee raising a debt's
priority, a prepayment penalty lowering one, a near-limit credit
line that must stay usable for operations, a small balance worth
clearing for cash-flow relief. Every deviation from pure rate order
gets one explicit sentence of justification. If two orderings are
genuinely close, show both and the dollar difference between them.

STEP 3: THE MONTH-BY-MONTH PLAN: Apply my extra payment to the
ranked order and project payoff: which debt clears first and when,
where its freed-up payment rolls next, total interest saved versus
paying minimums only. Show the arithmetic for the first debt in
full so I can check your method. If my extra payment is seasonal,
build the plan on the conservative months and treat good months as
acceleration.

STEP 4: GUARDRAILS: List the conditions under which I should pause
this plan and call my accountant: cash reserves dropping below a
stated floor, a variable rate moving, revenue falling more than
[X%] below plan. End with the first three actions this week, each
with a deadline, starting with confirming any UNSURE terms with
the lenders.

RULES: Show arithmetic for every dollar figure. Never advise
borrowing new money to pay old money. If keeping cash on hand
looks safer than accelerating paydown (thin reserves, seasonal
revenue), say so plainly even though I asked for a paydown plan.
Close by restating that my accountant should review this before I
change any payments.
```

## How to use it

1. Gather the real numbers first: log into each lender account and pull the current balance, rate, and minimum. Statements from three months ago will skew the ranking.
2. Fill in one block per debt, including the awkward ones like the supplier account you've been stretching.
3. Answer the follow-ups about guarantees and prepayment terms; call the lender if you don't know. Those two answers move rankings more than the rates do.
4. Check the full arithmetic shown for the first debt. If the method holds there, the rest of the projection is trustworthy.
5. Take the plan to your accountant before changing any payments, and put the three first-week actions in your calendar.
6. Re-run the prompt quarterly, or whenever a rate changes, with fresh balances.

## Example

Input: an 11-person catering company in London, Ontario with four debts: a $38,000 line of credit at 9.2% variable (personally guaranteed, backstops payroll in slow months), a $52,000 equipment loan at 6.8% fixed with a prepayment penalty marked "unsure", a $14,600 business credit card at 19.99%, and an $18,000 interest-free government-backed loan. Extra capacity: $2,200/month, seasonal.

Sample output excerpt:

DEBT AUDIT: Credit card: $14,600 at 19.99% costs you roughly $2,919/year at this balance ($14,600 x 0.1999). Line of credit: $38,000 at 9.2% costs roughly $3,496/year, variable and personally guaranteed, and it is your payroll backstop. Before ranking, I need the equipment loan's prepayment terms; a penalty there could flip positions two and three.

RANKING WITH REASONING: 1) Credit card first: highest rate by far, no operational role. 2) Line of credit second despite the equipment loan being cheaper to hold, for two reasons: the rate is variable so its cost can rise without warning, and the personal guarantee puts your house behind it. 3) Equipment loan. 4) The interest-free loan stays at minimums; paying it early saves $0 in interest...

THE PLAN: $2,200/month extra clears the credit card in month 7 (arithmetic shown in full), then $2,200 plus the card's freed $350 minimum rolls to the line of credit...

## Pro tip

Rerun the plan with one variable changed: "same debts, but my extra payment is $1,200 instead of $2,200." Seeing that the difference is nine months and about $3,000 in interest, or that it barely matters, tells you whether squeezing the budget harder is worth it, and that's a judgment call the ranking alone can't make for you.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/debt-paydown-planner). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
