# Vexlo Toolbox: Claude skills and AI prompts for small business

Free, MIT-licensed Claude skills, master prompts and workflows for running a small business: bookkeeping, customer support, hiring, sales, marketing, operations. Written for owners, not developers, and built around the assistants you already pay for: Claude, ChatGPT, Copilot, Gemini.

Currently in the box: **35 agent skills, 97 master prompts, 4 workflows, 1 tool stack**.

Every skill is a folder with a `SKILL.md` in the Agent Skills format, so it installs as a native Claude skill and also works pasted into any other assistant. Every item lives on [vexlo.ca/toolbox](https://vexlo.ca/toolbox) too, with a worked example and a one-click install prompt. Star the repo, clone what you need, and make it yours.

## Install a skill

1. **One command.** `npx skills add VexloCa/toolbox` lists every skill here and installs the ones you pick into Claude Code, Cursor, Codex and other coding agents. Add `--skill bookkeeping-copilot` to install a single skill.
2. **Claude apps.** Download a skill folder from `skills/`, zip it, and upload it in Settings under Skills. Custom skills need a paid Claude plan with code execution switched on. Claude then uses the skill whenever a request matches its description.
3. **Claude Code by hand.** Copy the folder to `~/.claude/skills/<skill-name>/` for every project, or to `.claude/skills/` inside one project.
4. **ChatGPT, Gemini, Copilot, or Claude on the free plan.** Open the skill's `SKILL.md`, copy everything, and paste it at the start of a conversation or into a project's instructions. The skill runs its setup questions once, then works from there.

A skill is a set of instructions your assistant will follow, so read one before you install it, from this repo or any other. The free [Skill Check](https://vexlo.ca/skill-check) grades any skill file or GitHub link from A+ to F for prompt injection, data privacy and destructive actions.

## How this relates to Claude for Small Business

Anthropic's Claude for Small Business plugin bundles workflows and app connectors for paid Claude plans. The skills here need no connectors: they work from what you paste or upload, in any assistant, and you can read and edit every line. Use them alongside the plugin, or on their own if you are not on a paid Claude plan.

## Claude skills for small business

### Marketing & Content

| Skill | Setup | What you get |
| --- | --- | --- |
| [Website Design Studio](skills/website-design-studio) | Light setup | Plan, write, and review a website that actually converts |
| [Marketing Growth Engine](skills/marketing-growth-engine) | Light setup | Run strategy and content from one assistant that knows your brand |
| [SEO Audit Copilot](skills/seo-audit-copilot) | Light setup | A prioritized SEO fix list in plain English, no agency retainer |
| [Content Repurposing Studio](skills/content-repurposing-studio) | Light setup | One blog post becomes ten pieces of content in your voice |
| [Email Marketing Copilot](skills/email-marketing-copilot) | Light setup | A monthly email program that remembers what worked, instead of campaign amnesia |

### Sales & Lead Generation

| Skill | Setup | What you get |
| --- | --- | --- |
| [Sales Pipeline Copilot](skills/sales-pipeline-copilot) | Light setup | Personalize outreach, prep calls, and chase deals without dropped balls |
| [Proposal Studio](skills/proposal-studio) | Light setup | Proposals in your voice and format, out the same day |
| [Discovery Call Copilot](skills/discovery-call-copilot) | Light setup | Walk into every discovery call prepared, walk out with a decision |
| [Referral Program Copilot](skills/referral-program-copilot) | Light setup | Referrals become a system with a memory, not a thing you remember to do twice a year |

### Customer Support

| Skill | Setup | What you get |
| --- | --- | --- |
| [Customer Support Autopilot](skills/customer-support-autopilot) | Light setup | Answer 80% of support emails in your brand voice |
| [Review & Reputation Manager](skills/review-reputation-manager) | Light setup | More reviews coming in and every one answered well |
| [Complaint Resolution Copilot](skills/complaint-resolution-copilot) | Light setup | Every complaint answered in your policy and your voice, every promise tracked to done |
| [Knowledge Base Copilot](skills/knowledge-base-copilot) | Light setup | A help section that answers this month's questions, not the ones from launch day |
| [Customer Insights Copilot](skills/customer-insights-copilot) | Light setup | A running record of what customers keep saying, with the trend, the quotes, and the churn watch kept for you |

### Operations & Productivity

| Skill | Setup | What you get |
| --- | --- | --- |
| [Ops Automation Planner: AI Business Process Automation](skills/ops-automation-planner) | Light setup | Document your business processes, then automate the ones worth automating |
| [SOP Studio](skills/sop-studio) | Light setup | Turn a 10-minute voice ramble into an SOP your team follows |
| [Meeting Ops Assistant](skills/meeting-ops-assistant) | Light setup | Agendas, minutes, and follow-ups that run themselves |
| [Inventory Manager](skills/inventory-manager) | Light setup | Know what to reorder and what is dead stock from a pasted spreadsheet |
| [Quality Control Copilot](skills/quality-control-copilot) | Light setup | Growth without the quality slide, caught by spot checks instead of complaints |
| [Prompt Library Builder](skills/prompt-library-builder) | Light setup | One maintained prompt library the whole team uses, instead of six private note files |
| [Scheduled Tasks Copilot](skills/scheduled-tasks-copilot) | Light setup | A small roster of scheduled AI tasks that earn their slots, reviewed monthly so the noise gets retired |

### Finance & Admin

| Skill | Setup | What you get |
| --- | --- | --- |
| [Finance Analyst Copilot](skills/finance-analyst-copilot) | Light setup | Understand your monthly numbers and cash position in plain English |
| [Accountant Handoff Pack](skills/accountant-handoff-pack) | Light setup | Send your accountant one clean package instead of forty emails |
| [Grant Finder](skills/grant-finder) | Light setup | A shortlist of grants you might qualify for, with draft answers |
| [Bookkeeping Copilot](skills/bookkeeping-copilot) | Light setup | Books that stay categorized and reconciled monthly without dread |
| [AI Spend Auditor](skills/ai-spend-auditor) | Light setup | Every AI charge in one inventory, with renewal dates and expiry flags |
| [Cash Flow Copilot](skills/cash-flow-copilot) | Light setup | The cash crunch flagged six weeks out, while it is still a decision instead of an emergency |

### HR & Hiring

| Skill | Setup | What you get |
| --- | --- | --- |
| [Hiring Assistant](skills/hiring-assistant) | Light setup | Hire with structure: job posts, interview kits, rubrics, onboarding |
| [Recruiting Pipeline Manager](skills/recruiting-pipeline-manager) | Light setup | Every candidate moved, messaged, and scored from one place |
| [Onboarding Copilot](skills/onboarding-copilot) | Light setup | New hires productive by week two, and nobody re-invents day one |
| [Shift Scheduler Copilot](skills/shift-scheduler-copilot) | Light setup | The weekly schedule builds itself from memory; you make the judgment calls |

### Strategy & Planning

| Skill | Setup | What you get |
| --- | --- | --- |
| [The Idea Grill](skills/idea-grill) | No-code | Five hostile experts interrogate your idea and score it out of 100 before you build |
| [Competitor Radar](skills/competitor-radar) | Light setup | A monthly competitor briefing from what they publish publicly |
| [Business Plan Copilot](skills/business-plan-copilot) | Light setup | A working business plan and financial forecast, built section by section |
| [Quarterly Goals Copilot](skills/quarterly-goals-copilot) | Light setup | Goals that survive week three, because something remembers them and asks |

## Master prompts

Copy-paste prompts with [SQUARE BRACKET] placeholders. They work in any assistant and need no setup.

### Marketing & Content

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [High-Converting Ad Copy Generator](prompts/marketing/ad-copy-generator.md) | No-code | Produce 10 ad variants for Google & Meta in minutes |
| [Email Campaign Builder](prompts/marketing/email-campaign-builder.md) | No-code | Write a 5-email campaign that sounds like you |
| [90-Day Marketing Plan Builder](prompts/marketing/90-day-marketing-plan.md) | No-code | Get a complete quarterly marketing plan in 20 minutes |
| [Brand Voice Codifier](prompts/marketing/brand-voice-codifier.md) | No-code | Turn your best writing into a reusable voice guide |
| [Competitor Teardown](prompts/marketing/competitor-teardown.md) | No-code | Map a competitor's strategy, gaps, and your counter-moves |
| [30 Days of Social Posts in One Hour](prompts/marketing/social-content-machine.md) | No-code | Generate a month of on-brand posts from one product description |
| [Landing Page Copy Writer](prompts/marketing/landing-page-copy-writer.md) | No-code | Landing page copy built section by section from your customer's words |
| [Newsletter Issue Writer](prompts/marketing/newsletter-issue-writer.md) | No-code | An issue subscribers open next week too |
| [Google Business Profile Optimizer](prompts/marketing/google-business-profile-optimizer.md) | No-code | A profile that competes for the map pack in your neighbourhood |
| [Short-Form Video Script Writer](prompts/marketing/short-video-script-writer.md) | No-code | Thirty-second scripts with a hook that stops the scroll |
| [Customer Case Study Writer](prompts/marketing/case-study-writer.md) | No-code | A case study that sells without sounding like a brochure |
| [Product Launch Plan Builder](prompts/marketing/product-launch-plan.md) | No-code | A launch sequence with dates, owners, and a day-one checklist |
| [SEO Content Brief Generator](prompts/marketing/seo-content-brief-generator.md) | No-code | Briefs that make every article competitive before it's written |
| [Price Increase Letter Writer](prompts/marketing/price-increase-letter.md) | No-code | Announce a price increase without apologizing or losing your regulars |
| [Testimonial Collector](prompts/marketing/testimonial-collector.md) | No-code | Real client quotes you can publish, collected without the awkward ask |

### Sales & Lead Generation

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Objection Handling Playbook](prompts/sales/objection-handling-playbook.md) | No-code | Build responses to your 10 toughest objections |
| [Lead Qualification Scorer](prompts/sales/lead-qualification-scorer.md) | Light setup | Score and prioritize inbound leads automatically |
| [Cold Outreach Personalizer](prompts/sales/cold-outreach-personalizer.md) | No-code | Write cold emails that get replies, personalized at scale |
| [Follow-Up Sequences That Don't Beg](prompts/sales/follow-up-sequences.md) | No-code | Revive stalled deals with 5-touch follow-up sequences |
| [10-Minute Sales Call Prep](prompts/sales/sales-call-prep.md) | No-code | Walk into every sales call knowing exactly what to say |
| [Proposal & Quote Generator](prompts/sales/proposal-generator.md) | No-code | Turn call notes into a polished proposal in 15 minutes |
| [Sales One-Pager Builder](prompts/sales/sales-one-pager-builder.md) | No-code | A leave-behind that sells while you're not in the room |
| [Referral Request Scripts](prompts/sales/referral-request-scripts.md) | No-code | Referral asks that feel natural and actually get sent |
| [Win/Loss Analyzer](prompts/sales/win-loss-analyzer.md) | No-code | Learn why deals really close or die, from patterns not hunches |
| [Discovery Call Question Bank](prompts/sales/discovery-call-question-bank.md) | No-code | Questions that surface budget and urgency without interrogating |
| [Upsell & Cross-Sell Finder](prompts/sales/upsell-opportunity-finder.md) | No-code | Revenue sitting in your current client list, mapped |
| [CRM Hygiene Auditor](prompts/sales/crm-hygiene-auditor.md) | No-code | A pipeline you can finally trust for forecasting |
| [Win-Back Campaign Writer](prompts/sales/win-back-campaign-writer.md) | No-code | A 3-touch sequence that brings lapsed customers back without begging |

### Customer Support

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Support Macro Library](prompts/support/support-macro-library.md) | No-code | Generate 25 reusable reply templates for your business |
| [Review Response Writer](prompts/support/review-response-writer.md) | No-code | Respond to every Google/Yelp review: good or brutal |
| [FAQ & Knowledge Base Builder](prompts/support/faq-knowledge-base-builder.md) | No-code | Turn your inbox history into a complete FAQ |
| [Complaint De-Escalation Scripts](prompts/support/complaint-deescalation.md) | No-code | Turn angry customers into repeat customers |
| [Voice-of-Customer Miner](prompts/support/voice-of-customer-miner.md) | No-code | Mine support tickets for product and marketing gold |
| [SLA & Response Policy Writer](prompts/support/sla-policy-writer.md) | No-code | Service promises you can keep, written down |
| [Refund & Return Policy Writer](prompts/support/refund-policy-writer.md) | No-code | A policy that protects you without scaring buyers |
| [Churn Risk Detector](prompts/support/churn-risk-detector.md) | No-code | Spot the customers about to leave while there's time to act |
| [Help Doc Writer](prompts/support/help-doc-writer.md) | No-code | Help articles customers find before they email you |
| [Customer Feedback Survey Builder](prompts/support/feedback-survey-builder.md) | No-code | Surveys people finish, with answers you can act on |
| [Support Reply Auditor](prompts/support/support-reply-auditor.md) | No-code | Ten sent replies graded against your policy and your voice, with the drift named |

### Operations & Productivity

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [SOP Writer: AI SOP Generator for Small Business](prompts/operations/sop-writer.md) | No-code | Turn "how I do it" into documentation anyone can follow |
| [Project Brief Builder](prompts/operations/project-brief-builder.md) | No-code | Scope any project before kickoff: goals, risks, owners |
| [Weekly Report Automator: AI Weekly Report Generator](prompts/operations/weekly-report-automator.md) | No-code | Compile scattered updates into one clean weekly report |
| [Meeting Notes to Action Items: AI Action Item Extractor](prompts/operations/meeting-notes-to-actions.md) | No-code | Turn raw meeting notes into action items with owners and deadlines |
| [Vendor Comparison Matrix](prompts/operations/vendor-comparison-matrix.md) | No-code | Compare quotes and vendors on facts, not gut feel |
| [Email Inbox Triage System](prompts/operations/inbox-triage-system.md) | Light setup | Process 100 emails in 15 minutes with AI triage |
| [Automation Opportunity Audit](prompts/operations/automation-opportunity-audit.md) | No-code | Find the 5 processes you should automate first |
| [Delegation Planner](prompts/operations/delegation-planner.md) | No-code | Hand off half your task list without dropping quality |
| [Inventory Reorder Planner](prompts/operations/inventory-reorder-planner.md) | No-code | Reorder points that stop both stockouts and dead stock |
| [Process Bottleneck Finder](prompts/operations/process-bottleneck-finder.md) | No-code | Find the step that slows everything and what fixing it is worth |
| [Client Onboarding Checklist Builder](prompts/operations/customer-onboarding-checklist.md) | No-code | New clients hit their first win without you chasing anyone |
| [Daily Standup Summarizer](prompts/operations/daily-standup-summarizer.md) | No-code | Standup notes become blockers assigned before lunch |
| [Risk Register Builder](prompts/operations/risk-register-builder.md) | No-code | The ten risks that could actually hurt you, ranked, with responses |
| [Scheduled Task Builder](prompts/operations/scheduled-task-builder.md) | No-code | A recurring chore turned into a scheduled AI task that runs unattended and reports only what matters |

### Finance & Admin

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Invoice Chaser Sequences](prompts/finance/invoice-chaser.md) | No-code | Get overdue invoices paid without burning relationships |
| [Simple Budget Planner](prompts/finance/budget-planner.md) | No-code | Build a realistic annual budget from last year's numbers |
| [Cash Flow Analyzer](prompts/finance/cash-flow-analyzer.md) | No-code | Understand your cash position and 90-day runway in plain English |
| [Pricing Strategy Advisor](prompts/finance/pricing-strategy-advisor.md) | No-code | Pressure-test your pricing and find money you're leaving behind |
| [Financial Jargon Translator](prompts/finance/financial-jargon-translator.md) | No-code | Understand any contract, statement, or bank letter |
| [Expense Categorizer](prompts/finance/expense-categorizer.md) | No-code | Clean up a messy expense export for your bookkeeper |
| [Profit Margin Diagnostic](prompts/finance/profit-margin-diagnostic.md) | No-code | Find exactly where your margin leaks and what each leak costs per year |
| [Break-Even Analyzer](prompts/finance/break-even-analyzer.md) | No-code | Know exactly how many sales cover the bills each month |
| [Grant Application Writer](prompts/finance/grant-application-writer.md) | No-code | A draft application that answers what reviewers actually score |
| [Tax Season Prep Checklist](prompts/finance/tax-season-prep-checklist.md) | No-code | Walk into your accountant's office with everything they need, once |
| [12-Month Revenue Forecast](prompts/finance/revenue-forecast-builder.md) | No-code | A month-by-month forecast built from your real pipeline, not wishes |
| [Debt Paydown Planner](prompts/finance/debt-paydown-planner.md) | No-code | A payoff order for your business debts with the reasoning shown |
| [GST/HST Filing Prep](prompts/finance/gst-hst-filing-prep.md) | No-code | A filing-ready GST/HST package for your accountant, built in an evening instead of a lost weekend |

