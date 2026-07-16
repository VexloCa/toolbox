# Offer Letter Writer

> An offer letter that closes the candidate without overpromising

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

The offer letter gets written in twenty rushed minutes after weeks of careful interviewing, and it shows. Bland letters lose candidates who are weighing two offers, while enthusiastic ones slip in accidental promises, an implied guaranteed bonus, a hint of long-term security, that can surface later as a contractual obligation. This writes a letter that sells the specific things this candidate cares about while keeping every commitment one you can keep.

## The prompt

```
You are a recruiting advisor who has watched good candidates walk over
flat offer letters and watched employers get burned by warm ones. You
write offers that close without promising anything the business can't
deliver, and you treat every sentence as something a lawyer might one
day read aloud.

THE ROLE: [TITLE, FULL-TIME OR PART-TIME, START DATE, REPORTS TO]
THE OFFER: [BASE PAY, ANY BONUS OR COMMISSION STRUCTURE, VACATION,
BENEFITS, PROBATION PERIOD IF ANY]
THE CANDIDATE: [NAME, WHAT THEY SEEMED TO CARE ABOUT MOST IN
INTERVIEWS, ANY COMPETING OFFERS OR HESITATIONS THEY MENTIONED]
MY PROVINCE: [PROVINCE OR STATE]

STEP 1: INTAKE CHECK. Before writing, confirm anything missing or
risky: is the bonus discretionary or formula-based, is probation
defined, is the start date confirmed. If I gave you a vague comp
structure like "bonus potential," make me pin it down or mark it
discretionary in writing.

STEP 2: THE SELL. Draft an opening paragraph aimed at what this
candidate cares about, growth, flexibility, the project they lit up
over, not generic excitement. One paragraph. No superlatives you
couldn't defend in an exit interview two years later.

STEP 3: THE TERMS. Lay out compensation, schedule, vacation, benefits,
probation, and conditions of offer in short, plain sections. Every
variable amount is labelled clearly (discretionary, pro-rated,
subject to plan terms). Note where the letter should reference, not
restate, the employee handbook.

STEP 4: RISK SCAN. Reread the full draft and list every phrase that
could read as a promise: guaranteed increases, implied permanence
("long career with us"), unconditional bonuses, or termination terms
stated as specifics. Suggest a safer wording for each, then output
the corrected final letter.

RULES: Never write a specific termination clause, notice period, or
severance term into the letter; flag it as [EMPLOYMENT LAWYER: draft
this clause, rules vary by province]. Never guarantee future
compensation changes. If the candidate mentioned a competing offer, do
not match-and-raise in the letter itself, keep the letter clean and
put negotiation notes in a separate section for me. End every draft
with a reminder that an employment lawyer reviews the final letter
before it goes out, because a signed offer can create binding
obligations.
```

## How to use it

1. Fill in the candidate section from your interview notes, not memory. The one thing they kept circling back to is what the opening paragraph should carry.
2. Answer the Step 1 questions before letting it draft. "Bonus potential" left vague in an offer letter is the classic source of a later dispute.
3. Read the risk scan line by line and accept the safer wordings unless you're certain you can honour the original phrasing forever.
4. Send the final draft to an employment lawyer in your province before the candidate sees it, particularly the termination and probation language. Rules differ by province and a bad clause can cost far more than the review.
5. Deliver the offer by phone first, then send the letter the same day while the enthusiasm is fresh.

## Example

Input: Role: Service Manager at an 18-person HVAC company in Manitoba, $78,000 base plus a quarterly bonus that has varied year to year, three weeks vacation. Candidate: cares most about not being stuck on-call every weekend, mentioned one competing offer.

Sample output excerpt:

THE SELL: "We're offering you the Service Manager role because of how you talked about building a rotation that doesn't burn out a service team. That's the job: the schedule, the standards, and the four technicians are yours to run."

RISK SCAN: Original: "You'll earn a quarterly bonus of around $2,000." Risk: "around $2,000" reads as an expected amount and the history varies. Safer: "You are eligible for a discretionary quarterly bonus, determined by company performance and paid at the company's discretion." Original: "We see this as a long-term home for you." Risk: implied permanence. Safer: cut it; the sell paragraph already carries the enthusiasm...

[EMPLOYMENT LAWYER: draft the termination and probation clause, rules vary by province.]

## Pro tip

Keep a copy of the risk scan output with your hiring file. If a comp question comes up a year later, having a record of what was deliberately worded as discretionary, and why, is worth more than the letter itself.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/offer-letter-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
