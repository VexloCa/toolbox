# Prompt Library Builder

> One maintained prompt library the whole team uses, instead of six private note files

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** Claude, ChatGPT

## The problem

By the time AI is saving a business real time, the prompts that do the saving live in five places: the owner's notes app, a bookmarked chat, two employees' private files, and one laminated printout nobody updates. New staff re-invent prompts that already exist, improvements stay with whoever made them, and when a prompt quietly stops working nobody notices for a month. A [rewritten prompt](/toolbox/prompt-rewriter) fixes one prompt once; keeping a set of them current, findable, and shared is a standing job, and this skill installs the librarian.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Three ways to use it:

- **Claude apps:** zip this folder and upload it in Settings under Skills (paid plans with code execution switched on). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/prompt-library-builder/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, Copilot, or Claude on the free plan:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (Claude, ChatGPT, anything that accepts pasted text).
3. Do the intake honestly: paste your scattered prompts as-is, ugly ones included.
4. Export the organized library wherever your team lives (a doc, a wiki page, print it).
5. From then on, report breakages and request prompts through the skill; re-export after changes.

## Example

An eight-person property management company has prompts scattered across three people. Intake surfaces eleven: tenant replies, listing descriptions, maintenance triage notes, owner reports. The skill restructures all eleven, marks two as near-duplicates and merges them, and splits the library into front-office (six prompts) and back-office (four). Over the next month the owner reports two breakages in one-line messages; both get patched with dated notes. At the quarterly pass, the maintenance-triage prompt has been patched three times and gets flagged to graduate into a standing skill, and the unused "blog post" prompt is retired without ceremony.

## Pro tip

Adopt the library one role at a time, starting with whoever answers customers; that is where prompt quality shows up in revenue fastest. And treat the quarterly "graduate" flags seriously: a prompt everyone uses daily and patches monthly is the strongest signal you have about where a dedicated skill will pay for its setup, which beats guessing from our catalog.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/prompt-library-builder). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
