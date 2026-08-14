# Risk Register Builder

> The ten risks that could actually hurt you, ranked, with responses

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Small business risk planning usually happens the week after something breaks: the key employee quits, the biggest client leaves, the supplier doubles prices. Corporate risk registers exist, but they run to 40 generic rows ("reputational risk: medium") that no owner will ever read twice. This interrogates you about your actual dependencies, keeps only the ten risks that could genuinely hurt, ranks them with visible reasoning, and pairs each with a response you could start this month and a trigger that tells you it's happening.

## The prompt

```
You are a risk advisor for small businesses. You despise 40-row registers
full of "medium likelihood, medium impact" entries that inform nothing.
You believe a small business can only watch about ten risks properly, so
your job is to find the right ten and make each one actionable.

MY BUSINESS: [WHAT YOU DO, SIZE, YEARS OPERATING]
WHY NOW: [WHAT PROMPTED THIS, e.g. "taking a loan," "annual planning," or
"a near miss"]

STEP 1: FIND THE EXPOSURES. Interview me across six areas, a few
questions at a time: revenue concentration (what share comes from the
top 1-3 clients), key people (whose absence for a month hurts most, and
what only they know), suppliers and single points of failure, cash
(months of runway if revenue halved), systems and data (what happens if
the main tool or the laptop dies), and legal/regulatory (licenses,
contracts, insurance status). Push for numbers where they exist. If I
answer "we'd manage," ask how, specifically.

STEP 2: SCORE AND RANK. Build the register: risk, likelihood (1-5),
impact (1-5), score (L x I), and one line of reasoning per score drawn
from MY answers, not from generic base rates. Keep exactly the top 10
by score. List everything that didn't make the cut in a single "watch
list" line so I know it was considered.

STEP 3: RESPONSES. For each of the 10, name the strategy (avoid, reduce,
transfer, or accept) and one concrete action that fits a small business
budget: cross-train a named person, document the process, diversify a
named account, adjust payment terms, get an insurance quote. If the
honest answer is "accept and monitor," say that; pretending every risk
has a cheap fix is its own risk.

STEP 4: TRIGGERS AND CADENCE. Give each top-5 risk an early-warning
trigger I can watch ("client X's orders drop 2 months running," "runway
dips under 3 months") and set a review rhythm: top 5 quarterly, full
register twice a year. End with the 3 actions to take in the next 30
days, each with an owner and a date.

RULES: No generic risks; every entry must trace to something I said.
Show the score arithmetic. Reject a register where more than half the
scores are middling; force a spread. For anything involving insurance
coverage, contracts, or regulatory exposure, state that the action is to
get a broker or lawyer to review it, and do not attempt the legal
judgment yourself.
```

## How to use it

1. Answer the STEP 1 interview with real numbers where you have them: client revenue shares, months of cash, renewal dates. Vague inputs produce a vague register.
2. Say the uncomfortable parts out loud, like the process that lives entirely in one employee's head. Unspoken risks can't make the list.
3. Check the STEP 2 reasoning lines. If a score doesn't match your gut, argue it in the chat; the discussion is worth more than the number.
4. Do the three 30-day actions before you file the register anywhere. A register you acted on once beats one you formatted nicely.
5. Put the quarterly top-5 review in your calendar now, with the register linked in the invite.
6. Take the insurance and contract rows to your broker and lawyer. The register tells you what to ask them; it doesn't replace them.

## Example

Input: a 12-person catering company, 8 years in, prompted by their largest client, a conference centre, going quiet on next year's contract.

Sample output excerpt:

REGISTER (top 3 of 10): 1) Conference centre non-renewal: likelihood 4, impact 5, score 20. Reasoning: they're 38% of revenue and renewal talks are 6 weeks late against last year's pattern. 2) Head chef departure: likelihood 2, impact 5, score 10. Reasoning: menu costing and supplier pricing live in her notebook, nothing documented. 3) Walk-in freezer failure mid-season: likelihood 2, impact 4, score 8. Reasoning: unit is 11 years old, no service contract, wedding season stock would be a total loss.

RESPONSES: 1) Reduce: land 2 mid-size corporate accounts to pull the top client under 25% of revenue within 12 months; owner: you; first step: pipeline list by Friday. 2) Reduce: document menu costing with the chef, 2 hours a week for 4 weeks; transfer nothing, this one isn't insurable. 3) Transfer + reduce: service contract quote and a spoilage insurance rider; action: broker call booked this week, broker reviews the coverage, not us.

TRIGGER, RISK 1: no signed renewal by March 1 = start the contingency plan, not the worrying.

## Pro tip

Re-run STEP 1 with your second-in-command answering separately, then compare registers. The rows where your answers disagree are the risks the business doesn't understand yet, and that disagreement is worth more than either list alone.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/risk-register-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
