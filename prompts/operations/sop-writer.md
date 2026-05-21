# SOP Writer: AI SOP Generator for Small Business

> Turn "how I do it" into documentation anyone can follow

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

The way you do things lives in your head, and every time someone new joins or a key person is out sick, that knowledge has to be re-explained from scratch. Writing a proper SOP feels like a project of its own, so it never happens until something goes wrong. This walks you through describing a process out loud, then turns your brain-dump into a numbered procedure someone else could follow without asking you a single question.

## The prompt

```
You are a process documentation specialist who has written SOPs for
operations teams at small and mid-size businesses. Your job is to turn a
messy verbal description of "how I do this" into a procedure a competent
new hire could follow without asking a single clarifying question.

STEP 1: INTERVIEW ME FIRST. Before writing anything, ask me clarifying
questions about the process I'm about to describe: [PROCESS NAME]. Ask
about triggers (what starts this process), tools/systems used, decision
points where the steps branch, who is normally involved, and what "done"
looks like. Ask no more than 6 questions, grouped in one message, and wait
for my answers before drafting anything.

STEP 2: ONCE I ANSWER, draft the SOP with these sections:

1. PURPOSE: One sentence, why this process exists.
2. PREREQUISITES: What must be true/available before starting (access,
   tools, information, approvals).
3. STEPS: Numbered, one action per step, written in imperative voice
   ("Open the invoice template," not "You would open..."). Where a step
   requires looking at something visual, mark it [SCREENSHOT NEEDED: what
   it should show]. Where the process branches, use "IF X → step Y, IF
   NOT → step Z."
4. COMMON FAILURE POINTS: Where this process typically breaks or gets
   delayed, and what to do when it does.
5. CHECKLIST VERSION: The same steps compressed into a one-page tickable
   checklist with no explanation, for someone who already knows the SOP
   and just needs a running-through reference.

RULES: Never assume a step "goes without saying", write for someone who
has never done this before. If my answers leave a gap, ask instead of
inventing a plausible-sounding step. Keep each step to one sentence where
possible; split anything longer into sub-steps.
```

## How to use it

1. Name the process you want documented and paste it in as [PROCESS NAME]. Start broad, like "how we onboard a new client."
2. Let the AI interview you first: answer its clarifying questions honestly and specifically, including the messy edge cases, before it drafts anything.
3. Review the draft SOP and mark every [SCREENSHOT NEEDED] tag. Go capture those screenshots and drop them in.
4. Walk through the CHECKLIST VERSION yourself once, exactly as written, to catch any step that assumes knowledge a newcomer wouldn't have.
5. Store the final SOP wherever your team keeps documentation and link it from the process's trigger point (e.g., the project template or ticket type).
6. Revisit and re-run the interview whenever the process changes. An outdated SOP is worse than none, because people trust it.

## Example

Input: [PROCESS NAME] = "how we handle a customer refund request." Owner is a 6-person online retailer.

Sample interaction: the AI asks "What triggers a refund request (email, support ticket, chat)? Is there a dollar threshold that needs manager approval? Which system do you issue the refund in? What happens if the item was already shipped vs. not yet shipped? Who tracks that a refund was actually completed?". Owner answers each in a few sentences.

Sample output excerpt:

STEPS:
1. Confirm the refund request came through the support inbox or chat. Do not action requests received via social media DMs.
2. Check order status in [ORDER SYSTEM]. IF item not yet shipped → proceed to step 3. IF already shipped → proceed to step 5.
3. Cancel the shipment in [ORDER SYSTEM]. [SCREENSHOT NEEDED: cancel button location]
4. Issue full refund via [PAYMENT PROCESSOR]; skip to step 7.
5. Confirm return tracking has been received before refunding...

COMMON FAILURE POINTS: Refunds get issued before the returned item is confirmed received, causing inventory mismatches: always check the returns log first.

## Pro tip

Answer the interview questions as if you're explaining it to a smart stranger who has never worked at your company. The SOPs that fail are the ones where the owner answered efficiently for someone who already knew the shortcuts.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/sop-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
