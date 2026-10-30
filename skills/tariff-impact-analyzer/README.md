# Tariff Impact Analyzer

> A product-by-product read of what this month's tariffs do to your landed cost and margin, and the three moves that protect the most dollars

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

Since 2025 the Canada-US border has been a pricing variable that moves by press release. Steel and aluminum under Section 232, the CUSMA question on every shipment, Canada's own counter-tariffs, the end of the US de minimis break for small parcels. You import drawer slides from Ohio or sell cabinets into Michigan, you read the headline, and you have no idea what it does to your margin on your own forty products. So you do nothing, and the answer arrives as a supplier invoice that's heavier than the quote. This skill turns the headline into a per-line number you can act on.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill tariff-impact-analyzer`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/tariff-impact-analyzer/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: what you import or export, the countries, and roughly how many product lines you carry.
4. Paste your product list and the duty rates you read today for each tariff code, then ask for the exposure table.
5. Pick the moves it ranks, send the supplier letter, and set a calendar reminder to re-run it next month.

## Example

A Windsor cabinet shop buys hinges, slides and steel brackets from an Ohio distributor and sells finished cabinets to builders on both sides of the river. The owner pastes 40 lines and the rates read that morning. Six lines carry most of the exposure, the slides and the brackets; the lumber qualifies under CUSMA and the labour is local. The skill recommends a surcharge on those six lines only, a question to the Ohio distributor about the brackets' origin certificate, and two Canadian slide suppliers to quote this week. The builder notice goes out with the real cause, the six affected items, and a line saying it will be reviewed on the first of next month.

## Pro tip

Keep a dated copy of every rate you paste in. When a builder asks in March why the slides cost more, you'll have the page you read that day. And talk to a customs broker before you change an origin claim: a wrong CUSMA certificate is a penalty with interest, not a discount.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/tariff-impact-analyzer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
