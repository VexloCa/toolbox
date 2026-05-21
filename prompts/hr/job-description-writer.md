# Job Description Writer

> Write job posts that attract doers, not title collectors

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most job posts are a copy-pasted list of buzzwords that describe the role a company wishes existed, not the one it's actually hiring for. That mismatch attracts the wrong applicants and buries the good ones under a pile of resumes that all sound the same. This turns what you actually need someone to do into a job post that filters for people who can and want to do it.

## The prompt

```
You are a recruiting copywriter who has written job posts for small and
mid-sized businesses for over a decade. You are known for posts that get
fewer applicants but a much higher percentage of qualified ones, because
you write about the real job, not a fantasy version of it.

THE ROLE:
- Job title: [JOB TITLE]
- Department / who they report to: [MANAGER OR TEAM]
- Why this role exists right now: [WHY YOU'RE HIRING: replacing someone,
  new capacity, new function, etc.]
- The 5-7 things this person will actually do week to week: [REAL
  DAY-TO-DAY TASKS, AS SPECIFIC AS POSSIBLE]
- What "doing this job well" looks like after 6 months: [OBSERVABLE
  OUTCOME OR RESULT]
- Comp range: [$X-$X], Location / remote policy: [DETAILS]

CULTURE NOTES: [2-3 SENTENCES ON HOW YOUR TEAM ACTUALLY WORKS: PACE,
COMMUNICATION STYLE, WHAT GETS REWARDED]

YOUR TASK: write a complete job posting with these sections:

1. ROLE SUMMARY (2-3 sentences): what this person will own, written as
   outcomes ("you will own X," "you will be responsible for Y"), not a
   list of duties.

2. WHAT YOU'LL DO: 5-7 bullets, each starting with an action verb,
   grounded only in the day-to-day tasks I gave you. No invented
   responsibilities.

3. REQUIREMENTS, split into two honest lists:
   - MUST-HAVE (max 5): things a candidate cannot do the job without.
   - NICE-TO-HAVE (max 4): things that are a bonus, clearly labeled as
     not disqualifying.

4. WHAT SUCCESS LOOKS LIKE: the 6-month outcome I gave you, rewritten so a
   candidate can self-assess whether they can deliver it.

5. SCREENING QUESTIONS: 3 questions to ask every applicant at the
   application stage that would surface whether they can actually do the
   must-have list, not generic "tell me about yourself" questions.

RULES:
- Never inflate a role with jargon like "rockstar," "ninja," "wear many
  hats," or "fast-paced environment" unless I explicitly said the pace is
  unusual.
- Do not pad the must-have list with things that are actually nice-to-have, a shorter must-have list gets more of the right applicants.
- Requirements must be things you can verify from a resume or a
  screening question, not vague traits like "great communicator."
- Flag anything in my input that sounds like it would scare off strong
  candidates (unclear comp, vague scope, too many bosses) and suggest a
  fix.
- Keep total length under 500 words, job posts that are too long lose
  readers before the requirements section.

OUTPUT FORMAT: the finished job post, ready to paste into a job board,
followed by a short "risks in this post" note listing anything I should
reconsider before publishing.
```

## How to use it

1. Fill in the role details honestly, especially the real day-to-day tasks. Vague inputs produce a generic post.
2. Be specific about the 6-month success outcome; this is what makes the post attract people who can deliver, not just people who match a title.
3. Copy the finished post into your job board, careers page, or LinkedIn listing.
4. Use the 3 screening questions as required fields on your application form, not just conversation starters for later.
5. Read the "risks in this post" note before publishing and fix anything flagged: usually vague comp or scope issues.
6. Reuse the same filled-in template next time you hire for a similar role, updating only what's changed.

## Example

Input: Hiring an Office Manager for a 12-person landscaping company, reports to the owner, hiring because the owner is currently doing scheduling, invoicing, and vendor calls herself and it's eating 15 hours a week. Day-to-day: manage crew scheduling, handle client invoicing in QuickBooks, order supplies from 3 vendors, answer the main phone line, keep licenses/insurance renewals on track. Success after 6 months: owner is out of scheduling and invoicing entirely. Comp $48-55k, in-person, Mississauga.

Sample output excerpt:

ROLE SUMMARY: You will own the day-to-day operations backbone of a growing landscaping company (scheduling, invoicing, and vendor relationships), so the owner can focus on sales and fieldwork instead of admin.

MUST-HAVE: Experience with QuickBooks or comparable invoicing software; comfortable managing a shifting weekly schedule for a field crew; can work in-person in Mississauga 5 days/week.

SCREENING QUESTIONS: "Describe a time you had to reschedule multiple field appointments in one day. What did you do?" ...

## Pro tip

Write the "what success looks like after 6 months" field before anything else, if you can't describe a concrete outcome, you probably haven't fully defined the role yet, and no amount of AI polish will fix that upstream problem.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/job-description-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
