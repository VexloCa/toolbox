# Vexlo Toolbox: Claude skills and AI prompts for small business

Free, MIT-licensed Claude skills, master prompts and workflows for running a small business: bookkeeping, customer support, hiring, sales, marketing, operations. Written for owners, not developers, and built around the assistants you already pay for: Claude, ChatGPT, Copilot, Gemini.

Currently in the box: **57 agent skills, 102 master prompts, 4 workflows, 1 tool stack**.

Every skill is a folder with a `SKILL.md` in the Agent Skills format, so it installs as a native Claude skill and also works pasted into any other assistant. Every item lives on [vexlo.ca/toolbox](https://vexlo.ca/toolbox) too, with a worked example and a one-click install prompt. Star the repo, clone what you need, and make it yours. New to skills? [Claude skills for small business](https://vexlo.ca/blog/claude-skills-for-small-business) explains what they are and how to install one on any plan.

## Install a skill

1. **One command.** `npx skills add VexloCa/toolbox` lists every skill here and installs the ones you pick into Claude Code, Cursor, Codex and other coding agents. Add `--skill bookkeeping-copilot` to install a single skill.
2. **Claude apps, any plan including Free.** Download a skill folder from `skills/`, zip it, then open Customize > Skills, click +, choose Create skill, then Upload a skill. Code execution has to be switched on in Settings > Capabilities. Claude then uses the skill whenever a request matches its description.
3. **Claude Code by hand.** Copy the folder to `~/.claude/skills/<skill-name>/` for every project, or to `.claude/skills/` inside one project.
4. **ChatGPT, Gemini, or Copilot.** Open the skill's `SKILL.md`, copy everything, and paste it at the start of a conversation or into a project's instructions. The skill runs its setup questions once, then works from there.

A skill is a set of instructions your assistant will follow, so read one before you install it, from this repo or any other. The free [Skill Check](https://vexlo.ca/skill-check) grades any skill file or GitHub link from A+ to F for prompt injection, data privacy and destructive actions.

## How this relates to Claude for Small Business

Anthropic's Claude for Small Business plugin bundles workflows and app connectors, and runs in Cowork on paid Claude plans. The skills here need no connectors: they work from what you paste or upload, in any assistant, and you can read and edit every line. Use them alongside the plugin, or on their own on any plan, Free included.

## Claude skills for small business

### Marketing & Content

| Skill | Setup | What you get |
| --- | --- | --- |
| [Marketing Growth Engine](skills/marketing-growth-engine) | Light setup | Run strategy and content from one assistant that knows your brand |
| [Website Design Studio](skills/website-design-studio) | Light setup | Plan, write, and review a website that actually converts |
| [Content Repurposing Studio](skills/content-repurposing-studio) | Light setup | One blog post becomes ten pieces of content in your voice |
| [SEO Audit Copilot](skills/seo-audit-copilot) | Light setup | A prioritized SEO fix list in plain English, no agency retainer |
| [Email Marketing Copilot](skills/email-marketing-copilot) | Light setup | A monthly email program that remembers what worked, instead of campaign amnesia |
| [AI Search Visibility Checker](skills/ai-search-visibility-checker) | Light setup | A monthly read of what ChatGPT, Perplexity, Copilot and Google's AI answers say when someone asks for a business like yours, and the five page fixes that change the answer |
| [Ad Account Auditor](skills/ad-account-auditor) | Light setup | A plain-English read of your Google Ads or Meta export every month, with the three changes that would have saved the most money last month and the one that would have made the most |
| [Local Press Pitch Writer](skills/pr-pitch-writer) | Light setup | A short, specific pitch to a named local reporter or trade editor, built around a story they'd run with or without you, plus the follow-up and the quote sheet |
| [Holiday Promo Planner](skills/holiday-promo-planner) | Light setup | A holiday season plan from Black Friday to Boxing Day that fits your margin and your staff, with the offers, the dates, the emails and the inventory call made in October instead of the week of |

### Sales & Lead Generation

| Skill | Setup | What you get |
| --- | --- | --- |
| [Sales Pipeline Copilot](skills/sales-pipeline-copilot) | Light setup | Personalize outreach, prep calls, and chase deals without dropped balls |
| [Proposal Studio](skills/proposal-studio) | Light setup | Proposals in your voice and format, out the same day |
| [Discovery Call Copilot](skills/discovery-call-copilot) | Light setup | Walk into every discovery call prepared, walk out with a decision |
| [Referral Program Copilot](skills/referral-program-copilot) | Light setup | Referrals become a system with a memory, not a thing you remember to do twice a year |
| [Job Estimate Builder](skills/job-estimate-builder) | Light setup | A written estimate that goes out the same evening as the site visit, with the scope, the exclusions, the allowances, the deposit and the payment schedule a customer can't later say they misunderstood |
| [Call Notes to CRM](skills/call-notes-to-crm) | Light setup | Thirty seconds of talking after a sales call turned into the CRM fields, the next step with a date, and the follow-up email, before you've reached the next parking lot |

### Customer Support

| Skill | Setup | What you get |
| --- | --- | --- |
| [Customer Support Autopilot](skills/customer-support-autopilot) | Light setup | Answer 80% of support emails in your brand voice |
| [Review & Reputation Manager](skills/review-reputation-manager) | Light setup | More reviews coming in and every one answered well |
| [Complaint Resolution Copilot](skills/complaint-resolution-copilot) | Light setup | Every complaint answered in your policy and your voice, every promise tracked to done |
| [Knowledge Base Copilot](skills/knowledge-base-copilot) | Light setup | A help section that answers this month's questions, not the ones from launch day |
| [Customer Insights Copilot](skills/customer-insights-copilot) | Light setup | A running record of what customers keep saying, with the trend, the quotes, and the churn watch kept for you |
| [AI Receptionist Script Writer](skills/ai-receptionist-script-writer) | Light setup | The greeting, the five call flows, the disclosure line and the hand-off rules for an AI phone receptionist, written before you sign up for one, and the $0 voicemail-and-text version to run first |
| [Bilingual Reply Writer](skills/bilingual-reply-writer) | Light setup | Customer replies, notices and web copy in Canadian French and English that say the same thing in the same tone, with your product names and terms handled the same way every time |

### Operations & Productivity

| Skill | Setup | What you get |
| --- | --- | --- |
| [Ops Automation Planner: AI Business Process Automation](skills/ops-automation-planner) | Light setup | Document your business processes, then automate the ones worth automating |
| [SOP Studio](skills/sop-studio) | Light setup | Turn a 10-minute voice ramble into an SOP your team follows |
| [Inventory Manager](skills/inventory-manager) | Light setup | Know what to reorder and what is dead stock from a pasted spreadsheet |
| [Meeting Ops Assistant](skills/meeting-ops-assistant) | Light setup | Agendas, minutes, and follow-ups that run themselves |
| [Quality Control Copilot](skills/quality-control-copilot) | Light setup | Growth without the quality slide, caught by spot checks instead of complaints |
| [Prompt Library Builder](skills/prompt-library-builder) | Light setup | One maintained prompt library the whole team uses, instead of six private note files |
| [Scheduled Tasks Copilot](skills/scheduled-tasks-copilot) | Light setup | A small roster of scheduled AI tasks that earn their slots, reviewed monthly so the noise gets retired |
| [Vendor Contract Reviewer](skills/vendor-contract-reviewer) | Light setup | Every software, lease and supplier contract read before you sign it, with the auto-renewal, the exit terms and the price escalator pulled out onto one page and the questions to send back |
| [Cyber Incident Response Planner](skills/cyber-incident-response-planner) | Light setup | A one-page plan for the morning your email, your files or your payments are compromised, with who calls whom in the first hour, what the privacy law requires you to report, and the three fixes that make the plan rarely needed |
| [Website Accessibility Copilot](skills/accessibility-audit-copilot) | Light setup | Your website's pages, PDFs and forms checked against the WCAG rules Ontario's AODA points to, with the fixes written in plain words for whoever edits your site |
| [AI Consultant Proposal Checker](skills/ai-consultant-proposal-checker) | Light setup | An AI consultant's proposal or quote read before you sign it, with the price set against published rate bands, the scope gaps listed, the red flags named and the five questions to send back |

### Finance & Admin

| Skill | Setup | What you get |
| --- | --- | --- |
| [Finance Analyst Copilot](skills/finance-analyst-copilot) | Light setup | Understand your monthly numbers and cash position in plain English |
| [Accountant Handoff Pack](skills/accountant-handoff-pack) | Light setup | Send your accountant one clean package instead of forty emails |
| [Bookkeeping Copilot](skills/bookkeeping-copilot) | Light setup | Books that stay categorized and reconciled monthly without dread |
| [Grant Finder](skills/grant-finder) | Light setup | A shortlist of grants you might qualify for, with draft answers |
| [AI Spend Auditor](skills/ai-spend-auditor) | Light setup | Every AI charge in one inventory, with renewal dates and expiry flags |
| [Cash Flow Copilot](skills/cash-flow-copilot) | Light setup | The cash crunch flagged six weeks out, while it is still a decision instead of an emergency |
| [Tariff Impact Analyzer](skills/tariff-impact-analyzer) | Light setup | A product-by-product read of what this month's tariffs do to your landed cost and margin, and the three moves that protect the most dollars |
| [Payroll Prep Copilot](skills/payroll-prep-copilot) | Light setup | A payroll month that runs on a checklist instead of memory, with the CRA remittance date, the T4 deadline and the change-of-status paperwork all in one place |
| [Loan Application Prep](skills/loan-application-prep) | Light setup | A lender-ready package, from the one-page business summary to the cash-flow forecast, assembled in a week instead of a quarter |
| [Payment Fraud Screener](skills/payment-fraud-screener) | Light setup | A two-minute check on every payment request that changes banking details, adds a new payee or arrives in a hurry, plus the written rule your staff follow when you're away |

### HR & Hiring

| Skill | Setup | What you get |
| --- | --- | --- |
| [Hiring Assistant](skills/hiring-assistant) | Light setup | Hire with structure: job posts, interview kits, rubrics, onboarding |
| [Recruiting Pipeline Manager](skills/recruiting-pipeline-manager) | Light setup | Every candidate moved, messaged, and scored from one place |
| [Onboarding Copilot](skills/onboarding-copilot) | Light setup | New hires productive by week two, and nobody re-invents day one |
| [Shift Scheduler Copilot](skills/shift-scheduler-copilot) | Light setup | The weekly schedule builds itself from memory; you make the judgment calls |
| [Job Posting Compliance Checker](skills/job-posting-compliance-checker) | Light setup | Every job ad checked against Ontario's 2026 posting rules before it goes live, with the pay range, the AI line and the vacancy statement where the law wants them |
| [Health and Safety Policy Writer](skills/health-and-safety-policy-writer) | Light setup | The written health and safety policy, the violence and harassment policies and the posting checklist an Ontario workplace with six or more workers has to have, drafted from how your shop runs |
| [Handover Doc Builder](skills/handover-doc-builder) | Light setup | The knowledge in a departing employee's head captured in a document their replacement can run from on day one, built in three short interviews before they leave |
| [Safety Talk Generator](skills/safety-talk-generator) | Light setup | A five-minute safety talk for every crew morning, written for this week's job and this crew's hazards, with the sign-in sheet that proves it happened |

### Strategy & Planning

| Skill | Setup | What you get |
| --- | --- | --- |
| [The Idea Grill](skills/idea-grill) | No-code | Five hostile experts interrogate your idea and score it out of 100 before you build |
| [Competitor Radar](skills/competitor-radar) | Light setup | A monthly competitor briefing from what they publish publicly |
| [Business Plan Copilot](skills/business-plan-copilot) | Light setup | A working business plan and financial forecast, built section by section |
| [Quarterly Goals Copilot](skills/quarterly-goals-copilot) | Light setup | Goals that survive week three, because something remembers them and asks |
| [Exit Readiness Planner](skills/exit-readiness-planner) | Light setup | An honest read of what a buyer or a successor would find in your business today, the eight things that move the price most, and a twelve-month plan to fix them before anyone looks |
| [Business Context Builder](skills/business-context-builder) | Light setup | A folder on your computer that tells your AI assistant what you sell, who buys it, how you sound and what it must never say, with a score for how much of the picture is backed by evidence |

## Master prompts

Copy-paste prompts with [SQUARE BRACKET] placeholders. They work in any assistant and need no setup.

### Marketing & Content

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [90-Day Marketing Plan Builder](prompts/marketing/90-day-marketing-plan.md) | No-code | Get a complete quarterly marketing plan in 20 minutes |
| [High-Converting Ad Copy Generator](prompts/marketing/ad-copy-generator.md) | No-code | Produce 10 ad variants for Google & Meta in minutes |
| [Brand Voice Codifier](prompts/marketing/brand-voice-codifier.md) | No-code | Turn your best writing into a reusable voice guide |
| [Competitor Teardown](prompts/marketing/competitor-teardown.md) | No-code | Map a competitor's strategy, gaps, and your counter-moves |
| [Email Campaign Builder](prompts/marketing/email-campaign-builder.md) | No-code | Write a 5-email campaign that sounds like you |
| [30 Days of Social Posts in One Hour](prompts/marketing/social-content-machine.md) | No-code | Generate a month of on-brand posts from one product description |
| [Customer Case Study Writer](prompts/marketing/case-study-writer.md) | No-code | A case study that sells without sounding like a brochure |
| [Google Business Profile Optimizer](prompts/marketing/google-business-profile-optimizer.md) | No-code | A profile that competes for the map pack in your neighbourhood |
| [Landing Page Copy Writer](prompts/marketing/landing-page-copy-writer.md) | No-code | Landing page copy built section by section from your customer's words |
| [Newsletter Issue Writer](prompts/marketing/newsletter-issue-writer.md) | No-code | An issue subscribers open next week too |
| [Product Launch Plan Builder](prompts/marketing/product-launch-plan.md) | No-code | A launch sequence with dates, owners, and a day-one checklist |
| [SEO Content Brief Generator](prompts/marketing/seo-content-brief-generator.md) | No-code | Briefs that make every article competitive before it's written |
| [Short-Form Video Script Writer](prompts/marketing/short-video-script-writer.md) | No-code | Thirty-second scripts with a hook that stops the scroll |
| [Price Increase Letter Writer](prompts/marketing/price-increase-letter.md) | No-code | Announce a price increase without apologizing or losing your regulars |
| [Testimonial Collector](prompts/marketing/testimonial-collector.md) | No-code | Real client quotes you can publish, collected without the awkward ask |

### Sales & Lead Generation

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Cold Outreach Personalizer](prompts/sales/cold-outreach-personalizer.md) | No-code | Write cold emails that get replies, personalized at scale |
| [Follow-Up Sequences That Don't Beg](prompts/sales/follow-up-sequences.md) | No-code | Revive stalled deals with 5-touch follow-up sequences |
| [Lead Qualification Scorer](prompts/sales/lead-qualification-scorer.md) | Light setup | Score and prioritize inbound leads automatically |
| [Objection Handling Playbook](prompts/sales/objection-handling-playbook.md) | No-code | Build responses to your 10 toughest objections |
| [Proposal & Quote Generator](prompts/sales/proposal-generator.md) | No-code | Turn call notes into a polished proposal in 15 minutes |
| [10-Minute Sales Call Prep](prompts/sales/sales-call-prep.md) | No-code | Walk into every sales call knowing exactly what to say |
| [CRM Hygiene Auditor](prompts/sales/crm-hygiene-auditor.md) | No-code | A pipeline you can finally trust for forecasting |
| [Discovery Call Question Bank](prompts/sales/discovery-call-question-bank.md) | No-code | Questions that surface budget and urgency without interrogating |
| [Referral Request Scripts](prompts/sales/referral-request-scripts.md) | No-code | Referral asks that feel natural and actually get sent |
| [Sales One-Pager Builder](prompts/sales/sales-one-pager-builder.md) | No-code | A leave-behind that sells while you're not in the room |
| [Upsell & Cross-Sell Finder](prompts/sales/upsell-opportunity-finder.md) | No-code | Revenue sitting in your current client list, mapped |
| [Win/Loss Analyzer](prompts/sales/win-loss-analyzer.md) | No-code | Learn why deals really close or die, from patterns not hunches |
| [Win-Back Campaign Writer](prompts/sales/win-back-campaign-writer.md) | No-code | A 3-touch sequence that brings lapsed customers back without begging |
| [Change Order Writer](prompts/sales/change-order-writer.md) | No-code | A written change order the customer signs before the extra work starts, with the reason, the price, the schedule impact and the one sentence that protects the original estimate |
| [RFP Go/No-Go Scorer](prompts/sales/rfp-go-no-go-scorer.md) | No-code | A twenty-minute decision on whether a tender or RFP is worth the forty hours it takes to answer, scored on the ten things that decide it, with the outline of the response if the answer is go |

### Customer Support

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Complaint De-Escalation Scripts](prompts/support/complaint-deescalation.md) | No-code | Turn angry customers into repeat customers |
| [FAQ & Knowledge Base Builder](prompts/support/faq-knowledge-base-builder.md) | No-code | Turn your inbox history into a complete FAQ |
| [Review Response Writer](prompts/support/review-response-writer.md) | No-code | Respond to every Google/Yelp review: good or brutal |
| [Support Macro Library](prompts/support/support-macro-library.md) | No-code | Generate 25 reusable reply templates for your business |
| [Voice-of-Customer Miner](prompts/support/voice-of-customer-miner.md) | No-code | Mine support tickets for product and marketing gold |
| [Churn Risk Detector](prompts/support/churn-risk-detector.md) | No-code | Spot the customers about to leave while there's time to act |
| [Customer Feedback Survey Builder](prompts/support/feedback-survey-builder.md) | No-code | Surveys people finish, with answers you can act on |
| [Help Doc Writer](prompts/support/help-doc-writer.md) | No-code | Help articles customers find before they email you |
| [Refund & Return Policy Writer](prompts/support/refund-policy-writer.md) | No-code | A policy that protects you without scaring buyers |
| [SLA & Response Policy Writer](prompts/support/sla-policy-writer.md) | No-code | Service promises you can keep, written down |
| [Support Reply Auditor](prompts/support/support-reply-auditor.md) | No-code | Ten sent replies graded against your policy and your voice, with the drift named |
| [No-Show Reducer](prompts/support/no-show-reducer.md) | No-code | A reminder sequence, a plain-language late-cancellation policy and a rebooking message built for your business, so the empty 2 p.m. slot stops being a weekly event |

### Operations & Productivity

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Automation Opportunity Audit](prompts/operations/automation-opportunity-audit.md) | No-code | Find the 5 processes you should automate first |
| [Email Inbox Triage System](prompts/operations/inbox-triage-system.md) | Light setup | Process 100 emails in 15 minutes with AI triage |
| [Meeting Notes to Action Items: AI Action Item Extractor](prompts/operations/meeting-notes-to-actions.md) | No-code | Turn raw meeting notes into action items with owners and deadlines |
| [Project Brief Builder](prompts/operations/project-brief-builder.md) | No-code | Scope any project before kickoff: goals, risks, owners |
| [SOP Writer: AI SOP Generator for Small Business](prompts/operations/sop-writer.md) | No-code | Turn "how I do it" into documentation anyone can follow |
| [Vendor Comparison Matrix](prompts/operations/vendor-comparison-matrix.md) | No-code | Compare quotes and vendors on facts, not gut feel |
| [Weekly Report Automator: AI Weekly Report Generator](prompts/operations/weekly-report-automator.md) | No-code | Compile scattered updates into one clean weekly report |
| [Client Onboarding Checklist Builder](prompts/operations/customer-onboarding-checklist.md) | No-code | New clients hit their first win without you chasing anyone |
| [Daily Standup Summarizer](prompts/operations/daily-standup-summarizer.md) | No-code | Standup notes become blockers assigned before lunch |
| [Delegation Planner](prompts/operations/delegation-planner.md) | No-code | Hand off half your task list without dropping quality |
| [Inventory Reorder Planner](prompts/operations/inventory-reorder-planner.md) | No-code | Reorder points that stop both stockouts and dead stock |
| [Process Bottleneck Finder](prompts/operations/process-bottleneck-finder.md) | No-code | Find the step that slows everything and what fixing it is worth |
| [Risk Register Builder](prompts/operations/risk-register-builder.md) | No-code | The ten risks that could actually hurt you, ranked, with responses |
| [Scheduled Task Builder](prompts/operations/scheduled-task-builder.md) | No-code | A recurring chore turned into a scheduled AI task that runs unattended and reports only what matters |
| [Privacy Policy Drafter](prompts/operations/privacy-policy-drafter.md) | No-code | A plain-language privacy policy that describes what your business collects, why, who sees it and how long you keep it, drafted from an interview so it matches how you work, and ready for a lawyer's hour instead of a lawyer's week |