### HR & Hiring

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Job Description Writer](prompts/hr/job-description-writer.md) | No-code | Write job posts that attract doers, not title collectors |
| [Performance Review Helper](prompts/hr/performance-review-helper.md) | No-code | Turn scattered observations into fair, specific reviews |
| [Resume Screener](prompts/hr/resume-screener.md) | No-code | Screen 50 resumes against your real requirements in minutes |
| [Tough Conversation Scripts](prompts/hr/tough-conversation-scripts.md) | No-code | Prepare for raises, PIPs, and lettings-go with a script |
| [30-60-90 Onboarding Builder](prompts/hr/onboarding-plan-builder.md) | No-code | Give every new hire a ramp-up plan on day one |
| [Interview Question Bank](prompts/hr/interview-question-bank.md) | No-code | Build role-specific interviews that actually predict performance |
| [1:1 Meeting Agenda Builder](prompts/hr/one-on-one-agenda-builder.md) | No-code | One-on-ones your team stops dreading |
| [Team Training Plan Builder](prompts/hr/training-plan-builder.md) | No-code | A skills-gap map and a training plan someone will actually follow |
| [Offer Letter Writer](prompts/hr/offer-letter-writer.md) | No-code | An offer letter that closes the candidate without overpromising |
| [Compensation Benchmark Helper](prompts/hr/compensation-benchmark-helper.md) | No-code | A defensible pay range before the negotiation, not during it |
| [Employee Handbook Drafter](prompts/hr/employee-handbook-drafter.md) | No-code | A working handbook draft your lawyer reviews instead of writes |
| [Exit Interview Analyzer](prompts/hr/exit-interview-analyzer.md) | No-code | Turn exit interviews into the three fixes that stop the next departure |
| [Shift Schedule Builder](prompts/hr/shift-schedule-builder.md) | No-code | Next week's schedule built in ten minutes, with the conflicts caught before they call in |

