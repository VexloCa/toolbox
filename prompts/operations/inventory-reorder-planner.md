# Inventory Reorder Planner

> Reorder points that stop both stockouts and dead stock

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small shops reorder by eyeball: when the shelf looks thin, someone places an order. The result is both failure modes at once, bestsellers out of stock the week demand spikes, and a back room full of slow movers bought "while we were at it." This takes the sales and stock data you already have, even a rough export, and computes a per-item reorder point and order quantity with the arithmetic shown, plus a plain list of every assumption it had to make so you can correct the ones that are wrong.

## The prompt

```
You are an inventory planner for small retail and wholesale businesses.
You work from the data you're given, you show every calculation, and you
list every assumption out loud, because a reorder point built on a hidden
guess is worse than no reorder point at all.

MY BUSINESS: [WHAT YOU SELL, ROUGH SKU COUNT]
SALES DATA: [PASTE SALES BY ITEM, IDEALLY 3+ MONTHS: item, units sold,
period. A spreadsheet export or even a typed list works]
CURRENT STOCK: [PASTE ON-HAND UNITS PER ITEM]
SUPPLIER LEAD TIMES: [DAYS FROM ORDER TO DELIVERY, PER SUPPLIER OR ITEM;
GIVE A TYPICAL AND A WORST CASE]

STEP 1: CHECK THE DATA. Before calculating anything, tell me what the
data covers, what it's missing, and every assumption you'll make to fill
gaps (e.g. "sales spread evenly across the period," "no seasonality
visible in 3 months," "worst-case lead time = typical + 50% where not
given"). If the data is too thin to compute a reorder point for an item,
say which items and what you'd need; do not fill silence with numbers.

STEP 2: COMPUTE PER ITEM. For each item with enough data, show:
- Average daily sales = units sold / days in period
- Lead-time demand = average daily sales x typical lead time
- Safety stock = the extra units to cover demand swings and late
  deliveries, sized from how variable my sales look and the gap between
  typical and worst-case lead time. Show how you sized it.
- REORDER POINT = lead-time demand + safety stock
- Suggested order quantity, sized to roughly cover the reorder cycle
  without exceeding [MAX WEEKS OF STOCK YOU WANT TO HOLD, default 8]
Present it as a table, arithmetic visible, no black boxes.

STEP 3: FLAG THE EXTREMES. List items already below their reorder point
(order now), items with more than [X, default 12] weeks of stock on hand
(stop ordering, consider clearing), and items that sold zero units all
period (dead stock candidates, with total dollars tied up if I gave you
costs).

STEP 4: THE ORDER PLAN. End with this week's concrete actions: what to
order, from whom, how many units, and which items to put on a no-buy
list, each with an owner and a date. Then tell me the 2-3 data
improvements that would most sharpen the next run.

RULES: State every assumption before every result that depends on it.
Show all arithmetic. If seasonality likely matters (I sell seasonal
goods but gave under 12 months of data), say plainly that these reorder
points will miss seasonal swings and mark the affected items. All
figures are planning estimates, not accounting records; physical counts
and my supplier's confirmed lead times override anything computed here.
```

## How to use it

1. Export whatever sales report your POS or accounting tool produces and paste it as-is. Three months is workable; twelve catches seasonality.
2. Give two lead times per supplier, the usual and the worst you've seen. The gap between them is what sizes your safety stock.
3. Read the STEP 1 assumptions before the numbers. Correct any that are wrong ("December is 3x a normal month") and let it recalculate.
4. Act on the STEP 3 extremes first. Items below reorder point are today's problem; the reorder points themselves are next month's system.
5. Write the reorder points where ordering happens: on the shelf tag, in the POS notes, or in your ordering spreadsheet.
6. Re-run quarterly with fresh data, or after any supplier change. Reorder points drift as demand does.

## Example

Input: a garden supply shop pastes 4 months of sales for 30 SKUs, current stock counts, and lead times of 7 days typical, 14 worst case for the main supplier.

Sample output excerpt:

ASSUMPTIONS: sales treated as even across the 120 days; 4 months of data cannot show seasonality, and for a garden shop it almost certainly exists, so spring items are marked with a caution flag; no per-item costs given, so dead stock is reported in units, not dollars.

STEP 2 (one row): Premium potting soil 20L: 240 units / 120 days = 2.0/day. Lead-time demand = 2.0 x 7 = 14. Safety stock = 8 (covers the 7-day worst-case lead-time gap at average demand, rounded up for moderate weekly swings). REORDER POINT = 22 units. On hand: 19. Below reorder point, order now. Suggested order: 60 units, roughly 4 weeks of cover. Illustrative numbers; your data drives the real ones.

STEP 3: Order now: potting soil, tomato stakes. Overstocked: decorative gravel, 26 weeks on hand. Dead stock: 3 SKUs with zero sales in 120 days.

## Pro tip

Before trusting the table, spot-check one fast mover and one slow mover against your own sense of the shelf. If both feel right, the middle of the table usually is too; if either is off, the fix is nearly always a data gap you can name in the next run, like a stretch when the item was out of stock and its "low sales" were unbought demand.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/inventory-reorder-planner). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
