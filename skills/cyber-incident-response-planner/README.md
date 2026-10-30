# Cyber Incident Response Planner

> A one-page plan for the morning your email, your files or your payments are compromised, with who calls whom in the first hour, what the privacy law requires you to report, and the three fixes that make the plan rarely needed

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

At 7:10 on a Tuesday your bookkeeper can't open the shared drive and there's a text file on the desktop with a payment address in it. Or a customer calls to say they got an invoice from you with someone else's banking details. Or your Instagram is posting crypto ads. In that hour, a small business with a plan makes four phone calls in the right order. A small business without one spends the morning googling, pays a ransom it didn't need to pay, and finds out three weeks later that the breach had to be reported to the Privacy Commissioner. The plan is one page. Writing it before Tuesday is the whole trick. This skill writes it from how your business runs.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill cyber-incident-response-planner`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/cyber-incident-response-planner/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the interview: your systems, your data, your backups, your access, your insurer, your IT help.
4. Print the one-page plan and the contact card, fill in the numbers by hand, and put a copy where the plan can be found without a computer.
5. Do the three fixes it ranks, then re-read the plan every six months or after any change in staff or systems.

## Example

A dental lab in Mississauga with eleven staff runs the interview and discovers three things in twenty minutes: the only person with admin access to email is on vacation half of July, the backups go to a drive that sits plugged into the server (so ransomware would take them too), and nobody knows whether the business insurance policy covers cyber incidents. The plan that comes out names the office manager as the second admin, moves backups to a rotated offline drive tested on the first Monday of each month, and puts "ask the broker about cyber coverage" at the top of the fixes. The customer notice is drafted and filed. Eight months later a phishing email gets a password; the first-hour checklist is followed, the account is locked in twenty minutes, nothing is reported because nothing left, and the log shows what happened.

## Pro tip

Test the backup by restoring one file this week. A backup nobody has restored from is a hope, not a backup, and ransomware operators know which drive is plugged in. And put a paper copy of the contact card in the cash drawer or the first-aid kit, because the morning you need it, the computer with the plan on it is the one that's locked.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/cyber-incident-response-planner). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