### Strategy & Planning

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Quarterly Goals (OKR) Builder](prompts/strategy/quarterly-okr-builder.md) | No-code | Set 90-day goals your team can actually execute |
| [AI Board of Advisors](prompts/strategy/ai-board-of-advisors.md) | No-code | Stress-test any business decision from 5 expert angles |
| [SWOT That Isn't Useless](prompts/strategy/swot-that-isnt-useless.md) | No-code | A SWOT analysis that ends in actions, not a poster |
| [Customer Persona Builder](prompts/strategy/customer-persona-builder.md) | No-code | Build data-grounded personas from real customer evidence |
| [Partnership Evaluator](prompts/strategy/partnership-evaluator.md) | No-code | Know if the partnership is worth it before the handshake |
| [Pricing Experiment Designer](prompts/strategy/pricing-experiment-designer.md) | No-code | Test a price change without betting the business |
| [Annual Retrospective Guide](prompts/strategy/annual-retrospective-guide.md) | No-code | A year review that changes next year's plan |
| [Pivot Decision Framework](prompts/strategy/pivot-decision-framework.md) | No-code | A structured answer to "should we change course?" |
| [Business Model Stress Test](prompts/strategy/business-model-stress-test.md) | No-code | Find the assumption that kills your business before it does |
| [New Market Entry Analyzer](prompts/strategy/market-entry-analyzer.md) | No-code | A go/no-go on the new market with the evidence listed |
| [AI ROI Reality Check](prompts/strategy/ai-roi-reality-check.md) | No-code | A keep / cancel / renegotiate verdict on every AI tool you pay for |
| [Software Buying Scorecard](prompts/strategy/software-buying-scorecard.md) | No-code | A buy / skip / wait verdict on any software before you pay for it |
| [Custom AI Project Scoper](prompts/strategy/custom-ai-project-scoper.md) | No-code | A one-page project brief that makes custom-AI quotes comparable |
| [Prompt Rewriter](prompts/strategy/prompt-rewriter.md) | No-code | Turn the prompt that gave you beige output into one that gives you a usable draft |
| [Context Pack Builder](prompts/strategy/context-pack-builder.md) | No-code | Stop retyping your business's story into every prompt; paste a ready context block instead |
| [AI Usage Policy Writer](prompts/strategy/ai-usage-policy-writer.md) | No-code | One page of house AI rules your team will read, before the first incident instead of after |
| [AI Pilot Designer](prompts/strategy/ai-pilot-designer.md) | No-code | A 30-day AI pilot with success measures and kill criteria decided before anyone gets attached |
| [AI Opportunity Self-Audit](prompts/strategy/ai-opportunity-self-audit.md) | No-code | A ranked map of where AI pays first in your business, before you buy anything |

## Workflows

| Workflow | Category | What you get |
| --- | --- | --- |
| [LinkedIn Founder-Brand Engine](workflows/linkedin-sales-engine.md) | Sales & Lead Generation | Generate inbound leads from 3 LinkedIn posts a week |
| [SEO Blog Post Engine](workflows/seo-blog-engine.md) | Marketing & Content | Publish search-ranking blog posts weekly without a writer |
| [Annual Planning Workshop](workflows/annual-planning-workshop.md) | Strategy & Planning | Run a one-day annual planning session: solo or with your team |
| [Monthly Finance Close](workflows/monthly-finance-close.md) | Finance & Admin | Close your books every month in one sitting, ending accountant-ready |

## Tool stacks

| Tool stack | Category | What you get |
| --- | --- | --- |
| [The SME AI Starter Stack](tool-stacks/sme-ai-starter-stack.md) | Strategy & Planning | The 7 AI tools a small business should adopt first |

## About Vexlo

[Vexlo](https://vexlo.ca) is the AI audit and toolbox for small business. Take the [free AI audit](https://vexlo.ca/audit) to find out where AI can save you hours every week, or learn the fundamentals at the [Academy](https://vexlo.ca/academy).

## License

MIT. Use these in your business, tweak them, share them.
