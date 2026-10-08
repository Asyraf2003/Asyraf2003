<div align="center">

# Hi, I'm Asyraf Mubarak <img src="./img/Hi.gif" width="32px" alt="Hi">

### Software Engineering building production systems around transaction integrity, operational reliability, and explicit web standards

![Laravel](https://img.shields.io/badge/Backend-Laravel-red?logo=laravel&logoColor=white)
![Go](https://img.shields.io/badge/Backend-Go-00ADD8?logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/Language-PHP-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Tools-Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Dev-Linux%20%2F%20WSL-FCC624?logo=linux&logoColor=black)

</div>

---

## About me

I am a Software Engineering student focused on backend engineering, system design, and production reliability.

Most of my engineering growth comes from maintaining systems connected to real operational workflows rather than building isolated demo CRUD applications. I care about state consistency, auditability, failure handling, regression protection, clear boundaries, and whether a system remains understandable after its business rules become complicated.

My current work is best represented by two production-oriented projects:

- **GlassPos** — transaction-heavy operational software where money, stock, payments, revisions, refunds, procurement, and reporting must remain coherent.
- **SchoolAI** — a multilingual production web platform where UI, CMS workflows, security, accessibility, media, roles, performance, and deployment are treated as engineering concerns rather than decorative layers.

Together they represent the two sides of the work I enjoy most: **backend/system integrity** and **product-facing engineering backed by explicit controls**.

---

## Featured projects

### GlassPos — Production Workshop POS & Operations System

**Repository:** [github.com/Asyraf2003/GlassPos](https://github.com/Asyraf2003/GlassPos)

A production workshop POS and operations system designed around **transaction integrity rather than CRUD completeness**.

A single business transaction can affect payment allocation, stock movement, revisions, refunds, supplier obligations, audit history, and multiple reports. GlassPos is built so those effects remain explainable and reconcilable as the transaction evolves.

**Engineering focus**

- Hexagonal / Ports and Adapters architecture
- stateful transaction lifecycle modeling
- payment and refund allocation boundaries
- cancellation vs refund semantics
- stock movement, reversal, costing, and negative-stock protection
- transaction revision and historical traceability
- procurement, supplier finance, landed cost, and payables
- audit-aware mutations and operational diagnostics
- report consistency across screen, PDF, and Excel outputs
- regression tests for duplicate execution, stale state, financial bounds, and UI/backend drift

**Verification snapshot — 2026-09-30**

- **1,849 tests passing**
- **14,308 assertions**
- **0 PHPStan errors**
- line / Blade / contract audits passing
- **100% `strict_types` coverage** across the audited application source snapshot

> The interesting part of GlassPos is not that it can create a sale. It is what happens after cash, stock, corrections, history, and reports all need to agree about that sale.

---

### SchoolAI — Production Multilingual School Platform

**Repository:** [github.com/Asyraf2003/schoolai](https://github.com/Asyraf2003/schoolai)  
**Live site:** [almustaqbal.sch.id](https://almustaqbal.sch.id)

A maintained production school platform combining a multilingual public experience, editorial CMS workflows, admissions content, gallery composition, role-specific portals, account/session controls, media infrastructure, and explicit production web standards.

**Engineering focus**

- Indonesian, English, and Arabic public experiences with RTL-aware presentation
- native article canvas with autosave, media upload, publishing, placement, and restore workflows
- canonical gallery/media composition and lifecycle management
- PPDB/admissions state managed from application data
- separate administrator, teacher, and student portal boundaries
- Google OAuth and role-aware authentication flows
- active-account and active-session enforcement
- nonce-based Content Security Policy and explicit security-header contracts
- CSRF, stateful OAuth, secure-cookie, HTTPS, and XSS regression boundaries
- accessibility-conscious semantic presentation
- first-paint, critical CSS, font-loading, and frontend performance contracts
- S3-compatible external media architecture
- reproducible cPanel-oriented deployment workflow

**Verification snapshot — 2026-10-01**

- Laravel **13.34.0**
- **304 tests / 3,487 assertions — PASS**
- Composer audit: **0 security advisories**
- npm audit: **0 vulnerabilities**
- Vite production build: **PASS**
- GitHub Actions: **GREEN**

> The standard is not only whether the homepage looks good. It is whether content, security, language, roles, media, performance, deployment, and operations continue to behave coherently as the product changes.

---

## Engineering approach

I prefer systems that make important behavior explicit.

That usually means:

- define invariants before adding convenience;
- distinguish business states instead of collapsing them into generic CRUD actions;
- keep historical meaning when data changes;
- turn discovered failure modes into regression tests;
- treat security and operational constraints as application behavior;
- keep deployment and verification reproducible;
- diagnose production problems read-only before mutating data;
- avoid complexity that does not buy correctness, clarity, or resilience.

AI-assisted development is part of my workflow, but generated code is not treated as proof of correctness. The proof comes from architecture boundaries, tests, static analysis, audits, reproducible verification, and observable production behavior.

---

## Skills

| Area | Current focus |
|---|---|
| Backend | Laravel, PHP, Go, REST APIs, application services, transactional workflows |
| Architecture | Hexagonal Architecture, domain boundaries, system design, resiliency |
| Data | MySQL, PostgreSQL, consistency, migrations, historical traceability |
| Reliability | regression testing, auditability, idempotency, failure-mode analysis |
| Web engineering | authentication, authorization, security headers, CSRF/XSS boundaries, multilingual UX |
| Frontend/product | Blade, Tailwind CSS, Vite, Three.js, CMS/editorial workflows |
| Infrastructure | Linux / WSL, Docker, Nginx, GitHub Actions, shared-hosting deployment workflows |

---

## Current focus

- backend engineering with **Laravel and Go**
- deeper **system design and resiliency** work
- PostgreSQL-oriented backend architecture
- production-grade transaction and audit models
- cloud and deployment engineering
- building systems where correctness can be demonstrated, not merely asserted

---

## Engineering philosophy

Good software is not only software that works on the happy path.

I value systems that remain **clear, traceable, testable, and dependable as operational complexity grows**. Features matter, but so do the boundaries around them: what happens on retries, corrections, stale state, partial completion, invalid input, deployment constraints, and future change.

CRUD is useful. The engineering starts when the rows begin affecting each other.

---

## Connect

- GitHub: [github.com/Asyraf2003](https://github.com/Asyraf2003)
- LinkedIn: [linkedin.com/in/asyraf-mubarak-4016a8305](https://www.linkedin.com/in/asyraf-mubarak-4016a8305/)
- Email: asyrafwebsite@gmail.com
