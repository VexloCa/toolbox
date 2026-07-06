# Partnership Evaluator

> Know if the partnership is worth it before the handshake

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Partnership offers arrive wrapped in good feelings: a friendly meeting, talk of shared customers, a vague split of the upside. Six months later one side is doing most of the work, the referrals flow one way, and unwinding it costs a relationship. The trap is that both parties negotiate the happy case and nobody prices the likely one. This prompt values the deal in dollars, names how it dies, and gives you walk-away terms before you're sitting across the table nodding.

## The prompt

```
You are a deal advisor who has seen dozens of small-business
partnerships, and the honest pattern is this: most quietly fizzle, a
few work, and the difference was visible on day one to anyone who
priced the exchange instead of the vibe. Price this one.

MY BUSINESS: [WHAT YOU DO, SIZE, WHAT YOU WANT FROM THIS PARTNERSHIP]
THE PROPOSED PARTNER: [WHO THEY ARE, THEIR SIZE, WHAT THEY'VE PROPOSED]
THE SHAPE OF THE DEAL SO FAR: [REFERRALS, REVENUE SHARE, CO-SELLING,
SHARED COSTS, WHATEVER HAS BEEN DISCUSSED, HOWEVER VAGUE]

STEP 1, PRICE THE EXCHANGE: Build a two-sided table of what each party
gives and gets, and put a dollar figure or time cost on every line,
asking me for inputs where needed. A referral is worth (my average
customer value) x (a realistic close rate), not "exposure." Show the
multiplication. If the totals are lopsided by more than 2 to 1, name
which side is subsidizing the other and ask whether that's intended.

STEP 2, PRE-MORTEM: Assume it's 12 months from now and the partnership
quietly died. Give me the three most likely causes for THIS deal
specifically, drawing on the classic failure modes: one-way referral
flow, mismatched effort, a partner's priorities shifting, quality
problems reflecting on my brand, and a customer-ownership dispute.
For each cause, name the earliest observable warning sign.

STEP 3, TERMS BEFORE HANDSHAKE: Draft the five terms I should settle
in writing before starting: what each side commits to monthly, how we
measure it, who owns the customer relationship, how either side exits,
and when we review. For each, give me a reasonable opening position
and my walk-away line. Then state a verdict: proceed, proceed smaller
(propose the 90-day pilot version), or decline, with the reasoning in
two sentences.

RULES: Refuse to score "brand exposure" or "synergy" as value until
converted to an estimated number, however rough. If I haven't said
what I want from the deal, make me answer that before anything else.
Flag that anything contractual, revenue share especially, should be
reviewed by a lawyer before signing; your draft terms are a
negotiation prep sheet, not an agreement.
```

## How to use it

1. Run this before the second meeting, once you know the rough shape of the proposal but before anyone has shaken on anything.
2. Come armed with two numbers: your average customer value and your realistic close rate on warm referrals. Guesses beat blanks.
3. Be honest in Step 1 about what the partner gets from you. Undervaluing your own side is how you end up subsidizing theirs.
4. Take the Step 2 warning signs and put a calendar reminder 60 days out to check for them. Dead partnerships rarely announce themselves.
5. Bring the Step 3 terms sheet to the negotiation, and have a lawyer review whatever you both sign, especially anything touching revenue share or customer data.

## Example

Input: a 6-person web design studio in Halifax weighing a referral partnership with a 15-person marketing agency; the agency proposed "we send each other clients."

Sample output excerpt:

PRICE THE EXCHANGE: You give: priority scheduling for their referrals (est. 10 hours/month of flexibility cost) plus a 10% referral fee. You get: their referrals, est. 2 per month x $6,000 average project x 40% close rate = $4,800/month expected. They get: your referrals, est. 1 per month x $2,500 retainer x 30% close = $750/month expected, plus the 10% fee on work they send. Expected flow is roughly 6 to 1 in your favor. That imbalance is the deal's biggest risk: they will notice it by month four.

PRE-MORTEM, cause #1: The agency's referrals dry up once the imbalance surfaces internally. Earliest warning sign: their referral count drops to zero for six weeks while yours continue.

TERMS: Monthly commitment: each side makes a minimum of one qualified introduction per month, tracked in a shared sheet. Review at 90 days. Walk-away: no exclusivity of any kind in year one.

## Pro tip

The "proceed smaller" verdict is the one to take most seriously. A 90-day pilot with one named commitment per side costs almost nothing to run, and it converts the whole evaluation from prediction into observed data. Most bad partnerships would have revealed themselves in a pilot nobody thought to propose.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/partnership-evaluator). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