### Finance & Admin

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Simple Budget Planner](prompts/finance/budget-planner.md) | No-code | Build a realistic annual budget from last year's numbers |
| [Cash Flow Analyzer](prompts/finance/cash-flow-analyzer.md) | No-code | Understand your cash position and 90-day runway in plain English |
| [Expense Categorizer](prompts/finance/expense-categorizer.md) | No-code | Clean up a messy expense export for your bookkeeper |
| [Financial Jargon Translator](prompts/finance/financial-jargon-translator.md) | No-code | Understand any contract, statement, or bank letter |
| [Invoice Chaser Sequences](prompts/finance/invoice-chaser.md) | No-code | Get overdue invoices paid without burning relationships |
| [Pricing Strategy Advisor](prompts/finance/pricing-strategy-advisor.md) | No-code | Pressure-test your pricing and find money you're leaving behind |
| [Break-Even Analyzer](prompts/finance/break-even-analyzer.md) | No-code | Know exactly how many sales cover the bills each month |
| [Debt Paydown Planner](prompts/finance/debt-paydown-planner.md) | No-code | A payoff order for your business debts with the reasoning shown |
| [Grant Application Writer](prompts/finance/grant-application-writer.md) | No-code | A draft application that answers what reviewers actually score |
| [Profit Margin Diagnostic](prompts/finance/profit-margin-diagnostic.md) | No-code | Find exactly where your margin leaks and what each leak costs per year |
| [12-Month Revenue Forecast](prompts/finance/revenue-forecast-builder.md) | No-code | A month-by-month forecast built from your real pipeline, not wishes |
| [Tax Season Prep Checklist](prompts/finance/tax-season-prep-checklist.md) | No-code | Walk into your accountant's office with everything they need, once |
| [GST/HST Filing Prep](prompts/finance/gst-hst-filing-prep.md) | No-code | A filing-ready GST/HST package for your accountant, built in an evening instead of a lost weekend |
| [Equipment Buy vs Lease](prompts/finance/equipment-buy-vs-lease.md) | No-code | A side-by-side of buying, financing, leasing and renting a piece of equipment over its working life, in cash out the door by month, with the questions your accountant needs to settle the tax side |

