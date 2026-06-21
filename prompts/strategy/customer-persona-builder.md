# Customer Persona Builder

> Build data-grounded personas from real customer evidence

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most customer personas are guesswork dressed up with a stock photo and a made-up name ("Busy Barbara, 42"), that nobody on the team actually uses when writing an ad or pitching a sale. This builds personas only from evidence you already have: reviews, support tickets, sales call notes, and won/lost deal reasons, and it tells you honestly when you don't have enough evidence to trust a detail.

## The prompt

```
You are a customer research analyst. You build personas exclusively from
evidence provided to you, you never invent demographic details, quotes, or
behaviors that aren't grounded in what I give you. Where evidence is thin,
you say so instead of filling the gap with a plausible-sounding guess.

MY BUSINESS: [WHAT YOU SELL, WHO YOU THINK BUYS IT TODAY]

EVIDENCE I'M PASTING (paste as much as you have, reviews, support ticket
themes, sales call notes, survey responses, won/lost deal reasons):
[PASTE RAW EVIDENCE HERE]

YOUR TASK:

1. THEME EXTRACTION: Read all the evidence and pull out recurring patterns, language customers use, problems they mention, moments that triggered
   them to buy or walk away. Quote directly from the evidence where you can.

2. BUILD 2-3 PERSONAS (only as many as the evidence actually supports, do
   not force a third persona if the evidence only clearly supports two).
   For each persona:
   - Name and one-line summary
   - Jobs-to-be-done: what they're actually trying to accomplish (not
     "buy a product", the underlying goal)
   - Buying triggers: what specific event or frustration makes them start
     looking for a solution
   - Objections: the real hesitations, in their words if you have them
   - Where they'd encounter us: channels implied by the evidence, not a
     generic list
   - One sample message: a single sentence written the way this persona
     would want to be talked to

3. EVIDENCE GAPS: List anything you had to leave out or mark as low-
   confidence because the evidence didn't support it, and what specific
   input would fill the gap (e.g. "need 5 more reviews from repeat buyers"
   or "no data on price sensitivity, pull from lost-deal notes").

RULES: Never invent a quote. Never assign an age, income, or family status
unless it's stated or strongly implied in the evidence. Mark anything you're
inferring rather than reading directly as "inferred."
```

## How to use it

1. Gather your raw evidence first (reviews, support ticket exports, sales call notes, survey text), the more you paste, the less the AI has to leave marked as a gap.
2. Copy the prompt into Claude or ChatGPT and paste the evidence directly into the bracketed section.
3. Read the evidence gaps section closely. It tells you exactly what to collect next to strengthen weak personas.
4. Share the personas with whoever writes marketing copy or handles sales calls; have them sanity-check against their own conversations.
5. Re-run quarterly with fresh evidence: personas drift as your customer base and offer change.

## Example

Input: a 3-person accounting firm pastes 15 Google reviews, notes from 8 discovery calls, and reasons for 4 lost deals.

Sample output excerpt:

THEME EXTRACTION: 9 of 15 reviews mention "finally understood my taxes" or similar: customers frequently arrive after a bad experience with a previous accountant who "just filed forms" without explaining anything. 3 of 4 lost deals cite price as the stated reason, but call notes show 2 of those prospects also said "I wasn't sure what I was actually paying for". Suggesting the real issue may be pricing clarity, not price itself (marked as inferred).

PERSONA 1, "Burned-Once Owner": Jobs-to-be-done: not just tax filing, but confidence they aren't missing deductions or making costly mistakes. Buying trigger: a bad surprise from a previous accountant (mentioned in 6 of 15 reviews) or a tax season where they felt lost. Objection: "How do I know you're different from my last accountant?": direct quote from call notes. Sample message: "You'll know exactly what we did and why, every time."

EVIDENCE GAPS: No clear data on business size or industry mix of customers. Persona details on "who they are" beyond behavior are inferred from context only. Recommend pulling this from your CRM.

## Pro tip

Paste lost-deal notes even though they feel like failures. The objections and price-sensitivity language in lost deals is often the most honest evidence you have, sharper than anything in a positive review.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/customer-persona-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
