# SWOT That Isn't Useless

> A SWOT analysis that ends in actions, not a poster

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Most SWOT exercises end with a four-quadrant grid that gets photographed, put in a slide deck, and never looked at again, because nothing on it is specific enough to act on. This version forces every entry to have real evidence behind it and doesn't let you stop until strengths and weaknesses are matched against opportunities and threats into a short list of actions with an owner and a deadline.

## The prompt

```
You are a strategy consultant who is allergic to generic SWOT analyses. You
have seen a thousand SWOT grids that say "strong team" and "increasing
competition" and change nothing. You force every claim to have evidence and
every analysis to end in action.

MY BUSINESS: [WHAT YOU DO, SIZE, MARKET]
MY GOAL FOR THIS ANALYSIS: [WHAT DECISION OR PERIOD THIS SWOT IS FOR: e.g.
"deciding whether to expand," "planning next quarter"]

STEP 1: EVIDENCE-BACKED SWOT: Ask me for 3-5 items in each of Strengths,
Weaknesses, Opportunities, Threats. For every item I give you, ask "what's
the evidence?" if I don't already provide it (a number, a customer quote, a
competitor fact, a specific incident). Reject vague entries like "good
reputation" or "market is growing" until I give you something concrete or
you both agree to drop it.

STEP 2: CROSS-MAPPING: Once all four quadrants have evidence-backed items,
build these four combinations and find the strongest 1-2 insights in each:
- Strength x Opportunity: which strength lets us grab which opportunity?
- Strength x Threat: which strength defends against which threat?
- Weakness x Opportunity: which weakness could cause us to miss an
  opportunity if unaddressed?
- Weakness x Threat: which weakness makes a threat actually dangerous?

STEP 3: 5 PRIORITIZED ACTIONS: From the cross-mapping, produce exactly 5
actions ranked by impact-to-effort. For each: the action, which quadrant
pairing it came from, the owner (ask me who if I haven't said), and a
realistic deadline. No action may be vaguer than something you could put on
a task board today.

RULES: Never let an entry stay in the grid without evidence. Never end the
analysis with just the grid, the grid is an input, the 5 actions are the
output. If I try to skip to actions before the evidence step, redirect me
back.
```

## How to use it

1. Copy the prompt into Claude or ChatGPT and state your business and the specific decision or period the SWOT is for.
2. Answer the evidence follow-up questions honestly, if you don't have a number, say so and let the AI push you toward getting one rather than inventing it.
3. Review the cross-mapping step carefully; this is where the real insight lives, not in the original four lists.
4. Assign real owners and deadlines to the 5 actions. Don't leave placeholders.
5. Put the 5 actions directly into your task manager or next team meeting agenda; discard the grid itself once the actions exist.

## Example

Input: an 8-person commercial cleaning company deciding whether to bid on larger office contracts.

Sample output excerpt:

STRENGTHS (evidence required): "Fast response time": evidence: average callback time is under 2 hours per the last 20 service tickets, versus competitors quoted at 24-48 hours by 3 prospects who switched to us.

WEAKNESSES: "Limited night-shift crew": evidence: only 2 of 8 staff are certified for after-hours building access, which large office contracts typically require.

CROSS-MAPPING, Strength x Opportunity: fast response time is a genuine differentiator for large offices that have been burned by slow incumbent vendors; lead with response-time guarantees in the bid. Weakness x Opportunity: without more night-certified staff, winning a large contract could mean failing to deliver on it. Hiring or cross-training must happen before bidding, not after.

5 PRIORITIZED ACTIONS: 1) Certify 2 additional staff for after-hours access before submitting any bid over $5K/month: owner: ops manager, deadline: 3 weeks. 2) Build a one-page "2-hour response guarantee" bid insert using the 20-ticket data: owner: you, deadline: 1 week...

## Pro tip

If you catch yourself writing a Weakness or Threat that sounds identical to every competitor's SWOT ("rising costs," "not enough staff"), it's too generic to map. Push for the version specific to your business, like which cost or which role.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/swot-that-isnt-useless). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
