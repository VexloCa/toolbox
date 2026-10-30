# AI Receptionist Script Writer

> The greeting, the five call flows, the disclosure line and the hand-off rules for an AI phone receptionist, written before you sign up for one, and the $0 voicemail-and-text version to run first

**Category:** Customer Support · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

The AI receptionist products are good enough now that a plumber or a clinic can have one answering by Friday. What they can't do is know your business. Left to their defaults they greet callers like a bank, book a job you don't do, quote a price you've never charged, and transfer the one call that mattered to a voicemail nobody checks. The script is the product, and the vendors expect you to write it. Most owners type a paragraph into the setup box and wonder why the calls come out odd. This skill writes the script the way a good receptionist would learn the job: the greeting, what callers want, what you can promise, when to hand off, and what never to say.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill ai-receptionist-script-writer`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/ai-receptionist-script-writer/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: what the phone rings for, your hours, what you can book, who takes the hand-offs, and whether calls are recorded.
4. Paste the flows into your receptionist product's setup, or run the $0 version first for two weeks.
5. Each month, paste a handful of call summaries and ask for the script fixes.

## Example

A two-truck HVAC company in Windsor is about to turn on a receptionist product and has typed "answer calls for an HVAC company" into the setup box. The skill's interview finds the five reasons the phone rings in October: no heat, a furnace tune-up booking, a quote for a new furnace, "when is the technician coming", and the gas smell nobody should be handling by text. The flows that come back book tune-ups into the two slots a day the owner opens, take the furnace-quote details and promise a call by 5 p.m., read the technician's window from a list the owner updates each morning, and send any mention of a gas smell to the owner's cell immediately with a scripted "leave the house and call the gas utility" line first. The never-say list includes every price. The owner runs the $0 voicemail version for two weeks first and counts 31 missed calls, 9 of them no-heat emergencies, which is the number that justifies the subscription.

## Pro tip

Write the no-promises rule into the script before anything else: the receptionist may say "someone will call you by 5" only if someone will. A receptionist that over-promises costs you the customers it was supposed to save. And read your provincial rules on call recording before you turn it on; a recorded line needs the caller told, and a health or legal practice has extra duties on where the recording lives.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-receptionist-script-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
