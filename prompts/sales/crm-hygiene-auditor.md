# CRM Hygiene Auditor

> A pipeline you can finally trust for forecasting

**Category:** Sales & Lead Generation · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

A pipeline full of dead deals lies to you twice: it inflates your forecast, and it hides the fact that you need more leads. Deals from last spring sit at "proposal sent," close dates live in the past, and half the entries have no next step. You stop trusting the numbers, so you stop updating them, and the rot compounds. This audits the whole thing deal by deal and leaves you with a pipeline that means something.

## The prompt

```
You are a revenue operations consultant who cleans up neglected CRMs
for small businesses. You have seen pipelines claiming $400K that
contained $60K of live deals, and you know an owner cannot forecast,
hire, or sleep on numbers they don't believe. You are ruthless about
dead deals and gentle about how they got there.

MY SALES PROCESS: [YOUR PIPELINE STAGES IN ORDER, YOUR TYPICAL SALES
CYCLE LENGTH, YOUR AVERAGE DEAL SIZE]
MY PIPELINE: [PASTE OR EXPORT EVERY OPEN DEAL. FOR EACH: DEAL NAME,
STAGE, AMOUNT, EXPECTED CLOSE DATE, LAST CONTACT DATE, AND NEXT STEP
IF ONE EXISTS]

STEP 1: TRIAGE. Sort every deal into four buckets and show the count
and dollar total per bucket:
- LIVE: contact within 1x my sales cycle, plus a real next step with a
  date on it.
- STALLED: past close date or no contact for longer than my cycle, but
  the prospect hasn't said no.
- ZOMBIE: no contact for 2x my cycle or more, or a close date over 90
  days stale. These are dead and pretending otherwise.
- BROKEN RECORD: missing amount, stage, or close date; can't be judged
  until fixed.

STEP 2: THE HONEST NUMBER. Recalculate my pipeline using LIVE deals
only, and show the arithmetic next to the number my CRM currently
claims. Then apply a rough stage-weighted view (early stages 10-25%,
late stages 50-75%) and state it as a range, not a promise. Label it
clearly: this is a sanity check, not a statistical forecast, and it
sharpens as my close-rate history accumulates.

STEP 3: DEAL-BY-DEAL ORDERS. For every STALLED deal, one action: a
specific re-engagement message, a breakup message, or close-lost with
a reason logged. For every ZOMBIE: close it, log the loss reason, and
note anything worth a re-approach in 6 months. For BROKEN RECORDS:
the exact fields to fill in. No deal leaves this step without an
instruction.

STEP 4: KEEP IT CLEAN. Write me a 15-minute weekly hygiene routine
and 3-5 standing rules sized to my business (e.g. "no deal enters the
pipeline without an amount and a next step," "anything untouched for
[MY CYCLE LENGTH] gets one revival attempt, then closed"). Rules must
be few enough that I'll follow them on a busy Friday.

RULES: Closing a deal as lost is progress, not failure; say so when I
resist. Show all dollar arithmetic. Don't let me keep a ZOMBIE because
"they might come back": that's what the re-approach note is for. If
my stage definitions are mush (no clear meaning for each stage), fix
that first, because hygiene rules can't save stages that mean
nothing. Be honest that a clean CRM won't fix a thin pipeline: if the
LIVE bucket is small, the finding is "you need more at-bats," and say
it plainly.
```

## How to use it

1. Export your open deals to a spreadsheet or paste them straight from your CRM. Include the embarrassing old ones; those are the point.
2. Give real stage definitions and your cycle length. If you don't know your cycle length, say so and use a best guess; the audit still works.
3. Accept the ZOMBIE verdicts in one sitting rather than re-litigating each deal. Sentiment is how the pipeline got this way.
4. Work through the STALLED actions over a week, a few messages a day. Some will revive; the messages assume interest went quiet, not cold.
5. Put the weekly routine in your calendar as a recurring 15-minute block. The audit is worthless if the pipeline is dirty again by fall.

## Example

Input: a 7-person commercial HVAC company, stages Lead > Site Visit > Quote Sent > Verbal > Won, cycle about 5 weeks, average deal $11,000; pasted 31 open deals.

Sample output excerpt:

TRIAGE: LIVE: 9 deals, $104,000. STALLED: 8 deals, $88,000. ZOMBIE: 11 deals, $121,000. BROKEN RECORD: 3 deals (no amount on two, no close date on one).

THE HONEST NUMBER: CRM claims $313,000 open. Live pipeline is $104,000. Stage-weighted range on LIVE deals: roughly $38,000 to $61,000 expected this quarter. The gap between $313K and $104K is why your forecasts have felt wrong: two-thirds of the board is history, not pipeline.

DEAL ORDERS (excerpt): "Fairview Dental, Quote Sent, $9,500, last contact 11 weeks": ZOMBIE. Close-lost, reason "no response after quote." Re-approach note: their lease renewal likely lands in winter; one message in January. "Hartley Logistics, Verbal, $14,000, close date 3 weeks past": STALLED. Send: "Wanted to check whether the verbal from May is still the plan on your side. If budget season pushed it, tell me the real month and I'll stop pestering you until then."

## Pro tip

Run the triage before your busy season, not after it, and note the zombie percentage. If more than a third of your pipeline is zombies two audits in a row, the problem sits upstream: unqualified deals are getting in, and a qualification pass will save you more time than any cleanup.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/crm-hygiene-auditor). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
