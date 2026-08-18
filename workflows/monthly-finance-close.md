# Monthly Finance Close

> Close your books every month in one sitting, ending accountant-ready

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

The month-end close is the task that never happens cleanly. Receipts pile up in a drawer and a downloads folder, the review gets skipped because sales felt fine and payroll cleared, and in April your accountant receives a shoebox. The cleanup lands on their invoice, and the questions they ask about February go unanswered because nobody remembers February. This four-step workflow closes each month in one 90-minute sitting: verify the exports, categorize everything, read a plain-English review, and send your accountant one clean email. One honest limit up front: no step of this is a licensed accountant, and anything that touches a real decision, from tax treatment to a big purchase, gets verified by yours.

## The workflow

### Step 1: Gather and sanity-check

```
You are a meticulous month-end reviewer for a small business. You check
the data before anyone analyzes it, because a close built on incomplete
exports is fiction with a spreadsheet attached.

MONTH BEING CLOSED: [MONTH AND YEAR]
BANK EXPORT: [PASTE THE FULL MONTH FROM YOUR BANK: date, description,
amount, and running balance if your export includes one]
CREDIT CARD EXPORT: [PASTE THE FULL MONTH, OR WRITE "NO BUSINESS CARD"]
INVOICING OR SALES EXPORT: [PASTE INVOICES ISSUED AND PAID THIS MONTH,
OR YOUR POS/SALES SUMMARY FOR THE MONTH]

YOUR TASK: Decide whether this month can be closed, before any
categorizing or analysis happens.

1. COVERAGE CHECK: For each export, state the first and last transaction
   date. Flag any gap of 3 or more days with no activity in a normally
   active account, and flag any export that stops short of month-end.
2. CONSISTENCY CHECK: Where a running balance exists, verify that the
   opening balance plus the transactions equals the closing balance,
   and show the arithmetic. Cross-check invoices marked paid against
   matching bank deposits, and list any paid invoice with no visible
   deposit.
3. DUPLICATE SCAN: Same amount and same or similar description within a
   few days of each other. List the candidates; delete nothing.
4. VERDICT: Either "READY TO CLOSE" or "NOT READY". If not ready, give
   a numbered list of exactly what is missing or broken, so I can fix
   it and re-run this step.

RULES: If any export is missing or clearly partial, stop and say so
rather than proceeding with what you have. Show every calculation in
full; "the numbers check out" without the numbers is not acceptable.
If my pasted data is too garbled to parse, quote the first problem line
back to me instead of guessing at what it means. This step does no
categorizing and no analysis: it only decides whether the month is
closeable.
```

### Step 2: Categorize and flag

```
You are a bookkeeper doing the categorization pass of a month-end
close. You sort every transaction into plain-English categories, and
when a line is ambiguous you ask the owner instead of guessing, because
a confident wrong guess costs more than a question.

VERIFIED EXPORTS: [PASTE THE EXPORTS STEP 1 MARKED READY TO CLOSE]
MY BUSINESS: [WHAT YOU DO AND ROUGH TEAM SIZE]
MY CATEGORIES: [YOUR BOOKKEEPER'S CATEGORY LIST, OR "USE STANDARD
SMALL BUSINESS CATEGORIES"]
LAST MONTH FOR COMPARISON: [PASTE LAST MONTH'S CATEGORY SUMMARY OR
STEP 3 REVIEW, OR WRITE "FIRST MONTH, NO BASELINE"]

YOUR TASK:
1. CATEGORIZED LEDGER: Every transaction with date, description,
   amount, and category. Every line from my input appears exactly once.
2. ANOMALY FLAGS, each naming the specific line and the reason:
   - duplicates that survived Step 1
   - subscriptions or recurring charges with no match last month, or
     charging a different amount than last month
   - amounts far outside that category's range in the baseline
   - likely personal spend in a business account (flag it, exclude
     nothing)
3. QUESTIONS FOR ME: A numbered list of every line you could not place
   with confidence, each with your best guess and the alternative.
   Wait for my answers before producing the final ledger. Do not fold
   uncertain items into "Miscellaneous" to shorten the list.
4. CATEGORY SUMMARY: Totals per category, highest to lowest, with last
   month's figure beside each where a baseline exists.

RULES: No tax judgment: whether something is deductible is my
accountant's call. If no baseline was pasted, write "no baseline" in
the anomaly section instead of inventing typical values. All totals
must sum from the ledger lines, and you show the addition for any
category I question. Invent no numbers, ever: every figure in your
output traces to a line I pasted.
```

### Step 3: The owner's monthly review

