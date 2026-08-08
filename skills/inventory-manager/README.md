# Inventory Manager

> Know what to reorder and what is dead stock from a pasted spreadsheet

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT, Claude Code

## The problem

Most small retailers and wholesalers reorder by gut feel: walk the shelf, notice a gap, phone the supplier. The result is predictable. Best sellers run out during the exact weeks they sell hardest, while the back room holds thousands of dollars of product that hasn't moved since last year. The data to fix this already sits in your POS export. Nobody has time to do the math on it.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Add it to your assistant's skills folder, or paste it at the start of a conversation.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, Cursor. Anything that can fetch a URL or accept pasted text).
3. Answer the setup questions about your suppliers, lead times, and storage costs.
4. Export sales by item for the last 8 to 12 weeks plus current stock on hand, and paste both in.
5. Review the reorder-now list against what you know (a promo, a season ending) before placing orders.
6. Repeat monthly. The more history it has seen, the better its seasonal sanity checks get.

## Example

Say you run a bike shop with about 400 SKUs. You paste a 12-week sales export and current stock counts. Output (condensed): "Reorder now: floor pumps. You sell 9 a week on average, your supplier takes 3 weeks, and you have 21 left. That covers about 2.3 weeks, so you'd likely run out before the order lands. Suggested order: 40 units (assumption: demand holds and lead time stays 3 weeks; both stated below). Dead stock: 11 SKUs with zero sales in 12 weeks, tying up about $3,800 at cost. At your stated 1.5% monthly holding estimate that is roughly $57 a month to keep them. Candidates for a clearance bin: the three oldest. Data note: your export has no costs for 6 SKUs, so they're excluded from the carrying-cost math."

## Pro tip

Paste one export from the same period last year alongside the current one. Reorder math built on the last 8 weeks is blind to seasonality, and a single year-ago snapshot is often enough for the skill to say "this item looks dead now but sold 30 units last November, hold it until December."

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/inventory-manager). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
