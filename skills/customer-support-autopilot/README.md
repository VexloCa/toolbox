# Customer Support Autopilot

> Answer 80% of support emails in your brand voice

**Category:** Customer Support · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

Most small businesses answer the same handful of support questions over and over, but every reply still takes a human ten minutes to write, format, and proofread. You need something that drafts a solid first-pass reply in your voice, knows when a question is too sensitive or too unusual to touch, and never sends anything on its own. This turns that into a standing setup you configure once and reuse every day.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Add it to your assistant's skills folder, or paste it at the start of a conversation.

## How to use it

1. Open a new Claude Project (or a Custom GPT in ChatGPT) dedicated to support.
2. Paste the block above into the Project's Custom Instructions field.
3. Fill in BUSINESS NAME, BUSINESS TYPE, OUR BRAND VOICE, and every policy section with your real, current policies. This is the part that determines accuracy, don't skip it.
4. Each time a support message comes in, paste the raw email or chat text into the chat and let it triage and draft.
5. Review the draft and internal note, edit if needed, then send it yourself from your actual inbox or helpdesk.
6. Revisit the policies section whenever a policy changes. Stale policies are the most common cause of bad drafts.

## Example

Input pasted into the assistant: "Hi, I ordered a espresso machine 9 days ago (order #4471) and it still says 'processing.' I need it for a work event this weekend, can you help?"

Output:
TRIAGE: Auto-draftable, order status question, answerable from shipping policy.

DRAFT REPLY: "Hi there: thanks for flagging this, and sorry for the delay. Order #4471 is a bit past our normal 3-5 business day processing window, so I've asked our warehouse to confirm status today. [CONFIRM CURRENT STATUS BEFORE SENDING]. If it hasn't shipped by tomorrow, we'll upgrade you to expedited shipping at no charge so it still arrives before your event. I'll follow up either way by end of day tomorrow.: The [Business Name] Team"

INTERNAL NOTE: Assumed 3-5 day processing window from policy doc; confirm actual warehouse status for order #4471 before sending, and confirm we can offer free expedited shipping in this case.

## Pro tip

Save your five most common real customer emails and their ideal replies as a short "GOOD EXAMPLES" appendix at the bottom of the instructions. Few-shot examples in your actual voice do more to fix tone drift than any amount of abstract tone rules.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/customer-support-autopilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
