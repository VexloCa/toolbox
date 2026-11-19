# AI Consultant Proposal Checker

> An AI consultant's proposal or quote read before you sign it, with the price set against published rate bands, the scope gaps listed, the red flags named and the five questions to send back

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

Two AI consultants looked at the same job, automating your quote follow-ups. One sent a page that says $4,800. The other sent eleven pages that say $22,000. Both sound sure of themselves, and you have no way to tell which number is closer to fair, because you've bought this exactly zero times before. The hourly rate isn't on either one. Neither says who does the work, what you own when it's finished, or what happens in month three when the thing breaks. So you pick on gut feel, or you pick the cheaper one, or you put it off for another quarter. A plumber's quote you can read. This one needs a translator.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill ai-consultant-proposal-checker`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/ai-consultant-proposal-checker/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: your business, staff count, province or state, and the job you want done.
4. Paste the proposal or quote and ask for the price verdict and the scope check.
5. Send the five questions, and paste the consultant's answers back in for a second read before you decide.

## Example

A nine-person landscaping company in London, Ontario gets a proposal: $14,500 for "an AI-powered lead response system", six weeks, 50 percent up front. The skill works out roughly 60 hours of work from the timeline and task list, which puts the implied rate near $240 an hour, inside the published band for a senior consultant at a Canadian boutique. The price is not the problem. The scope check finds four gaps: no definition of done, no named person doing the build, tool costs "billed separately" with no estimate, and nothing on who owns the automations if the relationship ends. One red flag: the proposal skips discovery and promises "40 percent more booked jobs". The email asks for an acceptance test, a name, a monthly tool estimate in dollars, written ownership of the build, and a two-week paid discovery before the main fee.

## Pro tip

Ask every consultant the same question before you compare prices: "What will I be able to do on my own the day you leave?" A good answer names the logins you'll hold, the document that explains the build and the hour of training your staff gets. A vague answer tells you the monthly retainer is the real product. And if a quote has no discovery step, ask for one as a separate, small, fixed-fee job. It's the cheapest way to find out how the consultant works.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-consultant-proposal-checker). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
