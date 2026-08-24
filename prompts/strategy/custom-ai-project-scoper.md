# Custom AI Project Scoper

> A one-page project brief that makes custom-AI quotes comparable

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

The moment a small business decides to build something custom, it meets the quoting problem: three consultants, three wildly different prices, and no way to compare them because nobody wrote down what "it" is. Vague briefs produce padded quotes, scope creep, and projects that ship a demo instead of a tool. This prompt turns "we want AI for our quotes" into a one-page brief specific enough that quotes come back comparable, and honest enough to reveal when you don't need a custom build at all.

## The prompt

```
You are a technical project scoper for a small business considering a
custom AI build. Your job is to interview me, then produce a brief a
developer or consultant could quote from without a discovery call.
You are not selling the build; if the answers point to an off-the-shelf
route, say so in the brief's first line.

THE IDEA: [WHAT YOU WANT BUILT, IN YOUR OWN WORDS, HOWEVER VAGUE]

MY BUSINESS: [WHAT YOU DO, TEAM SIZE, THE SYSTEMS THIS WOULD TOUCH:
CRM, BOOKING, ACCOUNTING, INBOX]

INTERVIEW ME, one batch of questions, covering:
1. THE TRIGGER: what happens today, step by step, that this replaces?
   Who does it, how often, how long does it take?
2. THE BOUNDARY: what must stay human? (approvals, money, anything
   customer-facing that could embarrass us)
3. THE DATA: where does the information live, how messy is it, and
   who is allowed to see it?
4. DONE LOOKS LIKE: the single measurable change that makes this a
   win in month three.
5. FAILURE TOLERANCE: what happens when it's wrong? Annoying, costly,
   or dangerous?

THEN WRITE THE ONE-PAGE BRIEF:
- Problem statement in two sentences, with today's cost in hours
- In scope / out of scope, as two short lists
- Systems and data touched, with access notes
- Success metric and the month-three target
- Human checkpoints (where a person approves before anything sends)
- Open questions a vendor must answer in their quote
- A build-vs-buy note: the closest off-the-shelf route and what it
  would NOT cover, so the custom premium is explicit

RULES: If my answers show the job is a prompt plus a template, say
that instead of writing a build brief. Do not include a price estimate;
briefs that guess prices anchor quotes. Keep it to one page; a longer
brief means the scope is not decided yet, and say which part isn't.
```

The upstream question, which process deserves automation first, is what the [Automation Opportunity Audit](/toolbox/automation-opportunity-audit) answers; the decision this brief feeds is walked through in [build vs. buy for small-business AI](/blog/build-vs-buy-ai-small-business). If the brief's first line says "off-the-shelf," score that purchase with the [Software Buying Scorecard](/toolbox/software-buying-scorecard) before signing up.

## How to use it

1. Copy the full prompt into Claude or ChatGPT and describe the idea as roughly as you like; the interview does the sharpening.
2. Answer the boundary and failure-tolerance questions with a real bad day in mind, not the demo day.
3. Send the same finished brief to every vendor you approach, unchanged. Comparable inputs are the whole point.
4. Treat the "open questions" list as your interview script for vendor calls.
5. When quotes return, compare them against the brief's scope lists; anything quoted outside them is scope creep arriving early.

## Example

A 14-person property manager wants "AI to handle maintenance requests." The interview surfaces that the real job is narrower: classify incoming tenant emails, draft the work order, and route urgent ones to a phone alert, with a human approving every message that goes back to a tenant. The brief marks payment disputes out of scope, names the property software and inbox as the systems touched, sets "average time from tenant email to dispatched work order under 2 hours" as the month-three metric, and notes the closest off-the-shelf route (their property software's ticketing add-on) covers classification but not the drafting. Three quotes come back within 30% of each other, and the vendor who ignored the human-approval checkpoint is easy to eliminate.

## Pro tip

Write the failure-tolerance answer before talking to any vendor, and put it in the brief verbatim. It is the single line that most changes an honest quote: a system allowed to be wrong sometimes costs a fraction of one that never may, and vendors can only price that difference if you state it.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/custom-ai-project-scoper). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
