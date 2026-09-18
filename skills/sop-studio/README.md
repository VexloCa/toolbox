# SOP Studio

> Turn a 10-minute voice ramble into an SOP your team follows

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

Every important process in your business lives in somebody's head, and writing it down is the chore that loses to every other chore. When an SOP does get written, the expert writes it: expert shortcuts, expert vocabulary, steps compressed past the point a new hire can follow. The document gets opened once, the new person asks a human instead, and the next departure or sick week hurts exactly as much as the last one.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Three ways to use it:

- **Claude apps:** zip this folder and upload it in Settings under Skills (paid plans with code execution switched on). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/sop-studio/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, Copilot, or Claude on the free plan:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Answer the setup questions: business, team size, where SOPs live, who reads them.
4. Record yourself explaining one task as if training a new hire, paste the transcript, and answer the gap questions.
5. Test the checklist on your newest team member and feed their stumbles back in.

## Example

A cafe owner records herself explaining the morning opening routine while doing it, and pastes the transcript. The skill asks four questions before writing: what happens if the espresso machine pressure reads low, where the float for the till comes from, who to call if the delivery hasn't arrived by 7:30, and whether the patio gets set up in winter. Output: a 14-step opening checklist that fits on one page, a training version explaining why the fridge temperatures get logged first, both stamped v1 with her as owner and a review date before the summer menu change. Steps she never mentioned aloud but the skill inferred from context are marked CONFIRM, and two of them were wrong.

## Pro tip

Record the ramble while performing the task, not from memory at a desk. Doing the work surfaces the real order and the small warnings ("don't refresh the portal, it double-submits") that a desk recollection smooths over, and those warnings are the most valuable lines in the finished SOP.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/sop-studio). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
