<div align="center">

# Hi, I'm Houssam Lemrini 👋

**Software Engineer (in training) · Building Production Systems**

Software engineer focused on AI-powered tools and business applications — from payroll and support-ticket systems to document intelligence and inventory management. Comfortable across the stack: React/Next.js and Electron on the frontend, Node.js/NestJS/FastAPI on the backend, PostgreSQL and vector search underneath.

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:houssamlemrini4@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/houssam-lemrini)

</div>

---

## 🧭 About Me

I build practical software for real businesses — payroll systems, support platforms, inventory tools — and I'm increasingly focused on applying AI where it adds genuine value: document Q&A, job-application automation, and process assistance. I care about clean architecture, testable code, and shipping things that actually work in production, not just demos.

---

## ⭐ Flagship Projects

The projects I'm most proud of — production-grade systems built for real companies, verified directly from their codebases.

### [Chronicler — AI-Powered Document Intelligence](https://github.com/houssam-lemrini) `Private`
Desktop application that lets users have natural-language conversations with their documents, with every answer backed by source citations. **In use at accounting/fiduciary firms and logistics and insurance companies.**

- **Stack:** Electron + Next.js 16 + React 19 · FastAPI · PostgreSQL + pgvector · sentence-transformers · OpenAI (swappable) · Ollama for fully local/self-hosted mode
- **Key features:** multi-format ingestion (PDF, DOCX, TXT, XLSX, PPTX) · multi-document chat across collections · full RAG pipeline (embed → retrieve → rerank → generate) · source citations and confidence indicators on every answer · privacy-first local deployment option
- **Status:** Beta — started as a final-year academic software engineering project by a team of three (IDELMOU Noaman, LEMRINI Houssam, OUDGHIRI Abdelaziz) · adopted by multiple accounting/fiduciary, logistics, and insurance firms

### [BKSM — Gestion des Tickets](https://github.com/houssam-lemrini/Getsion_de_ticket-BKSM) `Private`
Support-ticket management platform for BK Systèmes: clients open tickets, support staff work them through an SLA-tracked status workflow, and every action is audit-logged. **Now in active use at BK Systèmes.**

- **Stack:** Next.js 15 (App Router) · TypeScript · Tailwind 4 · NestJS 11 · Prisma 6 · PostgreSQL 16
- **Key features:** RBAC with custom roles · SLA deadlines with a pausable business-hours clock · MinIO file storage with ClamAV malware scanning · installable PWA with push notifications · admin dashboards with CSV/Excel export · full audit logging
- **Testing:** 117 unit tests, 74 end-to-end tests (Playwright) against real PostgreSQL, MinIO and ClamAV
- **Status:** All 10 roadmap phases implemented and building · deployed and in production use

### [CDL-Maroc — Payroll Management System](https://github.com/houssam-lemrini/CDL-Maroc) `Private`
Full-stack payroll ("Paie") management system for CDL-Maroc, built as a native Windows desktop app. **In production use at around 10 Moroccan companies**, including construction (BTP), industrial, and renewable-energy firms.

