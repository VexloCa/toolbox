# Job Estimate Builder

> A written estimate that goes out the same evening as the site visit, with the scope, the exclusions, the allowances, the deposit and the payment schedule a customer can't later say they misunderstood

**Category:** Sales & Lead Generation · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

You walked the job at 4:30, you know what it costs, and the estimate goes out on Thursday because writing it takes an hour you don't have in the truck. By Thursday the homeowner has two other quotes. When yours does arrive, it's a number and a paragraph, which is why six weeks later there's an argument about whether the electrical was included and who pays for the rotten subfloor nobody could see. In Ontario a home renovation contract over $50 has to be in writing with specific contents, and if you give an estimate you can't charge more than 10 percent over it without a signed change. A good estimate is a sales document and a legal one at once. This skill writes it from your voice notes in the truck.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill job-estimate-builder`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/job-estimate-builder/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: your trade, your labour rates, your material markup, your standard exclusions, your deposit policy, and your province.
4. After a site visit, dictate the job and answer the six questions it asks.
5. Read the draft once, fix anything it guessed, and send it that evening.

## Example

A two-person bathroom renovation company in Oshawa visits a 1970s bungalow at 4:15 p.m. In the truck the owner dictates: full gut, new tub, tile to the ceiling, move the vanity drain eighteen inches, customer hasn't picked tile, the floor felt soft near the toilet. The skill asks its six questions and drafts: eleven scope lines, an allowance of $6 a square foot for tile, exclusions for permits and painting, and a line that says the subfloor will be inspected after demolition and any repair priced as a written change order before work continues. Deposit 10 percent, progress payment at rough-in, balance on completion, estimate valid 30 days, cooling-off notice included because the contract will be signed at the house. It goes out at 6:40 p.m. The homeowner signs Saturday. The subfloor is rotten; the change order is signed before the first new board goes in.

## Pro tip

Put the allowance number beside every item the customer hasn't chosen yet. "Tile allowance $6 per square foot" turns the most common renovation argument into a sentence you can point to. And send the estimate the same day, even if it's 9 p.m. The customer who gets a careful written estimate twelve hours after the visit assumes the work will be done the same way.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/job-estimate-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
