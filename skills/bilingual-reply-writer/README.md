# Bilingual Reply Writer

> Customer replies, notices and web copy in Canadian French and English that say the same thing in the same tone, with your product names and terms handled the same way every time

**Category:** Customer Support · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

You sell into Quebec, or you're in Ottawa, Moncton, Sudbury or Winnipeg and a third of your customers write to you in French. Customers in Quebec have the right to be served and informed in French, and everywhere else a reply in someone's own language is the difference between a customer and a review. So you paste the English into a translation site, send it, and the customer gets "we regret the inconvenience of your experience" in a French nobody speaks. Or your product names get translated. Or the formal "vous" and the casual "tu" change from one email to the next. A translator for every reply isn't realistic. A consistent voice in both languages is. This skill keeps it.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill bilingual-reply-writer`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/bilingual-reply-writer/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: where your customers are, formal or casual, your product names, and three messages you send most.
4. Paste a reply, a notice or a page in either language and ask for the pair.
5. When a new term comes up, tell the skill how you want it rendered; it goes in the glossary.

## Example

A kitchen cabinet maker in Cornwall gets a quarter of its orders from Quebec and has been running emails through a free translator. In setup the owner decides on "vous" for customers, keeps the product line names in English, and chooses the Quebec terms for the parts customers ask about. The first paired reply is the delivery delay notice: the French version drops the translation site's "nous regrettons les inconvénients" for a plain sentence a Gatineau customer would write, and the delivery window reads the way Quebec customers expect. The glossary grows to forty terms by spring. When the owner asks for the warranty document, the skill drafts it and flags it for a certified translator before it goes on the website, because a warranty is a contract.

## Pro tip

Decide "vous" or "tu" once and write it into the setup, then don't revisit it reply by reply. Mixed registers read as careless faster than a small grammar error does. And read the French version's length against the English: French runs longer, and a text message that fits in English may split into two in French, which matters for a reminder with a link at the end.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/bilingual-reply-writer). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
