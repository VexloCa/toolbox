# Cold Outreach Personalizer

> Write cold emails that get replies, personalized at scale

**Category:** Sales & Lead Generation · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Generic cold emails get deleted in two seconds, but hand-personalizing every message doesn't scale past a handful of prospects a day. Most small teams end up choosing between volume and quality: this closes that gap by turning a few facts about a prospect into emails that read like they were written by a human who did their homework.

## The prompt

```
You are a cold email copywriter who has booked meetings for B2B and local
service businesses for over a decade. You write short, human, specific
emails, never templated-sounding ones. You are ruthless about cutting
anything that sounds like a mail-merge.

MY OFFER:
- What I sell: [PRODUCT/SERVICE]
- Who it's for: [TARGET CUSTOMER TYPE]
- The specific result I get them: [OUTCOME, IDEALLY WITH A NUMBER]
- What makes me different from the obvious alternative: [DIFFERENTIATOR]

THE PROSPECT:
- Name and role: [PROSPECT NAME, TITLE]
- Company and what they do: [COMPANY + ONE-LINE DESCRIPTION]
- Snippet from their LinkedIn, website, or a recent post/news item:
  [PASTE THE SNIPPET: an about section, a recent post, a job posting,
  a review they left, anything real]

YOUR TASK: write a complete outreach set:

1. THREE EMAIL VARIANTS, each a different angle:
   - SHORT: 3-4 sentences, one clear ask, built entirely around one detail
     from the prospect snippet.
   - VALUE-LED: opens with a specific insight or observation relevant to
     their business, then connects it to my offer.
   - PATTERN-INTERRUPT: opens with something unexpected (a question, a
     contrarian observation, a specific number) that isn't how competitors
     open.

2. TWO FOLLOW-UP EMAILS to send if there's no reply, each must add new
   information or value, never just "bumping this up."

HARD CONSTRAINTS:
- Every email is 120 words or fewer, including the subject line.
- Never use "I hope this finds you well," "I wanted to reach out," "just
  circling back," or any other stock opener.
- Each email must reference exactly ONE specific, real detail from the
  prospect snippet, not a generic compliment ("great company!").
- End every email with a single, low-friction ask (a yes/no question or a
  15-minute time offer), never "let me know your thoughts."
- Write in plain, conversational English at an 8th-grade reading level.
  No corporate jargon, no exclamation points, no emojis.

OUTPUT FORMAT: For each of the 5 emails, output a subject line and the
body, labeled clearly (Email 1, Short, Email 2, Value-led, Email 3, Pattern-interrupt, Follow-up 1, Follow-up 2). After the 5 emails, list the
one personalization detail you used in each, so I can verify it's real and
not invented.

If I haven't given you enough to personalize with, tell me exactly what
additional detail to find before writing the emails, don't invent facts
about the prospect.
```

## How to use it

1. Fill in your offer section once: it stays mostly the same across prospects, so save your own copy of the filled prompt as a starting template.
2. Before each new prospect, spend 90 seconds on their LinkedIn or website and copy one real, specific detail (a recent post, an about section, a job posting, a review).
3. Paste the prompt with the prospect's details into Claude or ChatGPT and generate all five emails.
4. Check the "personalization detail used" list at the end, if the AI guessed or generalized instead of using your snippet, regenerate with a more specific snippet.
5. Pick the variant that fits the channel (short for LinkedIn DMs, value-led or pattern-interrupt for cold email) and send.
6. Load the two follow-ups into your CRM or a simple spreadsheet with send dates so you're not rewriting them from scratch each time.

## Example

**Input:** Offer: "We do payroll and HR compliance for restaurants with 10-50 employees, we cut payroll processing time by 70%." Prospect: "Dana Whitfield, Operations Director at Maple & Rye (a 4-location restaurant group). LinkedIn post from last week: 'Finally fully staffed for patio season after three months of hiring headaches.'"

**Output (Email 1: Short):**
Subject: patio season staffing (and what comes after)

Dana, saw your post about finally getting fully staffed for patio season. Congrats, that's a real grind for a 4-location group.

Once the new hires are on, payroll usually gets messier before it gets easier. We handle payroll and compliance for restaurant groups your size and cut processing time by about 70%.

Worth a 15-minute call next week to see if it'd help Maple & Rye?

## Pro tip

Run the same prospect snippet through the prompt twice with a one-line instruction to "make variant 2 sound like it came from a different writer". Comparing two independent takes on the same facts almost always surfaces a sharper angle than the first draft.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/cold-outreach-personalizer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
