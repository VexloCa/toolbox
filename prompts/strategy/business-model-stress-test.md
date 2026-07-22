# Business Model Stress Test

> Find the assumption that kills your business before it does

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Every business model rests on a handful of assumptions the owner stopped noticing years ago: customers will reorder, the key supplier stays reliable, the referral pipeline keeps flowing. Nobody writes them down, so nobody tests them, and the fatal one gets discovered by the bank balance instead of by you. Asking an AI "is my business model sound?" gets you a polite essay. This prompt makes it hunt for the specific assumption that breaks you, then prove or disprove it cheaply.

## The prompt

```
You are a due-diligence analyst whose job is to break business models on
paper so reality doesn't get the chance. You are not here to reassure the
owner. You are here to find the load-bearing assumption they've stopped
seeing.

MY BUSINESS: [WHAT YOU SELL, TO WHOM, ROUGH ANNUAL REVENUE, TEAM SIZE]
HOW MONEY ACTUALLY FLOWS: [WHERE CUSTOMERS COME FROM, WHAT THEY PAY, WHAT
YOUR 2-3 BIGGEST COSTS ARE]

STEP 1, ASSUMPTION INVENTORY: List every assumption my model depends on,
grouped as: demand (why customers buy and keep buying), supply (what I
need to deliver), channel (how customers find me), and money (margins,
payment timing, concentration). Aim for 8-12 total. For each, ask me one
sharp question to establish what evidence I have. "It's been fine so far"
is not evidence; label it as faith.

STEP 2, FRAGILITY RANKING: Score each assumption 1-5 on two axes: damage
if it turns out false, and how thin my evidence is. Multiply them. Show
the top 3 as a ranked list with the arithmetic visible. If a single
customer, supplier, or channel is over 30% of revenue or capacity, it
goes to the top regardless of score, and you say so.

STEP 3, BREAK IT: Take the number one assumption and write the plain
story of the quarter where it fails. What do I notice first, what does
the cash position look like at day 30, 60, 90, and what options have
closed by the time most owners would react?

STEP 4, CHEAP PROOF: For each of the top 3, design the cheapest test
that would tell me within 30 days whether the assumption holds. Each
test gets a cost estimate, a pass/fail threshold I set before running
it, an owner, and a start date. End with the one test to start this
week.

RULES: Reject any assumption phrased as a hope ("customers love us")
until it's restated as something checkable ("60% of customers reorder
within 90 days"). Do not soften the failure story in Step 3. If my
inputs are too vague to rank, stop and interrogate me before
continuing. The output is the test list, not the inventory.
```

## How to use it

1. Paste the prompt into Claude or ChatGPT with real numbers, revenue, customer counts, and your true cost structure. Rounded is fine, invented is not.
2. Answer the evidence questions in Step 1 honestly. Saying "I have no data on that" is useful; it moves the assumption up the fragility ranking where it belongs.
3. Read the Step 3 failure story slowly. If any sentence makes you uncomfortable, that discomfort is the finding.
4. Pick the single cheapest test from Step 4 and put it on your calendar before you close the chat.
5. Re-run the stress test twice a year, or after any big change: a new location, a major hire, a top customer leaving.

## Example

Input: a 12-person meal-prep delivery company in Calgary, about $900K annual revenue, 70% of orders from repeat weekly subscribers.

Sample output excerpt:

FRAGILITY RANKING: #1: "Subscribers stay past month three." Damage if false: 5. Evidence thinness: 4 (you track total subscribers but not cohort drop-off). Score: 20. #2: "One commercial kitchen lease renews at a similar rate." Damage: 4, evidence: 4, score: 16.

BREAK IT: If month-three churn is quietly running at 25%, your subscriber count looks flat while the machine underneath is a treadmill. Day 30 you notice acquisition spend creeping up. Day 60 a slow ad month means a visible revenue dip for the first time. Day 90 you're discounting to refill the base, which trains the exact behavior that started the slide.

CHEAP PROOF #1: Export the last 12 months of orders and count, per signup month, how many customers still ordered in month four. Cost: $0, an afternoon. Pass threshold: 70% or better. Owner: you. Start: this week.

## Pro tip

Run Step 1 with your bookkeeper or a senior staff member in the room and compare answers before feeding them in. The assumptions where you two disagree are almost always the ones that end up ranked most fragile.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/business-model-stress-test). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
