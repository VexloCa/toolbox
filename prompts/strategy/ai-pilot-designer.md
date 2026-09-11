# AI Pilot Designer

> A 30-day AI pilot with success measures and kill criteria decided before anyone gets attached

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Between "we picked a tool" and "was it worth it" sits a step most small businesses skip: the pilot. The [Software Buying Scorecard](/toolbox/software-buying-scorecard) handles the choosing and the [AI ROI Reality Check](/toolbox/ai-roi-reality-check) handles the judging, but without a designed trial in the middle, the judgment has nothing to judge. Tools get rolled out to everyone at once, nobody wrote down what success looks like, and three months later the renewal auto-charges because canceling would mean admitting nobody checked. This prompt designs the 30 days that produce a verdict.

## The prompt

```
You are helping a small business owner design a 30-day pilot for
an AI tool, so the trial ends in a decision instead of a shrug.
You are skeptical by profession: pilots exist to kill bad
purchases cheaply.

THE TOOL: [WHAT IT IS AND WHAT IT COSTS PER SEAT]
MY BUSINESS: [ONE LINE: WHAT YOU DO, TEAM SIZE]
WHY I'M TRYING IT: [THE HONEST REASON: A REAL PAIN, A DEADLINE
PROMO, A COMPETITOR USES IT, THE TEAM ASKED]
CANDIDATE USERS: [WHO MIGHT GET A SEAT, AND WHAT EACH DOES ALL
DAY]
THE PAINFUL TASKS: [THE 2-4 RECURRING TASKS THIS SHOULD HELP,
WITH ROUGH TIME EACH TAKES TODAY]

DESIGN THE PILOT, IN 5 PARTS:
1. SEATS: The fewest seats that give a real signal, matched to
   the tasks. If my candidate list is everyone, cut it and say
   why. Name who is excluded from the pilot and when they would
   join.
2. ASSIGNMENTS: Two named tasks per seat, currently painful,
   with today's time cost written down as the baseline.
3. SUCCESS MEASURES: For each assignment, the observable thing
   that counts as working (time, drafts accepted, errors
   caught). Numbers where possible, honest proxies where not.
4. KILL CRITERIA: The results that end the pilot early, stated
   now while nobody is attached: nobody opens it unprompted by
   day 10, outputs need so much fixing the baseline wins, or the
   one workflow it must fit refuses to fit.
5. THE DAY-30 SCORECARD: The questions to answer per seat, the
   expand / hold / cancel decision rule, and the calendar
   entries to create today (day 10 check, day 30 verdict,
   renewal date minus one week).

RULES: If my "why" is a promo deadline rather than a named pain,
say so and design the pilot to be finishable before the deadline
or tell me to ignore the deadline. Never design a pilot longer
than 30 days or wider than 5 seats; a bigger trial is a rollout
wearing a lab coat. If the tool duplicates something I already
pay for, flag it before designing anything.
```

The kill criteria are the section that earns the paste: deciding what failure looks like before the trial starts is the only defense against the sunk-cost renewal. Pair the finished pilot with a same-day [usage policy](/toolbox/ai-usage-policy-writer) if the tool touches company data, and if the tool is Copilot specifically, the full walkthrough is in [how to roll out Microsoft Copilot](/blog/roll-out-microsoft-copilot-small-business).

## How to use it

1. Copy the full prompt into Claude or ChatGPT and answer the "why" line honestly; the design changes if the reason is a countdown banner.
2. Accept the seat cuts. The urge to include everyone is the urge that produces shrugs.
3. Create the three calendar entries the same day, including renewal-minus-one-week.
4. Tell the pilot users their assignments and baselines; a secret pilot measures nothing.
5. On day 30, run the scorecard and act on the rule you wrote, especially when the answer is cancel.

## Example

A 12-person landscaping company considers a $30-per-seat AI quoting tool because a competitor mentioned it. The prompt flags the "why" as secondhand, then designs a 2-seat pilot: the estimator (baseline: 50 minutes per quote, two quotes a day) and the office manager (baseline: 20 minutes of follow-up formatting per quote). Success is quotes under 25 minutes with no accuracy complaints; kill criteria include any pricing error reaching a customer. Day 10 shows the estimator at 22 minutes but the office manager unable to make templates match the company's format, which was a named must-fit workflow. The day-30 rule says expand only on two clean seats: verdict is hold at one seat, renegotiate, and recheck in a quarter. Total spend on the question: $60.

## Pro tip

Put the renewal-minus-one-week calendar entry in before the pilot starts, with the kill criteria pasted into the event description. Future-you, reading that reminder next to the auto-renewal email, is the person this whole prompt was written for.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-pilot-designer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
