# Complaint De-Escalation Scripts

> Turn angry customers into repeat customers

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

An angry customer message can derail your whole day, and the wrong first line (defensive, dismissive, or just too slow), turns a fixable problem into a lost customer and a public complaint. You need a calm, structured way to respond in the moment that acknowledges the problem, owns it, fixes it, and actually repairs the relationship, whether it's a refund demand, a shipping delay, or a quality complaint.

## The prompt

```
You are a customer experience specialist trained in de-escalation. You
write responses to angry or upset customers that lower the temperature
without being weak, defensive, or over-apologetic.

MY BUSINESS: [WHAT YOU DO]

THE COMPLAINT (paste the customer's message and the channel, email,
phone call notes, live chat):
[PASTE COMPLAINT HERE]

COMPLAINT TYPE (pick one, or let me classify it): REFUND DEMAND / DELAY /
QUALITY ISSUE / BILLING ERROR / STAFF INTERACTION / OTHER

WHAT I CAN ACTUALLY OFFER (be specific, a full refund, partial refund,
replacement, credit, expedited fix, or just an apology and explanation):
[STATE WHAT YOU'RE WILLING/ABLE TO DO]

CHANNEL: [EMAIL / PHONE SCRIPT / CHAT]

YOUR TASK: Write a response using this exact structure, 1. ACKNOWLEDGE: Name the specific problem in one sentence, no hedging
   ("I see your order arrived three days late" not "I understand there
   was an issue").
2. OWN: A direct, non-defensive statement that this fell short, no
   blaming the courier, the system, or "unprecedented demand" unless
   that's genuinely relevant and stated factually, not as an excuse.
3. FIX: The concrete resolution from WHAT I CAN ACTUALLY OFFER, stated
   plainly with a timeframe.
4. MAKE-GOOD: One thing beyond the bare fix that shows you value the
   relationship (a discount on next order, a small credit, a direct
   contact for next time), only if realistic, never invented.
5. FOLLOW-UP: State exactly when and how you'll confirm the fix happened
   (e.g. "I'll email you the replacement tracking number by end of day
   Thursday").

FORMAT BY CHANNEL:
- EMAIL: Full written response, professional but warm, under 150 words.
- PHONE SCRIPT: Same 5 steps but written as spoken lines a person can read
  naturally, with a bracketed [PAUSE FOR RESPONSE] after ACKNOWLEDGE and
  after FIX.
- CHAT: Same structure broken into 3-4 short back-and-forth message
  bubbles instead of one long block.

RULES: Never say "I understand your frustration" without immediately
following with a specific fact or action. Never promise something not in
WHAT I CAN ACTUALLY OFFER. Never blame the customer, even subtly. If the
complaint is unclear or you're missing a fact needed to resolve it, add a
6th step: CLARIFY, one specific question to ask before you can finish
resolving it.
```

## How to use it

1. Paste the customer's complaint exactly as received and note the channel (email, phone, chat).
2. Decide upfront what you're actually willing to offer. The prompt will not invent a resolution for you.
3. Run it and get a structured response following the 5-step acknowledge-own-fix-make good-follow-up flow.
4. Read it out loud (especially phone scripts) before using it. Adjust anything that doesn't sound like you.
5. Send it through the actual channel, then set a reminder for the follow-up time you promised. The script only works if you keep it.

## Example

Input: Email complaint. "This is the second time my order has shown up with the wrong color. I've already emailed once about this. I want a refund, not another replacement." Complaint type: QUALITY ISSUE. What I can offer: full refund plus 20% off next order.

Output (email variant):
"Hi Marcus, two wrong-color shipments in a row on the same order is on us, not a fluke, and I understand why a replacement doesn't feel like the right answer this time. I've processed a full refund for order #8823, which will show on your statement within 3-5 business days. I've also flagged this SKU internally so we can figure out where the mix-up is happening. As an apology, I've added a 20% off code for your next order: [CODE]: no expiration. I'll follow up personally once the refund clears to confirm it went through. – Dana, Customer Care"

## Pro tip

Keep a running log of which complaint types trigger de-escalation scripts most often, if "wrong color shipped" keeps showing up, the fix isn't a better apology, it's a process fix upstream, and that pattern is worth feeding into an automation-opportunity-audit.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/complaint-deescalation). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
