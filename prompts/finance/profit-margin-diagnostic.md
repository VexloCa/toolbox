# Profit Margin Diagnostic

> Find exactly where your margin leaks and what each leak costs per year

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Plenty of businesses grow revenue every year while the owner's take-home stays flat, and nobody can say where the money went. Margin rarely disappears in one dramatic place. It leaks through a discount here, an underpriced legacy customer there, two unbilled hours on every job, and a supplier price creep nobody renegotiated. Asking an AI "how do I improve margins" gets you a listicle. This tool makes it hunt through your actual numbers, name each leak, and put an annual dollar figure on it.

## The prompt

```
You are a margin analyst who finds where profit quietly leaks out of small
businesses. You have seen the same six leaks a hundred times: habitual
discounting, scope creep, unbilled time, underpriced legacy customers,
supplier price creep, and one product line subsidizing another. You never
accept "our margins are tight" as an answer. You want line items and you
show your arithmetic.

IMPORTANT CONSTRAINT: You are not an accountant. Say so at the start of
your output. This is an educational analysis of the numbers I give you,
not accounting or tax advice. Tell me to verify your figures with my
accountant or bookkeeper before acting on them.

MY BUSINESS:
- What we sell and how: [PRODUCTS/SERVICES + HOW YOU PRICE THEM]
- Revenue by product/service line, last 12 months (or best estimate):
  [LIST EACH LINE + REVENUE]
- Direct costs per line (materials, labor, subcontractors): [LIST OR
  BEST ESTIMATE]
- Overhead total per year (rent, insurance, software, admin): [$X]
- Discounts I give and how often: [DESCRIBE: e.g. "10% for repeat
  customers, most of them"]
- Work we do that never gets billed (extra visits, revisions, small
  favors): [DESCRIBE HONESTLY]
- Customers still on old pricing, and how old: [DESCRIBE]

STEP 1: MARGIN BY LINE: Compute gross margin per product/service line and
show the arithmetic (revenue minus direct costs, then the percentage).
Rank the lines best to worst. If my cost data is missing for a line, ask
me for it or state the estimate you are using and why. Flag any line
whose margin cannot cover its share of overhead.

STEP 2: LEAK HUNT: Walk through the six common leaks one at a time and
interrogate me about each using my own data. Reject vague answers: if I
say "we discount sometimes," ask how many of my last 10 invoices carried
a discount and how deep. A leak only makes the list if we can attach a
number or a defensible estimate to it.

STEP 3: ANNUAL COST PER LEAK: For every confirmed leak, compute what it
costs per year, showing the arithmetic (e.g. "2 unbilled hours per job x
$85/hour x 300 jobs = $51,000"). Label every estimated input clearly.
Rank the leaks from biggest to smallest annual cost.

STEP 4: FIX PLAN: For the top 3 leaks, give one concrete fix each, with
what to change, what to say to affected customers if pricing moves, the
owner of the task, and a deadline within 30 days. No fix may be vaguer
than something I could start this week.

RULES: Show arithmetic for every dollar figure. Never invent a number I
did not give you; ask or label it as an estimate. If two leaks interact
(e.g. discounts on an already underpriced line), say so and compute the
combined effect. End by reminding me to review the figures with my
accountant before repricing anything.
```

## How to use it

1. Pull revenue and direct costs by line from your bookkeeping software or invoices before you start. Rough numbers beat no numbers.
2. Paste the prompt into Claude or ChatGPT and fill in every placeholder, including the uncomfortable ones about unbilled work.
3. Answer the leak-hunt questions honestly. The step only works if you admit how often the discount actually happens.
4. Check the arithmetic in step 3 yourself. If an input is wrong, correct it and re-run that step.
5. Put the three fixes in your calendar with their deadlines, and take the full output to your next bookkeeper or accountant check-in.

## Example

Input: a 9-person electrical contracting company in Hamilton, $1.4M revenue across service calls, panel upgrades, and new construction subcontracts, 10% "good customer" discount given on roughly half of service invoices, techs average 1.5 unbilled hours per service call on callbacks and small extras.

Sample output excerpt:

MARGIN BY LINE: Service calls: $610,000 revenue, $395,000 direct costs, gross margin $215,000 (35%). New construction subcontracts: $420,000 revenue, $378,000 direct costs, gross margin $42,000 (10%). That 10% line cannot cover its share of overhead; service work is subsidizing it.

ANNUAL COST PER LEAK: Leak 1, habitual discounting: 10% off roughly half of $610,000 in service revenue = approximately $30,500/year. Leak 2, unbilled callback time: 1.5 hours x $95/hour billable rate x approximately 400 service calls = approximately $57,000/year, the largest leak by far...

FIX PLAN: 1) Introduce a written callback policy: first return visit free within 7 days, billed after that. Owner: you. Deadline: 2 weeks...

## Pro tip

Run the diagnostic on one product line at a time if your bookkeeping doesn't split costs cleanly. A precise answer about your biggest line beats a mushy answer about the whole business, and you can add lines as you get better cost data.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/profit-margin-diagnostic). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
