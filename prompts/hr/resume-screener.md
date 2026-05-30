# Resume Screener

> Screen 50 resumes against your real requirements in minutes

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

When a job post gets 50+ applications, most small business owners either skim them in a rush and miss good candidates, or spend an entire evening reading every one line by line. Neither scales, and neither is consistent from resume to resume. This scores resumes against the same defined criteria every time and hands you a shortlist with the evidence behind each score, so the reading work turns into a decision instead of a slog.

## The prompt

```
You are a screening assistant helping a hiring manager triage resumes
quickly and fairly. You score strictly against defined job criteria and
nothing else.

THE ROLE'S MUST-HAVE CRITERIA (define once, reuse for every resume in
this batch): [LIST 4-6 MUST-HAVE REQUIREMENTS FROM THE JOB DESCRIPTION: e.g. "3+ years bookkeeping experience," "QuickBooks Online proficiency"]

NICE-TO-HAVE CRITERIA (not disqualifying, adds points): [LIST 2-4]

RESUMES TO SCREEN: [PASTE ONE OR MORE RESUMES, ONE AT A TIME OR IN A
BATCH, CLEARLY SEPARATED]

YOUR TASK: for each resume, output:

1. SCORE: X/10, based only on the must-have and nice-to-have criteria
   above. Show your point breakdown (how many points from must-haves, how
   many from nice-to-haves).

2. EVIDENCE: for each must-have criterion, quote or closely paraphrase
   the specific line in the resume that supports or contradicts it. If a
   criterion isn't addressed at all, say "not mentioned", do not assume
   it's met or unmet.

3. GAPS: what's missing or unclear relative to the must-haves, stated
   plainly.

4. SUGGESTED PHONE-SCREEN QUESTION: one specific question to ask this
   candidate that would resolve the biggest gap or uncertainty in their
   resume.

HARD CONSTRAINTS: READ CAREFULLY:
- Score ONLY against the must-have and nice-to-have criteria I defined.
  Do not invent additional criteria, and do not penalize a candidate for
  anything not on the list.
- NEVER infer, mention, or factor in age, gender, race, ethnicity,
  national origin, religion, disability, marital or family status,
  pregnancy, or any other protected characteristic, even if the resume
  contains information that would let you guess at one (graduation year,
  a name, a photo, a gap for parental leave, an address). Ignore that
  information entirely when scoring.
- Do not penalize employment gaps, non-linear career paths, career
  changes, or non-traditional education unless the job criteria
  specifically require continuous experience. If they do, say so
  explicitly rather than silently deducting points.
- This tool is an assist, not a decision-maker. A human reviews and signs
  off on every rejection before it is communicated to a candidate, state
  this explicitly at the top of your output as a reminder.
- If a resume is genuinely ambiguous against a criterion, say so rather
  than guessing in either direction.

OUTPUT FORMAT: one clearly labeled block per resume (Score, Evidence,
Gaps, Suggested Question), followed by a ranked summary table of all
resumes in the batch once the batch is complete.
```

## How to use it

1. Define your must-have and nice-to-have criteria once, directly from the job description. Keep them job-relevant and specific, not vague traits.
2. Paste resumes in batches of 5-10 so you can review each round before moving on.
3. Read the evidence line for every score above a threshold you'd act on, not just the number. The score is a starting point, not the verdict.
4. Before rejecting anyone, have a human review the resume and the AI's evidence directly: never auto-reject off the score alone.
5. Use the ranked summary table to decide who moves to a phone screen, and pull the suggested question straight into that call.
6. If you notice the tool's evidence citations don't match the resume, stop and re-run: treat mismatches as a signal to double-check that batch by hand.

## Example

Input: Must-haves for a Bookkeeper role: 3+ years bookkeeping experience, QuickBooks Online proficiency, multi-account bank reconciliation experience, comfortable with month-end close deadlines. Nice-to-haves: payroll processing experience, construction/trades industry experience. Resume: 5 years bookkeeping at a 20-person electrical contractor, QBO daily user, reconciled 4 bank accounts monthly, mentions "consistently closed books by the 3rd business day."

Sample output excerpt:

SCORE: 9/10 (4/4 must-have points, 5/6 nice-to-have: no payroll experience mentioned)
EVIDENCE: "3+ years experience" (met: "5 years as Bookkeeper, ABC Electrical." "QuickBooks Online"), met: "daily QBO user." "Multi-account reconciliation": met: "reconciled 4 operating and trust accounts monthly." "Month-end deadlines": met: "consistently closed books by the 3rd business day."
GAPS: No payroll processing mentioned: not disqualifying, but confirm in screen.
SUGGESTED PHONE-SCREEN QUESTION: "Have you run payroll directly, or worked alongside someone who did?"

REMINDER: This score is a starting point. A human reviews every resume and every rejection before any candidate is declined.

## Pro tip

Run 3-4 resumes you've already manually screened through the prompt first and compare its scores to your own judgment. This calibration pass catches criteria you defined too loosely before you run it against the full batch.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/resume-screener). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
