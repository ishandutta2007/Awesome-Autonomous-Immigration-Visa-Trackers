# Awesome-Autonomous-Immigration-Visa-Trackers

# Top Autonomous Immigration Visa Trackers Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Case Status Monitoring, Document Automation & Immigration CRM*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Immigration Visa Trackers**. These tools enable immigration attorneys, HR mobility teams, and applicants to monitor case status, automate document collection, track priority dates, and manage visa application workflows across multiple government agencies.

**Examples** include Envoy Global, Bridge US, Tracker Corp, Docketwise, Campfire Legal, Cerenade, INSZoom, LawLogix, SimpleCitizen, and Boundless Immigration (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, browser-based case tracking, and open immigration CRM—ideal for applicants, legal teams, and developers seeking transparent, vendor-independent visa tracking.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Envoy Global](https://www.envoyglobal.com/)**  
  AI-powered immigration management platform with **AskEnvoy** conversational reporting, **USCIS E-Filing** for automated electronic filing, **AI Quality Sensors** that screen every form for errors before filing, and **Automated Data Capture** that scrapes expiration dates directly from government websites . Features case milestones, unified communications center, HRIS integration, and mobile app for case status checks and document uploads . Trusted by **2,000+ corporate clients** with a **75+ NPS** from client employees .

- **[Docketwise](https://www.docketwise.com/)**  
  Modern immigration case management software trusted by thousands of immigration lawyers. Features **multilingual intakes** that dynamically generate complete immigration applications, comprehensive form library, **Priority Date Tracking** with automatic Visa Bulletin updates and email/in-app notifications , **DocketWise Leads CRM**, bulk email and SMS messaging, **HR Portal** for corporate clients, QuickBooks integration, and **eFiling** for USCIS (I-130, N-400, I-765, I-129), DOL (ETA-9141, ETA-9035), and CEAC (DS-160, DS-260) . Integrates with Clio for automatic contact and matter syncing .

- **[Bridge US](https://www.bridge.us/)**  
  Immigration case management and compliance platform for employers and law firms. Features case tracking, document management, and compliance workflows.

- **[Tracker Corp](https://www.trackercorp.com/)**  
  Immigration case management and compliance software for corporate immigration programs. Features case tracking, reporting, and integration with HR systems.

- **[Campfire Legal](https://www.campfirelegal.com/)**  
  Immigration case management platform for law firms. Features client intake, document automation, and case workflow management.

- **[Cerenade](https://www.cerenade.com/)**  
  Immigration case management software with forms automation, case tracking, and compliance reporting.

- **[INSZoom](https://www.inszoom.com/)**  
  Immigration case management platform for law firms and corporate clients. Features case tracking, document management, and reporting.

- **[LawLogix](https://www.lawlogix.com/)**  
  Immigration case management and I-9 compliance software. Features case tracking, forms automation, and compliance workflows.

- **[SimpleCitizen](https://www.simplecitizen.com/)**  
  Immigration application platform for individuals and employers. Features guided application workflows and case tracking.

- **[Boundless Immigration](https://www.boundless.com/)**  
  Immigration services platform combining software with legal support. Features application preparation, case tracking, and attorney review.

## Open-Source GitHub Projects

- **[USCIS Case Tracker (humanstack)](https://github.com/humanstack/uscis-case-tracker)**  
  Free, open-source, **privacy-focused** USCIS case tracking tool that runs **entirely in your browser** . Track multiple immigration cases (I-485, I-765, I-131, I-140, I-130, N-400, I-129), view unified timelines, and monitor updates **without sending any data to external servers**. Features: **100% client-side processing** with zero data sent to servers, all data stored locally in browser, no tracking/analytics, **receipt number masking** for sharing, smart insights that identify system vs. officer updates, biometric and FBI check pattern detection, supervisor review highlighting, and **Reddit-friendly export**. No account required. Works offline after initial load. The most privacy-preserving open-source USCIS tracker available .

- **[VisaStatusMonitor](https://github.com/yuanweize/VisaStatusMonitor)**  
  Full-process international visa appointment and residence permit status monitoring system with multi-channel alerts (MIT) . Features **multi-country support** via plugin architecture (currently Czech Republic, expanding), **multi-user management** with registration/login, responsive web interface, **email/Telegram/WebSocket notifications**, smart scheduling to avoid overwhelming target websites, plugin system for adding new countries, real-time status updates and history, multi-language support (Chinese/English), and **Docker one-click deployment**. Tech stack: FastAPI, SQLAlchemy, SQLite/MySQL, APScheduler, Vue 3, Vite, Element Plus. **Explicitly independent**—not affiliated with any government immigration agency .

- **[CRMIntranet (danjohn007)](https://github.com/danjohn007/CRMIntranet)**  
  Open-source **Visa Application CRM** (Spanish interface) with comprehensive case management . Features real-time dashboard with interactive charts, **export to Excel/CSV/PDF**, role-based dashboards, global configuration (site name, logo, email, themes), **PayPal integration**, QR code generation API, and integrations with HikVision and Shelly Cloud devices. Built with PHP 7.4+, MySQL 5.7+, Apache. Includes sample database schema for Querétaro state with test users. **License not specified**—review before production use .

- **[CM Immigration CRM](https://github.com/simontcodes/captstone-front)**  
  Open-source CRM with custom intake form built for an immigration consultation company . Features appointment scheduling with date/time selection, service type selection, payment processing, personal information intake, admin authentication, client and appointment viewing, and sorting. Built with React, Sass, and requires a separate API backend .

- **[Git for Immigration](https://devpost.com/software/git-for-immigration)**  
  Open-source project treating **immigration cases as GitHub repositories**—every missing artifact becomes a labeled Issue, every milestone becomes a tagged Release, every helper review becomes a Pull Request . Built with Next.js 14, TypeScript, Tailwind, Featherless.ai (6 AI workloads through one API), Tavily (live USCIS research), and React Flow (interactive Evidence Graph). **Hackathon project**—not production-ready .

- **[Prarabda/visa-application](https://github.com/Prarabda/visa-application)**  
  Web-based visa application system built with HTML, CSS, PHP, and MySQL . Users fill out multi-step visa application forms, view and confirm details, and track application status using passport number. Admin dashboard for managing applications. **Stars: 0**—early-stage project .

- **[VisaShield AI](https://github.com/Yash-Kavaiya/VisaShield-Angular)**  
  Enterprise-grade immigration intelligence platform using **Google Agent Development Kit (ADK)** and **Gemini AI** to automate visa petition adjudication . Features AI-powered adjudication with chain-of-thought reasoning, **RAG-based knowledge retrieval** from USCIS Policy Manual/INA statutes/AAO decisions, real-time citation validation to prevent hallucinations, comprehensive audit trails, **sensitive data scanner** (A-Number, passport, SSN/ITIN detection), threat protection (jailbreak detection), and Kanban case board. Built with Angular 20, FastAPI, Google ADK, Gemini 3 Flash, Cloud Run, Datadog. **Note**: Adjudication automation raises serious legal and ethical concerns—human review remains essential .

### Additional Strong Open-Source Options

- **[VisaStatusMonitor Plugin System](https://github.com/yuanweize/VisaStatusMonitor)** — Extensible plugin architecture for adding new country support beyond Czech Republic .
- **[USCIS Case Status Notifier](https://github.com/ubaniabalogun/uscis-case-status-notifier)** — Serverless application sending SMS when USCIS case status changes .
- **[USCIS Case Tracker Bot](https://github.com/pedrocastellanos/uscis-case-tracker-bot)** — Simple Telegram bot for tracking USCIS cases .
- **[RogueArt USCIS Notifier](https://github.com/RogueArt/uscis-notifier)** — Desktop app built with React and Rust to notify on USCIS case status changes .
- **[H1B Visa Analytics Dashboard](https://github.com/lokesh97jain/H1B-Visa-Analytics-Dashboard)** — Power BI dashboard for visualizing H1B visa application data .
- **[Visa Bulletin Scraper](https://github.com/DavidBellamy/visa_dates)** — Web scraper for US visa bulletins .
- **[Passport Index DB](https://github.com/ngshiheng/passportindexdb)** — Tracking historical changes in passport rankings and visa requirements .
- Community **n8n** workflows for visa status alerting and document collection automation.

**Frameworks for building custom systems**: Combine **USCIS Case Tracker** for privacy-focused browser-based tracking with **VisaStatusMonitor** for multi-country monitoring and notifications, **CRMIntranet** for case management, **Docketwise** integration patterns for legal practice workflows, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade visa tracking platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Immigration tracking tools handling personal data must comply with data protection regulations (GDPR, CCPA, etc.) and maintain appropriate security for sensitive documents.
- **Open-source immigration trackers are limited in enterprise features.** The most mature options (Envoy Global, Docketwise) are commercial SaaS platforms. Open-source alternatives focus on **individual case tracking** (USCIS Case Tracker), **status monitoring** (VisaStatusMonitor), or **basic CRM** (CRMIntranet). Enterprise-grade document automation, e-filing, and compliance workflows are not available in open-source.
- **Privacy is the primary advantage of open-source trackers.** USCIS Case Tracker runs entirely in your browser with no data sent to servers . For applicants concerned about data privacy, browser-based tools eliminate third-party data exposure. However, they require manual JSON extraction from USCIS portal—not automated.
- **AI-powered adjudication requires extreme caution.** VisaShield AI automates visa petition adjudication with AI . Immigration decisions have profound legal consequences—AI outputs must be reviewed by qualified immigration attorneys. No open-source tool should be used as a substitute for legal advice.
- Self-hosted open-source solutions require proper security hardening, document storage encryption, and ongoing maintenance. Immigration data is highly sensitive and subject to strict confidentiality obligations.

---

**Made for immigration attorneys, HR mobility teams, applicants, and developers building transparent visa tracking solutions.**  
Let's make Autonomous Immigration Visa Trackers more open, data-driven, and privacy-preserving.
