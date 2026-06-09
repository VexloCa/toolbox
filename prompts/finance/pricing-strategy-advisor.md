# Pricing Strategy Advisor

> Pressure-test your pricing and find money you're leaving behind

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small businesses set prices once, based on a competitor's number or a gut feeling, and never revisit them even as costs, demand, and reputation change. Raising prices feels risky without a clear case for it, so owners leave margin on the table for years. This pressure-tests your current pricing against what you actually cost, what competitors charge, and what your close rate is telling you, then hands you concrete experiments instead of a vague "you should charge more."

## The prompt

```
You are a pricing consultant who has helped service and product businesses
find underpriced offers for two decades. You think in three lenses, cost-
plus, competitive, and value-based, and you never recommend a price change
without a specific rollout plan for existing customers.

MY PRICING TODAY:
- What I sell and current price(s): [PRODUCT/SERVICE + PRICE(S)]
- My true cost to deliver (materials, labor, overhead allocation): [$X OR
  BEST ESTIMATE]
- Close rate at current price (deals won / deals quoted, if known): [X%]
- What competitors charge for the closest equivalent: [LIST 2-4
  COMPETITORS + PRICES IF KNOWN]
- How long since my last price change: [TIMEFRAME]
- What customers say when they push back on price (if anything): [DESCRIBE
  OR PASTE OBJECTIONS]
- What makes my offer different from the cheapest alternative: [DESCRIBE]

YOUR TASK: analyze in 3 parts:

1. THREE-LENS ANALYSIS: Evaluate my current pricing against each lens, COST-PLUS (what margin am I actually running, and is it sustainable),
   COMPETITIVE (am I anchored too close to the cheapest or most expensive
   competitor, and does that match my differentiation), VALUE-BASED (based
   on what customers get and what they say, am I pricing to the value
   delivered or just to my costs). Call out the biggest mismatch between
   what I charge and what my differentiation actually justifies.

2. THREE PRICING EXPERIMENTS: For each, state the exact change (e.g. "raise
   the base package from $X to $Y," "introduce a $Z premium tier," "bundle
   A and B instead of selling separately"), the reasoning tied to the
   analysis above, and the expected impact on close rate and margin, labeled clearly as an estimate, not a guarantee.

3. ROLLOUT SCRIPT FOR EXISTING CUSTOMERS: A short, direct script/email for
   informing current customers of a price change without apologizing for
   it or over-explaining. Include how much notice to give and what to offer
   customers who push back (if anything).

RULES: Never recommend a price change without connecting it to a specific
piece of data I gave you, no "just charge more" without a reason. If my
close rate is already low, flag that raising price without addressing why
deals are lost first is risky, and say so. If I haven't given you enough
information (e.g. no cost data) to responsibly recommend a change, say
exactly what's missing before proceeding. State clearly that these are
strategic suggestions based on the numbers I provided, not guaranteed
outcomes, actual market response can differ.

OUTPUT FORMAT: Three labeled sections as above, with the pricing
experiments in a short table (change / reasoning / expected impact).
```

## How to use it

1. Pull your real cost numbers before starting. A pricing analysis without true cost data is guesswork.
2. Fill in your close rate as honestly as possible, even if it's a rough estimate from memory.
3. Paste in real competitor prices where you can find them (their website, a quote you've seen, a customer who mentioned it).
4. Read the three-lens analysis first and flag anything that doesn't match your gut. The AI only knows what you told it.
5. Pick one experiment to run for a full sales cycle before changing anything else, so you can tell what actually moved the needle.
6. Use the rollout script as a starting draft, not a final send: adjust the tone to match how you actually talk to your customers.

## Example

Input: a residential HVAC maintenance company, current plan $299/year for 2 visits, true cost to deliver ~$140/visit including labor and overhead, close rate 62%, competitors range $249-$399/year for similar plans, no price change in 3 years, customers rarely push back on price but frequently ask "what's included," differentiation is same-week emergency callouts included free.

Sample output excerpt:

THREE-LENS ANALYSIS: Cost-plus. You're running roughly a 6% margin on the plan itself once both visits are counted, which is thin for a business absorbing emergency callout risk for free. Competitive. You're priced in the middle of the range but your free emergency callout (a real cost driver) isn't reflected in the price, meaning you're underpriced relative to competitors who charge extra for it...

THREE EXPERIMENTS: 1) Raise to $349/year and explicitly name the emergency callout benefit in the offer: closes the value gap without changing the close rate meaningfully given customers rarely object on price...

## Pro tip

Ask the AI to build the experiment you're most nervous about first, not the safest one. Pricing changes that only nudge the number by a few dollars rarely produce enough signal to tell you anything, while a bolder, well-justified change gives you a real read within one sales cycle.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/pricing-strategy-advisor). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
