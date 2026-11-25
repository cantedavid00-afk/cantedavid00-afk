# David Alonso Cante Herrera

**Software Developer | Backend & Full Stack | Mobile Development | Applied AI**

Computer Engineering Student · Universidad Autónoma de Tlaxcala · Graduation: **December 2026** · Tlaxcala, Mexico

I design and build software for real small businesses: REST APIs, full stack web apps, an offline-first Android point-of-sale app, and conversational assistants that use LLMs while keeping business rules in the backend. I care about clear architecture, documented decisions and code that survives contact with real users.

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Mobile Development**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)

**Applied AI & Integrations**

![Google Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![GitHub Models](https://img.shields.io/badge/GitHub_Models-181717?style=flat-square&logo=github&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_%28Baileys%29-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)

**Cloud, Databases & Infrastructure**

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Cloud Firestore](https://img.shields.io/badge/Cloud_Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Microsoft Azure Fundamentals (AZ-900) — *In Progress*

**Tools & Workflow**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

---

## Featured Projects

| Project | Stack | Business Challenge & Solution | Links |
|---|---|---|---|
| **GS Mobile Ops Console** *(in active development)* | TypeScript · Next.js · Supabase · Express · Evolution API (WhatsApp) · MikroWisp API | **Challenge:** a fiber-optic internet provider handles support, payments and outage reports through a single WhatsApp number shared by several agents. **Solution:** an operations console with a shared inbox, where deterministic TypeScript rules classify 20 intents, assign P0–P3 priority with SLAs, open tickets and detect when an "outage" is actually a suspended account, with an integration to the ISP's management system (MikroWisp) for subscriber data. The LLM only phrases replies the backend has already decided. 39 test files run without credentials. | [Case study](https://github.com/cantedavid00-afk/gsmobile-case-study) · Code is private |
| **Florería RoCé** | TypeScript · Node.js 22 · Next.js 16 · Supabase · Baileys · Gemini API · Docker | **Challenge:** a local flower shop handled quotes, orders and follow-up by hand over WhatsApp. **Solution:** *Flora*, a WhatsApp sales assistant where the backend owns every business decision (order state machine, schedule and price validators, event bus with Telegram alerts) and the LLM only writes the reply, with a fallback chain across several AI providers; plus a Next.js admin panel. A companion web app quotes a bouquet from a photo: a vision model identifies the flowers, the backend maps them to the live catalog and prices the order. | [Bot code](https://github.com/cantedavid00-afk/jardin-roce-bot) · [Quote app code](https://github.com/cantedavid00-afk/floreria-app) |
| **POS Mobile System** | Flutter · Dart · Firebase Auth · Cloud Firestore · Hive · GitHub Actions | **Challenge:** a poultry shop with several branches tracked sales, stock and shifts on paper. **Solution:** an Android point-of-sale app with a feature-first architecture (14 modules), offline-first sync, employee PIN access, shifts, inventory per branch, transfers, losses, and Excel/PDF reports for the owner, plus a desktop admin dashboard. About 200 automated tests run in GitHub Actions on every push. | [Code](https://github.com/cantedavid00-afk/POS) · [Releases](https://github.com/cantedavid00-afk/POS/tags) |
| **BarberElite** | Node.js · Express · PostgreSQL (Supabase) · node-cron · Baileys (WhatsApp) | **Challenge:** a barbershop scheduled appointments by hand, with no shared view of each barber's availability. **Solution:** a multi-tenant booking API that computes real availability per barber (working hours, blocked days, service duration), records appointments and client history, and sends automatic WhatsApp reminders. Admin access uses signed, expiring sessions with hashed passwords and deny-by-default authorization. | [Code](https://github.com/cantedavid00-afk/barberelite-backend) · [Live demo](https://barberelite-backend.vercel.app) |

**Also built:** [Club Hípico](https://github.com/cantedavid00-afk/clubhipico) (riding-class booking with packages and reminders · [demo](https://clubhipico.vercel.app)) · [Flor & Arte](https://github.com/cantedavid00-afk/floreria-frontend) (vanilla JS storefront + Express/MongoDB API)

---

## Languages

- Spanish — Native
- English — B1 Intermediate (EF SET Certified)

## Open to Work

Open to **Junior Software Developer**, **Backend Developer**, **Full Stack Developer** and **Software Engineering Intern** opportunities.

[LinkedIn](https://www.linkedin.com/in/david-alonso-cante-057554378)
