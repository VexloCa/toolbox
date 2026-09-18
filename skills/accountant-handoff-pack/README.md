# Accountant Handoff Pack

> Send your accountant one clean package instead of forty emails

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

You and your accountant don't speak the same language, and the gap gets billed by the hour. They ask for the ledger export and the receivables aging; you send screenshots and a photo of a receipt. Every clarifying email adds a day, every miscategorized charge survives until year-end, and the cleanup lands on the invoice. The information exists on your side. It arrives on theirs scattered, late, and half-labeled.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Three ways to use it:

- **Claude apps:** zip this folder and upload it in Settings under Skills (paid plans with code execution switched on). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/accountant-handoff-pack/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, Copilot, or Claude on the free plan:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Answer the setup questions: business, country and province or state, software, handoff cadence.
4. At month-end, export your statements and transactions, strip account numbers, paste them in, and review the package before sending it as one email.

## Example

A salon owner in Ontario closes out July. She pastes two card statements and a QuickBooks export. Output (condensed): a checklist showing the HST summary still missing; 148 transactions categorized with 6 marked UNSURE (two look personal, one $340 charge has no receipt, three are new vendors); a flag on a second booking-software subscription that started in May; four questions for the accountant, ranked; and a cover memo opening "July package attached: statements, categorized export, HST summary to follow Tuesday. Known issues below." One email out, one reply back.

## Pro tip

Run the skill a few days before your handoff date, not on it. The gap is where you hunt down the missing receipt and cancel the duplicate subscription, so the package that goes out is one your accountant can process in a single sitting.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/accountant-handoff-pack). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
