# Call Notes to CRM

> Thirty seconds of talking after a sales call turned into the CRM fields, the next step with a date, and the follow-up email, before you've reached the next parking lot

**Category:** Sales & Lead Generation · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

The call went well. You know the budget, the decision maker's name, the thing they're worried about and the date they want to start. Then the next call starts, and by Friday the CRM says "spoke with Dan, follow up". The detail that would have closed the deal (he mentioned the lease ends in March) is gone. Sales teams at big companies have assistants and call recorders. You have a phone and a parking lot. The fix is to talk for thirty seconds while it's fresh and let something else do the typing. This skill is the something else.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill call-notes-to-crm`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/call-notes-to-crm/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: your CRM, its pipeline stages, the fields you fill, and how you sign emails.
4. After each call, dictate or type what happened in your own words, as messy as you like.
5. Paste the fields into the CRM, send the email, and glance at the missed-questions list before the next call.

## Example

A commercial cleaning company owner in Vaughan finishes a walkthrough with a dental office and talks for forty seconds into her phone: "Dr. Patel, four operatories, current cleaner is late and missed a sterilization room twice, contract up end of January, she wants weekend service, budget she said around two thousand a month, office manager is Priya and she's the one who'll sign, wants a quote by the 15th." The skill returns the fields (stage: proposal, budget $2,000 a month, decision maker Priya, timeline January, objection: reliability), a two-sentence note, and an email to Priya that mentions the sterilization room and weekend service by name, with the quote date promised. The missed-questions list has one item: how many cleaners the current provider sends. She asks it in the email's last line.

## Pro tip

Dictate the objection and the competitor even when they're uncomfortable. "Said we're more expensive than the company they use now" is the most useful sentence in the record, and it's the one owners leave out. Six months later, when you're writing the win-loss analysis, it's the reason you lost or the reason you won.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/call-notes-to-crm). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
