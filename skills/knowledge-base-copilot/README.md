# Knowledge Base Copilot

> A help section that answers this month's questions, not the ones from launch day

**Category:** Customer Support · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

The [FAQ & Knowledge Base Builder](/toolbox/faq-knowledge-base-builder) writes a solid help section once, and then reality starts drifting away from it: customers invent new questions, the answers to old ones change, and the article everyone actually needed never gets written because nobody was tracking what people keep asking. A knowledge base is not a document, it is a garden, and gardens need a gardener with a memory. This skill installs one.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill knowledge-base-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/knowledge-base-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Seed it with your current articles, even messy ones.
4. Report questions as they arrive, two lines each; that habit is the entire system.
5. Monthly, read the report, approve the proposed edits, and publish the top item on the to-write list.

## Example

An online pottery-supplies shop seeds the skill with eleven help articles. Over a month, the owner reports questions as they land. The log shows the shipping article answering well (nine hits), the clay-shrinkage article answering badly (three customers asked follow-ups; a fix is proposed with plainer numbers), and a question with no article at all arriving five times: "can I mix your glazes with brand X?" That becomes the top of the to-write list, drafted the same day, in the shop's voice, with the honest "we have tested these six combinations" framing the owner gives it. When the shop changes its free-shipping threshold, one report returns the four articles that mention it with exact edits. The monthly read flags that "where is my order" keeps arriving despite a good article, and suspects the confirmation email is not linking it, which turns out to be true.

## Pro tip

Report the question in the customer's words, not your summary; "do your glazes work on stoneware" and "glaze compatibility" are the same topic and different search behavior, and the article should carry their phrasing. Pair the skill with the [Customer Support Autopilot](/toolbox/customer-support-autopilot): the autopilot answers with the knowledge base, and this skill is what keeps the knowledge base worth answering with.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/knowledge-base-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
