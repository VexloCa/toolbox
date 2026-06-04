# Support Macro Library

> Generate 25 reusable reply templates for your business

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Your team retypes near-identical replies dozens of times a week (order status, return instructions, shipping delays, billing questions), and everyone phrases them slightly differently, which looks inconsistent to customers. A proper macro library fixes this once: 25 ready-to-use templates with fill-in variables, so any team member sends a fast, on-brand, accurate reply instead of writing from scratch every time.

## The prompt

```
You are a support operations consultant who builds macro/canned-response
libraries for small businesses. You write templates that are specific
enough to sound human, with clear variables for the parts that change.

MY BUSINESS: [WHAT YOU SELL/DO, TYPICAL ORDER OR SERVICE SIZE]

MY POLICIES (paste what you have, returns, shipping, billing, warranty,
cancellation; incomplete is fine):
[PASTE POLICIES]

MY TONE: [DESCRIBE OR PASTE 1-2 EXAMPLE REPLIES YOU'VE SENT BEFORE]

YOUR TASK: Generate exactly 25 support reply templates covering these five
categories (5 templates each):
1. ORDERING, order confirmation follow-up, item unavailable, order
   change request, pre-purchase question, order not found
2. SHIPPING, delay notification, tracking not updating, wrong address
   caught before ship, lost package, expedited shipping request
3. RETURNS, return instructions, exchange instead of refund, item
   received damaged, late return request, return status update
4. BILLING, duplicate charge, failed payment, subscription
   cancellation, invoice request, price discrepancy
5. TECHNICAL/PRODUCT ISSUES, product not working, missing parts/
   instructions, how-to question, warranty claim, general troubleshooting
   opener

FOR EACH TEMPLATE, output:
- A short label (e.g. "Shipping Delay, Notification")
- The template text with [VARIABLES] in brackets for anything that
  changes per customer (name, order number, dates, amounts)
- Under 100 words each

RULES:
- Base every policy-dependent line (refund windows, timelines, fees) on
  MY POLICIES only. If a template needs a policy detail I didn't provide,
  write [CONFIRM POLICY: describe what's needed] instead of guessing.
- Vary the opening line across templates, no two templates should start
  identically, even within the same category.
- Keep language natural enough to send with zero editing once variables
  are filled in.
- End each template with a clear next step or question, never a dead end.

OUTPUT FORMAT: Organized by the 5 categories as headers, numbered 1-25
overall, ready to paste into a helpdesk macro tool or shared doc.
```

## How to use it

1. Gather whatever policy documentation you have. Even rough notes are enough to start.
2. Paste your business description, policies, and 1-2 example replies for tone.
3. Run the prompt and get all 25 templates in one pass.
4. Fill in any [CONFIRM POLICY] flags with your team before publishing the library.
5. Load the finished templates into your helpdesk tool (Gmail canned responses, Zendesk macros, Intercom saved replies) or a shared doc.
6. Review and refresh the library every 6 months or whenever a policy changes.

## Example

Input: A small furniture e-commerce business, standard 30-day return window, 5-7 business day shipping.

Output excerpt (2 of 25):

**14. Billing, Duplicate Charge**
"Hi [CUSTOMER NAME], thanks for flagging this. I can see [ORDER NUMBER] shows two charges of [$AMOUNT] on our end too. I've submitted a refund for the duplicate charge; it should post back to your card within 5-7 business days. Let me know if it hasn't cleared by [DATE] and I'll escalate directly with our payment processor."

**8. Returns, Return Instructions**
"Hi [CUSTOMER NAME], happy to help with your return. Since it's within our 30-day window, here's what to do: pack the item in its original box if possible, attach the prepaid label we're sending to [EMAIL], and drop it at any [CARRIER] location. Once we receive it, your refund processes within 5 business days. Let me know if the label doesn't come through."

## Pro tip

Sort the finished library by how often each scenario actually comes up: pin the top 5 most-used templates at the top of your helpdesk tool so your team reaches for the right one in seconds instead of scrolling through 25.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/support-macro-library). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
