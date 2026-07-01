# Ops Automation Planner: AI Business Process Automation

> Document your business processes, then automate the ones worth automating

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT, Claude Code

## The problem

In most small businesses, the way things get done lives in one person's head. Nothing is written down, every task is done slightly differently each time, and "we should automate this" stays a wish because nobody knows where to start or which tool to trust. Meanwhile hours disappear each week into copy-paste work a $20/month tool could do.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Add it to your assistant's skills folder, or paste it at the start of a conversation.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, Cursor. Anything that can fetch a URL or accept pasted text).
3. Answer the skill's setup questions about your business.
4. Start by mapping your single most painful process. Answer its interview questions, confirm the map is accurate, and let it write that SOP before touching automation.

## Example

A small e-commerce warehouse names returns processing as its worst process. The skill interviews the owner and plays back an 11-step map: three steps tagged Fragile (they live in the manager's head), two tagged Waste (the return is logged in both a spreadsheet and the store admin), one tagged Automatable. It writes the returns SOP, then recommends one automation: "When a return is approved in Shopify, create a row in the Returns sheet and notify #warehouse in Slack: buildable in Zapier on your existing plan, about 30 minutes of setup, saves roughly 3 hours/month of double entry." The build plan includes field mappings and three test cases to run before trusting it.

## Pro tip

Run the weekly ops report even in weeks when nothing broke. The habit is the point. After two months you have a searchable operating log, and the skill starts spotting patterns ("shipping complaints spike every long weekend") that no single week reveals.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ops-automation-planner). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
