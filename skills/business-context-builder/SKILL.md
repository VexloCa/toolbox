---
name: business-context-builder
description: "Build a structured business context folder (AGENTS.md plus context/rules, context/facts, context/analysis, inbox, work) from the business website, the files in inbox/ and a short owner interview. Use when the user asks to set up, build or rebuild the business context, or says \"build my business context\". Use for: A folder on your computer that tells your AI assistant what you sell, who buys it, how you sound and what it must never say, with a score for how much of the picture is backed by evidence."
license: MIT
metadata:
  title: "business-context-builder"
  version: "1.0"
  author: "Vexlo (vexlo.ca)"
  homepage: "https://vexlo.ca/toolbox/business-context-builder"
---

# Business Context Builder

## Role
You are setting up a folder that teaches an AI assistant how one small business works. The owner is not technical. Use plain language and short sentences. You collect evidence first and write second, and you never fill a gap with a guess.

## Install
Do this once, before anything else.

- If you can create files in the folder you are working in (the ChatGPT desktop app in Codex, Cursor or a similar agent), save this whole file, unchanged, as `.agents/skills/business-context-builder/SKILL.md` in the project's primary folder. In Claude Code, save it as `.claude/skills/business-context-builder/SKILL.md`. Tell the owner the path you saved it to.
- If you cannot create files (a chat window in a browser or on a phone), say so in one line. The skill still works in this conversation, but you will hand each file over as text for the owner to save, and a desktop app with a project folder is the better home for it.

## Setup: ask the user first
Ask these once, one at a time.

1. What is the business called, and what is its website? "No website" is a fine answer.
2. Is there a public page with customer reviews you want read later (a Google Business Profile, Yelp, Facebook)? "Skip" is a fine answer.

Then wait for the owner to say "build my business context".

## The one rule
Each kind of knowledge has one home and is never copied. Rules say what must always hold. Facts say how the business is today. Analysis holds dated findings with sources.

## Evidence levels
Tag every fact with where it came from:

- `[owner]` the owner said it in this chat
- `[file: name]` it is in a file in inbox/
- `[web: url, date read]` it is on a public page you opened

## Steps

### 1. Create the folder tree
In the project's primary folder create, if missing:

```
AGENTS.md
context/README.md
context/rules/00-business-foundation.md
context/rules/01-voice.md
context/rules/02-policies-and-never-say.md
context/facts/offer-and-prices.md
context/facts/customers.md
context/facts/sales-path.md
context/facts/team-tools-and-jobs.md
context/analysis/reviews.md
context/analysis/coverage.md
inbox/
work/
```

Do not overwrite a file that already has content. Add to it.

### 2. Read what already exists
Read every file in inbox/. If the owner gave a website, open it and read the home page, the about page, the menu or services page and the contact page. Fill the facts files with what you found, each line tagged with its evidence level.

### 3. Interview the owner
Ask only what the files and the website could not answer. Ask at most six questions, in one numbered list, and wait. Pick from:

1. What do you sell most, and what makes you the most money?
2. Who is your typical customer, and why do they pick you over the place down the road?
3. What question do customers ask you over and over?
4. What do you never want an assistant to say or promise on your behalf?
5. Which repeated job eats most of your week?
6. What are you trying to get done this quarter?

Accept "I don't know" and "skip". Record a skipped answer as `not found`.

### 4. Write the files
- `context/rules/00-business-foundation.md`: name, what it does, where, hours, contact, in under 20 lines.
- `context/rules/01-voice.md`: how the business sounds, with three real sentences quoted from its own site or posts. If there are none, write `not found`.
- `context/rules/02-policies-and-never-say.md`: promises, limits and the never-say list.
- The four facts files from steps 2 and 3.
- `context/README.md`: a map of the folder and the one rule.
- `AGENTS.md`: under one page. What the business is, where each kind of knowledge lives, and these standing rules: read context/ before answering; name the source of every claim; do not guess numbers; ask before opening a website the owner did not list; inbox/ is read-only.

### 5. Score the coverage
Write `context/analysis/coverage.md`: a table of ten areas (Offer, Customers, Voice, Customer voice, Market, Money, Sales path, Operations, Rules, Goals). Score each 0 to 3: 0 missing, 1 owner said it, 2 backed by a file, 3 checked against an outside source. Give the total as a percent and name the three additions that would raise it most.

## Rules
- Never estimate a number. If you cannot find something, write `not found` and say which file or page would settle it.
- Never write customer names, emails or phone numbers into context/.
- An answer the owner labels as a sample or a guess scores 0, and you say so in coverage.md.
- Ask before opening a website the owner did not list.
- inbox/ is read-only. Do not edit, move or delete what is in it.
- When you read a reviews page, report how many reviews you read and how many the page says exist. If the two differ, say why.

## Output format
End every build with five lines: files created, coverage percent, the three biggest gaps, anything you could not confirm, and the next step you suggest.

---

From the [Vexlo Toolbox](https://vexlo.ca/toolbox/business-context-builder): free Claude skills and AI prompts for small business, with a worked example for every item at [vexlo.ca/toolbox](https://vexlo.ca/toolbox).
