# Jesse van de Zand

I improve how teams work by redesigning processes and automating them with AI. Where a process needs its own software, I build it end to end with AI development tools. I live in Barcelona.

How I work: I identify the business need, discuss it with management and other stakeholders, I decide how it works, and with AI I write the code. I own the data model, the roles and permissions, the approval steps and the rollout.

The repositories behind the work below are private, because they hold company and client logic and data. This page describes them, and I am happy to walk through any of them in a call. For a public example of how I approach workflow automation, see [workflow-automation-skills](https://github.com/vandezand-ctrl/workflow-automation-skills).

## Workflow automation with Claude skills

At an international consultancy firm with offices in Europe, Africa and Asia, I built and curate a library of 40+ reusable Claude skills that automate recurring steps in project management and delivery. The skills are packaged as plugins that the whole team installs. Each skill has a plain-language summary that colleagues read in the firm's internal platform. Every change goes through a pull request with a review and an automated check before it merges. I teach the team to use them through an internal academy and in weekly courses and prompting sessions.

What the library covers:

- **Business development:** pre-screen a request for proposals into a go/no-go recommendation; match it to the firm's services and track record and produce a match brief.
- **Project management and delivery:** draft a project's background, budget and work plan from transcripts and emails; draft steering committee minutes with every action item captured; draft meeting agendas from earlier notes; write the weekly review of an accelerator programme per company; keep each project's onboarding documents in line with its files.
- **Research and customer insight:** a sourced research briefing with an independent review; qualitative thematic analysis; interactive value chain maps from field research; customer interview scripts grounded in Mom Test practice; transcription and summaries of interview recordings, with patterns across them; NPS survey analysis; competitor pricing comparisons.
- **Product and data:** critiques of a product strategy; answers to data questions by querying a database; weekly analytics dashboards; user-facing release notes from a commit.
- **Communication and design:** client emails in the writer's own voice, with a voice profile that learns from what was actually sent; on-brand slides, reports and prototypes from the firm's design system.

## AI-enabled software building

I build with AI coding tools inside a fixed review process, run through skills in the same library:

- Every implementation plan gets a CTO-level review with evidence sweeps, repeated until it passes, before any work starts.
- A clickable before-and-after prototype is approved before any code is written. Screenshots of the finished branch are signed off before it merges.
- Backend development plans are generated from an existing frontend. Code documentation is brought back in line with the code after each change.
- A safety check runs before any change to the operations platform's scripts.
- Flowcharts, system diagrams and UI wireframes are drawn as part of planning.

Four applications built this way are in daily use:

### Internal operations platform for an international consultancy firm
Started as a resource planner: staffing plans, availability, utilization and billability per person against targets, and income reporting, read from the finance system's exports. It has grown into the firm's operations platform: project tracking and project finances by phase, a CRM for business development, a learning academy with courses and progress per person, and a build board for the AI-coded tools. Used by management, HR, finance and every project manager; specific modules by the whole team.
Roles: regular, project manager, country lead, finance, HR, partnerships, management, IT lead. Working days and leave per country are calculated, not typed.
HTML, Python, JavaScript, TypeScript · 2,700+ commits

### Hiring and onboarding tool for a 500-employee health-finance company (India)
Tracks field-sales hiring from requisition to joining: requisition approvals, candidate pipeline, AI CV screening with the recruiter deciding, interview rounds, offer, onboarding, and headcount against plan by city, synced with the company's planning sheet. Built working directly with the CEO. 37 active users in four roles (admin, approver, talent acquisition, head of department); 214 candidates and 68 requisitions across two business units. After it went live, the HR team went from six to four people while HR productivity went up.
Google sign-in; users scoped by city and business unit.
TypeScript, JavaScript · 440+ commits

### Gap-assessment tool for a development bank's SME accelerator
A six-module assessment instrument (finance, governance, environmental and social standards, talent, digital, impact) with a pre-condition check, 140 lines of enquiry, per-company scorecards and a portfolio table, used by the bank and two advisory firms. AI reads meeting notes, emails and uploaded documents and proposes updates to scores and text; a named approver accepts or rejects each change.
Roles: read-only, expert, edit, admin; audit log of settings changes; selectable AI provider.
HTML, JavaScript, Python · 370 commits · live since Oct 2026

### ERP for a woodwork manufacturer (Ghana)
Purchasing from suppliers, materials issued to artisans, production jobs at agreed prices, take-in and grading, artisan and supplier payments after CEO approval, stock, invoicing, client orders and shipping. Five roles with their own menus and daily "Today" pages: CEO, operations, warehouse, accounts, production. Amounts in GHS, with USD, GBP and CAD on client orders; 42 products in 8 lines.
TypeScript, HTML, PL/pgSQL (PostgreSQL), Python · 2,000+ commits · live since Oct 2026

## Also

- Program lead for two multi-year technical-assistance programs (GBP 7m) for a development finance institution: 50+ projects in nine countries, over 95% on objective and within budget. PMP certified.
- Tools: Claude and Claude Code, VS Code, GitHub, Google Cloud, Python and SQL in AI-assisted development, Microsoft 365 and Copilot, Zapier, Miro. Reforge programs on AI, product and growth, 2025 to 2026.

Contact: jessevandezand@gmail.com · [LinkedIn](https://www.linkedin.com/in/jesse-van-de-zand-a4a08310/)
