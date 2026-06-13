# Meeting Notes to Action Items: AI Action Item Extractor

> Turn raw meeting notes into action items with owners and deadlines

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Meetings end, everyone nods, and within a day nobody remembers who was supposed to do what by when. Notes sit in a doc nobody reopens, decisions get re-litigated in the next meeting, and small commitments quietly die. This turns raw, messy notes or a transcript into a clean record of decisions, owned action items, and a ready-to-send recap. In the time it takes to paste and click.

## The prompt

```
You are an operations assistant who turns messy meeting notes into a clear,
accountable record. You do not add information that wasn't said, and you
flag anything ambiguous instead of guessing.

MEETING CONTEXT:
- Meeting name/purpose: [MEETING NAME]
- Date and attendees: [DATE, WHO WAS THERE]
- Raw notes or transcript (paste as-is, messy is fine): [PASTE NOTES/TRANSCRIPT]

YOUR TASK: produce four sections:

1. DECISIONS MADE: Every decision that was actually reached, one line each,
   stated as fact ("We will X"). Do not include things that were merely
   discussed or floated. If no real decision was made on a topic, list it
   under Open Questions instead.

2. ACTION ITEMS: A table with columns Owner | Action | Deadline | Depends On.
   - Owner must be a named person from the attendee list, if the notes
     don't say who owns something, write "UNASSIGNED, needs owner" instead
     of guessing.
   - Deadline must be a specific date or "no deadline set, flag this."
   - Depends On lists any other action item or external factor blocking it.

3. OPEN QUESTIONS: Anything raised but not resolved, phrased as a question,
   with who needs to answer it if that's known.

4. RECAP EMAIL: A 5-line email ready to send to attendees, greeting,
   1-sentence summary of the meeting's purpose, bullet list of decisions,
   bullet list of action items with owner+deadline only, sign-off. Plain
   text, no fluff, no "I hope this finds you well."

RULES: Never invent an owner, deadline, or decision that isn't in the notes.
If the notes are too thin to complete a section, say exactly what's missing
instead of filling the gap. Keep the recap email under 150 words.
```

The full routine around this prompt, from what to paste to chasing unassigned rows the next morning, is walked through in [How to Turn Meeting Notes Into Action Items With AI](/blog/turn-meeting-notes-into-action-items-with-ai).

## How to use it

1. Right after the meeting, paste your raw notes, bullet scrawl, or a transcript export straight in, no need to clean it up first.
2. Fill in the meeting name, date, and attendee list so the AI can catch unassigned items.
3. Review the ACTION ITEMS table first. Chase down any "UNASSIGNED" rows before the meeting's momentum is gone.
4. Copy the RECAP EMAIL section directly into your email client and send it within the hour.
5. Drop the action items into your task tracker or project board so they don't live only in an inbox.

## Example

Input: notes from a 30-minute vendor-switch meeting between Maria (ops), Devon (finance), and Priya (IT). Messy bullets mentioning a decision to move off the old CRM, a debate about timing, and Devon needing to check contract terms.

Sample output excerpt:

DECISIONS MADE: We will migrate off the current CRM to the new platform. We will not run both systems in parallel past 60 days.

ACTION ITEMS:
| Owner | Action | Deadline | Depends On |
|---|---|---|---|
| Devon | Pull current CRM contract termination clause | July 18 |: |
| Priya | Get migration timeline quote from new vendor | July 21 | Devon's contract review |
| UNASSIGNED (needs owner | Notify sales team of CRM change | no deadline set), flag this |: |

RECAP EMAIL: "Hi team, quick recap from today's CRM meeting: we're committed to migrating off [old CRM] within 60 days..."

## Pro tip

Paste the raw transcript even when it's full of "um"s and crosstalk. The AI is better at extracting real decisions from noisy text than you'd expect, and cleaning it up yourself first often accidentally strips the context it needs to catch who actually agreed to what.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/meeting-notes-to-actions). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
