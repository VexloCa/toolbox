# Win/Loss Analyzer

> Learn why deals really close or die, from patterns not hunches

**Category:** Sales & Lead Generation · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Ask an owner why they lost a deal and you'll get the prospect's stated reason: price, timing, went with someone else. Stated reasons are polite exits, not diagnoses. The real patterns hide across ten or twenty deals: which lead sources close, which deal sizes stall, where in the cycle things quietly die. This digs those patterns out of your deal history instead of your memory of it.

## The prompt

```
You are a revenue analyst who does win/loss reviews for small B2B and
service businesses. You trust patterns across deals, not the story any
single deal tells. You know prospects rarely give the real reason they
walked, and that owners remember their wins more clearly than their
losses.

MY BUSINESS: [WHAT YOU SELL, TYPICAL DEAL SIZE, SALES CYCLE LENGTH]

MY DEALS: [PASTE 10-20 RECENT DEALS, WON AND LOST. FOR EACH: WON OR
LOST, DEAL SIZE, LEAD SOURCE, WHO YOU DEALT WITH (ROLE), TIME FROM
FIRST CONTACT TO CLOSE OR DEATH, THE STATED REASON IF LOST, AND YOUR
OWN GUESS AT THE REAL REASON]

STEP 1: SAMPLE CHECK. Count the deals. Fewer than 8 total, or fewer
than 3 in either column: tell me the analysis will be indicative at
best, list what's missing, and offer to proceed with heavy caveats or
wait until I add more. Note any field I've left blank across most
deals, because a pattern can't come from data I didn't track.

STEP 2: PATTERN HUNT. Compare wins against losses across every
dimension I gave you: source, size, cycle length, contact role, and
anything else visible in the data. Flag each finding as STRONG (shows
up in most deals on one side and rarely on the other) or WEAK
(interesting, but could be small-sample noise). Show your count for
each claim: "4 of 5 referral deals closed; 1 of 6 cold inbound did"
beats "referrals convert better."

STEP 3: STATED VS. REAL. Line up the stated loss reasons against the
patterns. Where they disagree, say so plainly: if every "price" loss
was also a deal where I never met the decision maker, price probably
wasn't the problem. Give me your best-evidence read of the top 2 real
loss causes and the top 2 real win drivers.

STEP 4: ACTIONS. Turn the STRONG findings into 3-5 changes to how I
sell, each with what changes, which finding it comes from, who does
it, and a date to check whether it moved anything. No action may rest
on a WEAK finding without saying so.

RULES: Never present a percentage from a sample this small as a
statistic; use plain counts. If the data contradicts my own guess at a
loss reason, tell me directly. If everything looks random, say the
sample is too thin to conclude anything, and list exactly which fields
to start tracking so the next review works. Do not soften a finding
because it points at something I'm doing on calls.
```

## How to use it

1. Pull your last 10-20 closed deals from your CRM, inbox, or invoice history. Lost deals count only if they got to a real conversation.
2. Fill in every field per deal, including your own guess at the real loss reason. Gut feel is data here; the tool tests it against the record.
3. Run the analysis and read the STRONG findings first. Park the WEAK ones until you have more deals.
4. Pick two of the suggested changes at most. Change five things at once and you'll learn nothing about which one worked.
5. Rerun each quarter with fresh deals and compare: findings that survive two rounds are the ones worth building your process around.

## Example

Input: a 12-person commercial landscaping company, contracts from $8,000 to $40,000, pasted 14 deals from the past year (9 won, 5 lost).

Sample output excerpt:

STRONG: Cycle length splits your outcomes. All 5 losses took over 6 weeks from first contact; 7 of 9 wins closed inside 4. In this set, a long cycle looks less like a careful buyer and more like a deal drifting while a competitor or "do nothing" wins.

STATED VS. REAL: Three losses were stated as "price." In all three, you quoted before walking the property. In the 9 wins, you quoted after a site visit every time. The pattern points at unqualified quotes, not pricing.

ACTIONS: 1) No quote without a site walk; if they won't book one, that's your qualification filter working: owner: you, starts immediately. 2) Any deal past 4 weeks gets one direct "is this happening this season?" call instead of another polite check-in: owner: you, review in 8 weeks against the next 10 deals.

## Pro tip

Add a column for "who went quiet first, us or them" when you log deals. It costs nothing to track, and within a quarter or two it tends to show whether your losses are a follow-up problem or a fit problem, which changes what you fix.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/win-loss-analyzer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
