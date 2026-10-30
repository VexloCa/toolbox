# Equipment Buy vs Lease

> A side-by-side of buying, financing, leasing and renting a piece of equipment over its working life, in cash out the door by month, with the questions your accountant needs to settle the tax side

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** ChatGPT, Claude

## The problem

The dealer has a lease at $1,180 a month and a purchase price of $62,000, and the salesperson is good at making the lease sound like the obvious choice. Your accountant will tell you about the tax treatment, next month, when you call. What you need this afternoon is the plain arithmetic: what each option costs over the years you'll use the thing, what it does to your cash each month, what you own at the end, and what happens if the work dries up in year two. This prompt does the arithmetic and writes the questions for the accountant, so the tax conversation takes ten minutes.

## The prompt

```
You compare the ways a small business can get a piece of equipment:
buy with cash, buy with a loan, lease, or rent as needed. You do the
cash arithmetic. You don't do the tax calculation; you write the
questions the owner takes to their accountant.

THE EQUIPMENT: [WHAT IT IS, NEW OR USED, AND WHAT IT DOES FOR THE
BUSINESS]
HOW LONG I'LL USE IT: [YEARS, AND HOW MANY HOURS OR JOBS A MONTH]
PURCHASE PRICE: [$, TAXES EXTRA OR INCLUDED]
LOAN OFFER, IF ANY: [DOWN PAYMENT, RATE, TERM, MONTHLY PAYMENT]
LEASE OFFER, IF ANY: [MONTHLY, TERM, DOWN PAYMENT, END-OF-LEASE
BUYOUT OR RETURN TERMS, WHO PAYS MAINTENANCE AND INSURANCE]
RENTAL OPTION, IF ANY: [DAILY OR WEEKLY RATE, HOW OFTEN I'D NEED IT]
WHAT IT'S WORTH USED AT THE END: [MY GUESS, OR "DON'T KNOW"]
MY CASH POSITION: [HOW MUCH I CAN PUT DOWN WITHOUT HURTING OPERATIONS]
WHAT IT EARNS OR SAVES: [REVENUE PER MONTH IT MAKES POSSIBLE, OR THE
RENTAL OR SUBCONTRACT COST IT REPLACES]

GIVE ME:
1. TOTAL CASH OUT over the years I'll use it, for each option: price,
   interest, lease payments, buyout, maintenance and insurance where
   I've said who pays. Subtract the resale value where I own it at the
   end. Show the working.
2. MONTHLY CASH by option for the first 24 months, side by side.
3. THE BREAK-EVEN: how many hours or jobs a month the equipment has to
   do before it beats renting or subcontracting.
4. THE EXIT: for each option, what happens if I stop needing it in
   year two. What I owe, what I can sell, what I'm stuck with.
5. THE ACCOUNTANT'S QUESTIONS: five questions about the tax treatment
   of each option in Canada (capital cost allowance, lease deductions,
   HST input credits, whether the lease would be treated as a purchase)
   written so the accountant can answer each in a sentence. Don't
   answer them yourself.
6. A RECOMMENDATION in three sentences, based on the cash numbers and
   my cash position, with the one assumption that would change it.

RULES: Use only the numbers I gave. Where I wrote "don't know", say
what the comparison looks like at a low and a high value. Don't quote
tax rates or rules as fact.
```

Fill in the resale value honestly or leave it as "don't know" and read both cases. The resale guess decides the buy-versus-lease answer more often than the interest rate does. If the purchase needs a loan, the [Loan Application Prep](/toolbox/loan-application-prep) builds the package, and the [Break-Even Analyzer](/toolbox/break-even-analyzer) tells you what the equipment has to earn once it's in the yard.

## How to use it

1. Get the real offers in writing: the dealer's lease sheet, the bank's loan terms, a rental quote.
2. Fill in the prompt with those numbers and an honest guess at usage and resale.
3. Run it and read the 24-month cash line first; that's the one that puts businesses in trouble.
4. Send the five questions to your accountant before you sign anything.
5. Re-run it with the accountant's answers if they change the picture.

## Example

A tree service in Kelowna is choosing between buying a $62,000 chipper, a 48-month lease at $1,180 with a $9,000 buyout, and renting at $450 a day for the 6 to 8 days a month it would use one. Over five years the arithmetic shows renting costs the most if usage holds at 7 days a month, the lease and the loan land within a few thousand of each other, and the loan wins once the resale value is above $20,000. The 24-month cash line shows the lease is easier in year one, when the business has two other payments ending. The exit section is the surprise: if work drops in year two, the lease leaves the owner paying for 30 more months on a machine it can't sell. The accountant's five questions go out that afternoon; the answer about input tax credits comes back the same day.

## Pro tip

Ask the dealer for the lease's implied interest rate and the buyout terms in writing before you run the numbers. A lease that looks cheap by the month is often expensive by the rate, and the buyout is where the real price hides. And whichever option wins on paper, don't sign the one that leaves you with less than two months of operating cash in the bank.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/equipment-buy-vs-lease). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
