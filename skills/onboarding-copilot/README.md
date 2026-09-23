# Onboarding Copilot

> New hires productive by week two, and nobody re-invents day one

**Category:** HR & Hiring · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

In most small businesses, onboarding is whoever has time that morning. The new hire shadows someone, gets logins over three days of asking, and forms their picture of the company from whichever coworker talked most. The [Onboarding Plan Builder](/toolbox/onboarding-plan-builder) writes a solid plan for one hire; what it can't do is run the plan, adapt it mid-stream, or remember what worked so hire number four starts better than hire number one. That standing job is what this skill installs.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill onboarding-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/onboarding-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Answer the setup questions: the business, the roles you hire, what the first week looks like today.
4. On a new hire, give it the name, role, and start date; print or send what it produces.
5. After each check-in, paste two lines about how it went. That habit is the whole system.

## Example

An HVAC company with 11 staff hires two techs a year and loses a week each time to improvised starts. The skill interviews the owner once: certifications to verify before day one, the van and tool assignment, who rides along in week one, what "safe to send alone" means. The next hire gets a printed week-one plan, the supervisor gets three check-in scripts, and when the new tech's confusion about the parts-ordering app gets logged, a one-line explainer joins the playbook. By the second hire that year, day one runs off a checklist nobody had to rewrite, and the 60-day check-in agenda already lists the two skills the 30-day notes flagged as shaky.

## Pro tip

The two-line check-in log is the habit that separates this from a template folder. Pair it with the [One-on-One Agenda Builder](/toolbox/one-on-one-agenda-builder) once the hire graduates from onboarding: the 90-day record hands the first regular one-on-one its starting agenda.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/onboarding-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
