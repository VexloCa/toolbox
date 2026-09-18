# Complaint Resolution Copilot

> Every complaint answered in your policy and your voice, every promise tracked to done

**Category:** Customer Support · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

The [Complaint De-Escalation Scripts](/toolbox/complaint-deescalation) write one excellent reply, and that is where their job ends. What they cannot do is remember that you already gave this customer a make-good in June, notice that "wrong item shipped" is now a third of your complaints, or nag you about the follow-up you promised for Thursday. Those are the parts that decide whether complaints shrink over time or repeat forever, and they are a standing job, not a prompt. This skill installs the person who holds it.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Three ways to use it:

- **Claude apps:** zip this folder and upload it in Settings under Skills (paid plans with code execution switched on). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/complaint-resolution-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, Copilot, or Claude on the free plan:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Do the policy interview honestly, including what you will never offer.
4. Paste each complaint as it arrives; send the draft through the real channel after your read-aloud check.
5. Check in weekly: confirm kept promises, review overdue ones, read the pattern flags monthly.

## Example

A small furniture shop installs the skill and sets policy: full refund under $200 without approval, replacement first for damage, never blame the courier in writing. Over a month it handles eleven complaints. The ninth is a repeat customer whose first delivery was also late; the draft opens by acknowledging both, and the make-good steps up a level per policy. At the monthly check-in, the log shows four of eleven complaints trace to one product's packaging, with the note "this is an upstream fix, not a support script," and the owner takes it to the supplier. The promise tracker shows one overdue confirmation, which gets sent that morning instead of never.

## Pro tip

The weekly promise check is the habit that separates this from a reply generator: a perfect apology followed by a missed follow-up is worse than a clumsy apology followed by a kept one. Pair the skill with the [Review Reputation Manager](/toolbox/review-reputation-manager) so a complaint resolved well gets a shot at becoming the public review that mentions how you fixed it.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/complaint-resolution-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
