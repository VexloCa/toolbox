# Interview Question Bank

> Build role-specific interviews that actually predict performance

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business interviews are improvised. The same three generic questions, asked in whatever order comes to mind, with no way to compare candidates against each other afterward. That makes hiring decisions come down to gut feel and who interviewed best, not who can actually do the job. This builds a structured question set tied to the real role so every interview produces comparable, usable evidence.

## The prompt

```
You are a hiring consultant who designs structured interviews for small
businesses that don't have a dedicated recruiting team. You build
interviews that predict on-the-job performance, not ones that reward
smooth talkers.

THE ROLE: [PASTE THE JOB DESCRIPTION, OR LIST TITLE + KEY
RESPONSIBILITIES + MUST-HAVE REQUIREMENTS]

INTERVIEW LENGTH: [X MINUTES], INTERVIEW STAGE: [PHONE SCREEN /
FIRST ROUND / FINAL ROUND]

YOUR TASK: build a complete interview question bank:

1. BEHAVIORAL QUESTIONS (4-5): past-experience questions ("tell me about
   a time...") that map directly to the must-have requirements. For each,
   include:
   - The question
   - WHAT A STRONG ANSWER INCLUDES (2-3 concrete signals to listen for)
   - RED FLAGS (1-2 answers or patterns that suggest a mismatch)

2. SITUATIONAL QUESTIONS (3-4): hypothetical, job-realistic scenarios
   ("what would you do if...") drawn from likely real situations in this
   role. Same format: question, strong-answer signals, red flags.

3. SKILL/TECHNICAL QUESTIONS (2-4): questions or short exercises that
   directly test a must-have skill, not a proxy for it. Same format.

4. ONE CULTURE-FIT QUESTION that assesses working style without asking
   anything that functions as a personality test or a disguised
   protected-characteristic question (e.g. never ask about age, family
   plans, health, religion, or anything not job-related).

5. A SCORING SHEET: a simple table candidates can be rated on (1-5 per
   question or per competency) so interviewers can compare candidates
   side by side after the interview.

HARD CONSTRAINT: CONSISTENCY: These are the same core questions every
interviewer must ask every candidate for this role. Note this explicitly
in your output: interviewers may ask candidate-specific follow-ups, but
the core question set must not change person to person, that's what
makes candidates comparable and keeps the process fair.

OTHER RULES:
- Every question must trace back to something in the job description, no generic "where do you see yourself in 5 years" filler.
- Do not include any question that touches age, marital or family status,
  disability, religion, national origin, or other legally protected
  characteristics, even indirectly (e.g. "do you have reliable
  childcare?" is not allowed).
- Keep total interview time inside my stated length, accounting for
  candidate questions at the end.
- Flag any requirement in the job description that's too vague to write a
  good question for, and suggest what detail I should clarify first.

OUTPUT FORMAT: numbered sections as above, followed by the scoring sheet
as a markdown table, ready to print or paste into an ATS.
```

## How to use it

1. Paste the actual job description or a solid summary of the role: the sharper the input, the more targeted the questions.
2. Set the real interview length and stage so the question count fits the time you have.
3. Generate the bank once per role, then use the identical core questions for every candidate interviewed for that role. This is what makes scores comparable.
4. Print or share the scoring sheet with every interviewer before the interview, not after.
5. Fill in the scoring sheet immediately after each interview while the answers are fresh, and compare across candidates only using the same question set.
6. Regenerate the bank if the role's core requirements change materially. Don't keep reusing questions for a role that has evolved.

## Example

Input: Job description for a Bookkeeper at a 15-person contracting company. Must-haves: 3+ years bookkeeping experience, QuickBooks Online proficiency, experience reconciling multiple bank accounts, comfortable with month-end close under deadline pressure. 45-minute first-round interview.

Sample output excerpt:

BEHAVIORAL Q1: "Tell me about a time your books didn't reconcile at month-end and you couldn't immediately find why. Walk me through what you did."
- Strong answer includes: a systematic troubleshooting process, checking specific likely culprits first, escalating appropriately if stuck.
- Red flags: blames the software or a coworker with no ownership of the process; can't describe a specific real example.

SCORING SHEET: | Competency | Candidate rating (1-5) | Notes | ...

## Pro tip

Have every interviewer independently score the candidate on the scoring sheet before comparing notes as a group: discussing impressions first anchors everyone to whoever speaks loudest and defeats the purpose of a structured interview.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/interview-question-bank). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
