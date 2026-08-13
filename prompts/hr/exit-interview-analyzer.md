# Exit Interview Analyzer

> Turn exit interviews into the three fixes that stop the next departure

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Exit interviews at small companies get done, filed, and forgotten, which means you pay the full cost of a departure and skip the one thing it was worth. The raw notes are hard to use on their own: a leaving employee mixes genuine patterns with one-off grievances and polite non-answers, and it's tempting to either dismiss all of it or overcorrect on one person's complaint. This separates the signal from the vent and turns it into three concrete fixes ranked by what would have kept the person.

## The prompt

```
You are an HR analyst who has read hundreds of exit interviews and
knows that the stated reason for leaving is rarely the whole story.
You treat one person's account as one data point, not a verdict, and
you refuse to end an analysis without concrete fixes.

THE DEPARTURE(S): [ROLE, TENURE, VOLUNTARY OR NOT, WHERE THEY WENT IF
KNOWN, FOR EACH PERSON]
MY NOTES OR TRANSCRIPT: [PASTE THE EXIT INTERVIEW NOTES, MESSY IS
FINE. PASTE MULTIPLE EXITS IF YOU HAVE THEM.]
CONTEXT: [TEAM SIZE, ANY OTHER DEPARTURES IN THE LAST 12 MONTHS, ANY
CHANGES AROUND THE TIME THEY DECIDED TO LEAVE]

STEP 1: SORT THE STATEMENTS. Classify everything in my notes into
four buckets, quoting the supporting line for each: (a) fixable
pattern, something structural you could change; (b) one-off incident,
real but not systemic; (c) pull factor, they left toward something
you can't match, like a relocation or a big-company salary band;
(d) polite noise, non-answers given to keep the exit smooth. If a
statement could sit in two buckets, say so and what would settle it.

STEP 2: FIND THE REAL REASON. Distinguish the trigger (the event that
started the job search) from the stated reason (what they said on the
way out). Flag any gap between the two. If I pasted multiple exits,
identify which statements repeat across people, a complaint that
shows up twice is a pattern, not a personality.

STEP 3: THE THREE FIXES. Recommend exactly three changes, ranked by
how likely each would have kept this person, or the next one like
them. For each: the fix, the evidence from the notes, who should own
it, a realistic deadline, and what it costs (money, time, or a
harder conversation). At least one fix must cost little or nothing.

RULES: Quote the notes for every claim; no fix may rest on a reading
the notes don't support. Never recommend a change based on a single
bucket-(b) incident, park those in a "watch list" instead. If the
notes are all polite noise, say the exit interview failed and give me
five questions to ask departing staff next time instead of inventing
findings. Do not name-blame a specific manager in the fixes; describe
the behavior to change.
```

## How to use it

1. Paste the notes raw, including the awkward parts you're inclined to soften. Sanitized notes produce sanitized findings.
2. Add the context section even if it feels irrelevant. A departure two months after a comp freeze reads differently than one out of nowhere.
3. Challenge the bucket sorting where you disagree, you have context the notes don't, then re-run Step 3 with the corrected buckets.
4. Put the three fixes into your task list with the owners and dates attached. A fix without a deadline is a sympathy note.
5. Re-run this with every future exit and keep the outputs in one document. The cross-exit patterns in Step 2 get sharper each time.
6. If a fix involves a specific person's management style, take it to the one-on-one conversation, not a group meeting.

## Example

Input: a voluntary departure, front-desk coordinator at a 9-person physio clinic in Barrie, 2.5 years tenure, went to a hospital admin role. Notes mention pay "was fine," Saturday shifts that were supposed to rotate but didn't, and finding out about the hospital job from a friend.

Sample output excerpt:

SORT: "Saturdays were supposed to rotate but it ended up being me most weeks", bucket (a), fixable pattern, quoted directly. "Pay was fine, honestly", likely bucket (d) polite noise: she left for a hospital pay band, which suggests pay mattered more than stated. "The new booking system launch was stressful", bucket (b), one-off.

REAL REASON: Trigger appears to be the Saturday rotation quietly becoming permanent; the job search predates the booking system launch. Stated reason (career move) is true but was pulled forward by the schedule issue.

THREE FIXES: 1) Publish the weekend rotation two months ahead and track who covered what; owner: clinic manager, deadline: two weeks, cost: an hour a month. 2) Add a schedule-fairness question to every quarterly check-in...

## Pro tip

Run the departing employee's last two performance reviews through this alongside the exit notes. When the reviews say "reliable, no concerns" and the exit notes show a year of schedule resentment, the schedule was only the symptom: your check-ins were failing to surface problems, and that gap will outlast this departure.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/exit-interview-analyzer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
