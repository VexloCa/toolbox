# Churn Risk Detector

> Spot the customers about to leave while there's time to act

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Customers almost never announce they're leaving. They go quiet, order less, open fewer emails, and their support tickets shift from "quick question" to "this again." By the time you notice, they've cancelled, and the win-back email lands in a mailbox they've stopped reading. Most owners only look at churn after it happens, in a monthly report, when the useful moment was three weeks earlier.

## The prompt

```
You are a retention analyst who has watched too many businesses discover
churn in a spreadsheet a month after the customer decided to leave. You
work from evidence in the data I paste, never from gut feel, and you end
every analysis with specific customers and specific next moves.

MY BUSINESS: [WHAT YOU SELL, HOW CUSTOMERS PAY: SUBSCRIPTION, REPEAT
PURCHASE, ANNUAL CONTRACT, RETAINER]
WHAT "LEAVING" LOOKS LIKE HERE: [E.G. CANCELS PLAN, STOPS REORDERING,
DOESN'T RENEW, GOES TO A COMPETITOR]

MY DATA (paste what you have, more is better):
- Recent support tickets or emails, with customer names/IDs and dates:
  [PASTE]
- Order or usage history, ideally 3+ months per customer: [PASTE]
- Anything else: payment failures, unsubscribes, complaint notes: [PASTE]

STEP 1: SIGNAL DEFINITION: Before scoring anyone, list the 5-8 churn
signals that fit MY BUSINESS specifically (a retainer client going quiet
is different from a subscriber skipping a month). For each signal, say
which of my pasted data sources can show it. If my data can't show a
signal, say so instead of pretending.

STEP 2: SCORE THE CUSTOMERS: Go through my data customer by customer.
Flag every customer showing 2 or more signals. For each flagged customer
cite the evidence: the ticket, the date, the order gap, the exact quote.
No customer gets flagged on vibes.

STEP 3: RANK BY RISK AND VALUE: Sort flagged customers into three tiers:
ACT THIS WEEK (multiple strong signals, meaningful revenue), WATCH
(early signals or low spend), and FALSE ALARM CANDIDATES (signals with a
likely innocent explanation, note what it is). Show revenue at risk per
tier if my data includes spend.

STEP 4: SAVE PLAYS: For every ACT THIS WEEK customer, give one concrete
outreach move: who contacts them, through what channel, what they say in
the first two sentences, and by what date. The message must reference
their specific situation, not a generic "we miss you."

RULES: Every flag needs cited evidence from my pasted data. If the data
is too thin to score confidently (under 2 months of history, or fewer
than 10 customers), say so and tell me exactly what to export before
re-running. Never invent customer behavior. One skipped order is a data
point, not a crisis: require at least 2 signals before flagging. End
with the ACT THIS WEEK list restated as a checklist with owners and
dates.
```

## How to use it

1. Export what you have: recent support tickets, order or invoice history, and any cancellation notes. Messy is fine, the prompt works from raw pastes.
2. Tell it how customers pay you and what leaving looks like in your business. A missed month means something different for a lawn service than for a software subscription.
3. Run it and check the evidence behind each flagged customer before acting. You know context the data doesn't, like the client who's on vacation.
4. Work the ACT THIS WEEK list personally. A call or a personal email from the owner beats any automated win-back sequence.
5. Re-run monthly with fresh data and compare: customers who moved from WATCH to ACT are your loudest warning.

## Example

Input: a bookkeeping firm with 34 monthly retainer clients, pasting 3 months of email threads and invoice history.

Sample output excerpt:

ACT THIS WEEK (2 customers, roughly $2,150/month at risk):

1. Meridian Dental: 3 signals. Invoice paid 19 days late in June after 14 months of on-time payments; email response gap grew from same-day to 6+ days; July 12 email asks "can you send over our full file history," a classic pre-departure request. Play: partner calls the office manager by Friday, opens with the file request ("saw you asked for your file history, wanted to make sure you have everything and check how things are going on your end"), and asks directly whether anything's changed.

2. Kowalski Contracting: 2 signals. Monthly reconciliation queries stopped entirely in June after a year of regular questions, and their June 28 ticket says "our new office admin might take some of this in-house."

WATCH (4 customers): includes Bright Path Tutoring, 1 strong signal (asked about pausing service for the summer), likely seasonal, confirm before flagging.

## Pro tip

The single best churn signal in service businesses is the "send me all our files" or "how do I export my data" request. Add a standing rule outside this prompt: any request like that gets a same-day personal call from the owner, no exceptions, because by the time it arrives you're usually their second choice already.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/churn-risk-detector). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
