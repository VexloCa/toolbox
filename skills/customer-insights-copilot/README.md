# Customer Insights Copilot

> A running record of what customers keep saying, with the trend, the quotes, and the churn watch kept for you

**Category:** Customer Support · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

The [Voice-of-Customer Miner](/toolbox/voice-of-customer-miner) reads a batch of feedback once and finds the themes. Then the batch is gone, next month's batch gets read in isolation, and nobody can say whether the delivery complaints are shrinking or growing, whether the quote you loved in March ever got permission, or which customer has now raised the same issue three times. Feedback in a small business is a stream, and reading it in puddles loses the one thing only a stream can show: direction. This skill keeps the stream.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill customer-insights-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/customer-insights-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Seed it with your most recent feedback batch or Miner output, and answer its setup questions once.
4. Log feedback as it arrives, two lines each: where it came from and what they said. That habit is the whole system.
5. Monthly, read the report, act on the one change, and ask permission for the quote it picked.

## Example

A meal-kit business seeds the skill with 25 tickets the Miner already read, then logs feedback through September. The ledger shows late-delivery mentions falling from 9 to 3 after the new courier started (the fix is confirmed, not assumed), while "portion size on the family plan" climbs from 4 to 7 and becomes the top rising theme. The quote bank holds "the only box my kids do not argue about", status approved after the owner asked, and it goes on the landing page the same week. The churn watch flags one customer whose third ticket in five weeks shifted from polite to "last box if it happens again"; the owner calls them. The monthly read closes with one change: relabel the family plan as "feeds 3" until the portion is fixed, because seven customers in a month cannot all be wrong.

## Pro tip

Log the good feedback with the same discipline as the complaints. The rising theme in your praise is your next headline, and the skill can only show it rising if the five-star messages get logged too. Pair this with the [Feedback Survey Builder](/toolbox/feedback-survey-builder) once a quarter to fill the gaps the inbox does not cover on its own.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/customer-insights-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
