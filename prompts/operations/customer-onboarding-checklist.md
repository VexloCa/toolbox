# Client Onboarding Checklist Builder

> New clients hit their first win without you chasing anyone

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

The first month with a new client is when they decide whether you were the right call, and most small firms run it from memory: a welcome email if someone remembers, a kickoff that gets booked late, requests for documents that arrive in four separate messages. Each client gets a slightly different experience and the owner is the one chasing all of it. This builds a day-by-day onboarding checklist around one concrete milestone, the client's first win, with an owner for every step so nothing depends on anyone's memory.

## The prompt

```
You are a client onboarding specialist for small service businesses. You
have watched good firms lose clients in week two, not because the work was
bad but because the client sat in silence wondering if anything was
happening. You design onboarding around one thing: the fastest honest path
to the client's first visible win.

MY BUSINESS: [WHAT YOU DO, TEAM SIZE]
WHAT A NEW CLIENT BUYS: [THE SERVICE OR PACKAGE]
HOW ONBOARDING WORKS TODAY: [DESCRIBE THE CURRENT MESS HONESTLY, EVEN IF
IT'S "I WING IT"]

STEP 1: DEFINE THE FIRST WIN. Ask me what a new client should be able to
see, hold, or use that proves the engagement is working, and by what day.
Reject vague answers like "they feel taken care of." A first win is
observable: a report delivered, a system live, a first batch shipped. Ask
what typically delays it today.

STEP 2: MAP THE PATH. Working backward from the first win, list every
step from "contract signed" to "first win delivered" as a day-numbered
checklist (Day 0, Day 1, Day 3...). For each step: the action, the owner
(me, a named team role, or the client), what they need to do it, and
what "done" looks like. Client-owned steps get a due date plus a polite
nudge date.

STEP 3: WRITE THE TOUCHPOINTS. Draft the three messages that carry the
checklist: a welcome email sent within 24 hours (what happens next, what
we need from them, one date), a kickoff agenda under 30 minutes, and a
"we're on track" note for the midpoint. Plain language, no filler.

STEP 4: FAILURE POINTS. List the 3 most likely places this checklist
stalls (client goes quiet, missing access, scope drift) and give me a
scripted response for each, including exactly when to escalate from nudge
to phone call.

RULES: Every step must have one named owner; "the team" is not an owner.
If a step has no clear done-condition, rewrite it until it does. Keep the
total checklist under 20 steps; if it's longer, the service is doing too
much before the first win and you should say so. End with the one change
to make before the next client signs.
```

## How to use it

1. Describe your current onboarding honestly, including the parts that only exist in your head. The gaps are the point.
2. Push back on the first-win definition until it's something the client could screenshot. "Feeling confident" fails that test; "first month's books closed" passes.
3. Fill in real names or roles for every owner in the STEP 2 checklist. Unowned steps are the ones that stall.
4. Save the three STEP 3 messages as templates in your email client so sending them takes seconds, not composition time.
5. Run the checklist on your very next client and note where reality disagreed with the plan.
6. Feed those notes back in and regenerate. The second version is usually the one that sticks.

## Example

Input: a 5-person bookkeeping firm onboarding monthly-bookkeeping clients, where getting bank access from the client routinely drags for two weeks.

Sample output excerpt:

FIRST WIN: previous month's books closed and a one-page summary in the client's hands by Day 14.

CHECKLIST (excerpt): Day 0, owner: you, send welcome email with access request list, done when sent. Day 1, owner: client, grant read-only bank feed access, due Day 3, nudge Day 4. Day 5, owner: junior bookkeeper, confirm feeds reconcile, done when trial run matches statements. Day 10, owner: you, draft first monthly summary...

FAILURE POINT 1: client hasn't granted access by Day 4. Scripted nudge: "Quick one: the bank access from our welcome email is the only thing between you and your first closed month. Two minutes with this link does it." Escalate to a phone call on Day 6; a client who won't do two minutes of setup by then has a concern they haven't voiced, and that's the real conversation.

## Pro tip

Put one deliberately easy client-owned task in the first 48 hours, like confirming a logo file or picking a meeting slot. Clients who act once keep acting; the first small completed task is what makes the Day 3 access request get done on time.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/customer-onboarding-checklist). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
