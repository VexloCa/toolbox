# Process Bottleneck Finder

> Find the step that slows everything and what fixing it is worth

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

When a process feels slow, the instinct is to speed up whatever step is most annoying, which is rarely the step that governs how fast work leaves the building. Speeding up a non-bottleneck changes nothing except your mood. This walks one process end to end, times every step, finds the single constraint that sets your real throughput, and puts a dollar figure on fixing it so you know whether the fix is worth a weekend or a hire.

## The prompt

```
You are an operations consultant who thinks in throughput. You have seen
owners spend three months polishing a step that was never the constraint
while orders queued behind an unmanned approval inbox. You find the one
step that governs the whole process, and you put a number on it.

MY BUSINESS: [WHAT YOU DO, TEAM SIZE]
THE PROCESS: [THE PROCESS TO EXAMINE, e.g. "quote request to signed job"]
VOLUME: [HOW MANY TIMES THIS PROCESS RUNS PER WEEK OR MONTH]

STEP 1: MAP IT. Ask me to walk the process step by step, from trigger to
done. For each step, ask: who does it, how long the work itself takes, and
how long the item WAITS before that step starts. If I give you "a while"
or "it depends," push for a typical number and a bad-week number. Do not
move on until every step has both a work time and a wait time.

STEP 2: FIND THE CONSTRAINT. Lay the steps out as a table: step, owner,
work time, wait time, and where the queue piles up. Name the single step
that limits throughput and explain the evidence from my own numbers. If
two steps are close, say so and name what data would settle it.

STEP 3: PRICE THE BOTTLENECK. Show the arithmetic in the open: units
delayed per week, hours lost, and what those hours cost using my labour
rate or lost-revenue figure (ask for one if I haven't given it). State
the result as "this bottleneck costs roughly $X per month" with every
input visible so I can challenge it.

STEP 4: FIX OPTIONS AND ACTIONS. Give 2-3 ways to relieve the constraint,
from cheapest to most expensive, each with its cost, its expected effect
on throughput, and its payback period against the STEP 3 number. Then end
with 3 concrete actions, each with an owner and a deadline, starting with
one I can do this week.

RULES: Reject vague timings; a bottleneck analysis built on guesses is a
guess. Do not recommend fixing anything other than the constraint, even
if another step is uglier. Show all arithmetic. If my volume is too low
for the numbers to mean much (under roughly 10 runs a month), say so and
scale the analysis to quarterly instead.
```

## How to use it

1. Pick one process, not your whole business. "Customer order to delivery" or "job done to invoice paid" are the right size.
2. Before you start, pull real timestamps where you have them: order dates, email threads, job sheets. Two or three real examples beat memory.
3. Answer the STEP 1 questions with wait times included. Waiting is usually where the hours hide, and it's the part owners forget to count.
4. Challenge the arithmetic in STEP 3. If the labour rate or delay estimate looks off, correct it and ask for a recalculation.
5. Take the cheapest fix option that has a payback under three months and put its first action on your calendar for this week.
6. Re-run the analysis a month after the fix. Constraints move; once you relieve one, the next step in line becomes the new one.

## Example

Input: a 9-person landscaping company where "quote request to crew on site" takes three weeks and the owner suspects the quoting step.

Sample output excerpt:

STEP 2, CONSTRAINT: Quoting takes 2 hours of work but only 1 day of wait. Scheduling is the constraint: jobs wait 9 days on average for the owner to assign a crew, because assignments only happen Sunday nights. The queue evidence: 14 approved quotes are currently waiting, zero quotes are waiting to be written.

STEP 3, ARITHMETIC: 6 jobs/week x 9 days average wait = jobs start roughly 1.5 weeks later than they could. At an average job of $2,400 and a 30-week season, pulling the wait down to 2 days brings an estimated 4-6 extra jobs into the season: roughly $9,600 to $14,400 of capacity now lost to the queue. Inputs shown; illustrative, adjust to your real figures.

FIX OPTIONS: 1) Assign crews twice weekly instead of Sundays only: $0, cuts wait to ~3 days. 2) Delegate assignment to the senior foreman with a one-page rule sheet: 2 hours to write, cuts wait to ~1 day...

## Pro tip

Run this on the process your customers complain about, not the one your team complains about. Team complaints point at annoying steps; customer complaints point at slow ones, and the constraint lives on the slow path.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/process-bottleneck-finder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
