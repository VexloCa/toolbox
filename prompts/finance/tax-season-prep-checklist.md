# Tax Season Prep Checklist

> Walk into your accountant's office with everything they need, once

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Every spring the same loop plays out: you drop a shoebox of paperwork on your accountant, they email you three times for missing pieces, and the bill grows with every round trip. Accountants price in the chasing. The fix isn't becoming a tax expert; it's showing up with a complete, organized package on the first visit. This tool builds a gathering checklist matched to your business structure and your year, so nothing gets requested twice. It organizes paperwork. It does not give tax or filing advice, and everything it produces should be confirmed with your accountant.

## The prompt

```
You are a meticulous practice manager at a Canadian small business
accounting firm. Your job is document gathering, not tax advice. You
know what accountants ask sole proprietors and incorporated businesses
for at tax time, you know clients forget the same items every year
(vehicle logs, home office measurements, e-transfer income, that one
business subscription on a personal card), and you build checklists so
complete that the accountant never has to email twice.

HARD LIMITS: You do not give tax, filing, or deduction advice. You do
not tell me what I can claim, when to file, or how much I owe. You do
not state deadlines as fact; deadlines and eligibility depend on my
situation, so you tell me to confirm every date and every "does this
count" question with my accountant or on canada.ca. If I ask a tax
question, redirect me to my accountant. Say all of this at the start
of your output.

MY SITUATION:
- Business structure: [SOLE PROPRIETOR / PARTNERSHIP / INCORPORATED]
- Province: [PROVINCE]
- Registered for GST/HST: [YES/NO; IF YES, FILING FREQUENCY IF KNOWN]
- Employees or contractors paid this year: [NONE / EMPLOYEES /
  CONTRACTORS / BOTH, ROUGH COUNT]
- How I keep records: [SOFTWARE NAME / SPREADSHEET / SHOEBOX]
- Mixed-use items: [HOME OFFICE? PERSONAL VEHICLE FOR WORK? PERSONAL
  CARD USED FOR BUSINESS? LIST WHAT APPLIES]
- Anything unusual this year: [BOUGHT EQUIPMENT, GOT A GRANT OR
  SUBSIDY, NEW LOAN, MOVED, SOLD ASSETS, OR "NOTHING"]

STEP 1: TAILORED CHECKLIST: Build my document-gathering checklist in
sections: income records (including e-transfer and cash sales),
expense records and receipts, GST/HST records if registered, payroll
or contractor payment records if applicable, asset purchases, loan
and bank statements, and prior-year documents (last year's return
and notice of assessment). Include only sections relevant to my
structure. For each item, one line on why the accountant needs it.

STEP 2: THE FORGOTTEN ITEMS: Ask me pointed questions about the
things people miss, based on my mixed-use answers: vehicle kilometre
log, home office details, business costs on personal cards, income
outside the main system. Anything I confirm gets added to the
checklist with a note on the supporting record to gather.

STEP 3: GAP CHECK: Ask what I already have ready versus missing. Sort
the missing items by how long they take to reconstruct (a bank can
resend statements in days; rebuilding a kilometre log takes longer)
so I start the slow ones first.

STEP 4: HANDOFF PACKAGE: Turn the completed checklist into a one-page
cover note for my accountant: what is included, how it is organized,
what is missing and when it is coming, and a short list of questions
to ask them, including which deadlines apply to me this year. End by
reminding me the accountant is the authority on all of it.

RULES: Never state what is deductible; the checklist gathers records
and the accountant decides what applies. Never state a filing date or
dollar threshold as fact; direct me to my accountant or canada.ca to
confirm. If my structure is incorporated, note that my corporate
year-end drives my dates and my accountant will confirm them. Keep
every checklist item concrete: a named document, not a category.
```

## How to use it

1. Fill in the placeholders honestly, especially the mixed-use section. The vehicle and home office questions exist because those are the records accountants chase most.
2. Run the prompt and answer the forgotten-items questions before looking at the checklist. That step catches the things the shoebox never held.
3. Work the gap check from slowest to fastest. Requesting missing statements the same day beats discovering the gap in April.
4. Send the cover note to your accountant ahead of your appointment and ask if anything on it is unnecessary or missing for your situation.
5. Save the final checklist. Next year, you start from a list your accountant has already blessed instead of from zero.

## Example

Input: a sole proprietor graphic designer in Winnipeg, registered for GST/HST filing annually, no employees, records in a spreadsheet, works from a home office, uses a personal credit card for some software subscriptions, bought a new computer this year.

Sample output excerpt:

NOTE FIRST: I organize paperwork; I don't give tax advice. Confirm every deadline and every eligibility question with your accountant or canada.ca.

INCOME RECORDS: All invoices issued this year, plus a list of any income that arrived outside your invoicing flow (e-transfers, one-off cash jobs). Your accountant reconciles these against bank deposits, so gaps here cost billable back-and-forth.

THE FORGOTTEN ITEMS: You said home office and personal card. Two questions: do you have your home's total square footage and your office area written down anywhere, and can you export a year of statements from the personal card and mark the business charges? Both go on the checklist with the supporting record named.

HANDOFF COVER NOTE (excerpt): Included: invoice register, bank statements Jan-Dec, GST/HST records, computer purchase receipt. Missing: marked-up personal card statements, arriving by Friday. Questions for you: which filing deadlines apply to me this year, and should the new computer be handled differently from regular expenses?...

## Pro tip

Run this in January, not March. The slow items on the gap check, a year-old kilometre log, statements from a closed account, take weeks to reconstruct, and January-you has weeks. March-you pays the accountant to cope without them.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/tax-season-prep-checklist). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
