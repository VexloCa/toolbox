# Safety Talk Generator

> A five-minute safety talk for every crew morning, written for this week's job and this crew's hazards, with the sign-in sheet that proves it happened

**Category:** HR & Hiring · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

The morning safety talk is the most repeated meeting in the trades and the least prepared. The foreman grabs the same laminated card about ladders, reads it in ninety seconds while the crew looks at their phones, and the sheet gets signed. Then someone gets hurt doing the thing the talk wasn't about, and the inspector asks for the record of what the crew was told that week. A good talk is specific: this site, this task, this weather, the near miss from Tuesday. Writing one takes a foreman twenty minutes they don't have at 6:40 a.m. This skill writes it in two, from what's on the schedule.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill safety-talk-generator`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/safety-talk-generator/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: the trade, typical jobs, crew size, the training your workers already hold, and the hazards you worry about most.
4. Each morning (or the night before), tell it today's task, site and weather, and ask for the talk.
5. Read it out, ask the question, get the signatures, and photograph the sheet into the job folder.

## Example

A six-person roofing crew in Guelph is starting a steel roof on a two-storey commercial building the morning after the first frost. The owner types: "steel roofing, two storeys, frost overnight, new apprentice starting today, lift truck on site." The talk that comes back leads with frost on steel underfoot, covers the lift truck's swing radius because two trades share the yard, and ends with the apprentice: who his buddy is for the week, and that he can refuse work he believes is unsafe and nobody will hold it against him. The crew question is "where's the anchor point for the north slope?" and two people give different answers, which is the point. The sheet gets six signatures and a photo. Next week the log shows ladders haven't come up in a month, and the skill queues them.

## Pro tip

End every talk with a question the crew has to answer, not a statement they nod at. "Where's the nearest first aid kit on this site?" gets a room looking around; "remember the first aid kit" gets nothing. And when there's been a near miss, make that the next morning's talk even if it breaks the rotation: a hazard the crew saw yesterday is the one they'll listen to today.

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/safety-talk-generator). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
