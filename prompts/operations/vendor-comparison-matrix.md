# Vendor Comparison Matrix

> Compare quotes and vendors on facts, not gut feel

**Category:** Operations & Productivity · **Difficulty:** No-code · **Works with:** Claude, ChatGPT

## The problem

Vendor quotes rarely use the same format, so comparing them means squinting at PDFs, mentally normalizing prices, and hoping you didn't miss a hidden fee buried in the fine print. Most small businesses end up picking based on which salesperson was most likeable rather than which offer is actually best. This turns 2-5 raw quotes into one normalized comparison table with the hidden costs and red flags called out explicitly.

## The prompt

```
You are a procurement analyst who helps small businesses compare vendor
quotes objectively. You are skeptical of sales language and you specifically
hunt for costs and terms that are easy to miss.

WHAT I'M BUYING: [DESCRIBE THE PRODUCT/SERVICE AND WHY YOU NEED IT]

WHAT MATTERS MOST TO ME (rank if possible): [e.g. price, contract
flexibility, support quality, implementation speed]

VENDOR QUOTES (paste each one, labeled by vendor name): [PASTE QUOTE/
PROPOSAL 1] [PASTE QUOTE/PROPOSAL 2] [PASTE ADDITIONAL QUOTES AS NEEDED]

YOUR TASK: produce four things:

1. NORMALIZED COMPARISON TABLE: Columns for each vendor, rows for: base
   price, pricing model (per-seat/flat/usage), contract length, cancellation
   terms, what's included, what's explicitly excluded, implementation
   timeline, and any fee not in the headline price (setup, overage, support
   tier, etc). If a vendor's quote doesn't state something, write "not
   specified, ask" rather than assuming it's zero or included.

2. HIDDEN COSTS & RED FLAGS: Per vendor, list anything that could increase
   total cost beyond the sticker price, and any contract language that
   favors the vendor unusually (auto-renewal without notice, steep early-
   termination fees, vague SLA language).

3. QUESTIONS TO ASK EACH VENDOR: 3-5 specific questions per vendor that
   would close the gaps or resolve the ambiguities you found, not generic
   questions, ones tied to what's actually missing or unclear in their quote.

4. RECOMMENDATION: Which vendor best fits my stated priorities, with the
   reasoning stated in terms of my priorities specifically, not "best
   overall" but "best on [my top priority], acceptable trade-off on
   [lower priority]." If it's genuinely close, say so and name the deciding
   factor I should weigh.

RULES: Do not treat marketing language as fact, if a quote says "industry-
leading support" without specifics, note that as unverified, not as a pro.
Never invent numbers that aren't in the quotes.
```

## How to use it

1. Gather 2-5 vendor quotes or proposals, in whatever format they arrived: PDF text, email body, or a formal proposal doc.
2. State what you're buying and rank what matters most to you before pasting the quotes in, so the recommendation reflects your actual priorities, not generic ones.
3. Paste each quote in full, labeled clearly by vendor name.
4. Review the HIDDEN COSTS & RED FLAGS section closely. This is usually where the real price difference lives.
5. Send the generated QUESTIONS TO ASK back to each vendor before signing anything; a vendor's answers to pointed questions tell you more than their original quote.
6. Re-run the comparison if any vendor sends a revised quote. Don't manually patch the old table.

## Example

Input: comparing two point-of-sale system quotes for a 2-location retail shop: Vendor A quotes $89/month flat, Vendor B quotes "$59/month per register" with a separate line for "payment processing fee."

Sample output excerpt:

NORMALIZED COMPARISON TABLE:
| | Vendor A | Vendor B |
|---|---|---|
| Base price | $89/mo flat | $59/mo per register ($118/mo for 2) |
| Contract length | 12 months | 24 months |
| Cancellation | 30 days notice | not specified: ask |

HIDDEN COSTS & RED FLAGS: Vendor B's payment processing fee is not quantified in the quote. Likely adds meaningfully to true monthly cost. Vendor B's 24-month term has no stated early-termination clause, which is itself a red flag.

RECOMMENDATION: Vendor A fits your stated priority of contract flexibility better. Shorter term, clear cancellation terms, and a comparable total price once Vendor B's per-register pricing and unclear processing fee are accounted for.

## Pro tip

Ask every vendor the exact same follow-up questions from the QUESTIONS TO ASK section and paste their written answers back into a second pass of this prompt. Verbal reassurances from a sales call disappear, but a written answer becomes something you can hold them to.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/vendor-comparison-matrix). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
