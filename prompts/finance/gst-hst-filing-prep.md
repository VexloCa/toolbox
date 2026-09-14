# GST/HST Filing Prep

> A filing-ready GST/HST package for your accountant, built in an evening instead of a lost weekend

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Every quarter (or year, depending on your reporting period), the same scramble: what did we collect, what did we pay on inputs, which receipts count, and why does the software's number not match the spreadsheet? Most Canadian owners either lose a weekend to it or dump a shoebox on their accountant and pay for the sorting at professional rates. The job AI is genuinely good at here is the organizing and the reconciling questions; the job it must never do is decide what gets filed. This prompt draws that line and does the first half properly.

## The prompt

```
You are helping a Canadian small business owner prepare their
GST/HST filing package for their accountant. You organize,
total, and flag; you do NOT provide tax advice, decide
eligibility of input tax credits, or produce final numbers for
filing. Everything you output is marked "for accountant review."

MY BUSINESS: [WHAT YOU SELL, PROVINCE, GST OR HST REGISTERED,
REPORTING PERIOD: QUARTERLY / ANNUAL]
THE PERIOD: [START DATE TO END DATE]
MY RECORDS (paste exports as-is, messy is fine):
- SALES / INVOICES: [PASTE]
- EXPENSES / PURCHASES: [PASTE]
- WHAT MY SOFTWARE SAYS I OWE, IF IT SAYS: [NUMBER OR "N/A"]

BUILD THE PACKAGE, IN 5 PARTS:
1. COLLECTED: Total tax collected on sales for the period, with
   the line items grouped, and any invoice where tax looks
   missing, doubled, or at an unexpected rate flagged with a
   question, not a correction.
2. PAID ON INPUTS: Total tax paid on purchases, grouped by
   category, with a flag list: personal-looking expenses, meals
   and entertainment (note the special treatment exists, do not
   apply it), anything missing a receipt reference, and any
   vendor that did not charge tax where you expected it.
3. RECONCILIATION: My records' totals vs what my software says,
   with the likeliest reasons for any gap phrased as questions
   for my accountant.
4. THE ASK LIST: Every question this package raises, numbered,
   in plain language, so my accountant's hour goes to answers
   instead of sorting.
5. NEXT QUARTER CHEAPER: The 3 record-keeping habits that would
   have made this package build itself.

RULES: No netting, no final "amount owing," no advice on what to
claim; totals are labeled "draft, for review." If the records
are too thin for a section, list exactly what is missing. If I
appear to be near or past a registration or reporting threshold
worth asking about, say "ask your accountant about X" without
elaborating. Currency is CAD throughout.
```

The ask list is the money section: an accountant answering eight numbered questions bills differently than one excavating a shoebox. If the quarterly paste itself is the pain, the fix is upstream, and the [Bookkeeping Copilot](/toolbox/bookkeeping-copilot) keeps the records in a state where this package takes twenty minutes.

## How to use it

1. Copy the full prompt into Claude or ChatGPT.
2. Paste real exports, not summaries; the flags only work on line items.
3. Read the flag lists first, fix what is yours to fix (missing receipts), and leave the judgment calls in the ask list.
4. Send the whole package to your accountant before your filing deadline, with the ask list on top.
5. Adopt at least one habit from part 5; the package should get shorter every quarter.

## Example

An Ontario landscaping company on quarterly HST pastes a quarter of Wave exports. The package comes back: collected totals grouped by month with one flag (an invoice showing 5% on an Ontario job, question raised); paid-on-inputs totals with four flags (two fuel receipts missing references, one Costco run marked "looks mixed personal/business, split needed?", meals noted as special-treatment without a number applied); a $312 gap between the spreadsheet and Wave traced to two voided invoices, phrased as a question; and a seven-item ask list. The accountant's reply takes forty minutes instead of three hours, and next quarter's package inherits the "photograph fuel receipts weekly" habit.

## Pro tip

Run this two weeks before your deadline, not two days: the flag lists always surface a few missing receipts and one mystery transaction, and two weeks is the difference between fixing them calmly and filing with question marks. And keep every quarter's package in one folder; the year-end [Tax Season Prep Checklist](/toolbox/tax-season-prep-checklist) starts from those four documents instead of from zero.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/gst-hst-filing-prep). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
