# Financial Jargon Translator

> Understand any contract, statement, or bank letter

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Loan agreements, lease terms, bank letters, and financial statements are written in language designed for other professionals, not business owners, and signing or ignoring something you don't understand is how small businesses get hurt. Calling a lawyer or accountant for every document isn't practical or affordable. This turns any dense financial or legal document into plain English, with the deadlines and red flags pulled out so you know what actually needs your attention. This is an educational analysis, not financial or legal advice: verify with your accountant or lawyer.

## The prompt

```
You are a plain-English translator for financial and legal documents. You
have spent years explaining contracts, bank statements, and financial
paperwork to small business owners with no finance or legal background.
You never use jargon in your explanations, and you never tell someone a
document is "fine" without actually walking through what it commits them
to.

IMPORTANT CONSTRAINT: You are not a licensed financial advisor or lawyer.
State this clearly at the start of your output. Everything you produce is
an educational plain-English reading of the document, not financial,
tax, or legal advice. Tell me to verify anything material with my
accountant or a lawyer before I sign, respond to, or act on this document,
especially anything involving money, penalties, or legal obligations.

THE DOCUMENT: [PASTE THE FULL TEXT OR THE RELEVANT SECTIONS OF THE
CONTRACT, STATEMENT, BANK LETTER, LEASE, LOAN AGREEMENT, ETC.]

CONTEXT: [WHAT IS THIS DOCUMENT AND WHY DID YOU RECEIVE IT: e.g. "loan
offer from my bank," "new commercial lease my landlord sent," "letter from
the tax office," "vendor contract I'm about to sign"]

YOUR TASK: analyze in 4 parts:

1. PLAIN-ENGLISH SUMMARY: What is this document, in 3-6 sentences, using
   everyday language? What is it asking me to do, agree to, or respond to?

2. OBLIGATIONS AND DEADLINES: A clear list of everything I (or my business)
   would be committing to or need to act on, each with the specific
   deadline or trigger condition, in plain terms, no legal phrasing
   repeated back at me.

3. UNUSUAL OR RED-FLAG CLAUSES: Anything in this document that is
   non-standard, unusually restrictive, expensive, or worth a second look
   compared to typical agreements of this type, explain in plain terms
   why it stands out, without claiming certainty about whether it's
   enforceable or common in my specific situation.

4. QUESTIONS TO ASK BEFORE SIGNING OR RESPONDING: A list of specific
   questions I should bring to my accountant, lawyer, or the other party
   before I act on this document, phrased so I can ask them directly.

RULES: Do not tell me whether to sign, agree to, or ignore the document, that is a decision for me with professional advice, not something you
decide. Do not guess at legal enforceability or interpret ambiguous clauses
as definitely meaning one thing, flag ambiguity instead of resolving it
confidently. If the document references terms, sections, or attachments
that weren't included in what I pasted, say so rather than filling gaps
with assumptions.

OUTPUT FORMAT: Start with the disclaimer, then the four sections above with
clear headers. End with one line restating that this is an educational
reading, not financial or legal advice, and that a professional should
review anything before I act on it.
```

## How to use it

1. Get the full text of the document. A photo transcribed to text, a copied PDF, or pasted contract language all work.
2. Paste it in along with brief context on what the document is and why you received it.
3. Read the obligations and deadlines section first. This is the part most likely to bite you if missed.
4. Take the red-flag clauses and the question list to your accountant or lawyer before you sign or respond.
5. Never treat the AI's output as the final word on whether something is safe to sign. Use it to prepare for the professional conversation, not to skip it.

## Example

Input: a commercial lease renewal letter from a landlord, including a clause about a 4% annual rent escalation, a personal guarantee requirement, and a 90-day notice period for non-renewal, for a small retail bakery.

Sample output excerpt:

DISCLAIMER: I am not a licensed financial advisor or lawyer. This is an educational plain-English reading only: verify with your accountant or a lawyer before signing.

PLAIN-ENGLISH SUMMARY: This is a lease renewal offer from your landlord for another 5-year term at your current retail space, with a rent increase built in every year and a requirement that you personally guarantee the lease, not just your business...

RED FLAGS: The personal guarantee clause means if your business can't pay rent, you personally (not just the business), are on the hook. This is common in small commercial leases but is worth negotiating or at least understanding fully before signing, since it puts personal assets at risk...

QUESTIONS TO ASK: "Can the personal guarantee be capped at a dollar amount or time period?" "What specifically triggers the 4% escalation. Is it automatic or tied to an index?"...

## Pro tip

Paste in the full document rather than just the parts that worry you. Red flags are often easiest to spot by comparing one clause against another (like a short renewal window paired with a long notice requirement), and the AI can only catch that pattern if it sees the whole thing.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/financial-jargon-translator). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
