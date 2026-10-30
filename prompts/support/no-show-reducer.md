# No-Show Reducer

> A reminder sequence, a plain-language late-cancellation policy and a rebooking message built for your business, so the empty 2 p.m. slot stops being a weekly event

**Category:** Customer Support · **Difficulty:** No-code · **Works with:** ChatGPT, Claude

## The problem

A clinic, a salon, a tutor, a detailer, a contractor's estimate visit: every appointment business loses a slot or two a week to someone who didn't come and didn't call. The slot can't be resold at 1:55. The fix most owners reach for is a stricter policy nobody reads, or a reminder sent so late it's a notification, not a nudge. A good reminder sequence is three messages at the right times with the right words, a policy stated in one plain sentence at booking, and a graceful way to fill the slot and rebook the person. This prompt writes all three for your business, in your tone.

## The prompt

```
You design a no-show reduction system for an appointment-based small
business: the reminder sequence, the late-cancellation policy in plain
words, and the messages that fill a slot and rebook a customer.

MY BUSINESS: [WHAT YOU DO, WHERE, AND WHO BOOKS WITH YOU]
A TYPICAL APPOINTMENT: [LENGTH, VALUE TO ME, HOW FAR AHEAD PEOPLE BOOK]
HOW I BOOK TODAY: [PHONE / ONLINE TOOL / TEXT / WALK-IN]
HOW I CAN SEND MESSAGES: [TEXT / EMAIL / BOTH / THROUGH MY BOOKING APP]
MY TONE WITH CUSTOMERS: [FORMAL / FRIENDLY / SOMEWHERE BETWEEN]
MY NO-SHOWS LAST MONTH: [ROUGH COUNT, AND WHAT YOU KNOW ABOUT WHY]
DO I WANT TO TAKE DEPOSITS: [YES / NO / NOT SURE]
ANY RULES I MUST FOLLOW: [E.G. HEALTH PRIVACY, NO TREATMENT DETAILS
IN A TEXT]

WRITE:
1. THE REMINDER SEQUENCE: a booking confirmation (sent at once), a
   reminder 48 hours before with a one-tap way to confirm or
   reschedule, and a reminder two hours before with the address and
   what to bring. Each under 240 characters for text, with an email
   version if I said email. No treatment or service details if I
   named a privacy rule.
2. THE POLICY, in one plain sentence for the booking page and one
   for the confirmation message: the notice I need, what happens
   without it, and whether a deposit applies. Then a three-line
   version for my website.
3. THE DEPOSIT DECISION: if I said "not sure", tell me when a deposit
   helps and when it costs more bookings than it saves, for a
   business like mine, and what amount is usual.
4. THE SAME-DAY FILL: a short message to a waitlist or to the last
   three customers who asked for a sooner slot, offering the opening.
5. THE REBOOKING MESSAGE: a kind, firm message to the person who
   didn't show, applying the policy and offering the next slot.
6. THE REPEAT RULE: what I do the second time it happens with the same
   person, stated so my front desk can apply it without me.

RULES: Short, warm, specific. No guilt-trips. Use my tone. Every
message has one action in it.
```

Put the policy sentence in the booking confirmation, not only on the website; the person who no-shows never read the website. Once the sequence is running, the replies to "can I move to Thursday" come from the [Support Macro Library](/toolbox/support-macro-library), and if a receptionist product sends the reminders, the [AI Receptionist Script Writer](/toolbox/ai-receptionist-script-writer) carries the same wording into the phone flows.

## How to use it

1. Count last month's no-shows and note what you know about them (new customers, a particular day, a particular service).
2. Fill in the prompt, including how you can send messages, because the sequence is only as good as the channel.
3. Load the three reminders into your booking tool or your phone's templates, and the policy sentence into your confirmation.
4. Use the same-day fill message the first time a slot opens; it works more often than owners expect.
5. After a month, count again, and adjust the 48-hour message if confirmations are low.

## Example

A physiotherapy clinic in Burlington loses about six appointments a week, mostly new patients booked two weeks out. The prompt returns a confirmation that states the 24-hour policy in one sentence, a 48-hour reminder with "reply Y to confirm or R to reschedule", and a two-hour reminder with parking directions. No treatment details appear in any text, because the clinic named the privacy rule. The deposit section recommends a $25 deposit for new patients only, credited to the visit, with a note that regulars should be exempt. The rebooking message applies the fee once, kindly, and offers two slots. A month later the count is two a week, both regulars with real reasons, and the deposit has become a line on the booking page nobody argues with.

## Pro tip

Make the 48-hour message answerable with one letter. A reminder that requires a phone call to reschedule turns into a no-show; one that takes a "R" gets you the slot back in time to fill it. And when the policy fee is charged, charge it once, with the rebooking offer in the same message. The fee is for the slot, and the offer is for the relationship.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/no-show-reducer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
