# Meeting Ops Assistant

> Agendas, minutes, and follow-ups that run themselves

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT, Claude Code

## The problem

The Monday meeting happens because it has a calendar slot, not because anyone prepared for it. There is no agenda, the notes live in someone's notebook, and the action items from three weeks ago come up again because nobody wrote down who owned them. One-off prompts can clean up a single set of notes, but they forget everything by the next meeting, which is exactly when the memory matters.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Add it to your assistant's skills folder, or paste it at the start of a conversation.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, Cursor. Anything that can fetch a URL or accept pasted text).
3. Answer the setup questions about your recurring meetings and how your team communicates.
4. Before your next meeting, ask for an agenda and give it the one thing the meeting must decide.
5. After the meeting, paste your raw notes or transcript and send the recap it drafts.
6. Once a week, ask for the open-action report and chase whatever it flags as slipping.

## Example

Say you run a 12-person landscaping company with a Monday ops meeting. You paste ten messy bullet points after the meeting. The skill returns minutes with two decisions, five actions (one marked "UNASSIGNED, needs owner"), and a recap email. It also flags: "The trailer repair action has now appeared in three consecutive meetings without a deadline. Suggest assigning it to Dave with a date, or dropping it deliberately." That flag is the whole product.

## Pro tip

At setup, paste your last two or three meetings' notes before asking for anything new. The action log starts with history instead of a blank page, and the first slipped-item flags show up in week one rather than week four.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/meeting-ops-assistant). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
