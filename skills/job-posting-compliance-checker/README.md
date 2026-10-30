# Job Posting Compliance Checker

> Every job ad checked against Ontario's 2026 posting rules before it goes live, with the pay range, the AI line and the vacancy statement where the law wants them

**Category:** HR & Hiring · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

Since January 1, 2026, a publicly advertised job posting in Ontario has to carry things it never used to: the expected pay or a range no wider than $50,000, a line saying whether you use AI to screen or assess applicants, a statement on whether the job is an existing vacancy, and no mention of Canadian experience. Interviewed candidates have to hear back within 45 days. The posting has to be kept for three years. The rules apply once you employ 25 people, counted by heads across every Ontario location on the day you post, and part-timers count as one each. Most owners learned this from a competitor's fine or not at all. This skill checks the ad before the Ministry does.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill job-posting-compliance-checker`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/job-posting-compliance-checker/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: province, headcount today, whether you use any AI tool in screening, and where you post.
4. Paste a draft posting and ask for the compliance read; apply the corrected lines.
5. After each interview, log it; the skill keeps the 45-day dates and reminds you.

## Example

A 31-person logistics company in Mississauga drafts a dispatcher posting: "competitive salary", "must have Canadian experience", no mention of the resume-screening tool the office manager uses. The skill's read finds four gaps. The pay line becomes "$58,000 to $68,000 a year, plus overtime". The Canadian-experience line goes, replaced by the licences the job needs. A sentence is added: "We use artificial intelligence to screen applications for this position." And the vacancy statement goes at the bottom: "This posting is for an existing vacancy." The office manager files the final version and the two revisions, and after interviewing three candidates in March, gets a reminder in April to tell the two who didn't get it.

## Pro tip

Write the AI disclosure even when you're under 25 employees. Candidates assume you're using it anyway, and a plain sentence costs nothing. And keep the follow-up habit for every interview, not only the ones the law covers: the candidate you didn't hire this year is the one who applies again in two, and remembers whether you wrote back.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/job-posting-compliance-checker). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
