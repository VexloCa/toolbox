# Invoice Chaser Sequences

> Get overdue invoices paid without burning relationships

**Category:** Finance & Admin · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Chasing unpaid invoices is awkward: push too hard and you risk the relationship, stay too polite and the invoice sits unpaid for months while your own bills come due. Most owners either avoid the conversation or send the same one vague reminder on repeat. This builds a complete escalation sequence so every follow-up has a clear purpose and the tone matches how overdue the invoice actually is.

## The prompt

```
You are a collections specialist who has recovered overdue payments for
small service businesses for 15 years without losing clients over it. You
know that tone matters more than legal threats for 95% of late payers, and
you save firmness for the accounts that have earned it.

INVOICE DETAILS:
- Client/business name: [CLIENT NAME]
- What the invoice was for: [SERVICE/PRODUCT]
- Invoice amount: [$X], Invoice number: [#]
- Original due date: [DATE]
- Days overdue as of today: [X DAYS]
- Payment history with this client: [FIRST-TIME LATE PAYER / OCCASIONAL
  LATE PAYER / REPEAT OFFENDER, describe briefly]
- My relationship with them: [ONGOING CLIENT I WANT TO KEEP / ONE-OFF
  PROJECT / RELATIONSHIP ALREADY STRAINED]
- Preferred payment method/link: [HOW THEY CAN PAY]

YOUR TASK: build a complete 4-touch chase sequence:

1. DAY 3, FRIENDLY NUDGE: Assumes it's an oversight. Warm, brief, gives
   them an easy out (e.g. "just in case it slipped through").

2. DAY 14, FIRM CHECK-IN: More direct. Restates amount and due date
   clearly, asks for a specific response (payment or a date), no longer
   assumes it's an accident.

3. DAY 30, CONSEQUENCES: States what happens next if payment isn't
   received by a specific date (e.g. late fee per the contract, pause on
   further work, referral to collections), only if that's realistic for
   me to enforce. Still professional, not hostile.

4. DAY 45+, FINAL NOTICE: Formal, short, states the deadline and the
   exact next step if it passes. This is the last friendly-channel email
   before I escalate.

For EACH email, write two variants:
- VARIANT A, GOOD CLIENT, FIRST TIME LATE: warmer tone throughout, gives
  more benefit of the doubt even at day 30 and 45.
- VARIANT B, REPEAT OFFENDER: still professional and never rude, but
  skips the benefit-of-the-doubt framing and moves to firm language sooner.

Then write a PHONE SCRIPT for a day-14 or day-30 call: opening line, how to
state the ask without over-apologizing, how to handle "I'll pay next week"
non-commitments, and how to end the call with a specific next step logged.

HARD CONSTRAINTS:
- Every email is 100 words or fewer.
- Never use guilt-tripping, passive-aggressive language, or ALL CAPS.
- Every email states the exact amount and invoice number.
- Every email ends with one clear, specific ask (pay by X, or reply with a
  date), never an open-ended "let me know."
- Do not draft legal threats, collections-agency language, or anything that
  could be read as harassment, if the situation calls for actual legal
  escalation, say so and tell me to consult a lawyer instead of drafting it.

OUTPUT FORMAT: Organize by touch (Day 3, Day 14, Day 30, Day 45+), each
with Variant A and Variant B labeled, followed by the phone script.
```

## How to use it

1. Fill in the invoice details and pick which variant fits (good client vs repeat offender), or generate both and choose per situation.
2. Send the Day 3 email as soon as the invoice is 3 days past due; don't wait until it feels overdue enough to bother.
3. Log each send date somewhere (spreadsheet or CRM) so you know exactly when the next touch is due.
4. Use the phone script if an email goes unanswered past day 14. A short call often resolves what emails don't.
5. If day 45 passes with no payment or commitment, stop using this sequence and talk to your accountant or a lawyer about next steps.

## Example

Input: Client "Harlow Design Co.", invoice for a website redesign, $3,200, invoice #1042, due date June 1, now 14 days overdue, first time this client has paid late, ongoing client the owner wants to keep, payment via e-transfer.

Sample output excerpt:

DAY 14, FIRM CHECK-IN (Variant A, Good client, first time):
Subject: Invoice #1042: now 2 weeks past due

Hi Harlow team, following up on invoice #1042 for $3,200, due June 1. I haven't seen payment or a note about it yet. Could you confirm either payment today or a specific date I can expect it by? Happy to resend the e-transfer details if needed. Thanks for closing this out.

PHONE SCRIPT: "Hi [name], quick call about invoice #1042. Just want to make sure it didn't get lost. Can you tell me when I can expect payment?" If they say "next week": "Great. Can I pencil in [specific date] and follow up then if I haven't seen it?"

## Pro tip

Send the Day 3 email even when you're almost certain it's a simple oversight. It costs you nothing, and starting the paper trail early makes every later touch easier to justify if the client turns out to be a repeat offender.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/invoice-chaser). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
