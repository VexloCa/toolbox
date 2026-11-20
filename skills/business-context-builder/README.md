# Business Context Builder

> A folder on your computer that tells your AI assistant what you sell, who buys it, how you sound and what it must never say, with a score for how much of the picture is backed by evidence

**Category:** Strategy & Planning · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

You've explained your business to ChatGPT more often than to your accountant. Every new chat starts with the same three sentences: what you sell, who buys it, the tone you like. The answer still reads like it was written for a business a bit like yours. A paragraph typed from memory is thin input. It holds what you believe about the business, and it leaves out your price list, your hours, the promises on your website and the things a new hire gets told in week one. What an assistant needs is a place where all of that is written down once, with a note on where each line came from, so it reads the file and you stop repeating yourself.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill business-context-builder`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/business-context-builder/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. In the ChatGPT desktop app, choose Codex, create a project and attach an empty folder such as `my-business`.
2. Click "Install skill" on this page and copy the install prompt.
3. Paste it into a chat in that project. The assistant fetches the skill file and saves it under `.agents/skills/` in your folder.
4. Give it the business name and website, then say "build my business context".
5. Answer its questions. "I don't know" and "skip" are fine; they are recorded as not found.
6. Open `context/analysis/coverage.md`, read the three gaps, and drop the first missing file into `inbox`.

## Example

We ran the skill on the public website of an independent cafe, in a fresh project with an empty folder. It read the site through the app's own browser and asked six questions, among them what sells most, why customers pick the cafe over the one down the road and what an assistant should never promise. We answered with made-up replies and labelled them as samples. The skill kept those out of the score and said so. The first coverage score came out at 50 percent, 15 points of 30. Offer, voice, sales path and operations each scored 3, because the menu, the ordering steps and the cafe's own wording were on the published site. Customers, customer voice, market and money each scored 0, with a line saying what was not found: who the customers are, what the reviews say, how rivals compare, and real sales and margins. That list of zeros is the owner's to-do list.

## Pro tip

Don't tidy your files before the first run. Drop the messy price list and last year's invoices into `inbox` as they are and let the score tell you what's missing. Then rerun the skill after each addition and watch one area move. A folder that climbs from 50 to 70 percent in a week is worth more than a perfect one you plan to build next month.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/business-context-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
