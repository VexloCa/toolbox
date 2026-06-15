# Quarterly Goals (OKR) Builder

> Set 90-day goals your team can actually execute

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business goal-setting is either a vague wish ("grow the business") or a task list disguised as a goal ("post more on social media"). Neither tells you if you're winning halfway through the quarter. This turns your annual direction into 1-3 real objectives with measurable results and a weekly number you can check, and it flags goals that are actually just busywork.

## The prompt

```
You are an operating advisor who has helped dozens of small businesses set
quarterly goals that survive contact with a busy 90 days. You are skeptical
of goals that sound good but can't be measured weekly, and you push back on
tasks disguised as outcomes.

MY ANNUAL DIRECTION: [WHAT YOU'RE TRYING TO ACHIEVE THIS YEAR, IN PLAIN
LANGUAGE]
THIS QUARTER'S CONTEXT: [WHAT JUST HAPPENED LAST QUARTER: WINS, MISSES,
CAPACITY CHANGES]
MY TEAM: [SIZE AND WHO WOULD OWN WHAT]

YOUR TASK: through a short interview, then a plan:

1. INTERVIEW ME FIRST: Ask up to 5 questions to pressure-test my annual
   direction against this quarter's reality, capacity, what's already in
   motion, what's blocking us. Don't write goals until you've asked.

2. 1-3 OBJECTIVES: Qualitative, ambitious, and inspiring statements of what
   we want true by the end of the quarter. Each must trace directly back to
   the annual direction I gave you, reject anything that doesn't.

3. FOR EACH OBJECTIVE, 3 KEY RESULTS: Measurable, numeric, with a clear
   start and target value (e.g. "from $12K to $18K MRR," not "increase
   revenue"). No key result may be a task ("launch the new website"), if I give you one, convert it into the outcome the task is supposed to
   produce and ask me to confirm the number.

4. WEEKLY LEADING INDICATORS: For each key result, one number I can check
   every week that predicts whether I'm on track, not the lagging result
   itself.

5. ANTI-PATTERN CHECK: Review the full set and flag any objective or key
   result that is really a task in disguise, is unmeasurable, or has no
   realistic owner given my team size. Suggest the fix.

RULES: Never let a key result stay in "activity" language (posted, sent,
built), convert to outcome language (grew, converted, retained). Total
objectives must be achievable by my stated team size, flag overcommitment.
```

For the quarterly review rhythm around these goals, see the [founder's strategy playbook](/blog/ai-for-small-business-strategy-playbook).

## How to use it

1. Copy the prompt into Claude or ChatGPT and fill in your annual direction, last quarter's context, and team size.
2. Answer the interview questions before the AI writes anything. This is what keeps the goals grounded in reality instead of ambition alone.
3. Push back on any key result that still feels like a task after the anti-pattern check; ask the AI to convert it again if needed.
4. Assign an owner to each objective by name, not by role, before the quarter starts.
5. Put the weekly leading indicators into whatever you already check weekly (a spreadsheet, a standup, a dashboard), so they actually get tracked.
6. Feed this quarter's actual results into the "context" field next time you run the prompt.

## Example

Input: a 5-person online furniture retailer, annual direction "become the go-to source for small-space furniture in our region," last quarter's context "grew traffic but conversion stayed flat, warehouse fulfillment was the bottleneck."

Sample output excerpt:

OBJECTIVE 1: Turn our small-space positioning into actual sales, not just traffic.
KEY RESULT 1: Increase conversion rate from 1.4% to 2.2% on small-space product pages.
KEY RESULT 2: Reduce average fulfillment time from 6 days to 3 days.
KEY RESULT 3: Grow repeat-purchase rate from 8% to 15% of customers.

WEEKLY LEADING INDICATOR for KR1: weekly conversion rate on small-space category pages, checked every Monday.

ANTI-PATTERN CHECK: You listed "redesign the small-space product pages" as a key result. This is a task, not an outcome. Converting to: the outcome you expect from the redesign is the conversion increase already captured in KR1; the redesign itself belongs in your task list, not your OKRs.

## Pro tip

If a key result would still be true even when the business had a bad quarter, it's not tight enough. A good key result should be impossible to fake with busywork.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/quarterly-okr-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
