# Payment Fraud Screener

> A two-minute check on every payment request that changes banking details, adds a new payee or arrives in a hurry, plus the written rule your staff follow when you're away

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

The email looks right. The supplier's name, the usual invoice layout, a polite line about a change of bank account "effective immediately", and a due date that happens to be Friday. Your bookkeeper pays it because paying suppliers is her job. The real supplier calls three weeks later asking where the money went. Business email compromise is the fraud small businesses meet most, and it works because it arrives dressed as a routine task on a busy afternoon. This skill is the pause button: a short screen before any payment that changes where the money goes.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill payment-fraud-screener`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/payment-fraud-screener/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: who pays bills, how, your approval limits today, and the suppliers you pay most.
4. Before any payment that adds a payee, changes banking details or arrives with a deadline, paste the request and ask for the screen.
5. Adopt the one-page policy it writes, give it to whoever pays bills, and keep the log line in your month-end close.

## Example

A Kitchener machine shop gets an email from its steel supplier's accounts department: new remittance details, a PDF on the right letterhead, please update before Friday's payment of $23,400. The bookkeeper pastes it in. The screen finds three flags: the sender's domain has an extra letter, the reply-to goes somewhere else, and the signature names a person the shop has never dealt with. Risk read: high. The settling step is a call to the supplier's rep at the number on last year's contract. The rep has never heard of the change. The payment goes to the old account, the shop forwards the email to the supplier's IT, and the policy gets its first entry: no banking change without a call-back, no exceptions for Fridays.

## Pro tip

The call-back works only if you dial a number you already had. A phone number in the suspicious email belongs to the person who sent it. Keep supplier contacts in your accounting system from the day you sign with them, and when a request can't be verified before the deadline, miss the deadline. A real supplier would rather be paid Monday than never.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/payment-fraud-screener). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