### HR & Hiring

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [Interview Question Bank](prompts/hr/interview-question-bank.md) | No-code | Build role-specific interviews that actually predict performance |
| [Job Description Writer](prompts/hr/job-description-writer.md) | No-code | Write job posts that attract doers, not title collectors |
| [30-60-90 Onboarding Builder](prompts/hr/onboarding-plan-builder.md) | No-code | Give every new hire a ramp-up plan on day one |
| [Performance Review Helper](prompts/hr/performance-review-helper.md) | No-code | Turn scattered observations into fair, specific reviews |
| [Resume Screener](prompts/hr/resume-screener.md) | No-code | Screen 50 resumes against your real requirements in minutes |
| [Tough Conversation Scripts](prompts/hr/tough-conversation-scripts.md) | No-code | Prepare for raises, PIPs, and lettings-go with a script |
| [Compensation Benchmark Helper](prompts/hr/compensation-benchmark-helper.md) | No-code | A defensible pay range before the negotiation, not during it |
| [Employee Handbook Drafter](prompts/hr/employee-handbook-drafter.md) | No-code | A working handbook draft your lawyer reviews instead of writes |
| [Exit Interview Analyzer](prompts/hr/exit-interview-analyzer.md) | No-code | Turn exit interviews into the three fixes that stop the next departure |
| [Offer Letter Writer](prompts/hr/offer-letter-writer.md) | No-code | An offer letter that closes the candidate without overpromising |
| [1:1 Meeting Agenda Builder](prompts/hr/one-on-one-agenda-builder.md) | No-code | One-on-ones your team stops dreading |
| [Team Training Plan Builder](prompts/hr/training-plan-builder.md) | No-code | A skills-gap map and a training plan someone will actually follow |
| [Shift Schedule Builder](prompts/hr/shift-schedule-builder.md) | No-code | Next week's schedule built in ten minutes, with the conflicts caught before they call in |

