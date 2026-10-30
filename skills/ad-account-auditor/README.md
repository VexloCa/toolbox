# Ad Account Auditor

> A plain-English read of your Google Ads or Meta export every month, with the three changes that would have saved the most money last month and the one that would have made the most

**Category:** Marketing & Content · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

You spend $1,800 a month on Google Ads and $900 on Meta, and you couldn't say in a sentence what either one bought you. The dashboards are built for people who do this all day. The agency report, if you have an agency, arrives as a PDF of green arrows. Meanwhile a campaign that stopped converting in June is still spending, the search terms report has "free" and "jobs" in it, and the one ad group that brings real calls is capped by budget. You don't need a media buyer. You need someone to read the export once a month and tell you where the money went. This skill does the reading.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill ad-account-auditor`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/ad-account-auditor/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: what you sell, what a lead or sale is worth, what you can afford to pay for one, and who runs the account.
4. Each month, export the campaign, ad group and search terms reports (or the Meta campaign and ad set reports) as CSV and paste them in.
5. Make the three cuts and the one raise, then paste next month's export to see what changed.

## Example

A Barrie furnace and air conditioning company pastes four months of Google Ads data. The read is short. One campaign built for a spring AC promotion is still live in October, spending $340 a month on clicks for "air conditioner sale". The search terms report shows $210 a month on "furnace repair jobs" and "free furnace" and the like, with no negatives set. The emergency repair ad group, which produced 14 of the month's 19 phone calls, hit its daily budget by 2 p.m. on 22 days. The proposal: pause the AC campaign, add eleven negatives, move the $340 to the repair ad group. Next month's export shows 27 calls on the same total spend, and the owner finally understands what the account is for.

## Pro tip

Before you trust any number in the export, check that the conversion the account counts is a real one: a phone call over 60 seconds or a form that reaches your inbox, not a page view of the thank-you page that nobody lands on. The skill asks about this first for a reason. Half the "underperforming" campaigns we've seen were performing fine and tracking nothing.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ad-account-auditor). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
