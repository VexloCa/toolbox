# Context Pack Builder

> Stop retyping your business's story into every prompt; paste a ready context block instead

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

The context section is the longest part of every working prompt (the [role-context-task-format framework](/blog/role-context-task-format-prompt-framework) is blunt about this), and it is the part owners retype worst. At 9pm you compress "what my business is" into one vague line, the AI fills the gap with guesses, and the output reads like it was written for someone else's company, because it was. The fix is embarrassingly practical: write the context once, properly, in a few reusable versions, and paste the right one forever after. This prompt runs that one-time interview.

## The prompt

```
You are helping a small business owner build reusable context
blocks: the paragraphs they will paste into the CONTEXT section
of every AI prompt from now on.

MY BUSINESS, ROUGHLY: [ONE MESSY PARAGRAPH: WHAT YOU SELL, TO
WHOM, HOW BIG, WHERE, WHAT MAKES YOU DIFFERENT, WHAT YOU ARE
KNOWN FOR LOCALLY]

DO THIS, IN ORDER:
1. INTERVIEW: Ask me up to 6 numbered questions to fill what the
   paragraph left out. Only ask what a stranger doing my admin
   would need: customers, price range, voice, constraints,
   seasonality, what we refuse to do. Wait for answers.
2. BUILD THE PACKS: Write 4 context blocks from my answers:
   - CORE (under 120 words): the all-purpose version.
   - CUSTOMER-FACING (under 100 words): adds voice, what we
     promise, what we never say.
   - MONEY (under 100 words): adds pricing, terms, margin
     sensitivities stated plainly.
   - HIRING (under 100 words): adds team size, culture told
     honestly, what the work is like.
3. MARK THE MOVING PARTS: In each block, wrap anything that will
   change (prices, headcount, season) in [BRACKETS] with today's
   value noted, so future-me knows what to update.
4. TEST IT: Take this sample task, "write a follow-up email to a
   customer who went quiet after a quote," and show it briefed
   twice: once with my original messy paragraph, once with the
   CUSTOMER-FACING block. Two lines on what changed.

RULES: Use my words and my facts only; where you are tempted to
guess, ask. No marketing language I did not give you. If two of
my answers contradict each other, point it out instead of
smoothing it over.
```

The four-pack split matters more than it looks: the money block exists so pricing details never leak into customer-facing drafts, and the hiring block keeps the honest culture notes out of marketing copy. Store the finished packs wherever your prompts live; if that is nowhere in particular, the [Prompt Library Builder](/toolbox/prompt-library-builder) gives them a maintained home.

## How to use it

1. Copy the full prompt into Claude or ChatGPT and write the messy paragraph without polishing it.
2. Answer the interview in plain language; the blocks are only as true as the answers.
3. Save all four packs somewhere the whole team can paste from.
4. From now on, every prompt's context section starts with a paste, then one line about today's specific situation.
5. Re-run the moving-parts check when prices or the team change; the [BRACKETS] tell you what to look at.

## Example

A 9-person plumbing company owner writes the messy paragraph in two minutes. The interview asks about service area, emergency vs scheduled split, the price range they are comfortable stating, and what they refuse (no new-construction bids). The CORE block comes back at 110 words and reads like the owner on a good day. The test at step 4 is the convincer: the quote follow-up briefed with the old one-liner opens "We hope this message finds you well"; briefed with the customer-facing pack it opens with the customer's actual job and a straight question. The owner pins all four packs in the team chat, and every prompt in the shop starts from a paste.

## Pro tip

The blocks decay quietly: the price changes, the team grows, the packs still say last year. Put a 10-minute review of the [BRACKETS] values on the same calendar reminder as your quarterly price check, and treat any output that suddenly sounds off as a symptom that a pack has gone stale, not that the AI got worse.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/context-pack-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
