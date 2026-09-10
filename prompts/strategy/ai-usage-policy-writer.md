# AI Usage Policy Writer

> One page of house AI rules your team will read, before the first incident instead of after

**Category:** Strategy & Planning · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

The day AI lands on every desk (and with [Copilot now bundled into Microsoft 365 plans](/blog/microsoft-365-business-copilot-bundled), that day already happened for a lot of teams) is the day someone pastes a customer list into a chatbot to "clean it up." Not from malice; nobody ever said not to. Most small businesses run AI with zero written rules, and the corporate AI policies floating around are eight pages of legal language no seven-person company will ever read. What actually gets followed is one page, written for your business, with your examples. This prompt writes that page.

## The prompt

```
You are helping a small business owner write a one-page AI usage
policy their team will actually read and follow. Practical rules,
not legal boilerplate. Concrete examples over abstractions.

MY BUSINESS: [WHAT YOU DO, TEAM SIZE, WHO USES AI FOR WHAT TODAY]
AI TOOLS IN USE: [E.G. COPILOT ON EVERY SEAT, CHATGPT PLUS ON 2,
WHATEVER STAFF USE PRIVATELY THAT YOU KNOW ABOUT]
SENSITIVE STUFF WE HANDLE: [CUSTOMER DATA, HEALTH INFO, PRICING,
CONTRACTS, EMPLOYEE RECORDS, WHATEVER APPLIES]
WHAT PROMPTED THIS: [BE HONEST: NEW TOOL ROLLOUT, A NEAR MISS, A
CLIENT ASKED, JUST OVERDUE]

WRITE THE POLICY IN 5 SHORT SECTIONS:
1. WHAT'S ENCOURAGED: The uses we want more of, named
   specifically ("drafting replies, summarizing meetings"), so
   the policy reads as permission, not prohibition.
2. WHAT NEVER GOES IN A PROMPT: The specific categories from my
   sensitive list, each with one realistic example of the
   mistake ("pasting the client spreadsheet to deduplicate it").
   Include the approved alternative for each.
3. WHAT NEEDS HUMAN REVIEW BEFORE IT SHIPS: Anything customer-
   facing, anything with numbers, anything legal. State who
   reviews what.
4. LABELING: When AI drafts must be marked as drafts, and the
   one-line way to do it.
5. WHEN SOMETHING GOES WRONG: Who to tell, and the promise that
   telling fast is never punished. Two sentences maximum.

RULES: One page total. No "utilize," no "stakeholders," no
paragraph a busy person skims. Every rule gets a reason in
brackets, because rules without reasons get ignored. If my
answers reveal a risk I did not ask about, flag it under the
policy in a P.S. rather than silently expanding the scope.
```

The "what's encouraged" section going first is deliberate: a policy that opens with prohibitions teaches the team to hide their AI use, which is the actual worst outcome. Pair the finished page with the tool decisions themselves; the [SME AI Starter Stack](/toolbox/sme-ai-starter-stack) covers which tools deserve a seat, and this covers how the seats behave.

## How to use it

1. Copy the full prompt into Claude or ChatGPT and answer honestly, including the tools staff use that you never sanctioned.
2. Edit the draft down, not up; anything you would not enforce, delete.
3. Walk the team through it in ten minutes, examples first. Ask what it forgot.
4. Post it where the team actually looks, and revisit when a new tool arrives.
5. When an incident or near miss happens, update the example list the same week, while it is a story instead of a rule.

## Example

An accounting practice with nine staff fills it in: Copilot on all seats since the plan upgrade, client financials everywhere, prompted by a junior pasting a client's trial balance into free ChatGPT to "check the totals." The policy comes back with client-identifiable financials in the never-list (approved alternative: the anonymized-numbers version, or Copilot inside the tenant), returns-adjacent outputs flagged for partner review, and a P.S. flagging a risk the owner had not named: the practice's own fee schedule, which two staff had been pasting into prompt examples. The team meeting takes twelve minutes, and the near-miss junior is the one who suggests the labeling rule.

## Pro tip

Date the policy and put the tool list in it. Six months from now, "written back when we only had Copilot" is the sentence that tells you it needs the ten-minute refresh, and a dated policy is also the thing a nervous enterprise client asks to see before signing; a one-pager with a current date reads better in that meeting than eight perfect pages from last year.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-usage-policy-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
