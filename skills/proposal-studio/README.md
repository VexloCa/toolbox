# Proposal Studio

> Proposals in your voice and format, out the same day

**Category:** Sales & Lead Generation · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT, Claude Code

## The problem

Proposals go out three days after the call, sound like a template, and quote prices you improvised at 10pm. A generic prompt can structure one proposal, but it starts from zero every time: it doesn't know your services, your rate card, or the phrasing that won your last three deals. So each proposal costs you an evening, and the ones written tired cost you deals.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill proposal-studio`
- **Claude apps:** zip this folder and upload it in Settings under Skills (paid plans with code execution switched on). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/proposal-studio/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, Copilot, or Claude on the free plan:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, Cursor. Anything that can fetch a URL or accept pasted text).
3. Work through setup: your services, your rate card, and two or three proposals that won. This is the step that makes every later draft fast.
4. After a sales call, paste your raw notes and ask for a draft.
5. Resolve any [PRICE NEEDED] or gap flags, adjust, and send it while the call is still fresh.
6. When a proposal wins or loses, tell the skill. It sharpens what it emphasizes next time.

## Example

Say you run a 5-person branding studio. You paste call notes from a prospective client who wants a rebrand and "maybe a website." The draft comes back with the rebrand fully scoped from your rate card, three options (identity only at $6,500; identity plus guidelines at $9,000; the full package at $14,000, all pulled from your stored pricing), the website marked "[PRICE NEEDED: no rate-card entry for web builds. Quote separately or add a rate]", and a gap flag: "No budget was mentioned on the call. Consider a one-line check before sending the top option." Total time from notes to sendable draft: about fifteen minutes.

## Pro tip

Feed it losses, not just wins. Paste the proposal that lost and whatever the prospect said about why. Two or three of those and the skill starts steering drafts away from your losing patterns, like leading with process when the client cared about speed.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/proposal-studio). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
