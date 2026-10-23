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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[Retool](https://retool.com/)** | The category-defining internal tool builder with AI-native app generation, workflows, and self-hosting options. | **Free**: 5 users. **Team**: $10/builder/mo + $5/internal user/mo. **Business**: $50/builder/mo + $15/internal user/mo. **Enterprise**: custom . | **Free plan**: Up to 5 users, 500 workflow runs/month, 250 AI credits/month, unlimited web apps . |

| **[Power Apps (Microsoft)](https://powerapps.microsoft.com/)** | Microsoft's low-code platform integrated with the Power Platform and Dataverse. | **Premium**: $29.90/user/month (AU pricing) for unlimited apps, 500 AI Builder credits, 250 MB database . | **Power Apps Developer Plan**: Free for development/testing, includes Dataverse Developer environment and premium connectors. Not for production use. |

| **[OutSystems](https://www.outsystems.com/)** | Enterprise high-performance low-code platform with full DevOps automation and multi-app portfolios. | **Free**: up to 100 end users. **Standard**: from €1,250/month (approx. $1,350). **Enterprise**: custom . | **Free tier**: 1 app, up to 100 end users, one environment (dev/test/prod combined), community support . |

| **[Mendix](https://www.mendix.com/)** | Enterprise low-code with multi-app support and Siemens ecosystem alignment. | **Free**: $0. **Standard One App**: $1,090/month. **Standard Unlimited**: $2,725/month. **Premium**: custom . | **Free tier**: 1 app, limited users, Mendix Cloud hosting, community support . |

| **[Appian](https://appian.com/)** | Enterprise process automation and low-code platform with strong workflow capabilities. | Per-user, per-application pricing. Standard/Advanced/Premium tiers available; contact sales for quotes . | **Appian Community Edition**: Free for developers, 1 app, limited users, non-production use. |

| **[Quickbase](https://www.quickbase.com/)** | No-code platform focused on operational workflows and data management. | **Pave Free**: $0. **Team**: $25/mo (120 credits). **Department**: $300/mo (1,800 credits) . | **Free plan**: 1 app, 1 builder, up to 3 users, 100 credits (then $20 per 100 credits) . |

| **[Caspio](https://www.caspio.com/)** | No-code database app builder with **no per-user fees**—priced by records and features. | **Team**: $15/mo (prepaid) / on-demand. **Business/Enterprise**: scale with records . | **Free trial**: 14 days with full feature access. No permanent free tier . |

| **[Betty Blocks](https://www.bettyblocks.com/)** | No-code platform for business apps with a focus on speed and enterprise governance. | Custom pricing; typically enterprise-tier. | **Free trial**: 14 days. No permanent free tier. |

| **[WaveMaker](https://www.wavemaker.com/)** | Low-code platform for professional developers with full-stack app generation. | **Enterprise-only**: ~$24,000/year per application (AWS hosting included) . | **30-day free trial**. No free tier—**$99 developer license has been withdrawn** . |



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
