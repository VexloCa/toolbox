# Scheduled Task Builder

> A recurring chore turned into a scheduled AI task that runs unattended and reports only what matters

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** ChatGPT, Claude

## The problem

ChatGPT, and now most assistants, will run a prompt for you on a schedule. Most owners try it once with "remind me to check my invoices every Monday", get a notification that says "Reminder: check your invoices", and conclude the feature is a calendar alarm with extra steps. The feature is fine. The prompt was written for a conversation, and a scheduled task is not a conversation: it runs alone, it cannot ask you what you meant, it has no memory of your last chat unless you wrote it in, and it will happily send you a wall of text every morning until you stop reading it. This prompt turns a chore you describe in one line into a task prompt built for running unattended.

## The prompt

```
You write prompts for scheduled AI tasks: prompts that an assistant
runs alone, on a timer, with nobody there to answer questions. A good
scheduled task prompt is self-contained, says exactly what to check and
where, says what to do when there is nothing to report, and produces
something a busy owner reads in under a minute.

MY BUSINESS: [WHAT YOU SELL, TO WHOM, WHERE]
THE CHORE, IN MY WORDS: [e.g. "every Monday I should look at what
competitors changed on their pricing pages"]
MY ASSISTANT AND PLAN: [e.g. ChatGPT Free / Plus / Business, Claude]
HOW OFTEN IT SHOULD RUN: [DAILY / WEEKDAYS / WEEKLY ON ___ / MONTHLY]
WHAT I WILL DO WITH THE RESULT: [THE DECISION OR ACTION IT FEEDS]

FIRST, CHECK THE FIT. Tell me plainly if this chore is a bad match for
a scheduled task, because it needs data the assistant cannot reach
(my inbox, my books, my booking system) unless I paste it or connect
it. If so, say what I would have to connect or paste, or suggest the
nearest version that works with public information and my written
context only.

THEN WRITE THE TASK PROMPT with these parts, in this order:
1. CONTEXT BLOCK: everything the task needs to know about my business,
   written into the prompt, because the task will not remember our
   chat. Keep it under 120 words.
2. THE JOB: what to check or produce, which sources or sites to use by
   name, and the time window ("since the last run" or "past 7 days").
3. THE FILTER: what counts as worth telling me. Define it with a
   threshold or an example, not an adjective.
4. NOTHING-TO-REPORT RULE: the exact one-line message to send when the
   filter catches nothing, so I learn to trust silence.
5. OUTPUT SHAPE: a headline line, then at most five bullets, each with
   the fact, the source, and the suggested action. Hard cap 150 words.
6. GUARDRAILS: never invent a figure, link, or date; say "could not
   verify" instead; never take an action on my behalf, only report.

THEN GIVE ME:
- THE SCHEDULE LINE to type when I create the task, matched to my
  plan (free plans run at most once a day in a time window; paid plans
  can run hourly at exact times).
- A ONE-RUN TEST: the same prompt reworded to run right now, so I can
  judge the output before I schedule it.
- THE KILL RULE: the sign that this task should be paused or deleted
  (for example: three runs in a row I did not act on).

RULES: Write for someone who will read the result on a phone. No
filler in the task prompt. If my chore is two chores, split it and
tell me which one deserves the slot.
```

Run the one-run test before you schedule anything. A task you would not read once is a task you will not read weekly. The twelve ideas most small businesses start with, and the limits on each ChatGPT plan, are in [ChatGPT scheduled tasks: 12 ideas for a small business](/blog/chatgpt-scheduled-tasks-ideas-small-business). When you have more than three or four tasks running, the [Scheduled Tasks Copilot](/toolbox/scheduled-tasks-copilot) keeps the roster and tells you which ones to retire.

## How to use it

1. Write the chore the way you would say it to an employee, one line, no polish.
2. Fill in your assistant and plan honestly; the schedule line depends on it.
3. Run the prompt, then run the one-run test it gives you and read the output on your phone.
4. If the output is useful, create the scheduled task by pasting the task prompt and typing the schedule line.
5. After three runs, apply the kill rule. Keep the task, tighten the filter, or delete it.

## Example

A two-location physiotherapy clinic writes: "every Monday I should check if the clinics near us changed their prices or added services". The fit check says yes, this works from public pages, and asks for the competitor names. The task prompt that comes back carries a 90-word context block (the clinic's services, its prices, its three named competitors with URLs), a job line limited to "changes on those three sites in the past 7 days", a filter of "a price change, a new service, a new location, or a new booking offer", and the nothing-to-report line "No changes at the three clinics this week." The schedule line for their Plus plan reads "every Monday at 7:30 a.m.". The one-run test surfaces that one competitor added direct billing for a second insurer. That is a Monday decision, delivered in 60 words.

## Pro tip

Spend your task slots like money, because on most plans they are scarce: three on ChatGPT Free, five on Plus. A task that watches something outside your business (competitors, a regulator, a supplier's price page, grant deadlines) usually earns its slot. A task that reminds you to do something inside your business is a calendar entry, and your calendar is free. If a chore needs your own data every time, it belongs in the [Weekly Report Automator](/toolbox/weekly-report-automator) flow, where you paste the numbers and the AI writes the read.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/scheduled-task-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
