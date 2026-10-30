# Vendor Contract Reviewer

> Every software, lease and supplier contract read before you sign it, with the auto-renewal, the exit terms and the price escalator pulled out onto one page and the questions to send back

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

The point-of-sale contract was 31 pages. You read the price. Fourteen months later you find out it renewed itself for three years because the cancellation window was days 60 to 90 before the anniversary, the price went up 7 percent on a clause you never saw, and getting your own sales data out costs a fee. None of that was hidden. It was on page 19, in the language contracts use, and you had a store to run. A lawyer for every vendor agreement isn't realistic at your size. A first read that finds the clauses worth a lawyer's hour is. This skill is that read.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill vendor-contract-reviewer`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/vendor-contract-reviewer/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: what kind of contracts you sign, your province, and the ones already in force with their anniversary dates.
4. Paste a contract (or the relevant sections) and ask for the clause summary and the rating.
5. Send the vendor email, book the lawyer hour if a clause is flagged, and log the signed contract's dates in the renewal calendar.

## Example

A three-location coffee roaster in Hamilton is about to sign a 36-month agreement for a loyalty app. The summary finds an auto-renewal for a further 36 months unless cancelled in writing between 90 and 120 days before the end, a 5 percent annual increase "or CPI, whichever is greater", a $4,000 early termination fee, and a clause saying customer data is "retained by the provider" after exit. Three of the four are rated negotiate; the data clause is a walk-away as written. The email asks for a 12-month term, a 30-day cancellation window, a CPI cap, and a data export in a standard format within 30 days of exit. The vendor accepts three of the four. The roaster signs, and the cancellation window goes into the calendar for 2029.

## Pro tip

Ask for the cancellation window to be a date, not a range. "Cancel any time with 30 days' notice" is a sentence you can keep in your head; "between 60 and 90 days before the anniversary" is a sentence designed to be missed. And when a vendor says the contract is standard and can't be changed, ask for the renewal and the data clauses anyway. Those two move more often than vendors admit.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/vendor-contract-reviewer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
