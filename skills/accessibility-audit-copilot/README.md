# Website Accessibility Copilot

> Your website's pages, PDFs and forms checked against the WCAG rules Ontario's AODA points to, with the fixes written in plain words for whoever edits your site

**Category:** Operations & Productivity · **Difficulty:** Light setup · **Works with:** ChatGPT, Claude

## The problem

Under Ontario's Accessibility for Ontarians with Disabilities Act, a business or non-profit with 50 or more employees has had to meet WCAG 2.0 Level AA on its public website since January 1, 2021, and every organization over 20 employees files a compliance report. Smaller businesses aren't bound by the website rule, and many of them are still losing customers to it: a menu that can't be read by a screen reader, a booking form with no labels, grey text on a white background that a 68-year-old can't make out, a PDF price list that's an image. Accessibility audits are priced for large organizations. The checks themselves are mostly things a careful person can do with the page in front of them. This skill is the careful person.

## The skill

The installable file is [`SKILL.md`](SKILL.md) in this folder. Four ways to use it:

- **One command (Claude Code, Cursor, Codex and other agents):** `npx skills add VexloCa/toolbox --skill accessibility-audit-copilot`
- **Claude apps, any plan including Free:** zip this folder, then in Claude open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be on (Settings > Capabilities). Claude then loads it when a request matches.
- **Claude Code:** copy the folder to `~/.claude/skills/accessibility-audit-copilot/`, or to `.claude/skills/` inside a project.
- **ChatGPT, Gemini, or Copilot:** paste the contents of `SKILL.md` at the start of a conversation or into a project's instructions.

## How to use it

1. Click "Install skill" on this page and copy the install prompt.
2. Paste it into your AI assistant (ChatGPT, Claude, anything that accepts pasted text).
3. Answer the setup questions once: headcount, province, what the site is built on, and who edits it.
4. Start with the pages that matter most (home, services or menu, booking or contact, prices) and paste each page's text and structure for a check.
5. Give the drafted fixes to whoever edits the site, then run the check again on the same pages.

## Example

A 55-person home-care agency in Ottawa has a site built by a cousin in 2018. The first three pages checked turn up the same problems: every image's alt text is the file name, the "Book a consultation" button is an image with no text, the form's fields have placeholders instead of labels, and the body text is light grey on white at a ratio the skill estimates well under the standard's 4.5 to 1 once the owner pastes the hex codes. The fix list is written for the agency's website editor and takes an afternoon. The services brochure, a scanned PDF, becomes a web page. The agency's next AODA compliance report has a truthful yes in it, and the booking form's completion rate goes up, because labels help everyone.

## Pro tip

Fix the booking or contact path first, end to end, before touching anything else. A visitor who can't complete that form is a customer you lost; a visitor who struggled with your About page is a customer who shrugged. And write alt text the way you'd describe the photo to someone on the phone: "our front counter with the daily specials board", not "image1" and not "beautiful inviting café interior".

---

Part of the [Vexlo Toolbox](https://vexlo.ca/toolbox/accessibility-audit-copilot). Get a free report on where AI can save your business hours every week at [vexlo.ca/audit](https://vexlo.ca/audit).
