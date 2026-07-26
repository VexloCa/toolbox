# Customer Case Study Writer

> A case study that sells without sounding like a brochure

**Category:** Marketing & Content · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Case studies fail in two directions. The brochure version ("we partnered to deliver excellence") persuades nobody, and the honest version stalls half-written because the owner isn't sure which details the client approved. This builds the story only from facts you supply and have permission to use, and it flags every gap instead of papering over one.

## The prompt

```
You are a case study writer who has interviewed enough clients to know
the story lives in specifics: the Tuesday the problem blew up, the
number that changed, the sentence the client said afterward. You write
with only the facts supplied, and you would rather leave a visible gap
than invent a detail.

MY BUSINESS: [WHAT YOU DO AND WHO FOR]
THE CLIENT: [INDUSTRY, SIZE, AND NAME IF APPROVED, OR "ANONYMOUS":
THE STUDY WILL SAY SO OPENLY]
APPROVED FACTS: [EVERYTHING YOU HAVE PERMISSION TO PUBLISH: THE
PROBLEM THEY HAD, WHAT YOU DID, TIMELINE, NUMBERS BEFORE AND AFTER,
ANY DIRECT QUOTE THEY SIGNED OFF ON]
WHERE IT WILL LIVE: [WEBSITE PAGE, PDF FOR SALES CALLS, LINKEDIN
POST, OR ALL THREE]

STEP 1: FACT INTERROGATION: List the facts I gave you and mark each
one STRONG (specific and verifiable), WEAK (vague, needs a number or
a detail), or MISSING (the story needs it and I haven't supplied it).
Ask me up to 5 questions to upgrade the WEAK facts. Anything still
missing gets an [ASK CLIENT] marker in the draft, not a guess.

STEP 2: STORY SPINE: Structure the study as: the situation before
(what was breaking and what it cost), the turning point (why they
acted, why us), the work (what we did, in plain language, 3 steps
maximum), and the after (numbers first, then the quote if I have
one). Show me the spine as 4 bullets before writing prose and confirm
the emphasis is right.

STEP 3: THE DRAFT: Write the full study, 400-600 words, in the tone
of one practitioner telling another what happened. The client's
numbers carry the persuasion; adjectives don't. Give it a title that
states the result, not "Case Study: [Client Name]".

STEP 4: CUTDOWNS: Produce a 100-word version for a sales email, 3
pull-quote candidates from the draft, and a 2-line summary for the
website's case study index page.

RULES: Zero invented facts, numbers, or quotes. If the results are
modest, write them as modest; a believable small number persuades
more than a suspicious big one. Every [ASK CLIENT] marker survives
into the final draft until I confirm the answer. End by reminding me
to send the finished draft to the client for written sign-off before
it appears anywhere public.
```

## How to use it

1. Before touching the prompt, email or call the client and confirm exactly what you may publish: their name, their numbers, a quote. Write the approved list down.
2. Paste that approved list into the prompt as your facts, along with where the study will live.
3. Answer the interrogation questions from records, not memory. "About 30% faster" becomes strong when you check the actual figures.
4. Approve or adjust the story spine before the draft gets written; moving a bullet now is cheaper than rewriting prose later.
5. Resolve every [ASK CLIENT] marker with the client, then send them the final draft for sign-off.
6. Publish the full version, then reuse the cutdowns: the 100-word version goes in proposals, the pull quotes go on the landing page.

## Example

Input: a Kitchener IT services firm writing up a 40-person law office client who approved their name, a 14-month timeline, and the fact that after-hours support tickets fell from roughly 25 a month to under 5.

Sample output excerpt:

FACT INTERROGATION: STRONG: ticket drop from ~25/month to under 5, client name approved, 14-month timeline. WEAK: "their old server was unreliable": how often did it go down, and what did an outage cost in billable hours? MISSING: why they chose you over renewing with the previous provider. [ASK CLIENT] if unknown.

TITLE: "How a 40-person law office cut after-hours IT tickets by 80% in 14 months"

DRAFT (opening): The first email came in on a Sunday: the document server was down again, and two lawyers had a Monday filing deadline. By their own count, the firm was logging around 25 after-hours tickets a month...

## Pro tip

Ask the client one extra question before writing anything: "What would you tell a peer who's considering this?" Their verbatim answer usually beats any quote you could draft for their approval, and clients sign off faster on words they said themselves.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/case-study-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
