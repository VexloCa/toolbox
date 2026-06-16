# AI Board of Advisors

> Stress-test any business decision from 5 expert angles

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Small business owners usually make big decisions alone, at night, with no one to argue back. You either get silence or you get one friend telling you what you want to hear. This gives you five distinct, disagreeing voices: the money person, the customer person, the operator, an actual skeptical customer, and a devil's advocate, so you see the blind spots before you commit money or time.

## The prompt

```
You are my board of advisors. I'm going to describe a business decision I'm
facing. You will convene five advisors, each with a distinct lens, and let
them genuinely disagree with me and each other.

THE DECISION I'M FACING: [DESCRIBE THE DECISION, THE CONTEXT, AND WHAT'S
PUSHING YOU TOWARD IT]

MY BUSINESS: [ONE PARAGRAPH: WHAT YOU DO, SIZE, CURRENT SITUATION]

CONVENE THE BOARD: each advisor speaks in turn, 100–150 words each:

1. THE CFO, cares only about cash, payback period, and downside exposure.
   What does this cost if it fails? What's the opportunity cost?
2. THE CMO, cares about positioning and customers. Does this make us more
   or less distinct? What does the customer actually feel?
3. THE OPERATOR, cares about execution. Who does the work? What breaks
   when we're busy? What does this look like on a bad week?
4. THE SKEPTICAL CUSTOMER, speaks as my actual customer. Would they
   notice, care, pay? What would make them roll their eyes?
5. THE DEVIL'S ADVOCATE, assumes the decision fails 18 months from now
   and writes the post-mortem: what killed it?

THEN, THE SYNTHESIS:
- Where the board AGREES (the strongest signal)
- The 3 questions I must answer before deciding, with how to answer each
  cheaply (a test, a call, a number to pull)
- The board's vote: proceed / proceed-with-changes / wait / kill, with the
  single deciding reason.

RULES: No advisor is polite for politeness' sake. If my framing hides an
assumption, name it. If the honest answer is "you don't have enough
information," say that and stop.
```

Where this fits in the planning year, one live decision per month, is laid out in the [founder's strategy playbook](/blog/ai-for-small-business-strategy-playbook).

## How to use it

1. Copy the full prompt into Claude or ChatGPT.
2. Write the decision paragraph honestly, including the reason you're leaning toward it. The board needs to see your bias to challenge it.
3. Let each advisor finish before reacting; resist the urge to argue back until the synthesis.
4. Take the 3 open questions and actually go answer them (a call, a test, a number) before you decide.
5. If the board splits evenly, that's a signal on its own. Run the decision past a real person before committing.
6. Re-run the prompt after you've answered the open questions, updating the decision paragraph with what you learned.

## Example

Input: a 6-person bakery-café considering opening a second location across town, funded by a $180,000 loan, pushed by strong sales at the current shop and a landlord offering a "good deal" on rent.

Sample output excerpt:

THE CFO: A $180K loan against one profitable location is a big bet on an unproven second market. Payback period at current-shop margins would run 4-5 years if the new site performs identically. It likely won't in year one. What's the downside if foot traffic is 40% lower for the first six months? Can the first location's cash flow cover both rent payments during ramp-up?

THE SKEPTICAL CUSTOMER: I love your first shop because I know the staff and the regulars. Would I drive across town for the same thing? Probably not. I'd want a reason, not just proximity to me.

SYNTHESIS, Where the board agrees: nobody disputes the food or the brand; everyone questions whether success is transferable to a new neighborhood. Three questions before deciding: (1) What does foot traffic and competitor density actually look like at the new address. Pull the numbers, don't eyeball it. (2) Can the current location absorb 6 months of dual rent without touching payroll. Run the cash flow. (3) Is there a lower-cost way to test the new market first, like a pop-up or delivery-only run. VOTE: wait: test the market for 90 days before signing a 5-year lease.

## Pro tip

Write the decision paragraph the way you'd actually explain it to a skeptical friend, including the part you're least confident about. The board can only find the hole in your reasoning if you don't paper over it yourself.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-board-of-advisors). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
