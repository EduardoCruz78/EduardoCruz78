<p align="center">
  <img src="assets/banner.svg" alt="Eduardo Proença — Full Stack Developer · C# / .NET · TypeScript" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/eduardo-proenca-dev"><img src="https://img.shields.io/badge/LinkedIn-eduardo--proenca--dev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://curriculo-psi-drab.vercel.app"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-online-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Résumé"></a>
  <img src="https://img.shields.io/badge/Open%20to-freelance%20%26%20full--time-22c55e?style=for-the-badge" alt="Open to freelance and full-time">
</p>

## About me

I'm a **full stack developer** from Brazil (UTC-3, overlaps with US hours) working with **C# / .NET** on the backend and **TypeScript, React and Next.js** on the web.

- 💼 Former backend developer at **Qualyteam** (2025): REST APIs in .NET with EF Core and SQL Server, Clean Architecture, DDD and TDD
- 🎓 2.5-year full stack internship at the **Federal Institute of Santa Catarina (IFC)**, leading an ed-tech project and training new interns
- 🚀 Freelance: web systems, APIs and websites for clients in Brazil and abroad
- 💬 Remote, async and written communication. I use AI tools (Claude Code) daily, and I review, test and own every line I ship

## Featured projects

Three projects that work together in production, each with CI, tests and a live demo:

```mermaid
flowchart LR
  D[SchedulingDashboard<br/>Next.js] -- "admin API" --> S[SchedulingApi<br/>.NET 10]
  S -- "events (outbox)" --> R[WebhookRelay<br/>Node.js]
  R -- "signed webhooks" --> D
```

| Project | What it shows | Stack |
|---|---|---|
| [**SchedulingApi**](https://github.com/EduardoCruz78/SchedulingApi) · [live demo](https://scheduling-api-gf47.onrender.com/scalar) | Appointment booking API with real business rules: availability calculation (time zones, DST), double-booking prevention with a PostgreSQL exclusion constraint proven by a concurrency test, JWT roles, transactional outbox, 220 tests | C# · ASP.NET Core 10 · EF Core · PostgreSQL · Testcontainers · Docker |
| [**WebhookRelay**](https://github.com/EduardoCruz78/WebhookRelay) · [live demo](https://webhook-relay-1odf.onrender.com/docs) | Reliable event delivery: idempotent ingestion, at-least-once delivery with exponential backoff and a dead-letter queue, HMAC-signed webhooks, e-mail and Telegram channels, SSRF protection, 356 tests | Node.js 24 · TypeScript · Fastify · PostgreSQL · Drizzle · pg-boss · Vitest |
| [**SchedulingDashboard**](https://github.com/EduardoCruz78/SchedulingDashboard) · [live demo](https://scheduling-dashboard-brown.vercel.app) | Admin dashboard for the API: daily schedule, catalog, KPI charts, relay deliveries and a live feed of signed webhooks; backend-for-frontend security, OpenAPI-typed clients, 130 tests + end-to-end tests of all three services | Next.js 16 · React 19 · TypeScript · Playwright · Vitest |

More projects:

| Project | What it shows | Stack |
|---|---|---|
| [**EduPlatformJS**](https://github.com/EduardoCruz78/EduPlatformJS) · [live demo](https://edu-platform-js-five.vercel.app) | Education platform in a monorepo: Google sign-in, role-based access control, admin panel, audit trail, tests and CI | Next.js · tRPC · Prisma · PostgreSQL · Auth.js · Vitest |
| [**DesafioBackend**](https://github.com/EduardoCruz78/DesafioBackend) | KPI/indicators domain model built test-first: aggregate rules, 12 unit tests, CI on GitHub Actions | C# · .NET 8 · xUnit · FluentAssertions |
| [**Curriculo**](https://github.com/EduardoCruz78/Curriculo) · [live](https://curriculo-psi-drab.vercel.app/en) | Bilingual résumé site designed as a transit map, where each project is a line and the interchanges are the real integrations | Next.js 16 · React 19 · Tailwind CSS 4 · SVG |

## Tech stack

**Backend**
<br>
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
<img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET">
<img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="ASP.NET Core">
<img src="https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="Entity Framework Core">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify">
<img src="https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white" alt="tRPC">
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma">

**Frontend**
<br>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">

**Data, testing & tools**
<br>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="xUnit">
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest">
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/Rider-000000?style=flat-square&logo=rider&logoColor=white" alt="Rider">
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">

**Practices:** Clean Architecture · Domain-Driven Design · Test-Driven Development · REST API design · Code review

## Let's work together

I'm open to **remote full-time roles** and **freelance/contract projects**: REST APIs, web apps, integrations, automations and bug fixing.
The fastest way to reach me is a message on [LinkedIn](https://www.linkedin.com/in/eduardo-proenca-dev).

<details>
<summary>🇧🇷 Em português</summary>

<br>

Sou desenvolvedor full stack (C#/.NET e TypeScript/Node.js/React/Next.js). Trabalhei como desenvolvedor backend na Qualyteam, fiz 2 anos e meio de estágio full stack no IFC e atendo projetos freelance. Trabalho 100% remoto, com comunicação por texto. Meus projetos principais formam um sistema que funciona em produção: uma API de agendamentos em .NET, um serviço de entrega de eventos em Node.js e um painel em Next.js, todos com testes, CI e demo online. Estou aberto a vagas e a projetos freelance: me chame no [LinkedIn](https://www.linkedin.com/in/eduardo-proenca-dev).

</details>