- **Stack:** Electron 30 · React 18 · Vite · TypeScript · Node.js · Express · PostgreSQL · Prisma
- **Key features:** full Moroccan payroll calculation engine (CNSS, AMO, IGR per 2025 rates) · employee/contract/worksite management · PDF payslip generation (Puppeteer) · Excel exports for payroll journals and CNSS declarations · offline-ready UI
- **Companies using it:** publicly listed partners include Goldensun Tire Morocco, Aeolon Renewable Energy Morocco, Zhengzhou Jinyuan Construction Morocco, and Jing Yan Construction — plus several additional companies under client confidentiality
- **Companion project:** [`cdl-maroc-website`](https://github.com/houssam-lemrini/cdl-maroc-website) — the public marketing/download site for this app

### [PointX](https://github.com/houssam-lemrini/PointX) `Private`
Face-recognition-based attendance ("pointage") system that detects and recognizes employee faces via camera, automatically logging check-in/check-out times — replacing manual attendance tracking.

- **Stack:** Java · TypeScript · Python · HTML/SCSS
- **Key features:** real-time face detection and recognition · automatic check-in/check-out logging · employee enrollment and management · attendance history and reporting · designed to integrate with HR/payroll systems such as CDL-Maroc

### [VolumiX](https://github.com/houssam-lemrini/VolumiX) `Private`
3D reconstruction and volume-estimation tool for sand stockpiles — takes a set of photos of a pile, builds a 3D model, and calculates the volume of material it contains. **In use at Castel Cleopatra.**

- **Stack:** Python · QML · GLSL · CMake
- **Key features:** 3D reconstruction from photos · automatic volume calculation from the 3D model · interactive 3D visualization · modular capture → reconstruct → calculate pipeline

---

## 🛠️ Technical Skills

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Data & Infrastructure**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**AI & Automation**
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## 🚀 All Projects by Category

### 💼 Business Applications

Top picks (BKSM, CDL-Maroc, PointX, VolumiX) are detailed in [⭐ Flagship Projects](#-flagship-projects) above.

#### StockInBox `Not yet published`
Stock / inventory management software built for Stockbox. **In active use at Stockbox.**


- ** stack:** React/Next.js frontend · Node.js/NestJS or Express backend · PostgreSQL or MySQL
- **keyfeatures:** stock level tracking, low-stock alerts, supplier/product catalog management, inbound/outbound movement logs, reporting dashboard

---

### 🤖 AI & Automation

Chronicler is detailed in [⭐ Flagship Projects](#-flagship-projects) above.

#### AI Job Hunting
AI-assisted job application platform built around a "Fact Ledger" — every claim the app makes to an employer traces back to a stored, user-confirmed fact.

> ⚠️ **In progress — awaiting publish.**

- **Stack:** TypeScript monorepo (Turborepo + pnpm) · Next.js web app · NestJS API · BullMQ workers · Prisma + PostgreSQL (with pgvector for job embeddings) · Redis · Playwright
- **Key features:** resume parsing and fact extraction · an evidence-backed "Fact Ledger" with confirm/reject workflow · ATS job-source integrations (Greenhouse, Lever, Ashby, Workable, SmartRecruiters) · deterministic job-match scoring · AI-drafted application packs (cover letter, recruiter email) with a human approval gate · a supervised, human-in-the-loop browser step for reviewing applications — final submission is always manual, with no CAPTCHA-solving or unattended submission
- **Status:** Ready for local product testing; not yet production-launched
- **Visibility:** Public repository exists but not yet populated with code

---

### 📦 Inventory Management

Inventory-focused work is currently represented by **StockInBox** — see [Business Applications](#-business-applications) above.

---

### 🌐 Web Applications

#### [CaravaGo](https://github.com/houssam-lemrini/CaravaGo) `Public`
Web platform for renting caravans and planning road-trip adventures, built with a team.

- **Verified stack:** HTML · CSS · JavaScript
- **Key features (per project README):** caravan browsing and booking, an interactive map of camping spots and activities, an AI-assisted trip planner, community photo/trip sharing, and an admin dashboard
- **Team project** — built with a collaborator ([abdel-oue](https://github.com/abdel-oue))
- **Visibility:** Public

#### [MealMate Fitness](https://github.com/houssam-lemrini/mealmate) `Public`
Web app that suggests meals based on available ingredients and fitness goals. Live at [mealmate-lime.vercel.app](https://mealmate-lime.vercel.app).

- **Verified stack:** CSS · JavaScript · HTML · Python
- **Team project** — built with three collaborators
- **Visibility:** Public

#### [CDL-Maroc Website](https://github.com/houssam-lemrini/cdl-maroc-website) `Public`
Marketing and download site for the CDL-Maroc Paie desktop app (see above).

- **Stack:** React · Vite · TypeScript · Tailwind CSS · Three.js
- **Deployment:** Cloudflare Pages
- **Visibility:** Public

---

### 🎓 Software Engineering Projects

Smaller academic and practice projects demonstrating core CS fundamentals:

| Project | Description | Tech |
|---|---|---|
| [Chess Game](https://github.com/houssam-lemrini/Chess-game-in-c-) | Chess game implementation | C++ |
| [Tic-Tac-Toe (Console)](https://github.com/houssam-lemrini/Tic-Tac-Toe-Console-) | Console-based Tic-Tac-Toe | Python |
| [Snake Game](https://github.com/houssam-lemrini/Snake-Game-Basic-with-turtle-) | Classic Snake, built with the `turtle` graphics module | Python |
| [CV Portfolio](https://github.com/houssam-lemrini/CV-portfolio) | Personal CV/portfolio site | HTML/CSS |
| [PFA Presentation](https://github.com/houssam-lemrini/pfa-presentation) | Academic project presentation | TypeScript |

---

## 🔒 A Note on Private Projects

Several of my strongest projects — **Chronicler, BKSM, CDL-Maroc, PointX, VolumiX** — are under private repositories due to client or company confidentiality (see [⭐ Flagship Projects](#-flagship-projects) above for full details). Technical details were verified directly from each project's own documentation. Client/company names are shared only where public (e.g. CDL-Maroc's own partner page) or with the author's permission; some client relationships are covered by confidentiality agreements and are referenced only in aggregate. No proprietary source code, credentials, or confidential business data is exposed here or in those repositories.

---

## 📊 GitHub Stats

![Houssam's GitHub stats](https://github-readme-stats.vercel.app/api?username=houssam-lemrini&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=houssam-lemrini&layout=compact&hide_border=true&count_private=true)

---

## 📫 Get In Touch

- **Email:** [houssamlemrini4@gmail.com](mailto:houssamlemrini4@gmail.com)
- **GitHub:** [@houssam-lemrini](https://github.com/houssam-lemrini)

<div align="center">

*Open to discussing software engineering, AI integration, and interesting problems.*

</div>
