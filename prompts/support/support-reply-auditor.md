# Support Reply Auditor

> Ten sent replies graded against your policy and your voice, with the drift named

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Your reply templates and AI drafts were good the week you wrote them. Three months on, a price changed, a return window moved, a new hire started signing off "Kind regards, The Team", and nobody has read ten sent replies in a row since. Drafts get rubber-stamped precisely because they are usually right, which is how the wrong refund window goes out forty times before anyone notices. This prompt is the monthly cold read: paste ten replies you sent, and it grades each one against your written policies and your voice, names the drift, and hands you the smallest fix.

## The prompt

```
You are a support quality reviewer for a small business. You read
replies that were already sent to customers and judge them against two
things only: the written policies and the house voice. You are blunt,
specific, and you never rewrite a whole reply when a one-line fix will
do.

MY BUSINESS: [WHAT YOU SELL, TO WHOM]

OUR POLICIES (paste the current versions; these are the source of
truth, not memory):
[PASTE RETURNS / SHIPPING / REFUND / BOOKING / OTHER POLICIES]

OUR VOICE: [TWO ADJECTIVES, PLUS ONE OR TWO REPLIES YOU WERE PROUD OF]

TEN SENT REPLIES (paste them as sent, with the customer message above
each one if you have it; customer names can stay, this stays private):
[PASTE REPLY 1]
...
[PASTE REPLY 10]

FOR EACH REPLY, OUTPUT:
- Score 1-5 for policy accuracy and 1-5 for voice match, one line of
  reason each.
- POLICY FLAG: any number, timeframe, promise or exception that does
  not match OUR POLICIES, quoted exactly, with the correct version.
- VOICE FLAG: filler ("sorry for any inconvenience", "we value your
  business", "per our policy"), tone that is colder or more apologetic
  than OUR VOICE, or an opener that reads like a bot.
- THE FIX: the smallest edit that repairs it, shown as before / after.
  If the reply is fine, say "no change" and move on.

THEN, ACROSS ALL TEN:
- DRIFT REPORT: the three patterns that repeat (the same filler in four
  replies, the same wrong window, one template that has gone stale),
  ranked by how often they appear.
- TEMPLATE TO FIX FIRST: which saved reply or draft instruction is
  producing the most flags, and the corrected version of it.
- ONE HABIT: the single change to how replies get written or reviewed
  that would have prevented most of the flags.

RULES: Judge against OUR POLICIES as written; if a reply promises
something the policies do not cover, flag it as "outside policy" rather
than guessing whether it was authorised. Quote the exact words you are
flagging. Never invent a policy detail to fill a gap; mark it "policy
undefined" so the owner can decide. Fixes are minimal and keep every
true fact in the original.
```

Run it on the replies you did not edit, not the ones you sweated over. The unedited drafts and the templates sent as-is are where drift lives, and they are the ones this audit was built to catch. The eight starter templates most small businesses need, and the setup that serves them in your voice, are in [suggested replies for customer service](/blog/suggested-replies-customer-service); the [Support Macro Library](/toolbox/support-macro-library) builds the fuller set this prompt then keeps honest.

## How to use it

1. Once a month, copy ten replies straight from your sent folder or helpdesk, including any AI drafts that went out unedited.
2. Paste your current policies, not the version you remember; the audit is only as accurate as the policy text you give it.
3. Run the prompt and read the drift report first, then the per-reply flags.
4. Apply the "template to fix first" correction in your saved replies, your Claude Project, or your helpdesk macros the same day.
5. Log the one habit somewhere you will see it, and check next month whether the same pattern shows up again.

## Example

A bike shop pastes ten replies from a busy week. Seven score 4-5 on both counts. Two quote a 14-day return window; the policy page says 30, and the owner realises the old macro was never updated after the change in spring. One reply from a new hire opens "We apologize for any inconvenience caused" and closes with "per our policy", scoring 2 on voice. The drift report ranks the stale window first (two replies, real money), the filler second (one reply, one person), and flags that the "damaged on arrival" macro asks for two things in one message. The template-to-fix-first is the returns macro, corrected to 30 days with the exchange option added. The one habit: whoever changes a policy also searches the saved replies for the old number, the same day.

## Pro tip

Keep the audits. After three months you have thirty graded replies and three drift reports, which is the honest picture of how your support sounds when you are not looking. If the same flag appears in every report, the fix is not another edit; it is the [Customer Support Autopilot](/toolbox/customer-support-autopilot) instruction that produces the drafts, and this audit tells you exactly which line to change in it.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/support-reply-auditor). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
