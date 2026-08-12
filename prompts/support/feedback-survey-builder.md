# Customer Feedback Survey Builder

> Surveys people finish, with answers you can act on

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most small business surveys die two deaths: customers abandon them at question 9, and the responses that do come in ("service was fine") change nothing. The usual mistake is starting from "what would we like to know" instead of "what decision are we trying to make," which produces 15 curiosity questions and zero usable answers. A survey worth sending is short, tied to one decision, and comes with a plan for reading the results before you send it.

## The prompt

```
You are a survey researcher who has watched completion rates collapse
at question 8 and seen a hundred "how satisfied are you" surveys change
nothing. You build short surveys where every question earns its place
by feeding a named decision, and you kill questions that don't.

MY BUSINESS: [WHAT YOU SELL, ROUGH CUSTOMER COUNT]
THE DECISION THIS SURVEY INFORMS: [BE SPECIFIC: "whether to drop the
Saturday time slot," "which of two service tiers to build," "why
repeat orders dropped." "GENERAL FEEDBACK" WILL BE REJECTED]
WHO GETS IT: [ALL CUSTOMERS / RECENT BUYERS / CANCELLED CUSTOMERS / ...]
HOW IT'S SENT: [EMAIL / SMS / PRINTED CARD / LINK AFTER PURCHASE]

STEP 1: DECISION CHECK: If my stated decision is vague, push back and
make me sharpen it into something with at least two possible outcomes
("if answers say X we do A, if Y we do B"). Then state, in one line
each, the 2-4 things we must learn to make that decision. Nothing else
gets a question.

STEP 2: DRAFT THE SURVEY: Maximum 7 questions, under 3 minutes. Mix:
mostly specific behavior and preference questions ("which of these did
you use last month"), at most one rating scale, exactly one open-text
question near the end ("what almost stopped you from buying?" beats
"any other comments?"). For each question, name which STEP 1 learning
it feeds. Write the invitation message too: one honest sentence on why
you're asking, how long it takes, and what you'll do with answers.

STEP 3: BIAS AND FATIGUE PASS: Re-read every question and flag leading
wording ("how much did you enjoy..."), double-barreled questions
("was delivery fast and well-packaged?"), and options that don't cover
real cases (no "I didn't use this" choice). Fix each one and show the
before/after.

STEP 4: READING PLAN: Before I send anything, tell me how to read the
results: what response count makes each answer trustworthy for my
customer base size, which result triggers which action from STEP 1,
and one trap to avoid (e.g. angry customers reply more, so open-text
skews negative).

RULES: Never exceed 7 questions. Reject any question that feeds no
decision, even if it's interesting. Ask nothing I could find in my own
records (order history, purchase date). With a small customer base,
say plainly that 15 responses is a set of conversations, not a
statistic, and that patterns are directional, not proof. End with the
final survey text, the invitation, and the reading plan as three
copy-ready blocks.
```

## How to use it

1. Name the decision first. If you can't finish the sentence "depending on the answers, we will either A or B," you're not ready to survey, you're browsing.
2. Run the prompt and let it fight you on question count. Every question you cut raises the odds the rest get answered.
3. Send it through the channel your customers already use. A 5-question link in an SMS beats a beautiful 12-question form in an unopened email.
4. Wait for the response window to close before reading anything. Early responses skew toward your most opinionated customers.
5. Apply the reading plan, make the call it was built for, then tell customers what changed. That one follow-up email is why they'll answer your next survey.

## Example

Input: a 4-chair salon with about 300 active clients, deciding whether to extend Thursday evening hours or add Sunday openings, sent by SMS after checkout.

Sample output excerpt:

Q2: In the past 3 months, have you ever wanted an appointment but found no time that worked? (Yes / No / Don't recall). Feeds learning 1: is availability an issue at all.

Q3: If we opened ONE of these, which would you book? (Thursday until 9pm / Sunday 10am-4pm / Neither, current hours work for me). Feeds learning 2: the actual decision.

Bias pass example: original Q4 read "Would you love more evening availability?" Leading, and "love" invites polite yes. Rewritten: "When do you usually try to book?" with time-band options.

Reading plan: with roughly 300 clients, treat 60+ responses as solid, 25-59 as directional, and under 25 as anecdote. Decision trigger: if "Neither" wins or availability isn't a pain in Q2, extend nothing and revisit in 6 months. Trap: clients who already fit your hours are overrepresented among recent checkouts, so weight the "wanted but couldn't book" yeses seriously even if they're a minority.

## Pro tip

Steal your open-text question from the churn side: ask lapsed customers "what almost kept you coming back?" separately from active ones. Two audiences, same 5 questions, compared side by side, tells you more than any single survey, and it's still under 3 minutes each.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/feedback-survey-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
