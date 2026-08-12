# Help Doc Writer

> Help articles customers find before they email you

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

You answer the same question by email four times a week, and the help page you wrote about it sits unread because it's titled the way your company talks, not the way customers search. "Managing your account preferences" helps nobody who typed "how do I change my delivery day." A good help doc answers the question in the first three lines, in the customer's own words, and most owners either skip writing them or bury the answer under a company-history preamble.

## The prompt

```
You are a support content writer who measures success by one number:
tickets that never get sent. You write help articles in the customer's
language, put the answer first, and refuse to invent steps you weren't
given.

MY BUSINESS: [WHAT YOU SELL AND TO WHOM]
THE QUESTION CUSTOMERS ASK: [PASTE 1-3 REAL EXAMPLES OF HOW THEY ASK
IT, COPIED FROM ACTUAL EMAILS OR CHATS IF POSSIBLE]
THE ANSWER: [THE EXACT RESOLUTION STEPS, SETTINGS, POLICY, OR PROCESS.
BE COMPLETE: I WILL NOT INVENT BUTTONS OR MENUS YOU DIDN'T DESCRIBE]
WHERE THIS DOC WILL LIVE: [HELP CENTER / FAQ PAGE / PDF / EMAIL REPLY]

STEP 1: INTERROGATE ME: Before drafting, check THE ANSWER for gaps. If
a step is missing ("click the settings icon, then what?"), if you don't
know what happens after the last step, or if the answer changes by plan,
device, or customer type, ask me. Do not draft until the resolution is
complete enough that a stranger could follow it.

STEP 2: DRAFT THE ARTICLE:
- TITLE: the customer's question, phrased the way they ask it, under 60
  characters.
- QUICK ANSWER: the short version in the first 2-3 sentences. A reader
  in a hurry should be done here.
- STEPS: numbered, one action per step, naming exact buttons, menus, and
  fields from THE ANSWER. Note where a screenshot would help with
  [SCREENSHOT: what it should show].
- IF THAT DIDN'T WORK: the 2-3 most likely snags and what to do about
  each.
- STILL STUCK: one line telling them how to reach a human, with the one
  detail to include that speeds up the reply (order number, account
  email, error message).

STEP 3: FINDABILITY: List 4-6 alternate phrasings of the question that
should point to this article (search keywords, alternate titles), plus
1-2 places to link it from (order confirmation email, error message,
checkout page).

STEP 4: EXPIRY CHECK: Name what would make this article wrong (a menu
redesign, a policy change, a price change) so I know when to update it.

RULES: Grade-8 reading level or below. No sentence over 20 words in the
STEPS section. Never write "please note" or open with background about
the company. If THE ANSWER is a policy rather than a process, lead with
what the customer gets, then the conditions. If I gave you a vague
answer like "they can fix it in settings," push back and demand the
exact path.
```

## How to use it

1. Pick the question you've answered most often this month. Your sent folder will tell you which one.
2. Copy 1-3 real customer emails asking it, word for word. Those phrasings become the title and search keywords.
3. Write out the full resolution before you run the prompt, and answer its gap-check questions honestly. It will refuse to guess your menu names, which is the point.
4. Add the screenshots where it marked [SCREENSHOT] placeholders. A picture of the right button saves three sentences.
5. Publish, then link the article from wherever the question originates: the confirmation email, the error message, the product page.
6. Next time the question arrives by email anyway, reply with a one-line answer plus the link, and note what the customer searched for so you can add that phrasing.

## Example

Input: a meal-prep delivery company, question asked as "how do I skip next week's box?", answer involves the account page under Deliveries, with a Wednesday 11:59pm cutoff.

Sample output excerpt:

Title: How do I skip a week's delivery?

Quick answer: You can skip any upcoming box from your account page, as long as you do it before Wednesday at 11:59pm ET the week prior. Skipped weeks aren't charged.

Steps: 1. Log in and open Account, then Deliveries. 2. Find the week you want to skip. 3. Select Skip this box and confirm. You'll get a confirmation email within a few minutes. [SCREENSHOT: the Deliveries page with the Skip button highlighted]

If that didn't work: No Skip button showing? The Wednesday cutoff for that week has passed, so the box is already packed. The next week will show the button.

Findability phrases: "pause my subscription", "cancel one week", "going on vacation", "stop next delivery", "skip a box".

Expiry check: this article breaks if the cutoff day changes or the Deliveries page is renamed.

## Pro tip

Write the "If that didn't work" section from real failed attempts, not imagination. The next three replies you send about this topic will tell you exactly where people get stuck, and that section is what separates a doc that deflects tickets from one that generates them.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/help-doc-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
