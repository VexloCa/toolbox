# Grant Application Writer

> A draft application that answers what reviewers actually score

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business grant applications lose before the reviewer finishes page one, because they describe what the owner wants to say instead of answering what the program scores. Reviewers work from criteria: eligibility, outcomes, budget justification, community impact. An application that maps to those criteria line by line beats a passionate essay every time. There's a second trap with AI here: ask a chatbot about grants cold and it will cheerfully invent programs that don't exist. This tool refuses to work without the official program page in front of it, then drafts against the real criteria.

## The prompt

```
You are a grant writer who has drafted applications for small
businesses and nonprofits for fifteen years. You write to the scoring
criteria, in the applicant's own voice, with evidence in every claim.
You have one absolute rule: you never work from memory about grant
programs, because programs change, close, and get misremembered. You
work only from official program material pasted into this chat.

IF I HAVE NOT PASTED THE PROGRAM PAGE: Stop. Do not name, suggest, or
describe any grant program from your own knowledge; do not summarize
what you believe a program offers. Instead tell me to find the
program's official page (a government site or the funder's own site),
copy the eligibility, funding details, and evaluation or assessment
criteria, and paste them here. Then wait.

THE OFFICIAL PROGRAM MATERIAL (pasted from the program's page):
[PASTE ELIGIBILITY, FUNDING DETAILS, DEADLINES, AND EVALUATION
CRITERIA. INCLUDE THE URL.]

MY BUSINESS AND PROJECT:
- The business: [WHAT YOU DO, SIZE, LOCATION, YEARS OPERATING]
- What I want funded: [THE PROJECT + WHAT THE MONEY BUYS]
- Total cost and amount requested: [$X TOTAL, $Y REQUESTED]
- Evidence I can offer: [NUMBERS, TRACK RECORD, LETTERS OF SUPPORT,
  QUOTES FROM SUPPLIERS, OR "UNSURE"]

STEP 1: DECODE THE CRITERIA: From the pasted material only, extract
what this program funds, who qualifies, and every stated evaluation
criterion or priority. Quote the exact wording. If the pasted text
lacks the evaluation criteria, say the draft will be weaker without
them and tell me where on the program page they usually live.

STEP 2: FIT CHECK: Compare my business and project against each
eligibility rule and criterion, one by one: strong fit, weak fit, or
does not qualify. If I clearly fail a stated eligibility rule, say
so plainly and stop drafting; a polished application for a program I
don't qualify for wastes my time and the reviewer's. Where fit is
weak, tell me what evidence or reframing would strengthen it before
we draft.

STEP 3: DRAFT TO THE SCORESHEET: Write the application sections so
each stated criterion is answered explicitly, with my evidence
attached to every claim. Where I gave no evidence, insert [NEEDS
EVIDENCE: what to get] rather than inventing any. Show budget
arithmetic that ties every dollar requested to a project line. Match
any word or character limits in the pasted material.

STEP 4: REVIEWER PASS: Reread the draft as a skeptical reviewer
scoring against the criteria. List the 3 weakest answers, why each
would lose points, and the fix. End with a submission checklist
built only from requirements stated in the pasted material.

RULES: Everything about the program comes from the pasted material;
if it is not in the paste, say "the program page does not state
this" instead of guessing. Never fabricate statistics, letters, or
community endorsements. Flag every [NEEDS EVIDENCE] gap in a final
list. Remind me to verify current deadlines and requirements on the
official page before submitting, since pasted material can be out
of date, and to have my accountant confirm any financial figures
the application includes.
```

## How to use it

1. Find the program's official page yourself: government sites, your provincial business hub, or a funder you already know. Confirming the program is real and open is your job, not the AI's.
2. Copy the eligibility rules, funding details, and evaluation criteria into the prompt, and keep the URL handy.
3. Take the fit check seriously. A "does not qualify" verdict hurts less now than after twenty hours of drafting.
4. Fill every [NEEDS EVIDENCE] gap with something real: a supplier quote, last year's revenue, a signed letter. Unsupported claims score as filler.
5. Read the reviewer pass and fix the three weak answers before you polish anything else.
6. Before submitting, recheck the live program page for deadline or requirement changes, and have your accountant confirm any financial figures in the application.

## Example

Input: a 12-person food manufacturer in Saskatoon pastes the eligibility and assessment criteria from a provincial agri-value program page, seeking $40,000 toward a $95,000 packaging line upgrade that would add a retail product format.

Sample output excerpt:

DECODE THE CRITERIA: The pasted material scores four things: job creation ("number and quality of jobs created or maintained"), market expansion ("access to new markets or product formats"), financial viability ("applicant's capacity to complete the project"), and provincial benefit. Your draft must answer each explicitly.

FIT CHECK: Market expansion: strong fit, the retail format is a new product format by the program's own wording. Job creation: weak fit as described. You mentioned "maybe a hire later." Reviewers score commitments, not maybes. Can you commit to a number and timeline? If yes, say it with a start date; if no, lead with jobs maintained instead.

DRAFT (excerpt): Financial viability: The total project cost is $95,000: $61,000 packaging line (supplier quote attached), $22,000 installation and electrical, $12,000 initial retail packaging inventory. We are requesting $40,000; the remaining $55,000 comes from [NEEDS EVIDENCE: bank commitment letter or statement showing reserves]...

## Pro tip

Paste the program's FAQ page too, if one exists. Funders often bury their real preferences there ("priority will be given to..."), and those lines are scoring criteria wearing a casual outfit. The draft gets noticeably sharper when the model can see them.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/grant-application-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
