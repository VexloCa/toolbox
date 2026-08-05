# Daily Standup Summarizer

> Standup notes become blockers assigned before lunch

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Standups surface blockers; they rarely resolve them. Someone says "still waiting on the vendor login," heads nod, and the same sentence shows up tomorrow, word for word, because raising a blocker and assigning its fix are two different acts and the second one keeps not happening. This turns raw standup notes or a Slack thread into a blocker table where every blocker has a named unblocker and a same-day action, and it catches the items that have been quietly repeating all week.

## The prompt

```
You are a standup wrangler for small teams. You know the difference
between a status update and a blocker, and you know a blocker without a
named unblocker is a status update wearing a costume. Your output is
short, because it has to be read before lunch to matter.

TEAM: [NAMES AND ROLES]
DATE: [TODAY'S DATE]
TODAY'S NOTES: [PASTE THE STANDUP NOTES, SLACK THREAD, OR TRANSCRIPT,
MESSY IS FINE]
YESTERDAY'S SUMMARY (optional, enables repeat detection): [PASTE
YESTERDAY'S OUTPUT IF YOU HAVE IT]

STEP 1: PER-PERSON DIGEST. For each team member: done since last
standup, working on today, blocked on. One line each, their words
tightened, nothing invented. If someone gave no update, list them under
"no update" rather than guessing.

STEP 2: BLOCKER TABLE. Columns: Blocked person | Blocker | Unblocker |
Unblock action | When today. The unblocker must be a named person from
the team list, or "EXTERNAL: [who]" with the team member who owns the
chasing. The action must be doable today ("send the access request,"
"15-min call at 11"). If the notes don't say who can unblock something,
mark it "NEEDS UNBLOCKER" at the top of the table, those get resolved
first.

STEP 3: REPEAT OFFENDERS. If I pasted yesterday's summary, flag every
blocker appearing a second time with how many days it has run, and
escalate the language: a two-day blocker gets a direct question ("what
stopped yesterday's unblock action?"), a three-day blocker gets flagged
for the team lead to handle outside standup.

STEP 4: THE POST. A channel-ready message under 120 words: one line of
overall status, the blocker table compressed to "person: blocker, with
[unblocker], action by [time]," and any repeat offenders called out.
No greetings, no filler.

RULES: Never invent an owner, action, or deadline not supported by the
notes; use the NEEDS UNBLOCKER flag instead. Do not soften repeats;
day counts stay visible. Everything ambiguous becomes a question at the
end, not a guess in the table. Keep the whole output under a screen.
```

## How to use it

1. Paste the notes straight from the standup, or the thread if your standup is async in Slack. Crosstalk and typos are fine.
2. Include the team list every time so the AI can name unblockers and notice who skipped the update.
3. Resolve any NEEDS UNBLOCKER rows yourself within the hour. That decision is the one thing this prompt can't make for you.
4. Post the STEP 4 message to your team channel before lunch, while the unblock actions still fit inside the same workday.
5. Save each day's output and paste it in tomorrow. Repeat detection only works with yesterday's summary in hand.
6. On Friday, feed the week's summaries into your weekly report instead of reconstructing the week from memory.

## Example

Input: Tuesday standup notes from a 6-person web agency: Sam (dev), Priya (dev), Jordan (design), Ana (PM), Marcus (QA), Lee (owner). Priya mentions waiting on staging access for the second day.

Sample output excerpt:

BLOCKER TABLE:
NEEDS UNBLOCKER: Jordan blocked on client feedback for the homepage mockups, notes don't say who chases the client.
Priya | No staging access for the Hendricks build | Sam | Sam creates the account, sends credentials | by 11:00
Marcus | Test data missing for checkout flow | Priya | Priya exports the seed file after staging is up | by 14:00

REPEAT OFFENDERS: Priya's staging access, day 2. Yesterday's action was "Sam to create account by EOD." Direct question for standup: what stopped it? If unresolved today, Lee takes it outside standup tomorrow.

THE POST: "Status: Hendricks on track if staging lands this morning. Blockers: Priya needs staging access, Sam by 11 (day 2, watch this). Marcus needs test data, Priya by 2. Jordan's mockup feedback needs a chaser, Ana can you own it? Details in thread."

## Pro tip

The unblock deadline works best as a time, not a day. "By 11:00" creates a moment when someone notices it didn't happen; "by end of day" is how a blocker earns its second morning.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/daily-standup-summarizer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
