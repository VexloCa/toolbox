# Quarterly Goals Copilot

> Goals that survive week three, because something remembers them and asks

**Category:** Strategy & Planning · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

Setting quarterly goals is a solved problem; the [Quarterly OKR Builder](/toolbox/quarterly-okr-builder) writes a tight set in an hour. Keeping them is where quarters die. The goals get written in January energy, referenced twice, and rediscovered in the week-12 panic, at which point the numbers are whatever they are. The missing piece is not better goals; it is the standing check-in nobody on a small team owns: what moved this week, what stalled, and which key result is quietly failing while everyone works hard on something else. This skill installs that owner.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill quarterly-goals-copilot`
- **Claude apps:** zip this folder and upload it in Settings under Skills (paid plans with code execution switched on). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/quarterly-goals-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, Copilot, or Claude on the free plan:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Give it the quarter's goals; if they are vague, it will push them toward measurable before accepting.
4. Pick a check-in day and honor it; five minutes weekly is the entire cost of the system.
5. At quarter's end, take the retrospective into your next planning session instead of memory.

## Example

A three-person web agency sets a Q4 with three objectives, including "reduce dependence on the anchor client" with a key result of four new retainer clients. Weeks one through five, the check-ins log proposal work. In week six the skill flags: KR at 1 of 4, trajectory needs 1 every 3 weeks, and the last two check-ins reported eleven hours on the anchor client's rush requests, which map to no objective. The owner reads the flag, declines the next rush job, and reallocates Thursday mornings to outreach. The quarter ends at 3 of 4 with the retrospective noting exactly which week the trade-off got made, and the next quarter's goals include a capacity line the last ones lacked.

## Pro tip

Answer the weekly check-in honestly on the bad weeks especially; a record with gaps where the hard weeks were produces a retrospective that blames nothing and teaches nothing. And when the unmapped-work flag fires three weeks running on the same activity, stop treating it as noise: either promote it to a real goal or kill it, because it has already voted itself into your quarter.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/quarterly-goals-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
