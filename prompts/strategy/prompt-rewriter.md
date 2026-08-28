# Prompt Rewriter

> Turn the prompt that gave you beige output into one that gives you a usable draft

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most bad AI output traces back to the same cause: the prompt told the AI what topic to work on, but not who to be, what the situation is, what exactly to produce, or what shape to produce it in. Owners then conclude the tool is overrated and go back to writing everything by hand. The fix is a known structure ([role-context-task-format](/blog/role-context-task-format-prompt-framework)), but restructuring your own prompt is oddly hard; you know what you meant, so you cannot see what is missing. This prompt makes the AI do the restructuring, and makes it interrogate you for the parts you left out.

## The prompt

```
You are a prompt engineer for a small business owner. Your job is
to rewrite my rough prompt into the role-context-task-format
structure, and to refuse to guess at what I have not told you.

MY ROUGH PROMPT: [PASTE THE PROMPT THAT ISN'T WORKING]
WHAT I GOT BACK: [PASTE THE DISAPPOINTING OUTPUT, OR DESCRIBE IT]
MY BUSINESS: [ONE LINE: WHAT YOU SELL, TO WHOM, HOW BIG]

DO THIS, IN ORDER:
1. DIAGNOSE: In 2-3 sentences, name which of the four parts my
   prompt is missing or vague on (role, context, task, format),
   and which gap most likely caused the output I described.
2. INTERROGATE: Ask me up to 4 questions, only for information
   the rewrite needs and I have not given. Number them. Wait for
   my answers before writing anything.
3. REWRITE: Produce the full brief with the four parts labeled,
   using my answers verbatim where they fit. Keep my wording and
   my voice; you are restructuring, not ghostwriting.
4. EXPLAIN: Under the rewrite, one line per part on what it now
   does that my original did not.

RULES: Never invent facts about my business to fill a context
gap; ask instead. If my task was two tasks, split the brief in
two and say so. If my original prompt was fine and the problem
is the model or the source material, say that plainly instead of
rewriting for the sake of it.
```

The interrogation step is the part that earns the copy-paste: the questions it asks are the list of what your prompts have been missing all along, and after a few rounds you start writing complete briefs on the first try. Ten worked examples of where you should end up are in [role-context-task-format examples](/blog/role-context-task-format-examples), and our free [prompt improver](/prompt-improver) runs a lighter version of this in the browser without the back-and-forth.

## How to use it

1. Copy the full prompt into Claude or ChatGPT.
2. Paste your failed prompt and its output honestly; the diagnosis is only as good as the evidence.
3. Answer the numbered questions in one message, plainly.
4. Test the rewritten brief on the real job the same day, while the context is fresh.
5. When a rewrite earns a permanent spot in your week, save it; that pile is the start of a prompt library.

## Example

A landscaping company owner keeps asking ChatGPT to "write a spring cleanup promo email" and keeps getting generic lawn-care marketing. The rewriter diagnoses missing context and format, then asks four questions: who is the list, what did last spring's promo offer, what is different this year, what should the email not sound like. The rewritten brief carries a role (a neighborly crew owner writing to past customers), the four facts from the answers, a task with a number (one email, one offer, one deadline), and a format ban on "spruce up" puns. The next draft needs two edits instead of a rewrite, and the owner saves the brief for fall.

## Pro tip

Run your three most-used prompts through this once each, in one sitting. The questions it asks will repeat, and that repetition is the lesson: it is your personal list of what to include from now on. Keep the three rewritten briefs somewhere the whole team can reach; the [Prompt Library Builder](/toolbox/prompt-library-builder) exists for exactly that next step.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/prompt-rewriter). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
