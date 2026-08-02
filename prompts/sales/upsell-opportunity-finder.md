# Upsell & Cross-Sell Finder

> Revenue sitting in your current client list, mapped

**Category:** Sales & Lead Generation · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Chasing new clients while your current ones quietly buy elsewhere is the most common revenue leak in service businesses. Your existing clients trust you, pay on time, and have needs adjacent to what you sell them, yet the mapping of who could use what rarely gets done. Winging it produces awkward pitches to the wrong clients. Mapping it produces a short list of warm conversations with numbers attached.

## The prompt

```
You are a revenue strategist who finds growth inside existing client
lists before spending a dollar on new leads. You believe an upsell is a
service the client already needs, surfaced at the right moment, and
that pitching a client something they don't need burns trust worth far
more than the sale.

MY SERVICES: [EVERYTHING YOU SELL, WITH TYPICAL PRICE FOR EACH,
INCLUDING THINGS YOU COULD OFFER BUT RARELY PITCH]
MY CLIENTS: [8-20 CURRENT CLIENTS. FOR EACH: WHAT THEY BUY NOW, ROUGH
ANNUAL SPEND, HOW LONG THEY'VE BEEN A CLIENT, AND ANY SIGNAL YOU'VE
NOTICED: THINGS THEY'VE COMPLAINED ABOUT, ASKED ABOUT, OR DO IN-HOUSE
BADLY]

STEP 1: SERVICE MAP. Lay out my services as a grid: what each client
buys against what they could buy. Ask clarifying questions about any
service or client I've described too thinly to place. If I sell only
one thing, help me name the 1-2 natural adjacent offers hiding in what
clients keep asking me for, before mapping anything.

STEP 2: SIGNAL SCORING. Score each empty cell in the grid: STRONG (the
client has shown a signal: asked about it, complained about the problem
it solves, or does it in-house badly), POSSIBLE (clients like them
typically need it but this one hasn't signaled), or SKIP (wrong fit,
shaky relationship, or a client already stretched on budget). Every
STRONG needs the signal named; no scoring on vibes.

STEP 3: THE MATH. For the STRONG cells only, show the arithmetic:
service price, times realistic uptake if I asked all of them (assume
one in three says yes, not all of them), equals the revenue on the
table. Then rank the top 5 conversations by revenue times likelihood,
and flag which are one-time projects versus recurring.

STEP 4: THE CONVERSATIONS. For the top 3, write a short opener I can
use at the next natural touchpoint (invoice, check-in, project wrap).
Each opener references their specific signal, proposes a small first
step rather than the full service, and gives them an easy no.

RULES: A client with an unresolved complaint or overdue invoice gets
fixed before they get pitched; flag them and say so. Show every dollar
calculation in full. If my client data contains no signals, don't
invent any: give me the 5 questions to ask on my next round of
check-ins that will surface signals, and tell me to come back with
answers. When the numbers are close, rank recurring revenue above
one-time revenue.
```

## How to use it

1. List services you could offer, not only the ones on your price list. Half the value is spotting the adjacent offer you've been doing for free.
2. Fill in client signals from memory, old emails, and support threads. "Complained twice about their website" is worth more than any demographic.
3. Check the SKIP list before celebrating the STRONG list. Knowing who not to pitch protects the relationships that fund your business.
4. Have the top conversation this week, while the signal context is still loaded in the chat, so you can draft the follow-up on the spot.
5. Rerun the grid twice a year. Client needs shift, and last year's SKIP is sometimes this year's STRONG.

## Example

Input: a 9-person marketing agency with clients on $2,500/month retainers for social and ads; services it could offer include email marketing, landing pages, and quarterly strategy reviews.

Sample output excerpt:

STRONG: Client D (retainer 14 months, spends $30,000/year): asked in March whether you "know anyone who does email," currently sends a monthly newsletter through an intern. Signal: direct ask. Fit: email management at $800/month.

THE MATH: Email management, $800/month, 4 STRONG clients. If all 4 said yes: $38,400/year. Assume one in three: roughly $12,800/year recurring, from conversations with people who already pay you. Landing pages: 2 STRONG at $3,500 one-time; expect one, so $3,500.

CONVERSATION OPENER (Client D): "You asked in the spring if we knew anyone for email. We've since brought it in-house for a few clients, and since your newsletter's going out anyway, want me to sketch what it'd look like if we ran it? If the timing's wrong, no problem, the retainer work doesn't change either way."

## Pro tip

The signals column is the whole tool. Before you run this, spend ten minutes searching your sent mail for "do you guys do" and "know anyone who": clients tell you what to upsell in their own words, months before you think to ask.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/upsell-opportunity-finder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
