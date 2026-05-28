# Performance Review Helper

> Turn scattered observations into fair, specific reviews

**Category:** HR & Hiring · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Performance reviews at small businesses usually get written the night before they're due, from memory, which means recent events dominate and the actual pattern of someone's work gets lost. Vague feedback like "needs to be more proactive" doesn't help anyone improve and doesn't hold up if a decision is ever questioned. This turns your rough notes and specific examples from the review period into a structured, evidence-backed draft.

## The prompt

```
You are a manager coach who helps small business leaders write clear,
fair, specific performance reviews. You believe every piece of feedback
needs a real example behind it, and you push back when it doesn't.

THE EMPLOYEE:
- Role: [ROLE/TITLE]
- Review period: [DATES]
- Their key goals or responsibilities this period: [FROM JOB
  DESCRIPTION OR LAST REVIEW'S GOALS]

MY RAW NOTES (paste everything you have, messy is fine): [PASTE ROUGH
NOTES, SPECIFIC EXAMPLES, SLACK MESSAGES, PROJECT OUTCOMES, DATES,
ANYTHING RELEVANT FROM THE REVIEW PERIOD, GOOD AND BAD]

YOUR TASK: build a structured review draft:

1. STRENGTHS (3-5): each strength paired with a specific example from my
   notes, what happened, when, and the impact. No generic praise
   ("great attitude") without a concrete instance behind it.

2. GROWTH AREAS (2-4): framed constructively, the gap between current
   behavior and what's needed, paired with a specific example, and
   phrased as something actionable rather than a character judgment
   ("missed the March deadline on the Hendricks project because status
   wasn't communicated until the day before", not "poor time
   management").

3. GOALS FOR NEXT PERIOD: 2-4 goals directly tied to the growth areas
   above, each with a way to measure whether it was met.

4. OVERALL SUMMARY: 2-3 sentences suitable to read aloud to open the
   review conversation.

HARD CONSTRAINT: If I give you a strength or growth area with no specific
example or evidence behind it, do not write it into the review. Instead,
list it separately under "NEEDS AN EXAMPLE BEFORE THIS GOES IN THE
REVIEW" and tell me what kind of example would support it. Vague
criticism or vague praise without evidence does not belong in a
performance review, it's not actionable and it's not fair to the
employee.

OTHER RULES:
- Do not infer motive ("they don't care about the team"), describe
  behavior and impact only.
- Do not compare this employee to another employee by name.
- Keep language plain and direct, no corporate euphemism that obscures
  what actually needs to change.
- If my notes are almost entirely negative or almost entirely positive,
  say so and ask if that reflects the actual period or just what I
  happened to write down.

OUTPUT FORMAT: the four sections above, plus (if applicable) the "needs
an example" list, ready to paste into a review document or HR system.
```

## How to use it

1. Keep a running note through the review period (even a single messy doc) so you have real examples instead of relying on memory the night before.
2. Paste everything you have, unedited. Let the AI organize it rather than pre-filtering it yourself.
3. Review the "needs an example" list first; if you can recall a specific instance, add it and re-run before finalizing.
4. Read the growth areas out loud before the meeting, if any still sound like a character judgment rather than a behavior, rewrite that line yourself.
5. Use the overall summary to open the conversation, then walk through strengths before growth areas.
6. Save the finished goals section as the starting note for next period's review.

## Example

Input: Notes on a Sales Rep: "closed the Kavanagh account in March, biggest deal of the quarter, handled it mostly solo. Missed 2 of 4 weekly pipeline update meetings without notice. Team said he's been really helpful mentoring the new hire, saw him walk her through call scripts twice. Follow-up on the Bell account slipped for 3 weeks, lost some momentum, though we still closed it."

Sample output excerpt:

STRENGTHS: Closed the Kavanagh account in March (the largest deal of the quarter), managed largely independently. Example: [specific to the deal]. Proactively mentored the new hire, observed walking her through call scripts on at least two occasions.

GROWTH AREAS: Missed 2 of 4 weekly pipeline meetings without advance notice, which limits the team's visibility into deal status. Follow-up on the Bell account slipped for roughly 3 weeks before re-engaging, which delayed momentum even though the deal ultimately closed.

NEEDS AN EXAMPLE BEFORE THIS GOES IN: none: all notes included specific instances.

## Pro tip

When a growth area keeps recurring review after review with no real change, that's usually a signal to have the direct conversation now rather than writing it into a review again. Pair this tool with the tough-conversation-scripts prompt if a pattern like that shows up.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/performance-review-helper). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
