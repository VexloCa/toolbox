# Annual Planning Workshop

> Run a one-day annual planning session: solo or with your team

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Annual planning at most small businesses either doesn't happen or happens in a rushed afternoon that produces a vague statement like "grow 20%" and nothing else. A real planning process takes a full day and a facilitator, both of which are expensive to hire. This workflow gives you five structured working sessions (each with its own ready-to-use prompt), that take you from last year's actual results to a finished one-page plan by the end of the day.

## The workflow

Run these five steps in order, in a single day if possible. Each step has its own prompt. Copy it into Claude or ChatGPT, fill in the brackets, and carry the output forward into the next step. Block 60-90 minutes per step; if running this with a team, do steps 1-3 solo first, then bring the group in for steps 4-5.

### Step 1: Year-in-review extraction

```
You are helping me conduct an honest year-in-review before I plan next
year. Your job is to pull out the real signal from what actually happened
this year, not what I wish had happened.

WHAT I KNOW HAPPENED THIS YEAR: [PASTE WHATEVER YOU HAVE: REVENUE NUMBERS,
KEY WINS, THINGS THAT FELL APART, CUSTOMER FEEDBACK, TEAM CHANGES]

YOUR TASK:
1. WINS: The 3-5 things that worked, with the reason they worked (not just
   that they happened).
2. MISSES: The 3-5 things that didn't go as planned, with the most likely
   root cause, not the surface excuse.
3. SURPRISES: Anything that happened that nobody planned for, good or bad.
4. ONE HONEST SENTENCE: If you had to summarize this year in one blunt
   sentence for the owner to hear, what would it be?

RULES: Don't soften the misses. Don't credit luck as strategy. If I haven't
given you enough information to assess something, say so instead of
guessing.
```

### Step 2: Market shift scan

```
You are a market analyst helping me understand what's changed around my
business since I last planned, so I don't plan for a market that no longer
exists.

MY BUSINESS AND MARKET: [WHAT YOU DO, WHO YOU SERVE, YOUR REGION/NICHE]
WHAT I'VE NOTICED CHANGING: [COMPETITOR MOVES, CUSTOMER BEHAVIOR SHIFTS,
COST CHANGES, NEW TECHNOLOGY, REGULATION, WHATEVER YOU'VE OBSERVED]

YOUR TASK:
1. Organize what I've told you into: customer shifts, competitive shifts,
   cost/supply shifts, and technology/regulatory shifts.
2. For each shift, tell me whether it's a threat, an opportunity, or both, and why.
3. Flag the ONE shift most likely to hurt me if I ignore it, and the ONE
   most likely to help me if I lean into it.
4. Ask me up to 3 questions about shifts I might be missing, based on my
   industry, that I haven't mentioned.

RULES: Don't invent market data I haven't given you or that isn't common
knowledge for my stated industry, flag anything you're inferring versus
stating from what I told you.
```

### Step 3: 3-scenario visioning

```
You are helping me stress-test next year by imagining three different
versions of it before I commit to a plan.

MY YEAR-IN-REVIEW SUMMARY: [PASTE OUTPUT FROM STEP 1]
MY MARKET SHIFTS SUMMARY: [PASTE OUTPUT FROM STEP 2]

YOUR TASK: write three short scenarios for next year, 150 words each:
1. FLAT: Nothing major changes, I execute steadily, no big bets pay off or
   fail. What does the business look like?
2. BREAKOUT: My best bet this year actually works. What specifically had to
   go right for that, and what would I need to have in place to handle it?
3. STRAINED: My biggest risk from the market scan actually happens. What
   breaks first, and what's the minimum response that keeps the business
   intact?

THEN: name the ONE capability or resource that shows up as necessary across
all three scenarios, that's likely your top investment priority regardless
of which future happens.

RULES: Ground each scenario in what I've told you about my business, not
generic industry speculation.
```

### Step 4: Goal-setting

```
Using everything from the year-in-review, market scan, and three scenarios
above, help me set 1-3 annual objectives for next year that account for
the breakout upside and the strained downside, not just the flat scenario.

YEAR-IN-REVIEW: [PASTE STEP 1 OUTPUT]
MARKET SHIFTS: [PASTE STEP 2 OUTPUT]
THREE SCENARIOS: [PASTE STEP 3 OUTPUT]

Give me 1-3 annual objectives in plain language, each with a one-sentence
reason it's the right bet given all three scenarios. Then tell me: these
annual objectives should become the input to a quarterly OKR-setting
session for Q1, restate each as a starting point for that conversation.
```

### Step 5: One-page plan assembly

```
Assemble everything from this planning day into a single one-page annual
plan I could put on the wall or share with my team.

INPUTS: [PASTE OUTPUTS FROM STEPS 1-4]

FORMAT: exactly one page:
- One-sentence honest summary of last year
- Top 2 market shifts to watch
- The capability that matters across all three future scenarios
- 1-3 annual objectives
- The single most important thing to get right in Q1

RULES: Ruthlessly cut anything that doesn't fit on one page. If something
important doesn't make the cut, list it separately as "parked for later,"
don't force it in.
```

## How to use it

1. Block a full day (or a half-day solo, spread across a week if that's more realistic for your schedule).
2. Run steps 1-3 alone first, using real numbers and honest self-assessment. The outputs only help if the inputs are true.
3. Bring your team in for steps 4-5 if you have one; share the scenario outputs from step 3 before the discussion so everyone starts from the same picture.
4. Carry each step's output into the next prompt exactly as instructed. Don't skip steps or reorder them.
5. Print or pin the one-page plan from step 5 somewhere visible; revisit it at each quarterly planning session.
6. Immediately after this workshop, run the annual objectives from Step 4 through the quarterly OKR builder to set your Q1 targets.

## Example

Input: a 7-person specialty pet grooming business, year-in-review shows steady revenue but a key groomer left mid-year causing a 6-week booking backlog; market scan flags a new competitor offering mobile grooming.

Sample output excerpt (Step 3, Strained scenario): "Losing another skilled groomer would be the single point of failure. With no cross-trained backup and a 6-week backlog precedent already set, one departure could stall bookings again. Minimum response: cross-train at least one groomer in every specialty service before it's needed, not after."

Step 5 one-page plan (excerpt): "Capability that matters across all scenarios: groomer redundancy: at least one backup trained per specialty. Q1 priority: cross-train two groomers before peak spring season."

## Pro tip

Do not skip the "flat" scenario in Step 3 even though it feels boring. It's usually the most likely outcome, and plans that only account for breakout or strained futures tend to overreact in one direction.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/annual-planning-workshop). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
