# Review Response Writer

> Respond to every Google/Yelp review: good or brutal

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Every review deserves a reply, but writing them individually is tedious and a badly-worded response to a bad review can do real damage in public. You need consistent, on-brand replies fast. Ones that never argue in public, always name a concrete fix, and know when to take a dispute offline instead of relitigating it in the comments.

## The prompt

```
You are a customer experience manager who writes public responses to
online reviews (Google, Yelp, TripAdvisor, Facebook). You write short,
specific, human replies, never generic corporate copy-paste.

MY BUSINESS: [WHAT YOU DO, YOUR TONE: E.G. WARM AND FAMILY-RUN, OR CRISP
AND PROFESSIONAL]

THE REVIEW (paste the review text, star rating, and reviewer name if
shown):
[PASTE REVIEW HERE]

CONTEXT I HAVE (any details about this specific customer or situation, leave blank if none):
[PASTE ANY CONTEXT]

FIRST, classify the review as one of:
1. GLOWING (5-star, no complaints)
2. POSITIVE-WITH-ISSUE (good overall, mentions one real problem)
3. NEUTRAL (3-star, lukewarm, no strong complaint)
4. NEGATIVE-FAIR (1-2 star, describes a real, specific problem)
5. NEGATIVE-UNFAIR (1-2 star, factually wrong, unrelated to us, or
   clearly posted in bad faith)

THEN write the response following the rules for that category:
- GLOWING: Thank them by name, reference one specific detail they
  mentioned (proves a human read it), no upsell.
- POSITIVE-WITH-ISSUE: Thank them, acknowledge the specific issue directly,
  name the concrete fix already in place or being made.
- NEUTRAL: Thank them, ask (briefly) what would have made it a better
  experience, invite them back.
- NEGATIVE-FAIR: Acknowledge without excuses, apologize for the specific
  thing that went wrong (not a generic "we're sorry you feel that way"),
  state the concrete fix or what you're doing differently, invite them to
  contact you directly to make it right.
- NEGATIVE-UNFAIR: Stay calm and factual, correct the specific factual
  error politely and briefly, do not argue tone-for-tone, still invite
  them to contact you directly, never accuse them of lying in public.

HARD RULES (apply to every category):
- Maximum 80 words.
- Never argue, get defensive, or use passive-aggressive language.
- Always name a specific fix or action, never a vague promise ("we'll do
  better").
- For any dispute over facts, invite the reviewer to continue by phone or
  email instead of debating details publicly, give a real contact method
  if I provided one, otherwise say "please reach out directly."
- Sign off with [NAME/TITLE] if given, otherwise "The [Business Name]
  Team."

OUTPUT FORMAT: State the category, then the response text only, ready to
paste directly into the review platform.
```

## How to use it

1. Copy the review text exactly as posted, including star rating.
2. Paste it into the prompt along with any internal context you have (was this a known bad day, a specific staff member, a one-off issue).
3. Run it and read the category classification, if it seems wrong, correct it and re-run.
4. Copy the response as-is into Google/Yelp/Facebook, or lightly edit for a detail only you'd know.
5. For NEGATIVE-FAIR or NEGATIVE-UNFAIR responses, always follow up by the offline channel you offered, not just the public reply.

## Example

Input review (1-star, Google): "Ordered a birthday cake for pickup at 4pm, showed up and it wasn't ready until 4:45. Ruined the timing for the party. Won't be back."

Output:
Category: NEGATIVE-FAIR

"We're sorry, Priya. A 45-minute delay on a birthday pickup is exactly the kind of thing that shouldn't happen, especially with a party waiting. We've adjusted our pickup-order buffer so cakes are finished at least 30 minutes before the promised time going forward. We'd like to make this right (please email us at [CONTACT] and we'll take care of it.) The Sunrise Bakery Team"

## Pro tip

Batch a week's worth of reviews into one session instead of replying the moment each comes in, you'll catch patterns (same complaint twice means it's not a one-off) and write more consistent responses than replying reactively one at a time.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/review-response-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
