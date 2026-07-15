# Mats Gustafsson

**Full-Stack Developer · Django · HTMX · TypeScript · Secure SaaS Systems**

I design and build production-oriented applications with a focus on security, privacy, domain modelling, clean architecture, and reliable delivery.

![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python\&logoColor=white)
![Django](https://img.shields.io/badge/Django-6-092E20?logo=django\&logoColor=white)
![HTMX](https://img.shields.io/badge/HTMX-3366CC?logo=htmx\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18-4169E1?logo=postgresql\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions\&logoColor=white)

**Based in:** France / Sweden · Remote within Europe
**Portfolio:** [nordiccodeworks.com](https://nordiccodeworks.com/)

---

## Current Focus

I am currently building **CareerOps**, a job intelligence and application operations platform designed as a serious, production-oriented Django system.

The project is being developed from the foundation upward with explicit domain ownership, strict repository policies, reproducible environments, automated security controls, and architecture intended to remain understandable as the product grows.

The goal is not to build another CRUD job tracker or thin AI wrapper. CareerOps is intended to demonstrate the engineering decisions, operational discipline, and long-term thinking expected from a real product.

---

## Selected Projects

### [CareerOps](https://github.com/Moonchichiii/careerops)

A job intelligence and application operations platform under active development.

CareerOps is designed to capture opportunities from controlled sources, preserve original evidence, resolve canonical job identities, structure candidate evidence, explain opportunity matching, and support the complete application lifecycle.

**Current foundation**

* Python 3.14 and Django 6
* PostgreSQL 18 as the authoritative data store
* Custom UUID and email-based user model
* Django templates and HTMX
* `uv` with a committed lockfile
* Strict mypy and `django-stubs`
* Ruff formatting, linting, and security rules
* pytest and migration-drift protection
* Minimum-permission GitHub Actions workflows
* CodeQL, OSV-Scanner, `pip-audit`, Dependabot, and zizmor
* Secret scanning and ephemeral CI credentials

**Architecture direction**

* Modular monolith with explicit bounded contexts
* Server-rendered interfaces as the primary application surface
* DRF reserved for genuine external consumers
* Immutable inbound envelopes and source observations
* Versioned normalization and append-only resolution decisions
* Manual HTMX capture, browser-extension capture, and CSV imports
* Mobile, Rust, and DuckDB capabilities behind explicit decision gates

---

### [Valunds ServiceBok](https://valunds.se)

A digital service-book SaaS platform for vehicle owners and automotive businesses.

Valunds centralizes service records, receipts, mileage history, documentation, and QR-verifiable certificates to create a trustworthy history for each vehicle.

**Technology:** Django, HTMX, Django REST Framework, React Native, Expo, Stripe, Cloudinary, OpenAI

**Engineering focus**

* Secure object ownership and authorization
* Privacy-aware account deletion
* Media lifecycle and Cloudinary cleanup
* OCR-assisted document processing
* Subscription and payment workflows
* Mobile application integration
* Apple and Google account-deletion requirements

---

### [SkogsKvitto](https://skogskvitto.se)

A specialised receipt, documentation, and financial-preparation platform for forestry and agriculture.

The product is intentionally focused on rural property operations, including forestry, farming, and closely related land-based activities.

**Technology:** Django, HTMX, PostgreSQL

**Engineering focus**

* Property-aware domain structures
* Strict access boundaries
* Receipt and expense documentation
* Accountant and bookkeeping workflows
* SIE and structured data exports
* Locked annual archives
* Long-term financial traceability

---

### [La Serenity](https://laserinity.fr)

A multilingual wellness and editorial content platform built with Django, Wagtail, React, and TypeScript.

The project includes multilingual content management, responsive frontend development, editorial workflows, containerized deployment, and cloud release management.

---

### sieverk

A Rust research project exploring SIE accounting-file parsing, tokenization, structural validation, and deterministic financial-data processing.

The project supports longer-term work around accountant-friendly exports, validation tooling, structured errors, and performance-sensitive file processing.

---

## Engineering Principles

### Secure by design

I treat security and privacy as architectural requirements rather than final-stage checklists.

My work includes authentication and authorization, object-level ownership, privacy-aware deletion, credential management, secure media removal, dependency scanning, static analysis, least-privilege CI permissions, and traceable audit records.

### Domain-led architecture

I prefer explicit ownership and clear boundaries over loosely connected abstractions.

That means using modular monoliths, bounded contexts, focused services and selectors, deliberate transaction boundaries, versioned contracts, append-only decisions where historical traceability matters, and asynchronous processing only where it provides a clear operational benefit.

### Quality built into delivery

I establish automated quality gates early so that they protect the system as it grows.

Typical controls include strict typing, formatting, linting, migration checks, unit and integration tests, repository-policy tests, locked dependencies, security scanning, workflow analysis, container validation, and reproducible CI environments.

I am particularly interested in domain-heavy SaaS products, secure Django and HTMX systems, authentication and authorization, privacy workflows, developer tooling, database design, document processing, and specialised products with real operational requirements.

---

## Technology

**Backend**

Python · Django · Django REST Framework · Wagtail · PostgreSQL · Redis · Celery

**Frontend**

Django Templates · HTMX · TypeScript · React · Tailwind CSS · Vite

**Mobile**

React Native · Expo

**Infrastructure**

Docker · GitHub Actions · Fly.io · Cloudflare · RabbitMQ

**Quality and security**

uv · Ruff · mypy · django-stubs · pytest · CodeQL · OSV-Scanner · pip-audit · Dependabot · zizmor

**Additional languages**

Rust · SQL · PowerShell

---

## Contact

* **Portfolio:** [nordiccodeworks.com](https://nordiccodeworks.com/)
* **Location:** France / Sweden
* **Availability:** Remote roles within Europe