### Strategy & Planning

| Prompt | Difficulty | What you get |
| --- | --- | --- |
| [AI Board of Advisors](prompts/strategy/ai-board-of-advisors.md) | No-code | Stress-test any business decision from 5 expert angles |
| [Customer Persona Builder](prompts/strategy/customer-persona-builder.md) | No-code | Build data-grounded personas from real customer evidence |
| [Quarterly Goals (OKR) Builder](prompts/strategy/quarterly-okr-builder.md) | No-code | Set 90-day goals your team can actually execute |
| [SWOT That Isn't Useless](prompts/strategy/swot-that-isnt-useless.md) | No-code | A SWOT analysis that ends in actions, not a poster |
| [Annual Retrospective Guide](prompts/strategy/annual-retrospective-guide.md) | No-code | A year review that changes next year's plan |
| [Business Model Stress Test](prompts/strategy/business-model-stress-test.md) | No-code | Find the assumption that kills your business before it does |
| [New Market Entry Analyzer](prompts/strategy/market-entry-analyzer.md) | No-code | A go/no-go on the new market with the evidence listed |
| [Partnership Evaluator](prompts/strategy/partnership-evaluator.md) | No-code | Know if the partnership is worth it before the handshake |
| [Pivot Decision Framework](prompts/strategy/pivot-decision-framework.md) | No-code | A structured answer to "should we change course?" |
| [Pricing Experiment Designer](prompts/strategy/pricing-experiment-designer.md) | No-code | Test a price change without betting the business |
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
| [Annual Planning Workshop](workflows/annual-planning-workshop.md) | Strategy & Planning | Run a one-day annual planning session: solo or with your team |
| [LinkedIn Founder-Brand Engine](workflows/linkedin-sales-engine.md) | Sales & Lead Generation | Generate inbound leads from 3 LinkedIn posts a week |
| [SEO Blog Post Engine](workflows/seo-blog-engine.md) | Marketing & Content | Publish search-ranking blog posts weekly without a writer |
| [Monthly Finance Close](workflows/monthly-finance-close.md) | Finance & Admin | Close your books every month in one sitting, ending accountant-ready |

## Tool stacks

| Tool stack | Category | What you get |
| --- | --- | --- |
| [The SME AI Starter Stack](tool-stacks/sme-ai-starter-stack.md) | Strategy & Planning | The 7 AI tools a small business should adopt first |

## About Vexlo

[Vexlo](https://vexlo.ca) is the AI audit and toolbox for small business. Take the [free AI audit](https://vexlo.ca/audit) to find out where AI can save you hours every week, or learn the fundamentals at the [Academy](https://vexlo.ca/academy).

## License

MIT. Use these in your business, tweak them, share them.
