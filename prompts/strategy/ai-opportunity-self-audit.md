# AI Opportunity Self-Audit

> A ranked map of where AI pays first in your business, before you buy anything

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

"We should be using AI" is a feeling; an audit is a map. Most owners have the feeling, skip the map, and start wherever a vendor demo pointed, which is how businesses end up with AI in the one place it mattered least. The [Automation Opportunity Audit](/toolbox/automation-opportunity-audit) ranks your processes for automation; this one asks the wider question: across everything your business does (selling, serving, admin, deciding), where does AI create real value first, and where would it be a mistake? This prompt runs the honest self-serve version of that assessment.

## The prompt

```
You are an AI-adoption auditor for small businesses. You are
paid to be skeptical: your job is to find where AI genuinely
pays in THIS business, rank it, and say plainly where AI is the
wrong answer. No tool names in the diagnosis; jobs first.

MY BUSINESS: [WHAT YOU SELL, TO WHOM, TEAM SIZE, REVENUE BAND
IF COMFORTABLE]
MY WEEK, HONESTLY: [THE 6-10 ACTIVITIES THAT EAT THE HOURS,
WITH ROUGH HOURS EACH: QUOTES, EMAIL, BOOKKEEPING, SCHEDULING,
CONTENT, DRIVING, WHATEVER IS TRUE]
CUSTOMER-FACING PAIN: [WHERE CUSTOMERS WAIT, COMPLAIN, OR
CHURN]
WHAT WE ALREADY USE: [ANY AI OR AUTOMATION IN PLACE, INCLUDING
"NOTHING"]
BIGGEST CONSTRAINT: [TIME / MONEY / SKILLS / TRUST]

AUDIT IN 4 PARTS:
1. THE MAP: Every activity I listed, scored 1-5 on two axes:
   how much an AI assistant helps today, and how risky it is to
   hand over (customer trust, money, legal exposure). Show it
   as a ranked table, best first.
2. THE TOP 3: For each: the specific job AI takes, what stays
   human, the time or money it plausibly returns per month
   (conservative, shown as a range with the assumption stated),
   and the first 60-minute step.
3. THE DO-NOT LIST: The 2-3 places in my business where AI
   would be a mistake right now, with the reason. This list is
   as important as the top 3.
4. THE 30-DAY SEQUENCE: The order to do it in, one thing per
   week, nothing overlapping, ending with a check: did the top
   pick return what part 2 estimated?

RULES: Conservative estimates only; if my hours are vague, ask
before scoring. Never recommend a paid tool where the assistant
I already have covers the job. If my answers show the real
bottleneck is not AI-shaped (pricing, hiring, one giant
client), name it in one honest paragraph before the map.
```

The do-not list is what separates an audit from a sales pitch, and it is the part to read first. This prompt is the self-serve version of the assessment we run as a service: the [Vexlo AI Opportunity Audit](/audit) does the same mapping against your real numbers and workflows, with a human on the other end and a report your team can execute from.

## How to use it

1. Copy the full prompt into Claude or ChatGPT and list your week honestly, boring parts included; the boring parts usually win.
2. Answer any hour-clarifying questions with real numbers, not wishes.
3. Read the do-not list first, then the top 3.
4. Put the 30-day sequence in your calendar and run week one this week; the [AI Pilot Designer](/toolbox/ai-pilot-designer) turns any pick that needs new software into a proper trial.
5. On day 30, check the estimate against reality before starting week five.

## Example

A two-person bookkeeping-and-payroll practice lists its week: client data entry (9h), email back-and-forth chasing documents (6h), payroll runs (4h), proposals (2h), a stalled blog (1h). The map ranks document-chasing email first (high help, low risk), data entry second (high help, medium risk, review required), and puts payroll runs on the do-not list: high stakes, compliance-shaped, and the 4 hours are mostly verification a machine should not absorb. The honest paragraph flags that the stalled blog is not an AI problem, it is a priorities problem, and the 30-day sequence starts with templated chase emails that save 4 of the 6 hours by week two.

## Pro tip

Rerun this every six months with your updated week, and keep the old outputs. The gap between audits is your actual AI adoption curve, in your own numbers, and it is the most convincing document you will ever show a skeptical business partner. When the map says the opportunity is real but the execution needs more than prompts, that is the moment the [professional audit](/audit) earns its fee.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-opportunity-self-audit). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
