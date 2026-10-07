# Rajat Diwakar | AI Automation Engineer

AI Automation Engineer building AI-based business solutions that remove repetitive manual work, reduce human intervention and cut human error: OCR and LLM document processing, API integration, workflow automation and full-stack internal tools.

**Location:** Faridabad, Haryana, India
**Email:** [diwakarrajat16@gmail.com](mailto:diwakarrajat16@gmail.com)
**LinkedIn:** [linkedin.com/in/rajat-diwakar-bb081524b](https://www.linkedin.com/in/rajat-diwakar-bb081524b)

> **Note:** This repository is a portfolio of project write-ups, diagrams and documentation. The source code, data and business rules of the internal tools below belong to the company they were built for and are not included.

---

## Technical skills

| Area | Skills |
|---|---|
| AI & Automation | OpenAI API, Claude API, Prompt Engineering, OCR / Document Processing, Workflow Automation, AI coding tools |
| Programming | Python, JavaScript, TypeScript, SQL (basic: C, Java) |
| Data & Web | Supabase, PostgreSQL, REST APIs, Next.js, React.js, HTML, CSS |
| Industrial Automation | ABB RobotStudio (simulation) |
| Tools & Deployment | Git, GitHub, Vercel |

---

## Experience

**IT Intern, Presto Stantest Pvt. Ltd., Faridabad** (Jun 2026 – Sep 2026)

- Built AI-based business solutions that automated repetitive internal processes and reduced human intervention, using Next.js and Supabase with AI-assisted development.
- Used OpenAI and Claude LLM APIs with OCR to read and analyse documents automatically, reducing manual data entry and human error.
- Delivered multiple internal applications covering service reports, call audits, HR, purchase orders, transport billing audit, performance analytics, task management and field sales.
- Tested and deployed on Vercel, and improved the tools based on feedback from users.

![Delivery workflow](docs/images/lifecycle.png)

**Industrial Training Intern, ABB Robotics India Pvt. Ltd.** (Feb 2026 – May 2026)

- Trained on ABB Robotics products and the customer service portfolio.
- Supported service coordination and reporting.

**Front-End / React.js Intern, CodTech IT Solutions (Remote)** (Jun–Oct 2025, Jan–May 2026)

- Completed two 16-week internships building responsive web apps with HTML, CSS, JavaScript and React.js.
- Worked on reusable components, state management and REST API integration.

---

## Projects at a glance

| # | Project | What it does | Key technology |
|---|---|---|---|
| 1 | [AI Service Report Analyzer](#1-ai-service-report-analyzer) | AI reading of service reports; conveyance audit | Next.js 14, TypeScript, Neon Postgres, Vercel, AI vision model |
| 2 | [Call Audit Application](#2-call-audit-application) | AI scoring of recorded calls | Next.js, Supabase, Claude API |
| 3 | [HR Support Platform](#3-hr-support-platform-hr-assessment-app) | HR process management with AI-assessed hiring | AI assessments and reports |
| 4 | [PO Manager](#4-po-manager) | AI validation and tracking of purchase orders | AI analysis and reports |
| 5 | [FieldBrief](#5-fieldbrief-sales-pitch-app) | AI visit briefs, GPS meeting tracking, team visibility | Next.js, React, Claude API |
| 6 | [TCAT](#6-tcat-transport-charges-audit--tracking-system) | AI freight calculator, monthly bill comparison, risk flagging | Next.js, Supabase, AI image input |
| 7 | [Task Management App](#7-task-management-app) | Task allotment, reminders, escalation, audit trail | Next.js, Supabase, Push Notifications |
| 8 | [Technical Dashboard](#8-technical-dashboard-meeting-dashboard) | Calendly replacement: booking, meeting tracking, AI insights | Next.js, TypeScript, Supabase, Claude API |

---

## Featured projects

*All built for internal use at Presto Stantest Pvt. Ltd.*

### 1. AI Service Report Analyzer

A web app that reads service visit reports with an AI vision model and tracks engineer performance and conveyance, reducing manual review and human error.

- Service visit reports read automatically by a vision model
- Separate Admin-only Conveyance Audit module, extended feature by feature
- Engineers get their own limited login to see only their own visits, bills and reports
- Admins create engineer accounts from an Engineer Directory

**Tech stack:** Next.js 14, TypeScript, Neon Postgres, Vercel, AI vision model

![AI Service Report Analyzer flow](docs/images/sra.png)

### 2. Call Audit Application

Employees upload call recordings; AI transcribes each call and scores it against a structured rubric.

- Automatic transcription and scoring of every uploaded call
- 5-category rubric: opening and rapport, needs discovery, value case, objection handling, closing and next steps
- Performance tracking across employees and calls

**Tech stack:** Next.js, Supabase (Postgres, Storage, Edge Functions), Claude API

![Call Audit flow](docs/images/call.png)

### 3. HR Support Platform (HR Assessment App)

A complete HR process management and digitalisation tool that covers candidate assessment through to hiring.

- DISC and cognitive tests generated from each candidate's resume
- AI-analysed assessment report prepared for every candidate
- Three hiring rounds run through structured pipelines
- Candidate management in one place

**Outcome:** Less manual screening and coordination effort for the HR team.

![HR platform flow](docs/images/hr.png)

### 4. PO Manager

A purchase order management tool where employees upload POs and every number is tracked.

- AI analysis of each PO to decide whether it is valid or not
- Auto-generated PO report highlighting the major numbers and details
- Helps the employee accept or reject the PO
- Lets the employer track employee performance and drive appreciation

**Outcome:** Less repetitive manual checking and human error in purchase order handling.

![PO Manager flow](docs/images/po.png)

### 5. FieldBrief (Sales Pitch App)

An AI-powered sales assistant that helps field reps prepare for customer visits. It is a complete Next.js and React application with mobile-first design.

- Smart briefs generated from company photos
- Meeting tracking with GPS
- Real-time team visibility for managers
- Optional Claude API integration for AI briefs

**Tech stack:** Next.js, React, JSON persistence, Claude API (optional)

![FieldBrief flow](docs/images/pitch.png)

### 6. TCAT (Transport Charges Audit & Tracking System)

An internal web app for auditing and managing transport billing and freight, with a built-in freight calculator.

- Freight calculator: the user provides a dispatch slip as an image and AI reads it
- Complete logic base that calculates freight from various parameters
- Monthly bill comparison and risk flagging
- Bill inbox, charge calculation, rule matching and negotiations modules
- Editable comparison reports with an auditor sign-off workflow

**Tech stack:** Next.js, Supabase, AI image input

**Outcome:** Freight calculation that took about 10 minutes of manual work on average now takes 20 to 30 seconds with AI.

![TCAT flow](docs/images/tcat.png)

### 7. Task Management App

A single-company internal task allotment and follow-up system where office staff assign tasks to colleagues and automatic push notifications keep work moving.

- Instant push notification with task details and deadline, then reminders timed by priority from low to urgent
- Automatic escalation of overdue tasks to the assignee's senior through the reporting hierarchy
- Manager view of team tasks, with every status change in an audit trail
- Role-based access for employees, managers and admins via row-level security, plus a notification log that prevents duplicate alerts

**Tech stack:** Next.js, Supabase (PostgreSQL, Auth, RLS, pg_cron, Edge Functions), Push Notifications

![Task Management flow](docs/images/task.png)

### 8. Technical Dashboard (Meeting Dashboard)

**Challenge:** No centralised system to manage client meetings, track outcomes or monitor individual performance. Calendly needed a paid plan for API access and could not record what happened in a meeting or measure deal progress.

**Solution:** A full-stack internal platform for the technical sales team that replaced Calendly with a custom, cost-free booking and meeting management system, built and deployed end to end.

- Public booking link per team member; meetings appear in the dashboard instantly
- PIN-protected availability settings for days and time slots
- Meeting table with filters, status, notes, interest level (Hot, Warm, Cold), deal status and next action
- Reassignment with a full audit log of who, when and why
- Employee performance tracking and charts for meetings per day and week, status and comparison
- Claude API: pre-meeting briefs, post-meeting summaries and management insights
- Live updates with Supabase Realtime

**Tech stack:** Next.js 14 (App Router), TypeScript, Tailwind CSS, Supabase (PostgreSQL, Realtime), Anthropic Claude API, Recharts, Vercel, GitHub

**Impact:** Removed dependency on paid scheduling tools, gave management real-time visibility into meetings and deal outcomes, and reduced manual effort tracking notes and follow-ups.

![Technical Dashboard flow](docs/images/dash.png)

---

## Entrepreneurial venture

**Runwise Automation Private Limited** (in development)

- Building a startup that develops AI-driven process automation software tools for small businesses.
- Company website being built on Supabase (content, logins, files) and Vercel hosting, with a no-code editable content model for the team.

## Academic project

**Pick & Place Robot Simulation** (ABB RobotStudio)

- Simulated and programmed an automated pick-and-place operation in ABB RobotStudio.
- Covered motion sequences and object handling.

## Education

**B.Tech, Robotics & Artificial Intelligence** (2022 – 2026)
Manav Rachna University, Faridabad, Haryana | CGPA: 7.54 / 10

---

## Contact

- Email: [diwakarrajat16@gmail.com](mailto:diwakarrajat16@gmail.com)
- LinkedIn: [linkedin.com/in/rajat-diwakar-bb081524b](https://www.linkedin.com/in/rajat-diwakar-bb081524b)
- Phone: +91 9625413403
