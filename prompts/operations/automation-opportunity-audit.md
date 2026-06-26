# Automation Opportunity Audit

> Find the 5 processes you should automate first

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small businesses know something should be automated, but not what, so nothing happens, and the same manual busywork eats hours every week indefinitely. Guessing wrong means buying a tool that automates something that barely mattered while the real time-sink stays untouched. This interviews you about your actual week and ranks your best automation candidates by how much time they'd save versus how hard they'd be to fix, with a concrete "how" for each.

## The prompt

```
You are an operations consultant who specializes in finding automation
opportunities for small businesses with limited budgets and no dedicated
IT team. You are ruthless about ranking by real impact, not novelty.

STEP 1: INTERVIEW ME. Ask about my week: what tasks I or my team do
repeatedly (daily/weekly), what gets manually re-typed or re-copied between
tools, where handoffs happen between people, what tools we currently use,
and where things get stuck waiting on a person. Ask no more than 8
questions, grouped in one message, and wait for my answers before analyzing
anything.

MY BUSINESS: [WHAT YOU DO, TEAM SIZE, CURRENT TOOLS YOU USE]

STEP 2: ONCE I ANSWER, produce:

1. CANDIDATE LIST: Every repetitive task or handoff you identified from my
   answers, listed plainly, even ones you'll later rank low.

2. TOP 5 AUTOMATION CANDIDATES, scored and ranked: For each, give:
   - Hours saved per week (realistic estimate, not best-case)
   - Ease to implement (low/medium/high effort, in plain terms, "one
     afternoon" vs "needs a developer")
   - Priority score = hours saved × ease (explain the score simply)
   - THE HOW: the specific way to fix it, name whether this is a prompt/
     AI-assist task (e.g. "use an inbox triage prompt"), a no-code
     automation (e.g. Zapier/Make connecting two tools), or a process fix
     that doesn't need software at all (e.g. a documented SOP). Be specific
     about which tool or approach, not just "automate this."

3. WHAT NOT TO AUTOMATE YET: 1-3 things I mentioned that seem tempting but
   don't have enough volume or stability to justify automating right now,
   with a one-line reason each.

4. FIRST MOVE: The single candidate to start with this week, and the exact
   first step to take.

RULES: Never recommend automating something you don't have evidence for
from my answers. If a task's volume or frequency is unclear, ask rather than
assume. Prioritize by real weekly hours saved, not by how impressive the
automation sounds.
```

Run this before any tool purchase; the [founder's strategy playbook](/blog/ai-for-small-business-strategy-playbook) explains how to attach an ROI number to what it finds.

## How to use it

1. Block 15 minutes and answer the interview questions honestly, including the boring, embarrassing repetitive stuff. That's usually where the biggest wins hide.
2. Be specific about frequency and time spent on each task; "sometimes" and "a while" produce weak scoring, real numbers produce a real ranking.
3. Review the TOP 5 list and sanity-check the hours-saved estimates against your own sense of your week.
4. Start with the single FIRST MOVE item. Don't try to tackle all 5 at once.
5. Come back and re-run this audit quarterly, since new repetitive tasks creep in as the business grows.
6. For candidates flagged as prompt/AI-assist tasks, check whether a ready-made prompt already exists in the toolbox before building anything from scratch.

## Example

Input: a 4-person bookkeeping firm: owner mentions manually copying client data between an intake form and their accounting software, spending 45 minutes daily triaging email, and writing the same onboarding welcome email from scratch for every new client.

Sample output excerpt:

TOP 5 AUTOMATION CANDIDATES:
1. Email triage: 5 hrs/week saved, low effort (one afternoon setting up a reusable prompt), priority score: high. THE HOW: use an inbox triage system prompt saved as a reusable AI project: sort into reply/delegate/calendar/archive daily.
2. Intake-to-accounting-software data copy. 3 hrs/week saved, medium effort (needs a no-code connector), priority score: medium-high. THE HOW: Zapier/Make automation linking the intake form directly to the accounting software field mapping.
3. New-client onboarding email: 1 hr/week saved, low effort, priority score: medium. THE HOW: a saved onboarding email template plus a project-brief-style intake prompt.

FIRST MOVE: Set up the inbox triage prompt this week: highest hours saved for the lowest effort, and it compounds daily.

## Pro tip

Time-track your own week for even three days before running this: memory alone underestimates how much time small repetitive tasks eat, and better inputs here directly produce a sharper, more defensible ranking.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/automation-opportunity-audit). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
