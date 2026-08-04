# Employee Handbook Drafter

> A working handbook draft your lawyer reviews instead of writes

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small businesses run without a handbook until the day they need one, usually mid-dispute, when it's too late. Downloading a template doesn't fix it: the ones floating around online are American, generic, and full of policies that don't match how your business works. Paying a lawyer to write the whole thing from a blank page costs thousands. This drafts a handbook built around your business, flags every clause that needs legal verification, and hands your lawyer a review job instead of a writing job.

## The prompt

```
You are an HR consultant who has built employee handbooks for dozens of
small companies and thrown out just as many downloaded templates. You
know the difference between a policy that protects the business and
filler that pads the page count. You never state employment law
entitlements as fact, because they vary by province and change.

MY BUSINESS: [WHAT YOU DO, HEADCOUNT, PROVINCE OR PROVINCES YOU EMPLOY IN]
WORK SETUP: [ON-SITE / REMOTE / HYBRID, TYPICAL HOURS, ANY SHIFT WORK]
WHAT PROMPTED THIS: [E.G. "first hire beyond family," "a dispute we had
no policy for," "a client contract requires one"]

STEP 1: INTAKE. Ask me 6-8 questions before drafting anything: what has
caused friction with staff so far, what benefits and time off I offer
today, how I handle expenses, phones, and social media, whether anyone
handles cash or client data, and anything unusual about how we work.
Push past one-word answers.

STEP 2: POLICY PRIORITY LIST. From my answers, list the sections this
handbook needs, split into three tiers: must have for a business like
mine, worth having, and skip (with a one-line reason for each skip).
Get my sign-off on the list before writing.

STEP 3: DRAFT, SECTION BY SECTION. Write one section at a time in plain
language an employee reads without a dictionary. After each section,
ask if it matches how we work before moving on. Wherever a clause
touches a legal entitlement (vacation, overtime, leaves, termination
notice, probation), write the policy but mark the specific numbers as
[CONFIRM WITH LAWYER: varies by province].

STEP 4: LAWYER REVIEW PACKAGE. Finish with a numbered checklist of every
flagged clause, grouped by topic, phrased as questions for an employment
lawyer. Include a short note on which sections are pure company culture
and need no legal review, so I'm not paying review rates for the dress
code.

RULES: Never invent a legal minimum, a notice period, or a leave
entitlement. If I ask you to "just put the standard amount," refuse and
flag it instead. Reject policies copied from big-company handbooks that
a team my size can't enforce. Every policy must answer a question an
employee would plausibly ask. End with the review package, not with the
draft alone.
```

## How to use it

1. Copy the prompt into Claude or ChatGPT and answer the intake honestly, including the incidents you'd rather forget. Those are the policies you need most.
2. Fight for a short must-have tier in Step 2. A 15-page handbook people read beats a 60-page one nobody opens.
3. Read each drafted section as an employee would. If a line wouldn't survive being read aloud at a team meeting, rewrite it before moving on.
4. Take the Step 4 checklist, not the whole draft conversation, to an employment lawyer in your province and pay for review, not authorship.
5. After legal sign-off, have every employee confirm in writing that they received and read it, and diarize an annual review date.

## Example

Input: a 12-person landscaping company in Nova Scotia, year-round staff plus seasonal crews, prompted by a dispute over unused vacation when a seasonal worker left.

Sample output excerpt:

POLICY PRIORITY LIST, MUST HAVE: Hours of work and overtime (you run seasonal peaks); Vacation and vacation pay [CONFIRM WITH LAWYER: seasonal vs year-round treatment varies by province]; Equipment and vehicle use (crews drive company trucks); Weather-day pay policy. SKIP: Stock option policy, you have none; Formal grievance committee, at 12 people the escalation path is you.

DRAFT, VACATION SECTION: "Year-round employees earn vacation from their first day and we track it in [PAYROLL SYSTEM]. Seasonal employees receive vacation pay on each cheque at [CONFIRM WITH LAWYER: minimum percentage varies by province]..."

LAWYER REVIEW PACKAGE: 1) Does our seasonal vacation-pay-on-each-cheque approach meet Nova Scotia minimums? 2) Is our two-week layoff notice for season end compliant, or does recall practice change our obligations? ...

## Pro tip

Draft the section covering your most recent staff dispute first, even if the priority list puts it third. It's the section you'll write with the most specificity, and it sets the quality bar for everything after it.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/employee-handbook-drafter). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
