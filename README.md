<div align="center">

# Arul G

### Data Engineer · Full Stack Developer

Building data pipelines, analytical systems, and practical software for real business workflows.

[Portfolio](https://YOUR_PORTFOLIO_URL) · [LinkedIn](https://YOUR_LINKEDIN_URL) · [Email](mailto:YOUR_EMAIL)

</div>

---

## About

I am a Computer Science Engineering graduate focused on Data Engineering, analytics, and full-stack application development. I combine software development skills with prior industrial experience in operations reporting and inventory management.

My current interests include building reliable ETL workflows, designing analytical data models, developing API-driven applications, and translating operational requirements into maintainable software.

- **Education:** B.Tech, Computer Science Engineering — 2026
- **Experience:** Junior Engineer Trainee, Asara Pvt Ltd (Jan 2022 – May 2023)
- **Focus:** Python, SQL, ETL, PySpark, PostgreSQL, and full-stack systems
- **Location:** Tamil Nadu, India

## Technical Skills

**Languages:** Python, SQL, JavaScript, TypeScript, C++

**Data Engineering & Analytics:** Pandas, PySpark, Apache Spark, Apache Airflow, ETL, data validation, dimensional modeling, PostgreSQL, MySQL, Power BI, DAX

**Backend & Databases:** FastAPI, Node.js, Express, Fastify, REST APIs, PostgreSQL, MongoDB, Prisma

**Frontend:** React, Next.js, Vite, HTML, CSS, Tailwind CSS

**Tools & Platforms:** Git, GitHub, Docker, Linux, Vercel

> Skills listed reflect technologies represented in my project documentation and development experience. Project-specific implementation details are described below.

---

## Featured Data Projects

### 1. CommercePulse — E-commerce Data Engineering Pipeline

A batch-oriented data platform concept for transforming Indian e-commerce operational data into an analytical warehouse.

**Technology:** Python · Pandas/PySpark · PostgreSQL · Apache Airflow · Docker · GitHub Actions · Power BI / Metabase

**Engineering scope**
- Layered data flow: raw landing, staging, warehouse, and audit.
- Incremental loading design using watermarks and upserts.
- Quarantine design for invalid records while valid data continues through processing.
- Dimensional warehouse model for sales, customers, products, payments, and inventory.
- Operational runbook and architecture decision records.

**Status:** Documented pipeline design; execution evidence and dashboard verification remain to be added.

[Repository](https://github.com/ARULKINT/REPLACE_COMMERCEPULSE_REPO)

### 2. Uber Data Engineering Pipeline

An end-to-end analytical pipeline built around a ride-booking dataset, covering ingestion, data quality, PostgreSQL warehousing, orchestration, and reporting.

**Technology:** Python · Pandas · PostgreSQL · Apache Airflow · Docker · dbt design · Power BI

**Documented scope**
- Processes a 150,000-row ride-booking dataset.
- Loads a star schema with one fact table and five dimensions.
- Includes data validation, logging, analytical SQL, and Docker Compose configuration.
- Documents a six-page Power BI dashboard specification.
- Investigates duplicate booking identifiers and records a composite-key approach.

**Status:** Project documentation includes run counts and architecture; automated test and CI evidence should be added before making production-readiness claims.

[Repository](https://github.com/ARULKINT/REPLACE_UBER_PIPELINE_REPO)

### 3. Weather Data Engineering Pipeline

An API-driven data pipeline that collects current weather observations for seven Indian cities and transforms them into a PostgreSQL analytical schema.

**Technology:** Python · PySpark · PostgreSQL · OpenWeather API · JDBC · Docker Compose

**Engineering scope**
- Extracts weather payloads from an external API.
- Validates payload fields before persistence.
- Stores raw JSON and transforms records using PySpark.
- Loads city and weather dimensions and a weather fact table.
- Includes structured logging, schema documentation, and container setup.

**Status:** Documented implementation; scheduling, robust rerun idempotency, and broader automated test coverage are improvement areas.

[Repository](https://github.com/ARULKINT/weather_data_eng)

### 4. Lead Acquisition Funnel Analytics

An analytics project examining lead progression, sales interactions, channel performance, and conversion patterns for an education/training dataset.

**Technology:** Python · CSV · Power BI · DAX

**Dataset described in project documentation**
- 360 leads
- 2,192 call records
- 4 senior and 16 junior sales managers
- Funnel analysis across demo, consideration, and conversion stages

**Analysis scope**
- Data cleaning and outlier flagging.
- Funnel and channel conversion analysis.
- Manager and city comparisons.
- Dashboard measures and business recommendations.

**Status:** Analysis documented. The project should be published with a clear README, transparent dataset provenance, and appropriately qualified conclusions.

[Repository](https://github.com/ARULKINT/REPLACE_FUNNEL_ANALYTICS_REPO)

---

## Software & Full Stack Projects

### 5. Business Platform — Multi-Tenant SMB SaaS

A business operations platform designed for Indian small and medium businesses, covering billing, inventory, finance, GST workflows, and sector-specific modules.

**Technology:** Fastify · TypeScript · React · Vite · PostgreSQL · Redis · PWA

**Engineering highlights**
- Schema-per-tenant data architecture.
- Integer-paise money representation and GST domain logic.
- Offline-first POS and ordered synchronization design.
- Role-based access control and audit-log primitives.
- Sector modules for mobile repair, gym, and automobile spare parts.

**Status:** Pre-launch development; documented package tests exist, but full application CI and production hosting remain incomplete.

[Repository](https://github.com/ARULKINT/REPLACE_BUSINESS_PLATFORM_REPO)

### 6. Rowdesk — Outreach Operations Tool

An internal lead-management workflow for importing business listings, assigning records safely, and coordinating a staged outreach process.

**Technology:** Next.js · React · Prisma · Neon PostgreSQL · Zod · Vitest

**Engineering highlights**
- CSV import and lead queue workflow.
- Compare-and-swap record claiming to reduce concurrent assignment conflicts.
- Database-backed revocable sessions.
- English and Tamil message templates.
- Google Drive read-only integration.

**Status:** In production for internal workflow use.

[Live Application](https://crm-fx2.vercel.app) · [Repository](https://github.com/ARULKINT/rowdesk)

### 7. Hello Mobiles CRM

A mobile-repair shop CRM for managing customer records, repair jobs, invoices, payments, and loyalty tiers.

**Technology:** Python · FastAPI · SQLAlchemy · Alembic · PostgreSQL · HTML/CSS/JavaScript

**Features**
- Repair workflow with defined job stages.
- Customer and technician workflows.
- GST invoicing and payment tracking.
- Customer loyalty tiers and search.
- Mobile-first interface.

**Status:** MVP deployed; real-shop user acceptance testing and security hardening remain.

[Live Application](https://hello-mobiles-crm.vercel.app) · [Repository](https://github.com/ARULKINT/hello-mobiles-crm)

### 8. Textile CRM

A retail operations prototype for textile and apparel businesses, combining POS, customer management, inventory, returns, loyalty, and reporting.

**Technology:** Next.js · TypeScript · Prisma · SQLite · Tailwind CSS · Vitest · Playwright

**Implemented areas documented**
- POS checkout and barcode scanning.
- Customer ledger, returns, and loyalty accrual.
- Sales reporting with CSV/PDF export.
- Audit-log functionality.

**Status:** Functional prototype. Several screens and settings remain incomplete; not presented as production-ready.

[Repository](https://github.com/ARULKINT/REPLACE_TEXTILE_CRM_REPO)

### 9. Forge & Flint — Company Website

A bilingual company website and lead-management back office for a software solutions business.

**Technology:** React · Vite · Tailwind CSS · Three.js · Framer Motion · Express · PostgreSQL

**Scope**
- English and Tamil interface.
- Responsive website with device-capability fallbacks for the WebGL hero.
- Contact, demo, and quote lead workflows.
- Staff-facing lead administration.

**Status:** Implemented; production hardening and lead-submission safeguards remain.

[Website](https://forgeandflint.in) · [Repository](https://github.com/ARULKINT/REPLACE_FORGE_FLINT_REPO)

### 10. Pandian Hotel & Room Stay

A hotel direct-booking website with guest booking flows and staff operations features.

**Technology:** JavaScript · Vite · Tailwind CSS · Express · PostgreSQL

**Scope**
- Room availability and booking workflow.
- Centralized price quote calculation.
- GST-aware pricing logic.
- Staff access and booking management.

**Status:** Functionally complete prototype; payment processing and email delivery are not implemented.

[Live Website](https://eloquent-blancmange-9d37ea.netlify.app) · [Repository](https://github.com/ARULKINT/pandian-hotel-room-stay)

---

## Additional Work

- **Personal Portfolio:** [Live portfolio](https://YOUR_PORTFOLIO_URL) · [Repository](https://github.com/ARULKINT/REPLACE_PORTFOLIO_REPO)
- **Blogging Website:** [Live website](https://YOUR_BLOG_URL) · [Repository](https://github.com/ARULKINT/REPLACE_BLOG_REPO)
- **PDF Question Bank Analyzer:** Python, NLP, and MongoDB-based document analysis application. [Repository](https://github.com/ARULKINT/REPLACE_PDF_ANALYZER_REPO)

---

## What I Am Working Toward

- Strengthening production-grade ETL design, testing, and observability.
- Building reproducible data pipelines with clear data-quality contracts.
- Improving SQL, dimensional modeling, and analytical reporting.
- Applying reliable backend and database patterns to business software.

## Connect

- **Portfolio:** https://YOUR_PORTFOLIO_URL
- **LinkedIn:** https://YOUR_LINKEDIN_URL
- **Email:** YOUR_EMAIL

---

<div align="center">

*Focused on reliable data systems and useful software.*

</div>
