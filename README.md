# Awesome-Low-Code-Internal-Tools

## Top Low-Code Internal Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Drag-and-Drop App Builders, Workflow Automation & Self-Hosted Internal Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Low-Code Internal Tools**. These tools enable teams to build admin panels, dashboards, approval workflows, and operational CRUD apps with minimal hand-written code—connecting to existing databases and APIs while providing a visual builder for rapid iteration.



**Examples** include Retool, Power Apps, OutSystems, Mendix, Appian, Appsmith, Budibase, ToolJet, and Windmill (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-user SaaS fees, and retaining full control over data and deployment. The open-source landscape is anchored by **Appsmith** (the most widely adopted open-source Retool alternative), **Budibase** (the all-in-one platform with built-in database), **ToolJet** (the enterprise-focused builder with strong data source coverage), and **Windmill** (the developer-first platform turning scripts into workflows and UIs), with **NocoDB** and **Baserow** serving Airtable-style database needs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global low-code development technologies market is estimated at **$25B–$35B+** (projected by Gartner to exceed **$58B by 2029** at a ~14% CAGR). The sector is **moderately fragmented**—while enterprise mega-caps (Microsoft Power Apps) and established leaders (OutSystems, Mendix, Appian) dominate large corporate IT footprints, the market does not have a single winner-take-all monopoly due to wide fragmentation across developer-centric tools (Retool), specialized operational platforms (Quickbase, Caspio), and thriving self-hosted open-source alternatives.

## SaaS/Hosted Platforms

| Product | Size / Valuation / Revenue | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Power Apps (Microsoft)](https://powerapps.microsoft.com/)** | **~$3.1T Market Cap** (Parent Microsoft; Power Platform generates multi-billion $ revenue) | Microsoft's enterprise low-code platform deeply integrated into Microsoft 365, Azure, and Dataverse. | Starts at **$20/user/month** (Power Apps Premium for unlimited apps); **$12/user/month** (Premium tier with 2,000+ seat volume minimum). | **Power Apps Developer Plan**: Free forever for 1 developer environment; includes Dataverse & premium connectors (strictly non-production dev/testing). |
| **[Mendix](https://www.mendix.com/)** | **$100M+ ARR** (Acquired by Siemens AG for **$730M / €600M**; Siemens Market Cap ~$150B+) | Enterprise low-code platform with multi-cloud deployment and industrial Siemens ecosystem alignment. | Starts at **$1,090/month** (Standard One App tier, billed annually); **$2,725/month** (Standard Unlimited Apps). | **Free Edition**: Free forever for 1 app environment on Mendix Cloud, up to 5 internal users, 1 GB storage, non-SLA community support. |
| **[OutSystems](https://www.outsystems.com/)** | **€500M+ ($500M+) Revenue** (Peak private valuation **$9.5B**) | High-performance enterprise low-code platform offering full-stack DevOps and governance. | Starts at **€1,250/month** (~$1,350/month, billed annually) for single-app production workloads. | **Free Edition**: Free forever for 1 active app, up to 100 end users, single shared dev/test/production environment. |
| **[Retool](https://retool.com/)** | **$3.2B Valuation** (Series C2; **~$120M+ ARR**) | The category-defining developer-first internal tool builder with visual UI canvas, workflows, and self-hosting. | **Free**: $0. Paid starts at **$10/builder/month + $5/user/month** (Team plan); **$50/builder/month + $15/user/month** (Business plan). | **Free plan**: Free forever for up to 5 users, includes 500 workflow runs/month, 250 AI credits/month, and unlimited web apps. |
| **[Appian](https://appian.com/)** | **~$3.0B Market Cap** (NASDAQ: APPN; **~$850M Annual Revenue**) | Process automation and low-code platform specializing in case management, BPM, and complex workflows. | Starts at **$70/user/month** (Standard tier for departmental workflows; enterprise agreements typically require a 100-seat floor). | **Appian Community Edition**: Free forever sandbox environment for 1 developer to build/test applications (non-production use only). |
| **[Quickbase](https://www.quickbase.com/)** | **$1.0B Valuation** (Acquired by Vista Equity Partners; **$200M+ Revenue**) | No-code/low-code platform tailored for operational data management, field operations, and reporting. | Starts at **$25/month** (Team plan, includes 120 credit allowances); Department plan starts at **$300/month** (1,800 credits). | **Pave Free Plan**: Free forever for 1 app, 1 builder, up to 3 end users, with 100 platform credits. |
| **[Caspio](https://www.caspio.com/)** | **~$120M Revenue** (Bootstrapped / Private) | Visual relational database and application builder featuring flat fees without per-user licensing costs. | Starts at **$15/month** (prepaid Starter tier) or **$50/month** (Standard edition); pricing scales with data records rather than user seats. | **Free Trial**: 14-day free trial with access to all standard builder capabilities, full database storage, and integrations (no permanent free tier). |
| **[WaveMaker](https://www.wavemaker.com/)** | **~$25M–$50M Revenue** (Pramati Technologies subsidiary / Private) | Low-code full-stack platform generating open-standard Angular and Java/Spring Boot code. | Starts at **$99/developer/month** (WaveMaker Online starter license); Enterprise deployments start around **~$24,000/year/app**. | **Guided Free Trial**: 30-day fully functional free trial with full studio access and cloud prototyping environment (no permanent free tier). |
| **[Betty Blocks](https://www.bettyblocks.com/)** | **~$9M–$15M Revenue** (Historical private valuation €50M+) | Enterprise citizen-developer platform focused on business application building with strong governance. | Starts at **€1,500/month** (~$1,620/month, billed annually) for core builder platform with unlimited internal application users. | **Free Trial**: 14-day free trial with full access to sandbox studio, visual modeler, and templated components (no permanent free tier). |

## Open-Source GitHub Projects



- **[Appsmith](https://github.com/appsmithorg/appsmith)** [![GitHub Stars](https://img.shields.io/github/stars/appsmithorg/appsmith?style=social&color=white)](https://github.com/appsmithorg/appsmith/stargazers)  

  **The most widely adopted open-source Retool alternative.** Build admin panels, dashboards, and CRUD apps by dragging widgets and connecting to 25+ databases and any REST API. **Features**: JavaScript anywhere, Git sync for version control, granular RBAC, audit logs, and self-hosting via Docker/Kubernetes. **Cloud pricing**: Free for up to 5 users; Business $15/user/month; Enterprise $2,500 for 100 users . **Community Edition** is free to self-host with no user limits. Best for teams wanting a mature, well-documented builder with the broadest data source coverage.



- **[Budibase](https://github.com/Budibase/budibase)** [![GitHub Stars](https://img.shields.io/github/stars/Budibase/budibase?style=social&color=white)](https://github.com/Budibase/budibase/stargazers)  

  **The all-in-one platform with built-in database.** Combines an internal DB (or connects to external sources), drag-and-drop app builder, automation engine, and AI agent builder in one package. **Features**: 40+ pre-built components, workspace management, user roles, and SSO on paid tiers. **Cloud pricing**: Free (1 creator, 50k DB rows); Premium $49/mo (1 creator, 250k rows); Business $299/mo (3 creators, 500k rows) . **Self-hosted** is free with no creator limits. Best for teams wanting a single platform covering database, UI, and automation without stitching tools together.



- **[ToolJet](https://github.com/ToolJet/ToolJet)** [![GitHub Stars](https://img.shields.io/github/stars/ToolJet/ToolJet?style=social&color=white)](https://github.com/ToolJet/ToolJet/stargazers)  

  **The enterprise-focused builder with strong data source coverage.** Connects to PostgreSQL, MySQL, MongoDB, Snowflake, BigQuery, S3, and any REST/GraphQL API. **Features**: visual app builder with 50+ widgets, JavaScript code support, multi-page apps, granular permissions, and audit logs. **Self-hosted** Community Edition is free with no user limits. Best for teams needing a polished UI builder with enterprise features and broad database support.



- **[Windmill](https://github.com/windmill-labs/windmill)** [![GitHub Stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=social&color=white)](https://github.com/windmill-labs/windmill/stargazers)  

  **The developer-first platform turning scripts into UIs.** Write logic in Python, TypeScript, Go, Bash, or SQL; Windmill auto-generates UIs, APIs, and workflows. **Features**: Git-based deployment, VS Code extension, secrets management, and self-hosting via Docker/Helm. **License**: AGPL-3.0 for core; enterprise features under commercial license. Best for engineering teams that want to build internal tools by writing code, not dragging widgets.



- **[NocoDB](https://github.com/nocodb/nocodb)** [![GitHub Stars](https://img.shields.io/github/stars/nocodb/nocodb?style=social&color=white)](https://github.com/nocodb/nocodb/stargazers)  

  **The Airtable alternative for existing databases.** Turns any Postgres, MySQL, SQLite, or SQL Server database into a spreadsheet-like interface with forms, galleries, and kanban views. **Features**: REST APIs auto-generated, webhooks, and role-based access. **Self-hosted** is free and open-source. Best for teams wanting a familiar spreadsheet UI over their existing data without migrating it.



- **[Baserow](https://github.com/bramw/baserow)** [![GitHub Stars](https://img.shields.io/github/stars/bramw/baserow?style=social&color=white)](https://github.com/bramw/baserow/stargazers)  

  **The open-source Airtable alternative with a modern UI.** Spreadsheet-database hybrid with views (grid, gallery, form), formulas, and API access. **Self-hosted** via Docker is free. Best for teams wanting a polished Airtable-like experience they can host themselves.



### Additional Strong Open-Source Options



- **Directus** — Database-first headless CMS and data platform that wraps any SQL database with a no-code admin UI. Best for teams that want an instant admin panel over an existing schema.

- **Payload CMS** — Next.js-native headless CMS with a customizable admin UI. Best for Next.js teams wanting content and data management in one codebase.

- **Appwrite** — Self-hosted backend-as-a-service with database, auth, storage, and functions. Best for teams building internal tools that need a backend layer alongside the UI.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Pricing models vary dramatically**: Retool and Appsmith charge per user; Budibase charges per creator with generous end-user allowances; Quickbase charges by credits; Caspio charges by records with **no per-user fees** . Model your actual usage pattern before committing.

- **Free tiers are for evaluation, not production**: Retool Free caps at 5 users and 500 workflow runs; Power Apps Developer Plan is explicitly non-production; WaveMaker's free trial is 30 days with no permanent tier .

- **Open-source platforms still require infrastructure**: Appsmith, Budibase, and ToolJet all need servers, databases, and maintenance—free software is not free operations.

- **WaveMaker has withdrawn its affordable developer tier**: the $99 license is gone, replaced by enterprise-only pricing (~$24k/year per app) . Evaluate carefully before investing in a trial.



---



**Made for operations teams, internal tool builders, and developers who want to ship admin panels without writing frontend code.**  

Let's make low-code internal tools more open, appropriately priced, and self-hostable.
