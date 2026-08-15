# Product Launch Plan Builder

> A launch sequence with dates, owners, and a day-one checklist

**Category:** Marketing & Content · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business launches are one announcement post followed by silence, because the plan lived in the owner's head and the owner got busy. A launch that works is a sequence: things happen in order, on dates, done by named people. This builds that sequence backwards from launch day, checks the goal against your actual audience size, and refuses to leave any task without an owner.

## The prompt

```
You are a launch planner who has shipped products for small teams where
the founder is also the marketer, the support desk, and half of
fulfilment. You plan backwards from launch day, you assign every task
to a named person, and you treat "the team will handle it" as an
unassigned task.

THE PRODUCT: [WHAT'S LAUNCHING, THE PRICE, AND WHO IT'S FOR]
LAUNCH DATE: [THE DATE, OR "HELP ME PICK ONE"]
THE TEAM: [EVERY PERSON WHO CAN DO LAUNCH WORK, BY NAME, WITH THE
HOURS PER WEEK THEY CAN GIVE]
CHANNELS I HAVE: [EMAIL LIST SIZE, SOCIAL ACCOUNTS WITH FOLLOWER
COUNTS, PARTNERSHIPS, PAID BUDGET IF ANY]
GOAL: [A NUMBER: SALES, SIGNUPS, OR BOOKINGS IN THE FIRST 30 DAYS]

STEP 1: REALITY CHECK: Interrogate the plan before building it. Is the
goal plausible given my channel sizes? Show the arithmetic: list size
times a realistic conversion range, plus what each other channel might
add. Is the date far enough out for the asset list, given the hours
available? If either fails, say what to cut or when to move the date.
Ask me up to 4 questions about anything unclear.

STEP 2: BACKWARDS TIMELINE: Build a dated schedule from launch day
backwards in 3 phases: RUNWAY (2-4 weeks out: sales page, email
sequence, assets, partner outreach), WARM-UP (the final 7 days:
teasers, waitlist, final checks), LAUNCH DAY AND WEEK ONE. Every line
has a date, an owner from my named team, and the finished thing it
produces. Flag any week where one person carries more hours than they
gave.

STEP 3: DAY-ONE CHECKLIST: A morning-of checklist in run order: what
to publish, at what time, who verifies payment and links, what to
monitor, and the fallback if something breaks (page down, checkout
error, zero sales by noon). Each item must be checkable in under a
minute.

STEP 4: WEEK-ONE FOLLOW-THROUGH: The 5 tasks that keep momentum after
day one: the follow-up email, the objection post, the social proof
share, the non-buyer ask, and the numbers review, each with a date
and an owner. End with the single metric to check daily against the
goal.

RULES: No task without an owner and a date. Owners are names I gave
you, not roles. If the math doesn't work, show it and make me change
the goal, the date, or the channels. Keep the whole plan executable
by the team I described, not the team a bigger company would have.
```

## How to use it

1. Count your channels honestly before you start: open your email platform and social accounts and write down the real numbers.
2. List your team by name with the hours each person can commit. If it's only you, say so; the plan will shrink to fit.
3. Run the prompt and sit with the reality check. If the arithmetic says your list supports 15 sales and your goal was 50, fix the goal or add a channel now, not in week three.
4. Move the timeline into whatever you use to run your week: calendar, task board, or a printed sheet on the wall.
5. On launch morning, run the day-one checklist top to bottom before you post anything.
6. The Friday before launch, paste your current status back into the same chat and ask it to re-plan the final week around whatever slipped.

## Example

Input: a two-person Calgary meal-prep company launching a corporate lunch subscription at $89/week, launch in four weeks, email list of 1,400, Instagram at 3,200 followers, goal of 25 subscriptions in 30 days.

Sample output excerpt:

REALITY CHECK: 1,400 emails at a 1-2% launch conversion is 14 to 28 subscriptions, so 25 is at the optimistic end of plausible from email alone. Instagram at 3,200 might add 2-5. Recommendation: keep the goal, but add the partner channel you mentioned (two downtown gyms) with a concrete ask, or set 18 as the honest base case.

BACKWARDS TIMELINE (excerpt): Oct 14 (Sara): sales page copy final, checkout tested with a real card. Oct 16 (Dev): 4-email launch sequence loaded and scheduled. Oct 21 (Sara): teaser 1 posted, waitlist link in bio.

DAY-ONE CHECKLIST (excerpt): 7:00 send launch email (Dev). 7:05 confirm checkout works from the email link on a phone (Sara). 12:00 if under 3 orders, send the FAQ story addressing price per meal (Sara).

## Pro tip

Write the launch-day email before anything else in the runway phase, even though it sends last. Every teaser, post, and partner ask gets easier to write once the final pitch exists, and if you can't write that email convincingly, you've found a product problem while there's still time to fix it.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/product-launch-plan). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
