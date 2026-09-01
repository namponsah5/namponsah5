<h1 align="center">Hi, I'm Nathaniel Amponsah 👋</h1>
<h3 align="center">Software Engineer building production fintech infrastructure in Ghana 🇬🇭</h3>

<p align="center">
  <a href="https://website.workbenefits.app"><img src="https://img.shields.io/badge/WorkBenefits-Live%20Platform-1f6feb?style=flat-square" alt="WorkBenefits"/></a>
  <a href="https://employer.workbenefits.app"><img src="https://img.shields.io/badge/Employer%20Dashboard-Live-1f6feb?style=flat-square" alt="Employer Dashboard"/></a>
  <a href="https://wa.me/233539066050"><img src="https://img.shields.io/badge/RenmoBot-Chat%20on%20WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="RenmoBot on WhatsApp"/></a>
</p>

---

### 🚀 About Me

I'm a Software Engineer at **Renmo, Inc.**, where I build and maintain the **WorkBenefits** platform — a financial wellness and employee benefits product serving **60+ employers** and **1,000+ employees** across Ghana, spanning Earned Wage Access, Rent/Shop/Drive & Pay Monthly, Health Insurance, and Organisational Therapy.

I architected **RenmoBot v2**, an in-house conversational AI system that replaced a third-party agent framework — cutting boot memory from ~5.7 GB and eliminating daily production instability, while powering Renmo's customer-facing WhatsApp assistant for rent, asset-purchase, and vehicle financing onboarding.

I like owning problems end-to-end: diagnosing a live production defect, shipping the fix, and writing the regression test that keeps it fixed.

- 🏦 Currently building: **WorkBenefits** (fintech employee benefits) & **RenmoBot v2** (self-owned agent runtime)
- 🎓 BSc. Computer Engineering, Kwame Nkrumah University of Science and Technology (KNUST), Nov 2025
- ☁️ AWS Academy Graduate — Cloud Architecting, Cloud Developing, Cloud Security, Data Engineering, ML Foundations
- 📍 Based in Accra, Ghana
- 📫 Reach me: **amponsahnathaniel69@gmail.com**

---

### 🛠️ Tech Stack

**Frontend**
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/-React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black)

**Backend**
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

**Data & Infra**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=celery&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Linear](https://img.shields.io/badge/-Linear-5E6AD2?style=flat-square&logo=linear&logoColor=white)

---

### 💼 Featured Work

**[WorkBenefits](https://website.workbenefits.app)** — Financial wellness & employee benefits platform
Public-facing product plus an [employer admin dashboard](https://employer.workbenefits.app) used by 60+ companies to onboard employees, configure benefit offerings, and monitor real-time utilization across five product lines.

**RenmoBot v2** — In-house conversational AI platform (Node.js/TypeScript)
Replaced a third-party agent framework powering Renmo's WhatsApp assistant. Highlights:
- Channel-adapter layer (WhatsApp Cloud API, Google Chat, Facebook Messenger) behind a single agent runtime
- Replaced a 118 MB monolithic JSON session store with a SQLite-backed store using atomic writes + history compaction
- Durable outbox with exponential-backoff retry so replies survive crashes and transient Meta API failures
- Multi-model fallback chain over Google Gemini with per-request timeouts and per-conversation turn serialisation
- Golden-conversation regression suite replaying 32 recorded production conversations in CI, part of a 325-test suite
- 👉 [Chat with RenmoBot on WhatsApp](https://wa.me/233539066050)

**Smart Inventory & Order Management System** — Python, FastAPI, SQLAlchemy, MySQL, Celery, Redis, Docker
Backend system for product/stock management and order tracking, with JWT auth and role-based access, containerized and deployed via Railway with GitHub Actions CI/CD.

**Agrisense** — React Native, TypeScript, AWS Amplify, AppSync, DynamoDB, IoT Core, Lambda
Cross-platform smart agriculture app with a real-time IoT ingestion pipeline (IoT Core → Lambda → DynamoDB → AppSync) and offline-first sync via Amplify DataStore.

**Welfare Collection Platform** — Laravel, PHP, MySQL, Tailwind CSS, Alpine.js, Sanctum
Digitized staff welfare contribution tracking for 37 Military Hospital's biomedical department, with Paystack integration and Excel reporting.

**Hospital Equipment Management System** — Laravel, PHP, MySQL, Tailwind CSS, Vite
Asset and maintenance tracking system with fault-reporting workflows, work orders, and role-based access across departments.

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=namponsah5&show_icons=true&theme=default" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=namponsah5" alt="GitHub Streak" height="165"/>
</p>
