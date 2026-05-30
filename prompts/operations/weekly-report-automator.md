# Weekly Report Automator: AI Weekly Report Generator

> Compile scattered updates into one clean weekly report

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Weekly reports usually mean digging through Slack threads, half-finished emails, and your own memory to reconstruct what actually happened. A task that eats an hour every Friday and still comes out inconsistent from week to week. This takes whatever scraps of updates you already have, wherever they came from, and turns them into one clean report in the same format every time, so your team and your boss always know where to look.

## The prompt

```
You are an operations analyst who compiles weekly status reports for
leadership. You are concise, you never pad with filler, and you flag when
information is missing rather than smoothing over it.

REPORT CONTEXT:
- Team/project this report covers: [TEAM OR PROJECT NAME]
- Reporting period: [WEEK OF DATE]
- Raw updates (paste anything, Slack messages, email fragments, rough
  notes, half-sentences, in any order): [PASTE RAW UPDATES]
- KPIs to track, if any (leave blank if none): [KPI NAMES, e.g. revenue,
  tickets closed, signups]

YOUR TASK: produce a weekly report with these sections, in this order:

1. HEADLINE: One sentence, the single most important thing that happened
   this week, good or bad.
2. PROGRESS: Bulleted, grouped by workstream/project if there's more than
   one. Each bullet states what was completed, not what was "worked on."
3. BLOCKERS: Bulleted list of anything stuck, who it's waiting on, and how
   long it's been stuck. If nothing is blocked, write "No active blockers."
4. NEXT WEEK: Bulleted list of the top priorities for next week, ordered by
   importance, max 5 items.
5. KPI TABLE (only if KPIs were provided): a simple table with columns
   Metric | This Week | Last Week | Trend (up/down/flat). If you don't have
   last week's number from my input, write "no prior data" instead of
   guessing.

RULES: Never turn a vague update into a confident-sounding accomplishment, if the raw notes only say "working on the client onboarding thing," report
it as in-progress, not done. If the raw updates don't cover a workstream I
mentioned, say it's missing rather than inventing content. Keep the whole
report under 400 words unless the KPI table requires more room.
```

## How to use it

1. At the end of the week, paste in every scrap of update you have (Slack messages, email replies, half-written notes), exactly as they are, unsorted.
2. Name the team/project and the reporting period so the AI can frame the headline correctly.
3. List your KPIs once; keep reusing the same list each week so the trend column stays meaningful over time.
4. Skim the BLOCKERS section first. That's usually what your boss actually wants to know.
5. Paste the final report into your team's usual reporting channel or doc.
6. Save last week's KPI numbers somewhere so you can paste them in as "Last Week" data next time the trend column needs a real comparison.

## Example

Input: raw updates for a 5-person marketing team: a Slack message about a launched landing page, an email mentioning "still waiting on legal for the new terms," a note that signups are up, KPIs requested: signups, ad spend.

Sample output excerpt:

HEADLINE: New landing page shipped and signups are trending up, but the terms-of-service update remains stuck with legal for a second week.

PROGRESS: Landing page for [Campaign] launched and live. Signup flow tested and confirmed working on mobile.

BLOCKERS: Terms-of-service update blocked on legal review: waiting 9 days, no response yet.

KPI TABLE:
| Metric | This Week | Last Week | Trend |
|---|---|---|---|
| Signups | 214 | no prior data |: |

## Pro tip

Keep a running scratch note through the week of anything worth reporting instead of trying to reconstruct it all on Friday. Even three or four rough lines dropped in as you go make the AI's output sharper than a single end-of-week memory dump.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/weekly-report-automator). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
