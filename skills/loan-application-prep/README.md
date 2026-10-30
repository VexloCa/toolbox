# Loan Application Prep

> A lender-ready package, from the one-page business summary to the cash-flow forecast, assembled in a week instead of a quarter

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

The bank says yes in principle and then sends the list: two years of financial statements, a twelve-month cash-flow forecast, a business plan summary, a personal net worth statement, the aging reports, a use-of-funds table. You have most of it somewhere. You have none of it in the shape they want, and the loan that was going to fund the second truck sits in "pending documents" for nine weeks while you assemble it between jobs. Meanwhile the lender reads the delay as disorganization. This skill builds the package in the lender's order, and tells you what's missing before the banker does.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill loan-application-prep`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/loan-application-prep/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: what the loan is for, how much, which lender or program, and what financial records you have.
4. Work through the checklist it gives you, pasting exports and quotes as you go; it drafts each document in turn.
5. Run the banker's-questions rehearsal before you submit, and fix whatever you couldn't answer.

## Example

A two-location bakery in Hamilton wants $180,000 to fit out a third site and applies through its bank under the small business financing program. The skill's checklist shows the gap on day one: the landlord's offer to lease isn't signed, and the equipment quotes are six months old. The owner fixes both before touching the forecast. The use-of-funds table shows $142,000 of equipment and leasehold improvements against quotes, $38,000 of working capital, and the owner's own $25,000. The rehearsal catches the hard question: January and February are the bakery's slow months, and the forecast's cash dips close to zero in February with the new payment. The owner moves the opening to March and the forecast holds. The banker's first comment is that it's the cleanest file she's seen this quarter.

## Pro tip

Write the assumptions page before the forecast, not after. A lender who sees "sales grow 4 percent a month" with no reason behind it stops reading; one who sees "third location, same menu, same neighbourhood profile as location two, which did $31,000 a month in year one" keeps going. And have your accountant read the statements before the bank does: lenders notice the difference between compiled and notice-to-reader, and your accountant knows which one you have.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/loan-application-prep). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
