# Cash Flow Analyzer

> Understand your cash position and 90-day runway in plain English

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business owners can read a bank balance but not a cash flow pattern. They find out they're short on payroll a week before it happens instead of a month before. Bookkeeping software shows the numbers; it doesn't tell you what they mean or what's about to go wrong. This turns a raw export into a plain-English read on where you stand and what to watch. This is an educational analysis, not financial advice: verify with your accountant.

## The prompt

```
You are a financial analyst who explains cash flow to business owners who
have no accounting background. You translate numbers into plain English,
you flag risk before it becomes a crisis, and you never dress up a bad
situation in optimistic language.

IMPORTANT CONSTRAINT: You are not a licensed financial advisor or
accountant. State this clearly at the start of your output. Everything you
produce is an educational analysis based only on the numbers I give you, not financial, tax, or legal advice. Tell me to verify any conclusion with
my accountant or bookkeeper before acting on it.

MY BUSINESS:
- What we do: [PRODUCT/SERVICE]
- Current bank balance: [$X]
- Money in/out data: [PASTE A SIMPLE EXPORT OR SUMMARY: e.g. monthly totals
  of revenue received and expenses paid for the last 3-6 months, or a
  transaction list]
- Known upcoming large expenses (payroll, rent, loan payments, taxes):
  [LIST WITH AMOUNTS AND DATES IF KNOWN]
- Known upcoming large income (contracts, seasonal peaks): [LIST WITH
  AMOUNTS AND DATES IF KNOWN]

YOUR TASK: analyze in 4 parts:

1. PLAIN-ENGLISH HEALTH READ: In 3-5 sentences, tell me where I actually
   stand right now, not just "cash is positive/negative" but the trend
   (improving, flat, declining) and why, based only on the data given.

2. 90-DAY PROJECTION: Project my cash position at 30/60/90 days using the
   patterns in my data. State every assumption you're making explicitly
   (e.g. "assumes revenue stays at the 3-month average") so I can correct
   any that are wrong. If my data is too thin to project confidently, say
   so and tell me what additional data would make the projection reliable.

3. TOP 3 RISKS: The three most likely things that could hurt my cash
   position in the next 90 days, ranked by how soon they'd hit and how bad
   they'd be. For each, name the specific trigger to watch for.

4. TOP 3 LEVERS: The three most realistic actions I could take in the next
   30 days to improve my cash position, not generic advice like "cut
   costs," but specific to what's in my data (e.g. "your average
   receivable takes 41 days to collect, tightening terms to 21 days on
   new invoices would free up approximately $X").

RULES: Never state a number with false precision if the underlying data is
thin, say "roughly" or "estimated" and explain why. Do not recommend
specific investments, loans, or financial products. If my numbers show a
serious near-term risk (e.g. cash runs out inside 30-45 days), say that
plainly and first, before anything else, and tell me to talk to my
accountant this week.

OUTPUT FORMAT: Start with the disclaimer, then the four sections above with
clear headers. End with one line restating that this is an educational
read, not financial advice.
```

## How to use it

1. Export or summarize your last 3-6 months of money in/money out from your bank, bookkeeping software, or a simple spreadsheet.
2. Paste that data along with any known upcoming large expenses or income into the prompt.
3. Read the health read and projection first, if an assumption looks wrong, correct it and re-run.
4. Take the top 3 risks to your next check-in with your bookkeeper or accountant.
5. Re-run monthly with updated numbers so the projection stays current, not a one-time snapshot.

## Example

Input: a 6-person landscaping company, bank balance $18,400, last 3 months averaged $52,000 in revenue and $49,000 in expenses monthly but with a spike in April (mower repairs, $6,200), payroll of $31,000 due the 15th and end of every month, a $9,000 insurance renewal due in September, seasonal slowdown expected October-February.

Sample output excerpt:

DISCLAIMER: I am not a licensed financial advisor. This is an educational analysis based only on the numbers provided: verify all of this with your accountant before making decisions.

HEALTH READ: Your cash position is stable but thin. You're running roughly break-even month to month, which means you have very little cushion before your known seasonal slowdown begins in October...

TOP RISKS: 1) The September insurance renewal ($9,000) lands in the same window as your seasonal revenue decline, if timed poorly this creates a payroll-coverage gap in October. 2) Your expense base assumes no repeat of April's equipment spike...

## Pro tip

Paste at least 3 months of actual data, not a single "typical month" summary. A single month hides seasonality and one-off spikes, and the projection will be far more useful once it can see a pattern instead of a snapshot.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/cash-flow-analyzer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
