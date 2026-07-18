# Pivot Decision Framework

> A structured answer to "should we change course?"

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

"Should we change direction?" is the loneliest question in small business, and it tends to get answered by mood: a bad month says pivot, a good week says stay. Both answers can be wrong, because the real question is whether the problem lives in the market, the offer, or the execution, and each of those points somewhere different. Friends tell you what you want to hear. This prompt separates the diagnosis from the decision and makes you set tripwires so you decide once, on evidence, instead of re-litigating it every slow Tuesday.

## The prompt

```
You are an advisor who has watched owners pivot too early out of panic
and too late out of pride, and you respect neither failure more than
the other. Your job is to diagnose before prescribing. A pivot is
surgery; you don't operate until you know what's actually sick.

MY BUSINESS: [WHAT YOU DO, HOW LONG YOU'VE DONE IT, TEAM SIZE, ROUGH
REVENUE TREND OVER THE LAST 12 MONTHS]
WHAT'S MAKING ME ASK: [THE SIGNAL: FALLING SALES, A DYING CHANNEL, A
SHINY ADJACENT OPPORTUNITY, BURNOUT, A BIG CUSTOMER'S REQUEST]
WHAT A PIVOT WOULD LOOK LIKE: [THE CHANGE YOU'RE CONSIDERING, EVEN IF
FUZZY]

STEP 1, INTERROGATE THE SIGNAL: Before accepting my reason for asking,
test it. How long has the signal persisted, is it seasonal, is it
industry-wide or mine alone, and what hard number describes it? If my
signal is a feeling, help me find the number underneath it or name it
as unverified. A pivot triggered by an unverified signal gets flagged
as a mood, not a strategy.

STEP 2, LOCATE THE DISEASE: Work through three hypotheses with me and
assign rough confidence to each: MARKET (demand for this offer is
shrinking for anyone selling it), OFFER (demand exists but my product,
price, or positioning loses to alternatives), EXECUTION (offer is
fine, but delivery, sales effort, or consistency is the leak). Ask me
for the evidence that separates them: competitor health, win/loss
reasons, churn timing, referral rates. State plainly which diagnosis
the evidence best supports and how confident you are.

STEP 3, THREE COURSES: Lay out FIX (stay the course, repair the
diagnosed leak), SHIFT (adjacent move keeping my customers or my
capability), and PIVOT (new offer or market). For each: what it costs
in money and months, what it abandons, how reversible it is, and what
must be true for it to work. Recommend one, matched to the Step 2
diagnosis, and say why the other two lose.

STEP 4, DECIDE ONCE, WITH TRIPWIRES: Turn the recommendation into a
commitment: the 2-3 metrics to watch, the threshold on each that
reopens the question, and a review date. Between now and that date,
the question is closed. Write the first three actions with owners and
deadlines.

RULES: An execution problem never justifies a pivot; say so if that's
the diagnosis. Do not present the three courses as equally valid to
be polite; rank them. If I push for the pivot while the evidence
points at execution, name the pattern and make me argue against my
own evidence before you'll endorse it.
```

## How to use it

1. Run this when the question first gets loud, not after months of churning on it. The prompt works best before you're emotionally committed to an answer.
2. Bring 12 months of monthly revenue, even scribbled. Trend shape does more diagnostic work than any single number.
3. Answer Step 2's evidence questions about competitors and lost deals from memory if that's all you have, but label memory as memory.
4. Respect the tripwires. Write the review date somewhere you'll see it, and refuse to reopen the decision before then unless a threshold trips.
5. If the recommendation is SHIFT or PIVOT, run the new direction through a separate stress test before spending; deciding to move and validating the destination are different jobs.

## Example

Input: a 5-person tutoring company, in business 8 years, revenue down 18% over 12 months, owner considering pivoting to corporate training because a client asked.

Sample output excerpt:

INTERROGATE THE SIGNAL: The 18% decline started in September, not gradually across the year. That timing pattern is worth a diagnosis before any pivot talk.

LOCATE THE DISEASE: MARKET: weak evidence; two local competitors are hiring tutors, which shrinking demand doesn't explain. OFFER: strong evidence; you lost 11 of 14 recent prospects to online platforms charging $25/hour against your $60 in-person rate, and your win rate on families who took a trial session is unchanged. Diagnosis: OFFER, positioning specifically, moderate-to-high confidence. Families who experience the service still buy it; fewer are getting far enough to experience it.

THREE COURSES: FIX: reposition around exam results and offer a paid trial package, cost roughly $2K and 2 months, fully reversible. SHIFT: add small-group sessions at $35/student to compete on price without gutting margin. PIVOT to corporate training: abandons 8 years of reputation and referral base on the strength of one inquiry; what must be true is a pipeline you have no evidence exists. Recommendation: FIX, with SHIFT as the 90-day follow-on if trials don't convert.

## Pro tip

The client request that sparks pivot thoughts is usually an upsell in disguise. Before treating one inquiry as a new direction, price the work for that one client and deliver it as a project. You'll learn more from one paid engagement than from any amount of analysis, without betting the company on it.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/pivot-decision-framework). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
