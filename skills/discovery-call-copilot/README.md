# Discovery Call Copilot

> Walk into every discovery call prepared, walk out with a decision

**Category:** Sales & Lead Generation · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

Small-business discovery calls fail in two boring ways: walking in cold, so the first fifteen minutes are questions a website visit would have answered, and walking out warm, with friendly vibes, no budget number, and a "send me something" that turns into a proposal written on guesses. The call felt good; the deal was never real. What's missing isn't charm, it's a repeatable before-during-after routine.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill discovery-call-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/discovery-call-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Answer the setup questions: what you sell, your price floor, your ideal client, your dealbreakers.
4. Before each call, paste the lead's website text and intake answers; skim the prep page it returns.
5. After each call, talk through what happened and act on the pursue/pass line before the day ends.

## Example

A branding studio gets an inquiry from a restaurant group. The prep page flags that the group's three locations have three different logos, guesses the call is about consolidation, and suggests testing whether the founder or the new marketing hire owns the decision. On the call, the disqualifier surfaces fast: budget expectations sit at a third of the studio's floor. The debrief records it, the skill drafts a warm pass with a referral to a cheaper freelancer, and the log gains a data point that later shows restaurant inquiries have hit the budget floor problem four times running, which changes where the studio spends its outreach time. Scoring the ones worth a call in the first place is the [Lead Qualification Scorer](/toolbox/lead-qualification-scorer)'s job, one step upstream.

## Pro tip

Do the debrief ramble in the parking lot, or the minute the video call ends. The budget hesitation, the sideways glance at a partner, the "we tried an agency once" aside: those details evaporate within the hour, and they are exactly what the pursue/pass decision needs.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/discovery-call-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
