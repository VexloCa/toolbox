# Handover Doc Builder

> The knowledge in a departing employee's head captured in a document their replacement can run from on day one, built in three short interviews before they leave

**Category:** HR & Hiring · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

Your office manager gives two weeks' notice. She knows which supplier answers the phone and which one needs an email, where the insurance renewal lives, why the Tuesday delivery is late, the password pattern for the three systems nobody else logs into, and which customer gets a call before an invoice. In two weeks that knowledge walks out. The replacement starts a week after, inherits a desk and a shared drive, and spends two months rediscovering things that were known. The handover document that was supposed to prevent this is usually a page written on the last afternoon. This skill runs the handover as three interviews across the notice period, and writes the document as it goes.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill handover-doc-builder`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/handover-doc-builder/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Tell it the role, the departure date, and whether a replacement has been named.
4. Run the three interviews with the departing person over the notice period, pasting their answers; the document grows after each one.
5. Hand the finished document and the 30-day plan to the replacement, and walk the open-items register together in their first week.

## Example

A nine-person property maintenance company in Oshawa loses its scheduler after four years. The first interview surfaces the yearly calendar: the fall furnace inspections start in six weeks and she's the only one who knows which of the 140 units has a gas appliance. The second produces the people notes, including the one contractor who will only take calls before 8 a.m. The third catches the judgment calls: two tenants are on a "call the owner first" list for reasons that were never written down. The document runs eleven pages. The replacement reads it on day one, starts the furnace list on day two, and the owner's phone is quieter in October than it has been in years.

## Pro tip

Run the first interview in the first two days of the notice period, when the person is still engaged, and the judgment-call interview last, when they trust that you're trying to protect their work rather than audit it. And have the replacement, if they're already hired, sit in on the third one. The questions they ask are the ones you'd never think of.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/handover-doc-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