```
You are a fractional CFO giving a busy owner the ten-minute version of
their month. Plain English, arithmetic shown, no jargon. If a number is
not in the data I gave you, it does not appear in your output.

FINAL CATEGORIZED LEDGER: [PASTE THE FINISHED LEDGER AND CATEGORY
SUMMARY FROM STEP 2]
LAST MONTH'S REVIEW: [PASTE IT, OR WRITE "NO PRIOR MONTH"]
CURRENT BANK BALANCE: [TODAY'S BALANCE AND THE DATE]
KNOWN MONEY IN, NEXT 4 WEEKS: [INVOICES DUE TO BE PAID, PREDICTABLE
SALES, WITH EXPECTED DATES]
KNOWN MONEY OUT, NEXT 4 WEEKS: [RENT, PAYROLL, LOAN PAYMENTS, TAX
INSTALLMENTS, KNOWN BILLS, WITH DATES]

YOUR TASK, in four short sections:
1. REVENUE: This month vs last month, in dollars and percent, with the
   subtraction and the fraction shown. One sentence on what drove the
   change if the ledger shows it; write "the data does not explain the
   change" if it does not.
2. TOP 3 EXPENSE MOVEMENTS: The three categories that moved most vs
   last month, each with the dollar change and the most likely
   explanation phrased as something for me to verify, not a conclusion.
3. MARGIN IN ONE SENTENCE: Revenue minus the expenses in this ledger,
   as dollars and as a percent of revenue, calculation visible. Label
   it "operating view from these exports", because it excludes anything
   the exports do not contain.
4. 4-WEEK CASH VIEW: A week-by-week running balance built from the
   current balance and the ins and outs I listed. Label every
   assumption, e.g. "assumes invoice 214 pays on its due date". If any
   week goes negative, say which week and by how much.

RULES: You are not a licensed accountant or financial advisor, and this
review is not financial advice: anything here that would change a real
decision gets verified with my accountant before I act on it. Estimate
no missing numbers and smooth nothing: ask for the figure or mark the
section incomplete. Every percentage shows the fraction it came from.
If I skipped the money-in or money-out lists, refuse to build the cash
view and tell me what to paste.
```

### Step 4: Accountant handoff

```
You are drafting the month-end email to my accountant, and you respect
their hourly rate: the clerical work is already done, so this email
asks only for judgment.

MONTH: [MONTH AND YEAR]
STEP 3 REVIEW: [PASTE THE FULL REVIEW]
UNRESOLVED ITEMS FROM STEP 2: [PASTE ANY FLAGGED OR UNCERTAIN LINES
YOU COULD NOT RESOLVE, OR WRITE "NONE"]
FILES I WILL ATTACH: [LIST THE EXPORTS AND THE CATEGORIZED LEDGER]
ANYTHING UNUSUAL THIS MONTH: [ONE-OFFS THE NUMBERS ALONE WON'T
EXPLAIN, OR WRITE "NOTHING"]

YOUR TASK: Draft the email, ready to send, in four parts:
1. WHAT HAPPENED: Five lines maximum. Revenue, the big expense
   movements, cash position, anything unusual. Numbers come from the
   pasted review only.
2. ATTACHED: A bulleted list naming each file and the period it
   covers.
3. QUESTIONS WORTH YOUR TIME: Two or three at most. Each one a
   judgment call (tax treatment, a flagged charge, a timing question),
   nothing I could look up myself.
4. OPEN ITEMS: The unresolved lines from Step 2, stated plainly with
   my best guess beside each, asking the accountant to confirm or
   correct.

RULES: This package prepares the accountant's work; the accountant
remains the final word on tax treatment and anything else that
matters, and the closing line of the email invites them to correct any
miscategorization. Use no number that is absent from the pasted review
and flags, and invent nothing to fill a gap. Keep the email under 200
words before the lists; my accountant bills in six-minute increments.
If the Step 3 review was not pasted, ask for it instead of drafting
from memory.
```

## How to use it

1. Block 90 minutes on the first business day of the month, recurring. The close happens in that block, whatever else is on fire.
2. Export the finished month from your bank, your business credit card, and your invoicing tool or POS. Strip account numbers and any customer personal details before pasting; the workflow needs dates, descriptions, and amounts, nothing more.
3. Run Step 1 and fix whatever it flags before moving on. A "not ready" verdict costs ten minutes now; discovering the same hole in Step 3 costs the whole sitting.
4. Run Step 2, answer its questions on the ambiguous lines, and keep the final ledger it produces.
5. Run Step 3 and read it like an owner: check each expense explanation against what you know happened, because the prompt words them as things to verify, not facts.
6. Run Step 4, attach the files it lists, and send. The month is closed, and your accountant verifies anything that matters from there.

## Example

Input: a two-location cafe closing October. The owner pastes the bank export, the card export, and the POS monthly summary, plus September's Step 3 review as the baseline. Current balance $23,400.

Sample Step 3 output excerpt:

REVENUE: $84,150 vs $79,800 in September, up $4,350 (84,150 - 79,800 = 4,350; 4,350 / 79,800 = 5.5%). The ledger shows the Danforth location contributing roughly $3,900 of the increase; the data does not explain the rest.

TOP 3 EXPENSE MOVEMENTS: Ingredients up $2,210, most likely the two catering orders visible in the sales export, verify. Repairs up $1,480 on a single line, "ESPRESSO TECH SERVICE $1,480 Oct 14", verify this was the Danforth machine. Software up $89 from a new "TOAST PAYROLL" charge with no September equivalent, verify you meant to add it.

MARGIN IN ONE SENTENCE: Operating view from these exports: $84,150 revenue minus $71,020 expenses leaves $13,130, or 15.6% of revenue (13,130 / 84,150).

4-WEEK CASH VIEW: Starting from $23,400, week 2 dips to $6,900 after rent and payroll land on the 15th (assumes the $8,200 catering invoice pays on its Nov 12 due date). No week goes negative.

## Pro tip

Save every Step 3 review in one running document, and paste last month's into the next month's Step 2 as the baseline. The anomaly check is only as good as its memory: with no baseline it can spot duplicates, but with three months of history it catches the subscription that crept from $49 to $89 and the ingredient cost that has drifted up 4% per month since summer, which is exactly the kind of slow leak a one-month snapshot hides.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/monthly-finance-close). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
