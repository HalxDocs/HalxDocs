<div align="center">

# HalxDocs
### Product Engineer · Systems Builder · Full-Stack Infrastructure

<p>I build backends and web products that actually ship.</p>

[![Portfolio](https://img.shields.io/badge/halxdocs.com-000000?style=for-the-badge&logo=safari&logoColor=white)](https://halxdocs.com)
[![Email](https://img.shields.io/badge/halxdocs@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:halxdocs@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kamsy-ejindu-633272344/)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/halxdocs)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@halxdocs)
[![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/~halxdocs)

</div>

---

I work with founders and growing teams to design, architect, and ship production-grade software — backend systems, APIs, fintech infrastructure, full-stack web products, and developer tooling.

I don't just close tickets. I think about the system, make the hard call early, and build things that hold up when real users show up.

> **Build fast. Build clean. Build systems that last.**

---

## What I actually do

- Design and build production backend systems from scratch — auth, wallets, ledgers, payment flows
- Architect APIs that scale with traffic and stay maintainable as teams grow
- Ship full-stack web products end to end — frontend, backend, database, deployment
- Debug and stabilise existing codebases that are falling over in production
- Build developer tooling that solves real workflow problems
- Make sound technical decisions early — so you don't pay for them later

---

## Tech stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Remix](https://img.shields.io/badge/Remix-000000?style=flat-square&logo=remix&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend & Infrastructure**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Cloud & Deployment**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

---

## Selected work

| Project | Description | Link |
|---------|-------------|------|
| **contextpack** | CLI that bundles any codebase into a single LLM-ready file. Stop copy-pasting files into Claude or ChatGPT one by one. ![npm](https://img.shields.io/npm/v/@halxdocs/contextpack?style=flat-square&labelColor=000&color=1a1a1a) | [npm](https://www.npmjs.com/package/@halxdocs/contextpack) · [github](https://github.com/HalxDocs/contextpack) |
| **lazydb** | Keyboard-driven terminal UI for databases — like lazygit but for SQL. Supports Postgres, MySQL, SQLite. Built in Go with bubbletea + lipgloss. | [github](https://github.com/HalxDocs/lazydb) |
| **Fintech Banking Backend** | Production NestJS backend for a Nigerian mobile banking app — phone-number-first auth, OTP with brute force lockout, atomic wallet creation, full ledger system split into focused modules. Strict TypeScript throughout. | private |
| **Wedding Invitation App** | Full web app with animated envelope opening, personalised guest links, live RSVP dashboard, WhatsApp sharing, and CSV export. Built for a real wedding. | private |
| **Norah's Beauty Hub** | Full-stack Nigerian e-commerce platform — live debounced search, Cloudinary uploads, responsive admin dashboard with analytics, full auth system. | private |
| **BiblePlus Backend** | Node.js/TypeScript backend for a Bible quiz app. Rebuilt the daily quiz service with a deterministic seed algorithm — same question for every user on the same day, zero database dependency for selection. Fixed two production crashes on Render. | private |
| **JSONStack** | High-performance JSON processing tool. Handles 400k+ lines with optimised parsing and rendering. | [jsonstack.dev](https://jsonstack.dev) |
| **Cortex** | Extensible AI-powered analysis platform for structured processing and intelligent workflows. | [corte-x.vercel.app](https://corte-x.vercel.app) |
| **AIDevHelper** | Chrome extension that improves developer workflow speed without context switching. | [github](https://github.com/HalxDocs/Aidevhelper) |
| **Email Verifier API** | Lightweight, production-ready email validation API built in Go. | [render](https://email-verifier-xqd2.onrender.com) |

---

## How I think about production systems

Things I've learned from actually shipping and maintaining systems under real conditions:

- **Validate environment variables at startup.** Not buried in a function — at boot. If something is required, the service should tell you exactly what's missing, not die with a cryptic trace.
- **Never rely on files for secrets in PaaS deployments.** Render, Vercel, Railway — they don't have your gitignored files. Serialise secrets to environment variables.
- **Determinism is a feature.** For scheduled jobs, daily content, seeded selection — design for it explicitly. Don't rely on the runtime to give you consistency it was never designed to provide.
- **Store money in the smallest unit.** Kobo, cents, pence. Never floats.
- **Atomic operations for anything financial.** MongoDB transactions exist for a reason. Use them.
- **Split services by responsibility, not by size.** A ledger service that does money movement, querying, reconciliation, and helpers in one file is a liability. Split it early.

---

## Engineering philosophy

> Great products are systems, not features.

Clean foundations > flashy launches. Long-term value > short-term hacks.

The best time to make the right architectural call is before you have 50k users and a deadline. I try to make those calls early.

---

## Availability

Open to backend contracts, full-stack product builds, fintech engineering, and startup partnerships.

[![Portfolio](https://img.shields.io/badge/halxdocs.com-000000?style=for-the-badge&logo=safari&logoColor=white)](https://halxdocs.com)
[![Email](https://img.shields.io/badge/halxdocs@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:halxdocs@gmail.com)
[![X](https://img.shields.io/badge/DM_on_X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/halxdocs)
