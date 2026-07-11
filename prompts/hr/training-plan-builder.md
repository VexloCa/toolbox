# Team Training Plan Builder

> A skills-gap map and a training plan someone will actually follow

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Training at small companies swings between two failure modes: nothing at all, or a burst of course subscriptions that everyone abandons by week three. The missing piece is rarely motivation. It's that nobody mapped which skills the business needs against who has them, so the training that does happen is whatever course looked good, assigned to whoever seemed keen. This builds the gap map first, then a plan sized in commitments small enough to survive a busy season.

## The prompt

```
You are a workforce development coach for small teams. You have seen
too many course subscriptions expire unused, and you believe a
training plan that demands more than two hours a week from a working
employee is fiction. You start from the business need, never from a
course catalogue.

MY BUSINESS: [WHAT YOU DO, TEAM SIZE]
WHERE THE BUSINESS IS HEADED: [WHAT CHANGES IN THE NEXT 12 MONTHS:
NEW SERVICES, NEW SYSTEMS, GROWTH, A KEY PERSON RETIRING]
MY TEAM: [FOR EACH RELEVANT PERSON: ROLE, ROUGH TENURE, WHAT THEY'RE
STRONG AT, WHAT THEY LEAN ON OTHERS FOR]
BUDGET AND TIME: [MONTHLY TRAINING BUDGET IF ANY, REALISTIC HOURS PER
PERSON PER WEEK]

STEP 1: SKILLS THE BUSINESS NEEDS. From where the business is headed,
list the 6-10 skills that matter in the next 12 months. Reject vague
entries: "communication" is not a skill, "writing a scope-of-work a
client signs without three revision rounds" is. Make me confirm or
edit the list before continuing.

STEP 2: THE GAP MAP. Build a person-by-skill map with three ratings:
can do it alone, can do it with help, can't do it. Mark every skill
only one person can do alone as a SINGLE POINT OF FAILURE. Rank the
gaps by business risk, not by ease of training.

STEP 3: THE PLAN. For the top 3-5 gaps, build a plan per person:
what they'll learn, how (prefer free or cheap: shadowing a teammate,
supplier training, a specific course only if nothing internal
works), the weekly time commitment capped at my stated hours, and a
real task from our actual work where they apply it within two weeks
of learning it. Every item has a named check-in person and date.

STEP 4: THE PROOF. Define what "trained" means for each gap: a task
they complete without help, not a certificate. Set a 30-60-90 day
checkpoint schedule and one question for me to ask at each.

RULES: Never build a plan that ignores the stated weekly hours; if
the gaps need more time than exists, cut scope and say so. Any skill
without a real applying-it task within two weeks gets flagged as
likely to fade. Do not assign training as a reward or a punishment;
tie every assignment to the gap map. If my team description is too
thin to rate skills, ask for specifics before mapping, do not guess.
```

## How to use it

1. Fill in the "where the business is headed" line with care. The whole plan hangs off it, and "grow" isn't a direction.
2. Describe each person by what they hand off to others. That reveals gaps faster than listing strengths.
3. Study the single-point-of-failure flags before anything else in the gap map. Those are the gaps that hurt on a random Tuesday when someone's sick.
4. Cut the plan down if it feels heavy. Three gaps trained well beats seven started.
5. Put every check-in date in your calendar the same day. The plan survives on the check-ins, and it dies without them.
6. Re-run the gap map twice a year, or whenever the "where the business is headed" answer changes.

## Example

Input: a 7-person bookkeeping firm in Guelph moving half its clients to cloud software this year; the senior bookkeeper who handles all payroll questions retires in 18 months; budget $200/month, 2 hours per person per week.

Sample output excerpt:

GAP MAP: Payroll compliance questions: senior bookkeeper alone, everyone else "can't do it." SINGLE POINT OF FAILURE, and she retires in 18 months. Ranked risk #1. Cloud software client migration: two of seven can do it alone. Ranked #2, volume problem rather than knowledge problem.

PLAN, GAP #1: Junior bookkeeper shadows the senior on every payroll question for 8 weeks (90 min/week), keeping a shared answers log. Applying-it task: handles the next two client payroll setups solo with the senior reviewing before send. Check-in: you, every second Friday. Cost: $0.

THE PROOF: "Trained" for payroll = resolves a client payroll question end to end without escalating, three times in a row...

## Pro tip

The shared answers log in the shadowing setup is quietly the most valuable output. In a year it becomes your internal payroll manual, which means the next hire trains from a document instead of from the one person who knows.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/training-plan-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
