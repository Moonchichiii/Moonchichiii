# Mats Gustafsson

**Full-Stack Developer · Django · HTMX · TypeScript · Secure SaaS Systems**

I design and build production-oriented web applications with a focus on security, privacy, domain modelling, clean architecture, and reliable delivery.

My work spans the complete product lifecycle: application design, backend and frontend development, database modelling, authentication and authorization, automated testing, CI/CD, cloud deployment, and long-term product operations.

**Based in:** France / Sweden · Remote within Europe  
**Portfolio:** [nordiccodeworks.com](https://nordiccodeworks.com/)

---

## Current Focus

I am currently building **CareerOps**, a job intelligence and application operations platform designed as a serious, production-oriented Django system.

The project is being developed from the foundation upward with:

- A Django modular monolith
- Server-rendered interfaces using Django templates and HTMX
- PostgreSQL as the authoritative data store
- Explicit bounded contexts and domain ownership
- Immutable source evidence and traceable identity resolution
- Strict Python typing and repository policies
- Reproducible dependency management
- Automated vulnerability and supply-chain scanning
- Incremental TypeScript, browser-extension, and analytical capabilities

The goal is not to produce another CRUD job tracker or AI wrapper. CareerOps is intended to demonstrate the engineering decisions, operational discipline, and architecture expected from a real long-lived product.

---

## Selected Projects

### [CareerOps](https://github.com/Moonchichiii/careerops)

A job intelligence and application operations platform currently under active development.

CareerOps will capture job opportunities from multiple controlled sources, preserve original evidence, resolve canonical job identities, structure candidate evidence, explain opportunity matching, and support the complete application lifecycle.

**Current foundation:**

- Python 3.14 and Django 6
- PostgreSQL 18
- Custom UUID and email-based user model
- `uv` with a committed lockfile
- Strict mypy and `django-stubs`
- Ruff formatting, linting, and security rules
- pytest and migration-drift protection
- GitHub Actions with minimum permissions
- CodeQL analysis
- OSV dependency scanning
- `pip-audit`
- Conditional Bun auditing
- Dependency review and Dependabot
- GitHub Actions security auditing with zizmor
- Secret scanning and ephemeral CI credentials

**Architecture direction:**

- Django templates and HTMX as the primary web interface
- DRF only for genuine external consumers
- Capture Slice 1 through manual HTMX capture, a browser extension, and CSV import
- Immutable inbound envelopes and job observations
- Versioned normalization and append-only resolution decisions
- Mobile, Rust, and DuckDB behind explicit future decision gates

---

### [Valunds ServiceBok](https://valunds.se)

A digital service-book SaaS platform for vehicle owners and automotive businesses.

It centralizes service records, receipts, mileage history, documentation, and QR-verifiable value certificates to create a trustworthy history for each vehicle.

**Technology:** Django, HTMX, Django REST Framework, React Native with Expo, Stripe, Cloudinary, OpenAI

**Engineering focus:**

- Secure object ownership and authorization
- Privacy-aware account deletion
- Cloudinary media cleanup
- OCR-assisted document workflows
- Subscription and payment handling
- Mobile application integration
- Apple and Google account-deletion requirements

---

### [SkogsKvitto](https://skogskvitto.se)

A focused receipt, documentation, and financial-preparation platform for forestry and agriculture.

The product is intentionally limited to rural property operations, including forestry, farming, and related land-based activities.

**Technology:** Django, HTMX, PostgreSQL

**Engineering focus:**

- Property-aware data structures
- Strict access boundaries
- Receipt and expense documentation
- Accountant and bookkeeping workflows
- SIE and structured export planning
- Locked annual archives
- Long-term auditability

---

### [La Serenity](https://laserinity.fr)

A multilingual wellness and content platform.

**Technology:** Django, Wagtail CMS, React, TypeScript, Docker, Fly.io

**Engineering focus:**

- Multilingual content management
- Wagtail editorial workflows
- Responsive frontend implementation
- Containerized deployment
- Cloud hosting and release management

---

### sieverk

A Rust research project exploring SIE accounting-file parsing, tokenization, structural validation, and deterministic financial-data processing.

The project supports longer-term research for accountant-friendly exports and validation workflows related to SkogsKvitto.

**Technology:** Rust

**Engineering focus:**

- Deterministic parsing
- File-format validation
- Tokenization
- Structured error reporting
- Performance benchmarking

---

## Engineering Approach

### Security and privacy

I treat security as part of application design rather than a final checklist.

My projects include work around:

- Authentication and authorization
- Object-level ownership checks
- Privacy-by-design data handling
- GDPR-aware deletion workflows
- Credential and secret management
- Secure media removal
- Dependency vulnerability scanning
- Static security analysis
- Least-privilege CI permissions
- Immutable audit and provenance records

### Architecture and domain modelling

I prefer clear ownership and explicit boundaries over loosely connected service layers.

That includes:

- Modular monolith architecture
- Bounded contexts
- Domain services and selectors
- Short, deliberate transaction boundaries
- Versioned contracts
- Append-only decisions where historical traceability matters
- PostgreSQL as the authoritative source of truth
- Asynchronous processing only where it improves reliability or responsiveness

### Delivery and quality

I build automated quality gates early so that they protect the project as it grows.

Typical controls include:

- Strict static typing
- Formatting and linting
- Migration-drift checks
- Unit and integration tests
- Repository-policy tests
- Locked and reproducible dependencies
- GitHub Actions workflows pinned to full commit SHAs
- CodeQL
- OSV-Scanner
- `pip-audit`
- Bun dependency auditing
- Dependency review
- Dependabot
- Workflow security analysis
- Container and deployment checks

---

## Technology

**Backend**

Python · Django · Django REST Framework · Wagtail · PostgreSQL · Redis · Celery

**Frontend**

Django Templates · HTMX · TypeScript · React · Tailwind CSS · Vite

**Mobile**

React Native · Expo

**Infrastructure**

Docker · GitHub Actions · Fly.io · Cloudflare · PostgreSQL · RabbitMQ

**Quality and security**

uv · Ruff · mypy · django-stubs · pytest · CodeQL · OSV-Scanner · pip-audit · Dependabot · zizmor

**Additional languages**

Rust · SQL · PowerShell

---

## What I Enjoy Working On

- SaaS products with real operational requirements
- Django and HTMX applications
- Domain-heavy backend systems
- Authentication and authorization
- Privacy and deletion workflows
- Developer tooling and CI/CD
- Database and transaction design
- File parsing and document processing
- Products that serve specialised industries
- Systems that must remain understandable as they grow

---

## Contact

- **Portfolio:** [nordiccodeworks.com](https://nordiccodeworks.com/)
- **GitHub:** [github.com/Moonchichiii](https://github.com/Moonchichiii)
- **Location:** France / Sweden
- **Availability:** Remote roles within Europe
