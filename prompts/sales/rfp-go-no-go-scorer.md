# RFP Go/No-Go Scorer

> A twenty-minute decision on whether a tender or RFP is worth the forty hours it takes to answer, scored on the ten things that decide it, with the outline of the response if the answer is go

**Category:** Sales & Lead Generation · **Difficulty:** No-code · **Works with:** ChatGPT, Claude

## The problem

A tender lands from the school board, the municipality, a property manager or a bigger company's procurement portal. It's 60 pages, due in twelve days, and the number at the bottom is exciting. Responding takes forty hours you'd take from paying work, and most small businesses that respond to everything win almost nothing, because the tender was written around an incumbent, or needs bonding you don't have, or scores on criteria you'll never meet. The decision to bid is the most expensive one in the process, and it's usually made on enthusiasm. This prompt makes it on ten questions.

## The prompt

```
You help a small business decide whether to respond to a tender, RFP
or RFQ, and you decide on evidence, not enthusiasm. You score the
opportunity on ten factors, you tell me the cost of bidding, and if
the answer is go, you outline the response.

MY BUSINESS: [WHAT WE DO, SIZE, WHERE, YEARS OPERATING]
THE OPPORTUNITY: [WHO ISSUED IT, WHAT THEY WANT, CONTRACT VALUE OR
ESTIMATE, TERM, DUE DATE]
PASTE OR SUMMARIZE: the mandatory requirements, the evaluation criteria
and their weights, the insurance and bonding requirements, the
references required, the submission format, and any mention of an
incumbent or a previous contract.
OUR HISTORY WITH THIS BUYER: [NONE / SPOKE ONCE / DID WORK BEFORE /
CURRENT SUPPLIER]
OUR CAPACITY: [COULD WE DELIVER IT ALONGSIDE CURRENT WORK, AND WITH
WHAT HIRES OR SUBS]
OUR MARGIN AT THEIR LIKELY PRICE: [BEST GUESS, OR "DON'T KNOW"]
HOURS TO RESPOND: [MY ESTIMATE, OR "DON'T KNOW"]

SCORE THESE TEN, each 0 to 3, with one line of reasoning per score:
1. Do we meet every mandatory requirement today (not after a hire)?
2. Do we have the insurance, bonding, certifications and references
   they require, in hand?
3. Does the evaluation weighting favour what we're strong at (price,
   experience, local presence, approach), or something we're not?
4. Is there an incumbent, and does the document read as written
   around them?
5. Do we know the buyer, and did they know we exist before the tender?
6. Is the contract value worth the response cost (hours × my loaded
   rate) and the risk of losing?
7. Can we deliver with current capacity, or does winning require hires
   we'd be making on hope?
8. Does the timeline allow a careful response, including questions
   during the question period?
9. Does the margin survive their likely price and their payment
   terms?
10. Would winning this help us win the next one, or is it a one-off?

THEN GIVE ME:
- THE TOTAL out of 30, and a verdict: GO (22 or more), GO IF (16 to
  21, with the one or two things that must be true), NO-GO (under 16).
- THE COST OF BIDDING in hours and dollars, against the expected value
  (contract margin × an honest win probability you state and justify).
- THE QUESTIONS to submit in the question period, if any, that would
  change a score.
- IF GO OR GO IF: a response outline that mirrors their evaluation
  criteria in their order, with the evidence we'd put under each, and
  the three things to start on today.
- IF NO-GO: a two-sentence note to the buyer saying we're not bidding
  this time and would like to be considered for future work.

RULES: Score what's written in the tender, not what I hope. If I
don't meet a mandatory requirement, the verdict is NO-GO whatever the
total. Don't inflate the win probability to make the math work.
```

Run it before you open the pricing spreadsheet, and respect the mandatory-requirement rule; a tender you're not eligible for is a tender you can't win however good the response. When the verdict is go, the [Proposal Studio](/toolbox/proposal-studio) writes the response in the buyer's structure, and for the smaller quotes that don't need a full response, the [Proposal Generator](/toolbox/proposal-generator) is enough.

## How to use it

1. Read the tender once with a highlighter for the mandatory requirements, the evaluation criteria and the insurance and bonding section.
2. Fill in the prompt honestly, especially the capacity and margin lines.
3. Run it and read the verdict and the cost of bidding before you read the outline.
4. If it's GO IF, get the one or two things settled (a bonding quote, a reference confirmed, a question answered) before anyone writes a word.
5. Log every verdict and the result, so after a year you know which kinds of tenders you win.

## Example

A twelve-person commercial cleaning company in Winnipeg gets a three-year tender from a school division worth about $400,000 a year. The score comes back 14 out of 30: the mandatory requirements include a performance bond the company has never obtained, the evaluation weights 40 percent on "experience with educational facilities" (the company has none), and the document names the current provider's service schedule as the baseline. The verdict is NO-GO, with a note that a bonding relationship and one school-adjacent contract (a daycare chain) would move two scores next year. The owner sends the two-sentence note to the buyer instead of spending forty hours, and lands the daycare chain in the spring.

## Pro tip

Use the question period. A good question ("would a performance bond be required for a contract under $150,000 a year?") can change a mandatory requirement, and every bidder sees the answer, which means the ones who didn't ask still benefit from you asking. And keep the log. The pattern of what you win is the best bid decision tool you'll ever have, and it takes a year to appear.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/rfp-go-no-go-scorer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
