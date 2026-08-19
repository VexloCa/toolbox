# AI Spend Auditor

> Every AI charge in one inventory, with renewal dates and expiry flags

**Category:** Finance & Admin · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

AI spend is the fastest-growing line on a small business card statement and the least inventoried. A $20 subscription here, a $29 add-on there, a Zapier scenario quietly billing per call, and an agency retainer with model costs baked in. Nobody wrote any of it down, so renewals surprise you, two tools do the same job, and when a vendor's intro price expires (as [Gemini 3.7 Flash's will on December 31](/blog/gemini-3-7-flash-price-doubles)), no one connects the announcement to next year's budget.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Add it to your assistant's skills folder, or paste it at the start of a conversation.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Answer the setup questions: business, who approves spend, where the card statements live.
4. Paste your last two months of statements, or list every AI tool you can name. Let it ask about the ones you forgot.
5. Whenever you see a pricing announcement, paste it in. The inventory updates and tells you if you should care.

## Example

A 6-person bookkeeping firm pastes two months of statements. The skill finds nine AI-related charges, including a $24/month transcription tool no one has opened since the meeting-notes tool arrived (overlap, flagged), and a per-call charge from an automation platform that tripled in July (usage spike, flagged). It builds the inventory, sets three renewal alerts, and when the owner pastes the Gemini pricing news, it reports that only one line is affected: the client-intake bot an agency runs for them, and drafts the question to send that agency about who absorbs the increase.

## Pro tip

Feed it statements, not memory. In client work the forgotten charges average two or three per business, and they are usually the ones that fail the "would you buy it again today" test hardest. Once the inventory exists, run our [AI ROI Reality Check](/toolbox/ai-roi-reality-check) over it quarterly; the two are built to hand off to each other.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-spend-auditor). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
