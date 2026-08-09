# Bookkeeping Copilot

> Books that stay categorized and reconciled monthly without dread

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT, Claude Code

## The problem

Bookkeeping is the chore that slides. Transactions pile up for a quarter, then one grim Sunday gets sacrificed to categorizing them from memory ("what was that $84 charge in May?"). A generic AI prompt barely helps, because every chat starts from zero: it doesn't know your categories, your regular vendors, or that the same $210 supplier charge lands every month and is fine. So you re-explain, it re-guesses, and the books stay behind.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Add it to your assistant's skills folder, or paste it at the start of a conversation.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, Cursor. Anything that can fetch a URL or accept pasted text).
3. Answer the skill's setup questions about your business and categories.
4. Pick a monthly date and make it a ritual: export the month's transactions, strip out account numbers, paste them in, and work the close checklist top to bottom.
5. When it flags an item as uncertain, rule on it once. That ruling is remembered.

## Example

Say you run a two-van cleaning company. You paste 92 transactions from June. Output (condensed): "Categorized 86 of 92. Flagged for your ruling: $340 at a hardware store (supplies or equipment?), and two items I have no pattern for. Anomalies: the $89 charge from your scheduling software appears twice on June 12 and June 13, likely a duplicate worth disputing; fuel is up 22% on May with the same number of jobs. Month-end checklist: transactions categorized (done), receivables review (2 invoices past 30 days), HST set-aside check (pending your ruling on the flagged items). I'm not a licensed accountant or bookkeeper: please have your accountant verify anything important before you act on it."

## Pro tip

In your first session, paste your accountant's category list or last year's expense categories instead of letting the skill invent its own. Books categorized the way your accountant already thinks save you a correction round at tax time, and the skill will hold that structure from then on.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/bookkeeping-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
