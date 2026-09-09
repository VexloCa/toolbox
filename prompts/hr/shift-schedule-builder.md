# Shift Schedule Builder

> Next week's schedule built in ten minutes, with the conflicts caught before they call in

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

For most shops, restaurants, and clinics, the weekly schedule is an hour of squinting at a spreadsheet on Sunday night: who asked for what off, who closed last night and cannot open today, who is creeping into overtime, and which shift still needs someone who can run the register alone. Scheduling software wants a subscription and a setup weekend for what is, most weeks, a constraint puzzle. This prompt solves the puzzle: paste your people and your rules, get a draft schedule with every conflict named instead of buried.

## The prompt

```
You are a scheduling assistant for a small business. You build a
one-week staff schedule that satisfies hard rules first, then
preferences, and you list every conflict you could not solve
instead of quietly breaking a rule.

THE WEEK: [START DATE] to [END DATE]
SHIFTS TO COVER: [E.G. MON-FRI OPEN 7-3 AND CLOSE 3-9, SAT 8-6;
STAFF NEEDED PER SHIFT AND ANY ROLE THAT MUST BE PRESENT, LIKE
"ONE KEYHOLDER PER SHIFT"]
MY PEOPLE: [FOR EACH: NAME, ROLE(S), MAX HOURS/WEEK, AVAILABILITY
AND TIME-OFF REQUESTS, ANYTHING ELSE ("NO CLOSE-THEN-OPEN",
"SCHOOL UNTIL 3", "PREFERS WEEKENDS")]
HARD RULES: [E.G. NO CLOPENING FOR ANYONE, MINORS OFF BY 10PM,
OVERTIME NEEDS MY APPROVAL, MINIMUM TWO PEOPLE AT CLOSE]
FAIRNESS NOTES: [WHO GOT STUCK WITH WHAT RECENTLY, IF ANYTHING]

BUILD, IN ORDER:
1. THE SCHEDULE: A day-by-day table, name and role per shift,
   weekly hours totaled per person.
2. CONFLICTS: Every rule or request you could not satisfy, who it
   affects, and the least-bad trade you suggest. Never silently
   drop a time-off request.
3. RISK LIST: Single points of failure this week (the one day
   only one keyholder works, the person at 39.5 hours), so I know
   where a callout hurts.
4. THE ASKS: Draft messages for anything needing a person's
   agreement ("can you take Thursday close?"), one line each.

RULES: Hard rules are never broken, only flagged. Respect max
hours. Spread the unpopular shifts across weeks using my fairness
notes. If staffing cannot cover the shifts I listed, say so
plainly and show the gap instead of thinning every shift.
```

The risk list is the section owners skip and regret: the schedule that works on paper and dies on the first callout was a risk-list problem, not a scheduling problem. If the same conflicts show up week after week, that is a hiring or hours conversation, and the [Tough Conversation Scripts](/toolbox/tough-conversation-scripts) help with the version of it you keep postponing.

## How to use it

1. Copy the full prompt into Claude or ChatGPT.
2. Keep a note with your people, roles, and standing rules; paste it in and change only what is new this week.
3. Read CONFLICTS before the schedule itself; that is where the judgment calls live.
4. Send THE ASKS before posting the schedule, so agreements come before commitments.
5. Post the schedule wherever your team looks, and keep the risk list for yourself.

## Example

A cafe with nine staff pastes the week: two on until close, one keyholder per shift, two time-off requests, one student unavailable before 3pm, no clopening. The draft covers every shift, totals hours per person, and the conflicts section flags exactly one problem: Saturday close needs a keyholder, and both keyholders asked for Saturday off. It proposes the least-bad trade (the keyholder who had last Saturday off takes this one, and gets first claim on the next long weekend), with the ask drafted in one line. The owner sends the ask, gets a yes, posts the schedule, and Sunday night took eleven minutes.

## Pro tip

Keep last week's fairness notes in the prompt every week ("Dana took both closes last week"), because fairness is the part spreadsheets cannot see and staff never forget. When the weekly paste itself becomes the chore, the standing version of this job is the [Shift Scheduler Copilot](/toolbox/shift-scheduler-copilot) skill: it remembers the roster, the rules, and who got stuck with what, so each week starts from memory instead of a paste.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/shift-schedule-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
