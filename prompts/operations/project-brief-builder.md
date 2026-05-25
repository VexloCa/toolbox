# Project Brief Builder

> Scope any project before kickoff: goals, risks, owners

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Projects that start without a real brief drift. Scope creeps, nobody agreed on what "done" looks like, and three weeks in someone asks a question that should have been settled on day one. Writing a proper brief from scratch feels like overhead when you just want to get moving. This interviews you about the project idea and turns a loose idea into a one-page brief everyone can align on before a single task gets assigned.

## The prompt

```
You are a project management consultant who writes tight, one-page project
briefs that prevent scope creep before it starts. Before drafting, interview
me about the project.

STEP 1: ASK ME about the project idea below: what problem it solves, who
it's for, what "success" looks like in concrete terms, what's explicitly out
of scope, who needs to be involved, and what could realistically go wrong.
Ask no more than 6 questions in one message and wait for my answers.

PROJECT IDEA (rough description to start from): [DESCRIBE THE PROJECT IN A
FEW SENTENCES]

STEP 2: ONCE I ANSWER, produce a one-page brief with these sections:

1. OBJECTIVE: One or two sentences, what this project achieves and why it
   matters right now.
2. SUCCESS METRICS: 2-4 measurable outcomes, each with a number or a clear
   yes/no test. Reject vague metrics like "improve customer experience"
   unless I give you a way to measure it.
3. SCOPE: Two lists, IN SCOPE and OUT OF SCOPE. Be explicit; the out-of-
   scope list is what prevents future arguments.
4. STAKEHOLDERS: Table with columns Name | Role in Project | Decision
   Authority (who can actually say yes/no on changes).
5. RISKS: 3-5 risks, each with likelihood (low/med/high), impact
   (low/med/high), and a one-line mitigation.
6. MILESTONE PLAN: 3-6 milestones with target dates and the single
   deliverable that marks each one done. No task-level detail, this is
   milestones, not a full project plan.

RULES: Never fill a gap with a plausible-sounding guess, if my answers
leave something unclear, mark it "TBD, confirm with [likely stakeholder]"
rather than inventing it. Keep the whole brief to one page equivalent
(roughly 400-500 words).
```

## How to use it

1. Describe the project idea in a few loose sentences. It doesn't need to be polished, that's what the interview is for.
2. Answer the AI's clarifying questions specifically, especially on what's out of scope and who has real decision authority.
3. Review the RISKS section with a skeptical eye. Add any risk you know about that the AI couldn't have guessed from your answers.
4. Circulate the finished brief to stakeholders before kickoff and get explicit agreement on scope and success metrics, not just a skim-and-nod.
5. Keep the brief as the reference document. When scope questions come up mid-project, point back to it instead of re-litigating.

## Example

Input: project idea = "we want to build a self-serve FAQ page so support stops answering the same 10 questions."

Sample interaction: AI asks "Who is this for (new customers, existing customers, or both? What counts as success), fewer tickets, faster resolution, something else? What's explicitly not included (live chat, multi-language)? Who owns the content? What's the target launch window?". Owner answers each.

Sample output excerpt:

OBJECTIVE: Launch a self-serve FAQ page that resolves the 10 most common support questions without a ticket, reducing repetitive ticket volume within one quarter.

SUCCESS METRICS: Reduce tickets tagged "general question" by 30% within 60 days of launch. FAQ page live and linked from the support widget by [date].

SCOPE, IN: FAQ content for top 10 questions, searchable page, link from support widget. OUT: live chat integration, multi-language versions, video content.

RISKS: Content goes stale as product changes (med likelihood, med impact): mitigation: assign quarterly review owner.

## Pro tip

Push back on your own "success metrics" answer if it's vague. A brief with a fuzzy definition of done is the single biggest cause of projects that never quite finish, no matter how good the plan around it is.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/project-brief-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
