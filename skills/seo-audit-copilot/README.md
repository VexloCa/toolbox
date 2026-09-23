# SEO Audit Copilot

> A prioritized SEO fix list in plain English, no agency retainer

**Category:** Marketing & Content · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT, Claude Code

## The problem

SEO advice arrives in two flavors: a $2,000-a-month agency retainer, or a free automated audit that dumps 200 "critical errors" ranked by nothing. Neither tells a busy owner the thing they need to know: which three fixes are worth this month's limited hours, and why. So the audit PDF gets filed next to the gym membership, and the site keeps ranking on page four for the searches that would bring actual customers.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill seo-audit-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/seo-audit-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, Cursor. Anything that can fetch a URL or accept pasted text).
3. Answer the skill's setup questions about your business and the searches you want to win.
4. Export 3 months of Search Console performance data (queries and pages) and paste it in for the first audit.
5. Paste the copy, title, and description of your 3 most important pages for page reviews.
6. Work the fix list top to bottom, then re-export Search Console in 6 to 8 weeks and compare.

## Example

Say you run a furnace repair company in Winnipeg. You paste your homepage copy and a 3-month Search Console export. Output (condensed): "Top priority: your homepage title tag is 'Home | [Company Name]', which wastes your most valuable slot; suggested rewrite: 'Furnace Repair Winnipeg: Same-Day Service'. Second: 'furnace not blowing hot air' gets you 340 impressions at position 11 with no page addressing it; a 600-word page answering that one problem is your fastest win. Third: your service page mentions 'HVAC solutions' six times but 'furnace repair' once; searchers use the second phrase. Lower priority: meta descriptions missing on 4 pages (impact: modest, effort: 20 minutes). Not checked: site speed and mobile rendering, which I can't see from pasted text. No ranking is guaranteed; these changes improve your odds, nothing more."

## Pro tip

Paste the top-ranking competitor's page next to yours and ask what they do that you don't. The comparison is where vague advice turns specific: it stops being "add more content" and becomes "they answer the cost question in the first screen and you never answer it at all."

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/seo-audit-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
