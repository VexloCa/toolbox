# Refund & Return Policy Writer

> A policy that protects you without scaring buyers

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Refund policies at small businesses tend toward one of two failures: an all-caps NO REFUNDS wall that kills sales from cautious first-time buyers, or a vague "contact us and we'll sort it out" that turns every return into a one-off negotiation you handle at 9pm. Copying a big retailer's policy doesn't work either, because their margins absorb free returns and yours might not. You need rules you can afford, written so a nervous buyer reads them as reassurance rather than a threat.

## The prompt

```
You are a plain-language policy writer who has read a thousand refund
policies and knows that most were written to win arguments, not to
keep customers. You write policies the owner can afford, the buyer can
understand in 30 seconds, and staff can apply without asking the owner.

MY BUSINESS: [WHAT YOU SELL: PHYSICAL GOODS / SERVICES / DIGITAL /
CUSTOM WORK / MIX, AND WHERE: ONLINE, IN-STORE, BOTH]
WHERE MY CUSTOMERS ARE: [PROVINCES/STATES/COUNTRIES YOU SELL INTO]
MY COST REALITIES: [SHIPPING COSTS, WHETHER RETURNS ARE RESELLABLE,
PERISHABLES, CUSTOM ITEMS, DEPOSITS, THIRD-PARTY FEES]
CURRENT POLICY IF ANY: [PASTE IT, OR "NONE, I DECIDE CASE BY CASE"]
DISPUTES I ACTUALLY GET: [THE 2-3 REFUND SITUATIONS THAT COME UP MOST]

STEP 1: AFFORDABILITY CHECK: Before writing anything, walk through the
money. For my most common dispute, show the arithmetic of a generous
policy vs a strict one (item cost, return shipping, restock or
disposal, time). Tell me where I can afford generosity, where I can't,
and flag any product type that needs its own rule (custom, perishable,
digital, deposits).

STEP 2: DRAFT THE POLICY: Write it with these parts, each in plain
sentences a grade-8 reader follows: what's returnable and what isn't
(with the why for exclusions), the time window, condition required,
how to start a return, who pays return shipping, refund method and
how many days until the money shows up, and what happens with sale
items, gifts, and exchanges. Lead with the most reassuring true
sentence, not the exclusions.

STEP 3: NERVOUS-BUYER READ: Re-read the draft as a first-time buyer
deciding whether to trust me. Flag any line that reads as hostile or
lawyerly, and rewrite it to say the same rule in a human way ("custom
orders are made just for you, so we can't restock them" instead of
"CUSTOM ITEMS ARE FINAL SALE, NO EXCEPTIONS").

STEP 4: STRESS TEST: Run 5 hard scenarios against the draft (item
damaged in transit, return arrives on day 32 of a 30-day window, used
item returned, chargeback threat, gift return with no receipt). For
each, quote the line of the policy that answers it, or fix the policy
so one does. End with a one-paragraph internal note for staff: where
they can bend the rules and where they can't.

RULES: No legalese theater ("herein," "notwithstanding"). Every rule
needs a reason I could say out loud to an upset customer. Never write
"no refunds under any circumstances": consumer-protection law limits
what any policy can waive, and in Canada the rules differ by province
(and by state and country elsewhere). Mark anything law-adjacent with
[LAWYER: check this] and end by saying the final text needs a lawyer's
review before publishing.
```

## How to use it

1. Pull up your last 5 refund requests before running this. Real disputes make a better policy than imagined ones.
2. Be honest in the cost realities section. If a returned candle is resellable but a returned mattress isn't, the policy should treat them differently.
3. Run the prompt and pay attention to the affordability arithmetic. A 60-day window sounds friendly until you price the returns it invites.
4. Take the stress-test scenarios seriously, and add the weird dispute you got last year that the prompt didn't think of.
5. Send the draft to a lawyer before it goes on your site. Consumer-protection rules vary by province in Canada, and by state and country beyond it, and a policy that contradicts them isn't enforceable no matter how clearly it's written.
6. Post the final version where buyers see it before checkout, not buried in the footer, and give staff the internal note so answers stay consistent.

## Example

Input: an online pottery studio in Nova Scotia shipping mugs and custom dinnerware across Canada, most common dispute is items broken in transit.

Sample output excerpt:

Affordability check: a $42 mug costs you about $19 to make and $14 to ship. On a transit-damage claim, demanding a return means paying $14 more in shipping to receive a broken mug you'll discard. Photo-proof replacement is cheaper than a return in every damage scenario, so build that in. Custom dinnerware is different: a $380 commissioned set can't be resold, so deposits should be non-refundable after work begins [LAWYER: check this against provincial rules on deposits].

Draft opening: "We want you to love what arrives. If your piece shows up damaged, send us a photo within 7 days and we'll replace it or refund you, your choice, no need to ship anything back."

Stress test, scenario 3 (used item returned): current draft doesn't cover it. Added line: "Returned pieces need to arrive unused and in their original packaging so we can offer them to someone else."

## Pro tip

Track refund requests by reason for 90 days after the policy goes live. If one reason dominates, the policy isn't the fix. Broken-in-transit claims point at packaging, "not as pictured" points at product photos, and a policy rewrite won't move either number.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/refund-policy-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
