# Delegation Planner

> Hand off half your task list without dropping quality

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Owners hold onto tasks for reasons that sound like standards and are mostly habit: it's faster to do it myself, the client expects me, last time someone else tried it went sideways. So the task list grows and the business stays exactly as big as one person's week. This audits your real task list, challenges every "only I can do this," and builds a handoff plan per task with training steps and quality checks, so delegation stops meaning "hope for the best."

## The prompt

```
You are an operations coach who helps owners get out of their own way. You
have heard "it's faster if I do it" a hundred times and you know it's true
for exactly one more repetition, then false forever. You challenge hoarding
politely and relentlessly, and you build handoffs that protect quality
instead of assuming it.

MY WEEKLY TASK LIST: [LIST YOUR RECURRING TASKS WITH ROUGH HOURS EACH,
MESSY IS FINE]
MY TEAM: [NAMES OR ROLES, THEIR STRENGTHS, ROUGH SPARE CAPACITY]
MY HOURLY VALUE: [WHAT AN HOUR OF YOUR TIME IS WORTH, OR YOUR RATE]

STEP 1: SORT THE LIST. Put every task into one of four buckets: KEEP
(genuinely owner-only: strategy, key relationships, firing), DELEGATE
(someone on the team can own it), SYSTEMATIZE (delegate after a checklist
or template exists), or DROP (nobody would notice). For each task I mark
as owner-only, ask me for the evidence. "The client expects me" counts
only if the client has said so. Total the weekly hours in each bucket and
multiply the DELEGATE + SYSTEMATIZE hours by my hourly value so I can see
what holding on costs per month.

STEP 2: MATCH TASKS TO PEOPLE. For each DELEGATE and SYSTEMATIZE task,
name who takes it and why they fit, using the strengths and capacity I
gave you. Flag any person who ends up overloaded and rebalance. If a task
fits nobody, say so plainly and note whether that's a hiring signal or a
DROP.

STEP 3: BUILD EACH HANDOFF. For every reassigned task: what "done well"
looks like in one sentence, what to document first (a checklist, a
template, a 10-minute screen recording), one shadow round where they
watch me, one reverse round where I watch them, and a check frequency
that starts weekly and steps down as trust builds. Note the single most
likely failure mode per task and how the person should flag it early.

STEP 4: TWO-WEEK ROLLOUT. Sequence the handoffs so weeks one and two
each move at most three tasks. End with a day-by-day plan: what gets
documented, who gets briefed, which check-ins go in the calendar, and
the date I review whether quality held.

RULES: Do not accept "only I can do this" without evidence; push back
once, then respect my final call and mark the task KEEP. Show the
hours-and-dollars arithmetic from STEP 1 in the final plan. Cap the
rollout at six tasks; a delegation plan that moves twenty tasks at once
is how quality actually drops. Every handoff ends with an owner, a start
date, and a first check-in date.
```

## How to use it

1. Write your task list from your calendar and sent folder, not from memory. The tasks you forget to list are usually the most delegable ones.
2. Give honest hours per task. Rounding everything to "an hour or two" flattens the ranking that decides what moves first.
3. When the AI challenges an "only I can do this," argue back in the chat. If your defence survives one round, keep the task; if you hear yourself reaching, it moves.
4. Create the STEP 3 documentation before the handoff conversation, not after. A checklist in hand changes that conversation from "good luck" to "here's how."
5. Put every check-in from the rollout plan in your calendar the same day. Skipped check-ins are where delegation quietly reverts.
6. After two weeks, re-run STEP 1 on what's left of your list. The second pass moves tasks you weren't ready to release the first time.

## Example

Input: the owner of a 7-person HVAC company doing 31 hours a week of recurring tasks, including quoting, scheduling, invoicing, supplier orders, and all customer callbacks.

Sample output excerpt:

STEP 1 TOTALS: KEEP 9 hrs (complex quotes, hiring, key accounts). DELEGATE 11 hrs (scheduling, supplier orders, routine callbacks). SYSTEMATIZE 8 hrs (invoicing, standard quotes: need a template first). DROP 3 hrs (weekly report nobody reads). At your stated $85/hr, the 19 delegable hours are roughly $6,460/month of owner time spent on work someone else can own. Illustrative; your rate and hours drive the real number.

STEP 3, SCHEDULING HANDOFF: done well = every job booked within 4 hours of confirmation, no crew double-booked. Document: the 12-rule booking checklist, 10-minute screen recording of one booking. Shadow Tuesday, reverse-shadow Thursday, weekly check for three weeks. Likely failure: emergency calls bumping booked jobs without telling the customer; rule: any bump triggers a customer call within the hour, flagged to you same day...

## Pro tip

Delegate the decision rules, not only the task. "Order filters when the shelf looks low" hands back every edge case; "reorder at 10 units, up to $400 without asking" hands off the judgment too, and the judgment is the part that was eating your attention.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/delegation-planner). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
