# 30-60-90 Onboarding Builder

> Give every new hire a ramp-up plan on day one

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

New hires at small businesses usually get a laptop, a login, and a vague "shadow Dave for a bit". Then everyone's surprised when it takes three months to become productive. Without a real plan, ramp-up speed depends entirely on how much attention a busy manager happens to have that week. This builds a structured 30-60-90 day plan so every new hire knows what they're learning, who they need to meet, and what "on track" looks like from day one.

## The prompt

```
You are an onboarding specialist who designs ramp-up plans for small
teams without dedicated HR or L&D staff. Your plans are specific enough
that a manager could hand them to a new hire with zero extra explanation.

THE NEW HIRE:
- Role and title: [ROLE]
- Reports to: [MANAGER]
- Team size and structure: [WHO ELSE IS ON THE TEAM / ADJACENT TEAMS]
- Their top 3 responsibilities: [FROM THE JOB DESCRIPTION]
- What "fully ramped" looks like at 90 days: [CONCRETE, OBSERVABLE
  OUTCOME]
- Tools/systems they'll need to learn: [LIST: e.g. CRM, ticketing
  system, internal docs]
- Key people they should meet in the first month and why: [NAMES/ROLES +
  1-LINE REASON EACH, OR SAY "SUGGEST BASED ON ROLE" IF UNSURE]

YOUR TASK: build a complete 30-60-90 day plan with these sections:

1. DAY ONE CHECKLIST: the first-day logistics and first tasks (max 8
   items), nothing that requires deep context yet.

2. FIRST 30 DAYS, LEARN: 
   - Learning goals (what they need to understand about the business,
     product, and their role)
   - Relationship map: who to meet, in what order, and the one question
     they should ask each person
   - One early win they can realistically deliver by day 30 that builds
     confidence without requiring full context

3. DAYS 31-60, CONTRIBUTE:
   - What real work they should be doing independently by now
   - What still needs sign-off vs. what they can own outright
   - A mid-point check-in question list for their manager to ask

4. DAYS 61-90, OWN:
   - What full ownership of their role looks like, tied back to the
     90-day success outcome I gave you
   - A final check-in question list for the manager to assess readiness

5. MANAGER CHECK-IN CADENCE: a simple schedule (e.g. daily days 1-5,
   weekly after) with the specific question to open each check-in.

RULES:
- Every task or goal must be specific enough to check off, no "get
  familiar with the team" without a concrete way to know it happened.
- The early win in days 1-30 must not depend on skills or context they
  couldn't reasonably have yet.
- Check-in questions must be open-ended enough to surface real problems,
  not just "how's it going?"
- If I didn't give you enough detail to build a specific relationship map
  or tool list, say so and ask before inventing names or systems.
- Keep the plan realistic for a small team, don't assume dedicated
  training staff or a formal LMS unless I said so.

OUTPUT FORMAT: the four time-period sections above, each as a short table
or bulleted list, followed by the check-in cadence as a simple schedule.
```

## How to use it

1. Fill in the role details and the 90-day success outcome before anything else. The whole plan is built backward from that outcome.
2. List real names for the relationship map where you can; let the AI suggest roles where you're unsure who's relevant.
3. Hand the finished Day One checklist and Learn section to the new hire on their first day, not after they've already asked what to do.
4. Give the manager check-in questions to the manager directly. These are the questions that catch a struggling hire early, not just status updates.
5. Use the days 31-60 and 61-90 sections as a light performance-conversation script at each milestone, not just a checklist.
6. Reuse and lightly adjust the plan for the next hire in the same role instead of rebuilding it from scratch.

## Example

Input: New Customer Support Rep, reports to Support Lead, 4-person support team, top responsibilities: answer inbound tickets, manage the shared inbox, escalate technical issues. 90-day success: handling 80% of tier-1 tickets independently with under 4-hour response time. Tools: Zendesk, internal knowledge base, Slack.

Sample output excerpt:

FIRST 30 DAYS: LEARN
Learning goals: understand the top 10 most common ticket types and where to find answers in the knowledge base; learn Zendesk tagging and escalation workflow.
Relationship map: Support Lead (day 1, "what does a great ticket response look like here?"); a senior support rep (week 1, "what do you wish you'd known in your first month?"); Product lead (week 2, "what are customers most often confused about right now?").
Early win by day 30: independently close 10 straightforward tier-1 tickets with Support Lead spot-checking, not pre-approving.

## Pro tip

Build the plan around the 90-day success outcome first, then work backward. Plans built forward from "what should they learn" tend to drift into busywork that doesn't actually build toward independent ownership.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/onboarding-plan-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
