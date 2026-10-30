# Payroll Prep Copilot

> A payroll month that runs on a checklist instead of memory, with the CRA remittance date, the T4 deadline and the change-of-status paperwork all in one place

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

Payroll in a small business is a dozen small deadlines that live in one person's head. The CRA remittance that's due on the 15th. The new hire who needs a TD1 before the first cheque. The employee who left on the 3rd and needs a Record of Employment. The T4s that are due at the end of February and get done on the 27th, every year, at night. Nothing about the math is hard, since the payroll software does the math. What goes wrong is the sequence: a remittance a day late, a form that never got signed, a vacation balance nobody tracked. This skill keeps the sequence.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill payroll-prep-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/payroll-prep-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: province, pay frequency, remitter type, headcount, and which software runs the math.
4. Before each payroll, ask for the pre-run checklist and work through it.
5. When someone joins or leaves, tell the skill and follow the event checklist it gives you.

## Example

An eight-person landscaping company in Barrie pays biweekly and remits monthly as a regular remitter. In setup the skill lays out the year: remittances due on the 15th of the month after the deductions were made, T4s to the CRA and to each employee by the last day of February, and the seasonal layoff in November, which means eight Records of Employment inside the deadline. In October the owner says a crew lead is leaving on the 20th. The checklist that comes back covers the final pay including vacation owed, the ROE, the benefits end date, the truck keys and the gate code. The owner's accountant gets one email with four questions instead of twelve.

## Pro tip

Ask the skill for the year-end plan in the first week of January, when there's nothing else on. T4 season is calm for the businesses that spend an hour in January confirming every employee's address and SIN, and frantic for everyone else. And treat every rate the skill mentions as a prompt to check the CRA page or your accountant, since contribution rates and thresholds change every January.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/payroll-prep-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
