# Expense Categorizer

> Clean up a messy expense export for your bookkeeper

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

A raw bank or credit card export is a wall of cryptic merchant names and no categories, and sorting it by hand before handing it to a bookkeeper eats an afternoon every month. Miscategorized or missed expenses either cost you deductions or create cleanup work later. This turns a messy expense list into a categorized table your bookkeeper can use directly, with duplicates and odd entries flagged instead of buried.

## The prompt

```
You are a bookkeeping assistant who prepares expense data for accountants.
You use standard small-business bookkeeping categories, you flag anything
uncertain instead of guessing silently, and you never quietly decide
something is a business expense when it looks personal.

MY EXPENSE DATA:
[PASTE YOUR EXPENSE LINES: date, merchant/description, amount, one per
line, in whatever format your bank or card export gives you]

MY BUSINESS TYPE: [WHAT YOU DO: helps distinguish likely business vs
personal spend]

CATEGORIES TO USE: [LIST YOUR PREFERRED CATEGORIES IF YOUR BOOKKEEPER USES
SPECIFIC ONES, OR SAY "USE STANDARD SMALL BUSINESS CATEGORIES" AND I'LL GET
A DEFAULT SET: e.g. Office Supplies, Software/Subscriptions, Travel,
Meals & Entertainment, Advertising, Professional Services, Rent/Utilities,
Equipment, Insurance, Payroll, Other]

YOUR TASK: process the full list in 3 parts:

1. CATEGORIZED TABLE: Every line item with date, merchant, amount, and
   assigned category. If a merchant name is unclear (e.g. a generic
   processor name), make your best guess and mark it "UNCERTAIN" rather
   than picking silently.

2. FLAGS: A separate list of anything that needs my attention before this
   goes to my bookkeeper, - DUPLICATES: same amount and merchant within a few days of each other
   - ANOMALIES: amounts unusually large relative to the rest of that
     category, or merchants that don't fit the stated business type
   - LIKELY PERSONAL: line items that read as personal spend (groceries,
     personal retail, entertainment unrelated to business) mixed into a
     business account, flag, don't delete or silently exclude

3. SUMMARY BY CATEGORY: Total spend per category for the period, sorted
   highest to lowest, so I can see at a glance where the money went.

RULES: Never delete or silently omit a line item, every line from my input
must appear in the output. Never assume a flagged "likely personal" item
is definitely personal, just flag it for my judgment. Do not provide tax
advice about what is or isn't deductible, categorization only. If the
data format is inconsistent or line items are missing key info (no amount,
unclear date), tell me which lines couldn't be processed cleanly instead of
guessing.

OUTPUT FORMAT: Three sections as above, categorized table first, flags
second, category summary last.
```

## How to use it

1. Export your expenses from your bank or card statement as a simple list. Copy-paste from a PDF or CSV works fine, formatting doesn't need to be perfect.
2. Paste the raw list into the prompt along with your business type and preferred category names if you have them.
3. Review the UNCERTAIN and flagged items first. These are the ones that need your judgment, not the AI's guess.
4. Resolve flagged duplicates and likely-personal items before sending the table to your bookkeeper.
5. Hand the cleaned categorized table plus the category summary to your bookkeeper instead of the raw export.
6. Run this monthly right after you pull statements so the pile never gets big enough to dread.

## Example

Input: 14 lines from a business credit card including "SQ *DARKROAST COFFEE $340.00 Jun 3", "SQ *DARKROAST COFFEE $340.00 Jun 4", "ADOBE CREATIVE CLOUD $54.99 Jun 5", "WHOLEFDS MKT #204 $187.32 Jun 7", "STAPLES #1122 $62.10 Jun 9": for a 5-person graphic design studio.

Sample output excerpt:

CATEGORIZED TABLE: Jun 3 | SQ *DARKROAST COFFEE | $340.00 | Meals & Entertainment (UNCERTAIN: high amount for a coffee vendor, verify) | Jun 5 | ADOBE CREATIVE CLOUD | $54.99 | Software/Subscriptions | Jun 9 | STAPLES #1122 | $62.10 | Office Supplies...

FLAGS: DUPLICATES, "SQ *DARKROAST COFFEE" $340.00 appears on both Jun 3 and Jun 4, same amount, one day apart (verify this isn't a double charge. LIKELY PERSONAL) "WHOLEFDS MKT #204" $187.32 reads as a grocery purchase, uncommon for a design studio's business expenses: flag for owner review.

SUMMARY BY CATEGORY: Meals & Entertainment: $340.00 | Software/Subscriptions: $54.99 | Office Supplies: $62.10 | Uncategorized/Flagged: $187.32...

## Pro tip

Paste in two or three months at once instead of one. Recurring duplicate charges and creeping subscription costs are far easier to spot across a longer window than in a single month's snapshot.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/expense-categorizer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
