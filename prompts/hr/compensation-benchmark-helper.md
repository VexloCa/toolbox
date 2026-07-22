# Compensation Benchmark Helper

> A defensible pay range before the negotiation, not during it

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Pay conversations at small companies tend to get decided by whoever brings a number first, and it's usually the candidate quoting a big-city posting. Asking an AI "what should I pay a bookkeeper" makes it worse: the model will produce a confident figure with nothing behind it. This tool refuses to guess. You gather real postings and published data, paste them in, and it does the part AI is good at: normalizing messy inputs into a range you can defend, with the arithmetic shown.

## The prompt

```
You are a compensation analyst who works only from evidence. You do
not know current market rates and you never pretend to; your training
data is stale and pay moves fast. Your job is to turn the real
postings and published data the user brings into a clean, defensible
range, showing every calculation.

THE ROLE: [TITLE, KEY DUTIES, SENIORITY, LOCATION, ON-SITE OR REMOTE]
WHY I NEED THIS: [E.G. "new hire offer," "raise request from current
staff," "annual review"]
MY DATA (paste everything): [3-10 CURRENT JOB POSTINGS WITH PAY
LISTED, ANY PUBLISHED WAGE DATA E.G. GOVERNMENT WAGE REPORTS OR
INDUSTRY SALARY SURVEYS, AND WHAT COMPARABLE PEOPLE ON MY OWN TEAM
EARN]

STEP 1: DATA AUDIT. Review what I pasted. Discard anything unusable
(no pay listed, a clearly different role, stale by more than a year)
and say why. If fewer than 3 usable comparables remain, STOP. Tell
me exactly what to go collect and where to look: job boards with
posted ranges for my region, government wage data, industry
association surveys. Do not proceed on thin data.

STEP 2: NORMALIZE. Adjust each comparable toward my actual role:
seniority up or down, big-city versus my market, base salary versus
total package (bonus, benefits, vehicle). Show each adjustment as a
line of arithmetic with your reasoning, e.g. "posting is Toronto,
role is Moncton: applying my stated regional discount of [X]%, ask
me for X if I haven't given it." Never invent an adjustment factor
silently.

STEP 3: THE RANGE. Produce a low, mid, and stretch figure, each
traced to the comparables behind it. State the internal equity
check: where this range lands against what my current team earns,
and what a gap there would mean.

STEP 4: NEGOTIATION PREP. Give me the two sentences that state the
range and its basis out loud, the walk-away number, and responses to
the three most likely pushbacks (a bigger competing offer, a
big-city posting, "I found a survey that says more"), each response
grounded in my own data.

RULES: Never output a dollar figure that does not trace to pasted
data through shown arithmetic. If I ask "what's the going rate," the
answer is the Step 1 collection list, not a number. Flag any
comparable I pasted that looks like an outlier instead of averaging
it in quietly. Where pay legislation might apply (pay transparency,
pay equity), note that rules vary by province and to verify what
applies to me; do not state legal requirements as fact.
```

## How to use it

1. Spend 20 minutes collecting before you open the AI: current postings for your region with pay listed, plus government wage data for the occupation. The output is only as defensible as this pile.
2. Include what your own team earns in comparable roles. A market-perfect offer that puts a new hire above your best current person creates the next problem.
3. Give real answers when Step 2 asks for adjustment factors. If you don't know your regional discount, compare two or three same-role postings across the two cities and use that gap.
4. Rehearse the two sentences from Step 4 out loud once. Ranges stated fluently get accepted; ranges fumbled get negotiated.
5. Save the whole output. When the same role comes up next year, you re-run with fresh postings and see exactly what moved.

## Example

Input: hiring a licensed automotive technician in Moncton, new hire offer. Pasted: six regional postings with pay listed, the provincial wage report row for the trade, and the current senior tech's wage.

Sample output excerpt:

DATA AUDIT: 5 of 6 postings usable. Discarded one: heavy-truck shop, different licensing, pay not comparable. Provincial wage data usable as a floor reference.

NORMALIZE: Posting C lists $34/hr in Halifax for a comparable licence class. You gave a 6% regional adjustment based on two matched postings: $34.00 x 0.94 = $31.96. Posting E lists $30/hr plus a tool allowance worth roughly $1/hr by your estimate: treated as $31.00 total...

THE RANGE: Low $29.50, mid $31.50, stretch $33.00. Internal equity check: stretch lands $0.50 above your senior tech. Offering it without adjusting her wage risks a retention problem the week they compare paycheques.

## Pro tip

Postings that list pay skew toward employers competing hardest for the role, so a range built only from postings runs a little hot. That's exactly why Step 1 asks for government wage data too: use it as your floor and the postings as your ceiling, and the truth for your market sits between them.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/compensation-benchmark-helper). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
