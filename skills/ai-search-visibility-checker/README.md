# AI Search Visibility Checker

> A monthly read of what ChatGPT, Perplexity, Copilot and Google's AI answers say when someone asks for a business like yours, and the five page fixes that change the answer

**Category:** Marketing & Content · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

A growing share of your next customers won't type your category into Google and scroll. They'll ask ChatGPT, Perplexity or Copilot for "a good family dentist in Burlington that takes new patients", or they'll read the AI answer at the top of Google and stop there. Either you're in that answer or you aren't, and most owners have never checked. When they do check, the answer names two competitors and a clinic that closed in 2024. Nothing about the AI is personal. It's reading what's on the web about you, and what's on the web is thin, old, or missing the facts the question needs. This skill runs the check and tells you what to fix.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill ai-search-visibility-checker`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/ai-search-visibility-checker/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: what you do, for whom, where, and the three competitors customers compare you with.
4. Run the question set it writes in ChatGPT, Perplexity, Copilot and a Google search, and paste the answers back for scoring.
5. Work the fix list top down, then re-run the same questions in a month.

## Example

A physiotherapy clinic in Burlington runs the 18 questions. It's named in two answers, described as "a sports injury clinic" (it stopped marketing that way in 2022), and absent from every question that mentions direct billing or evening hours, both of which it offers. The two competitors named every time each have a page titled "Fees and direct billing" with the insurers listed. The fix list starts there: a fees page with the insurers and the evening hours, a questions page built from the front desk's call log, the Google profile's services list filled in, and a correction to a directory listing from 2019. Six weeks later, the clinic is named in eleven of the eighteen answers, and described the way it describes itself.

## Pro tip

Ask the assistants the question the way a stressed customer would, with the constraint attached: "open Saturday", "takes Blue Cross", "under $150". The constraint is where you win or lose, because the assistant can only name you if that fact is written somewhere it can read. And put the answers to those constraints on your own site in plain sentences, not in a PDF or an image. The assistants read text.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/ai-search-visibility-checker). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
