# Scheduled Tasks Copilot

> A small roster of scheduled AI tasks that earn their slots, reviewed monthly so the noise gets retired

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

The [Scheduled Task Builder](/toolbox/scheduled-task-builder) writes one good task. Then you write a second, a third, and by week six there are five notifications a morning, two of them overlapping, one watching a competitor who closed, and you swipe them all away unread. Scheduled tasks rot faster than any other automation because nothing breaks when they stop being useful. They keep arriving. Meanwhile your plan caps how many you can run (three on ChatGPT Free and Go, five on Plus, ten on Business), so every stale task is holding a slot a useful one could have. This skill keeps the roster.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill scheduled-tasks-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/scheduled-tasks-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: your plan, your slot limit, and every task currently scheduled.
4. When a task reports, tell the skill in one line what it delivered and whether you acted on it.
5. Monthly, ask for the review and carry out its keep, tighten and kill list the same day.

## Example

A renovation contractor on ChatGPT Plus has five tasks running and wants a sixth for permit-office notices. The skill shows the roster: the Monday competitor check has had one hit in seven runs, and the daily "material price watch" overlaps with a weekly supplier-newsletter summary. It recommends merging the two price tasks into one weekly run with a 5% change threshold, which frees a slot for the permit watch, and rewrites the merged prompt with a nothing-to-report line. At the monthly review the ranking is plain: the weather-window task for exterior jobs was acted on nine times out of twenty, the competitor check once. The competitor check goes from weekly to monthly, and the freed attention goes to the task that changes the schedule board.

## Pro tip

Log the misses. A task that reports "nothing this week" is doing its job, and a task you keep ignoring is not, and only the log can tell the two apart. If you are still choosing your first tasks, start with [ChatGPT scheduled tasks: 12 ideas for a small business](/blog/chatgpt-scheduled-tasks-ideas-small-business), and if the chore you want to schedule needs your own numbers every time, the [Ops Automation Planner](/toolbox/ops-automation-planner) will tell you whether it belongs in a real integration instead.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/scheduled-tasks-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
