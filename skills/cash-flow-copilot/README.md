# Cash Flow Copilot

> The cash crunch flagged six weeks out, while it is still a decision instead of an emergency

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

The [Cash Flow Analyzer](/toolbox/cash-flow-analyzer) answers the scary question once: where do we stand, how long is the runway. But cash flow is not a question, it is a weather system, and one reading tells you nothing about the storm forming two months out. Small businesses die of cash surprises that were visible six weeks earlier to anyone maintaining a rolling picture, and nobody on a small team maintains it. That rolling picture is a standing job with a memory, which makes it this skill.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Three ways to use it:

- **Claude apps:** zip this folder and upload it in Settings under Skills (paid plans with code execution switched on). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/cash-flow-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, Copilot, or Claude on the free plan:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Do the interview honestly, especially the sleep number; the flags calibrate to it.
4. Pick a weekly day and paste the update: balance, in, out, expected. Two minutes.
5. When a crunch flag fires, act on it that week; six weeks of warning is only worth something spent early.

## Example

A Winnipeg print shop installs the skill in September. The interview captures payroll on the 15th and 30th, rent on the 1st, the two big client accounts that pay net-45, and a $15,000 sleep number. In week three, the projection shows a dip to $9,200 in early November: the seasonal slowdown and an equipment lease renewal landing in the same fortnight, visible seven weeks out. The two levers offered: chase the larger net-45 account (invoice already 12 days old) and shift the lease renewal by three weeks, which the vendor agrees to by email. November's actual low comes in at $16,100. The crunch happened; the emergency never did.

## Pro tip

The weekly paste is the whole system, and it survives on being genuinely two minutes; do not polish the numbers, paste them raw and let the skill ask. Pair the receivable-drift flags with the [Invoice Chaser](/toolbox/invoice-chaser) so the chase email is drafted the same minute the drift is spotted, and give your accountant the monthly one-pager; it is the fastest way ever invented to make that relationship proactive instead of annual.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/cash-flow-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
