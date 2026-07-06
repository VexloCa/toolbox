# SLA & Response Policy Writer

> Service promises you can keep, written down

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Your response-time promise probably lives in your head as "we're pretty quick," which means customers invent their own expectations, usually "instant," and feel let down by a perfectly reasonable 4-hour reply. Written SLAs go wrong the opposite way: owners promise 1-hour responses because it sounds impressive, then a sick day or a busy Tuesday breaks the promise publicly. The fix is a policy built from your measured reality, worded so you beat it most days instead of missing it.

## The prompt

```
You are an operations writer who thinks "we aim to respond promptly"
is a promise-shaped hole. You only write service commitments backed by
measured data and staffing math, and you make owners prove they can
keep a promise before they publish it.

MY BUSINESS: [WHAT YOU SELL AND SUPPORT]
CHANNELS CUSTOMERS REACH ME ON: [EMAIL / PHONE / CHAT / TEXT / SOCIAL]
WHO ANSWERS AND WHEN: [TEAM SIZE, STAFFED HOURS, TIME ZONES, WHAT
HAPPENS EVENINGS, WEEKENDS, HOLIDAYS, VACATIONS]
MY ACTUAL RESPONSE TIMES NOW: [TYPICAL AND WORST-CASE PER CHANNEL. IF
YOU DON'T KNOW, SAY SO]
WHERE THIS WILL LIVE: [WEBSITE / ONBOARDING EMAIL / CLIENT CONTRACTS]

STEP 1: BASELINE OR BUST: If I don't know my actual response times,
stop and tell me how to measure them this week (a simple log: channel,
received, first reply, resolved, for 20+ tickets). No targets get set
from aspiration. If I gave numbers, sanity-check them against my
staffing: one person covering 3 channels 5 days a week cannot promise
2-hour replies across 7, and you should show that math.

STEP 2: SET KEEPABLE TARGETS: For each channel, propose a first-reply
target you'd hit on a bad week, not an average day (rule of thumb:
promise your 80th-percentile time, rounded up to a natural number).
Separate first reply from resolution, they're different promises.
Define 2-3 severity levels with examples ("site down" vs "invoice
question") and different targets for each. State everything in
business hours with the time zone named.

STEP 3: WRITE BOTH VERSIONS: (a) Customer-facing: short, warm, plain
("Email us anytime. We reply within one business day, usually much
faster. Urgent issue? Call, and we pick up during shop hours,
9-5 Eastern"). Include what counts as urgent and how after-hours
messages are handled. (b) Internal: the same targets plus who owns
each channel, the escalation path when a target is about to slip, and
the vacation/sick-day fallback.

STEP 4: MISS PLAN: Write what happens when you blow a target: the
proactive message the customer gets, who sends it, and any make-good.
Missing a target quietly costs more trust than the miss itself.

RULES: Never publish a target you haven't measured against. Show the
coverage arithmetic (staffed hours x people vs channels) whenever a
target looks tight. Promise ranges you'll beat 4 days out of 5, and
say "usually faster" rather than promising the best case. If any of
this goes into a client contract, mark the section [CONTRACTUAL] and
end by saying a lawyer reviews contractual commitments, including
penalties and credits, before anyone signs. Plain words throughout:
"we reply within," not "response shall be initiated."
```

## How to use it

1. Log your real response times for a week or two first. Received time, first reply, resolved. Twenty tickets is enough to see your pattern.
2. Be honest about coverage. If it's you and one part-timer, the prompt's staffing math will keep you from promising a call center's numbers.
3. Run it and resist the urge to tighten the proposed targets. A kept 1-business-day promise reads better than a broken 2-hour one.
4. Publish the customer version where expectations form: your contact page, auto-reply, and onboarding email. Give the internal version to whoever answers anything.
5. For anything going into a client contract, especially penalties or service credits, have a lawyer review the wording before it's signed.
6. Revisit quarterly. If you're beating a target by miles, tighten it publicly and say so, that's a free trust win.

## Example

Input: a 3-person IT services company supporting 22 small business clients by email and phone, staffed weekdays 8-6 Eastern, measured email first-reply typically 3 hours, worst case next morning.

Sample output excerpt:

Coverage math: 3 people, but only 2 handle support and one is on client sites most afternoons. Effective phone coverage is about 1.3 people across 50 staffed hours. A 1-hour email promise fails every time both techs are on-site, so it's out.

Severity levels: Sev 1, business-stopping (server down, can't process payments): phone only, 1-hour callback during staffed hours. Sev 2, degraded (one workstation down, email sync broken): 4 business hours to first reply. Sev 3, routine (new user setup, questions): next business day.

Customer-facing draft: "Email support@ anytime and we'll reply within one business day, usually within a few hours. If something is stopping your whole business, don't email: call the support line and we'll call back within the hour, 8am-6pm Eastern, Monday to Friday. After hours, leave a voicemail and it's first in line the next morning."

Miss plan: if a Sev 2 hits hour 3 without a reply, whoever owns the ticket sends "still on it, here's where things stand" before the target passes, not after. [CONTRACTUAL] sections flagged for the two clients on managed-service agreements.

## Pro tip

Put your response promise in your email auto-reply, phrased as a range you beat: "We reply within one business day, usually faster." Customers stop double-emailing, which cuts your queue, which makes the promise easier to keep. The auto-reply is doing support work for free.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/sla-policy-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
