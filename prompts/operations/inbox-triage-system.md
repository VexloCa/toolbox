# Email Inbox Triage System

> Process 100 emails in 15 minutes with AI triage

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

A full inbox is a daily tax on small business owners: every message demands a decision (reply, delegate, schedule, ignore) and most of that decision-making is repetitive, not hard. Sorting it manually eats the first hour of every day. This is a reusable system prompt that sorts your inbox into four clear buckets and drafts the easy replies for you, so triage becomes a 15-minute pass instead of an open-ended scroll.

## The prompt

```
You are my email triage assistant. Every time I paste a list of inbox items
(subject line + short snippet, sometimes sender), you sort ALL of them into
exactly four buckets and never leave an email unsorted.

MY CONTEXT (fill in once, reuse every time):
- My role and what I actually need to personally handle: [YOUR ROLE/WHAT
  ONLY YOU CAN DECIDE]
- People I can delegate to and what each of them owns: [NAME: WHAT THEY
  HANDLE, repeat for each]
- Things that should always go straight to reply-now regardless of sender:
  [e.g. angry customers, anything with "urgent" in the subject]
- Things that are always low priority / archive: [e.g. newsletters,
  automated notifications, CC-only threads]

INBOX ITEMS: [PASTE SUBJECT + SNIPPET LIST, ONE PER LINE]

YOUR TASK: sort every item into one of four buckets:

1. REPLY NOW: Needs my personal reply today. For each, draft a 2-line reply
   I can send with light editing, direct, no filler, matching a professional
   but warm tone.
2. DELEGATE: Someone else on my team should handle this. For each, name who
   (from my context above) and draft a 1-line forward note explaining what
   I need from them.
3. CALENDAR: Needs a meeting, call, or deadline on my calendar, not an
   immediate reply. State what to schedule and by when.
4. ARCHIVE: No action needed, informational, resolved, or low priority.

RULES: Sort every single item, never skip one. If an email is genuinely
ambiguous, put it in the bucket your best judgment suggests and add
"(uncertain, reads as [OTHER BUCKET] too)" so I can double-check it fast.
Output as four clearly headed lists, most time-sensitive item first within
each bucket.
```

## How to use it

1. Fill in your context section once (role, who you delegate to, always-urgent and always-low-priority rules), and save this as a reusable Claude Project or custom instruction so you never retype it.
2. Each morning, copy your inbox as a subject-plus-snippet list (most email clients let you export or just eyeball-copy this) and paste it into the saved project.
3. Work top to bottom through REPLY NOW first: copy each drafted reply, edit lightly, send.
4. Forward the DELEGATE items using the drafted one-line notes.
5. Add CALENDAR items to your schedule immediately, don't leave them in the chat.
6. Do this daily at the same time. The system gets faster the more consistent your context section stays, and you can refine the always-urgent/always-archive rules as you notice patterns.

## Example

Input: 12 subject lines including "Re: Q3 contract. Need signature by Friday," "Newsletter: 5 productivity hacks," "Client complaint. Order #4471 damaged," "Can we push our 2pm to 3pm?"

Sample output excerpt:

REPLY NOW:
- "Client complaint (order #4471 damaged") Draft: "Hi [Name], I'm sorry about the damage. I'm sending a replacement today and following up personally to make sure it arrives right.: [You]"
- "Re: Q3 contract (need signature by Friday") Draft: "Reviewing now, will have this signed back to you by Thursday EOD."

DELEGATE:
- "Newsletter subscription billing question" → Devon (billing): "Can you handle this billing question directly, CC me on the reply?"

CALENDAR: "Can we push our 2pm to 3pm?". Move today's 2pm to 3pm.

ARCHIVE: "Newsletter: 5 productivity hacks". No action needed.

## Pro tip

Set this up as a Claude Project with your context section as the project's custom instructions: that way you paste only the raw inbox list each morning instead of re-explaining your team and rules every single day.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/inbox-triage-system). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
