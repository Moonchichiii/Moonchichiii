# Hi, I'm Mats Gustafsson 👋

## Security-Minded Full-Stack Developer · Django / HTMX / React · SaaS Builder

I build production SaaS applications with a strong focus on **security, privacy, clean architecture and real-world deployment**.

My core stack is **Python, Django, HTMX, REST APIs, React, PostgreSQL, Docker and cloud infrastructure**.  
I enjoy building complete systems end-to-end: authentication, payments, media uploads, OCR workflows, mobile app APIs, CI/CD, account deletion, data retention and production operations.

Currently building products under **Valunds Digitala Tjänster**, including:

- **Valunds ServiceBok** — digital vehicle service history, receipts, reminders and value certificates
- **SkogsKvitto** — receipt and documentation workflows for forestry and agriculture

---

## What I Build

I focus on real products — not just demos.

- Production-ready SaaS platforms
- Django and HTMX-driven web applications
- REST APIs for mobile and frontend clients
- Secure authentication and account flows
- Stripe subscription billing
- Cloudinary signed media uploads
- OCR-assisted receipt workflows with OpenAI
- GDPR-aware account deletion and media cleanup
- Ownership checks and cross-user access protection
- CI/CD, Docker deployment and security-focused testing
- Long-term SOC 2 / ISO 27001 readiness thinking

---

## Current Focus

### Valunds ServiceBok

A production SaaS platform for digital vehicle service history, receipts, reminders and value certificates.

The product helps private vehicle owners and businesses collect vehicle documentation in one place, build a trustworthy service history and generate a verifiable value certificate with QR-based verification.

Key engineering areas:

- Django + HTMX web application
- Django REST Framework API for mobile app integration
- React Native / Expo companion app
- Stripe billing and subscription lifecycle handling
- Cloudinary signed uploads for vehicle images, receipts and documents
- OpenAI OCR workflows for receipt extraction
- GDPR-aware deletion with 30-day recovery window
- Permanent deletion pipeline with Cloudinary cleanup
- Account deletion flows aligned with Apple and Google Play requirements
- Ownership checks, rate limiting and upload validation
- Security-focused regression tests
- Privacy, Data Safety and App Privacy documentation based on real data flows

---

### SkogsKvitto

A focused receipt and documentation tool for forestry, agriculture and rural business workflows.

Built around a specific niche instead of a generic accounting tool.  
The goal is to support practical receipt, category and documentation needs for forestry and agriculture operations.

Key engineering areas:

- Django-based SaaS architecture
- HTMX-driven product flows
- Receipt and category management
- Ownership-aware data handling
- Privacy-aware deletion planning
- Maintainable architecture for a focused business domain

---

## Engineering Principles

I care about building systems that can be trusted and maintained over time.

- **Security first** — access control, rate limiting, upload validation and safe defaults
- **Privacy by design** — deletion workflows, retention thinking and minimal exposure of sensitive data
- **Clean architecture** — simple boundaries, readable code and predictable data models
- **Production readiness** — deployment, CI/CD, logging, backups and failure handling
- **Pragmatism** — ship useful features without breaking the foundation
- **Documentation-driven thinking** — risks, decisions and data flows should be understandable

---

## Tech Stack

### Backend & APIs

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/DRF-A30000?style=for-the-badge)
![Wagtail](https://img.shields.io/badge/Wagtail-43B1B0?style=for-the-badge&logo=wagtail&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![HTMX](https://img.shields.io/badge/HTMX-3366CC?style=for-the-badge&logo=htmx&logoColor=white)

### Frontend & Mobile

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Data, Media & Integrations

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

### DevOps & Infrastructure

![Docker](https://img.shields.io/badge/Docker-0DB7ED?style=for-the-badge&logo=docker&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=for-the-badge)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Selected Work

### Valunds ServiceBok

Digital service book SaaS for vehicle owners and businesses.

Focus areas:

- Service history
- Digital receipts
- Vehicle documentation
- Reminders
- Value certificates
- QR verification
- Stripe billing
- Privacy and account deletion
- Mobile app integration
- Security-focused SaaS architecture

---

### SkogsKvitto

Receipt and documentation platform for forestry and agriculture.

Focus areas:

- Forestry and agriculture receipt workflows
- Category-based documentation
- Ownership-aware access control
- Privacy-aware data handling
- Niche SaaS product design

---

### La Serenity

Multilingual wellness platform built with Django/Wagtail, React, Docker and modern cloud infrastructure.

Tech used:

- Django
- Wagtail CMS
- React
- TypeScript
- Docker
- Fly.io
- Cloudflare Pages
- Neon PostgreSQL
- Upstash Redis
- Cloudinary

🔗 https://laserinity.fr

---

## Security & Privacy Mindset

A lot of my current work is focused on making SaaS products safer and more trustworthy.

This includes:

- Account deletion flows
- Soft-delete and permanent deletion pipelines
- Cloudinary media cleanup
- Stripe subscription cancellation on account deletion
- Ownership and cross-user access tests
- Secure file upload constraints
- Rate limiting
- Privacy policy and Data Safety preparation
- Vendor awareness
- Security documentation
- SOC 2 / ISO 27001 readiness thinking

I do not see security as a final checklist.  
I see it as part of the product architecture.

---

## Currently Learning & Improving

- Advanced Django architecture
- HTMX product patterns
- Mobile app production readiness
- Security testing and CI hardening
- SOC 2 / ISO 27001 readiness practices
- Better UX for complex SaaS workflows
- Practical product marketing for technical SaaS

---

## Connect

- Portfolio: https://nordiccodeworks.com/
- GitHub: https://github.com/Moonchichiii
- Location: France / Sweden
- Working style: Remote EU

---

> Build real systems. Protect the data. Keep the architecture clean.
