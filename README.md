<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Egor Yarovitsyn — fullstack developer: TypeScript and Python, React, Next.js, FastAPI, PostgreSQL, AI tooling" />
</p>

<p align="center">
  <a href="https://t.me/egoryaaa"><img src="https://img.shields.io/badge/Telegram-@egoryaaa-111827?style=for-the-badge&logo=telegram&logoColor=67E8F9" alt="Telegram @egoryaaa" /></a>
  <a href="mailto:egoryarovitsyn1@gmail.com"><img src="https://img.shields.io/badge/Email-egoryarovitsyn1@gmail.com-111827?style=for-the-badge&logo=gmail&logoColor=A78BFA" alt="Email" /></a>
</p>

## About

Fullstack developer, 4 years of commercial development with React, Next.js and TypeScript, about two of them also with a Python / FastAPI backend. At Sovcombank I'm a lead frontend developer: the frontend of Tekhnologii Dobra, the bank's portal for 3,000+ non-profits from 79 regions (Next.js 15, SSR, ~42k lines of TypeScript), an internal CRM for curators, and the presentation-generation module of the bank's AI assistant, built end to end from FastAPI to React.

I work AI-first: Claude Code and Codex every day, my own MCP server for API contracts, AI code review in CI/CD. Agent output gets the same review as a colleague's: diff and tests.

## Impact

<table>
  <tr>
    <td align="center" width="25%"><h3>3,000+</h3><sub>non-profits on the bank portal I build the frontend for</sub></td>
    <td align="center" width="25%"><h3>350+</h3><sub>tasks at Sovcombank · 3rd by commits among 20+ contributors</sub></td>
    <td align="center" width="25%"><h3>20 → 12 s</h3><sub>camera setup on a dashboard with ~100 live video streams</sub></td>
    <td align="center" width="25%"><h3>500 → 900</h3><sub>daily sessions in an online-school student account</sub></td>
  </tr>
</table>

## What I've shipped

**Sovcombank** · Lead frontend developer · 2025 – now
- Portal and curators' CRM from design to release: multi-step forms, tables with server pagination, server prefetch with TanStack Query cache hydration, optimistic updates.
- My own TypeScript MCP server for backend API contracts: agents find the endpoint and get ready TS types; the whole team uses it.
- AI code review moved into a group-level CI/CD component that plugs in with one line; system prompts rewritten into a checklist of team standards.
- Co-designed a drag-and-drop kanban engine: the reducer is passed in from outside, so a new board needs no changes to the core.

**Appricot** · Fullstack developer · 2024 – 2025
- Video-surveillance dashboard with ~100 concurrent streams: grid virtualization and lazy player initialization.
- Gantt planner: API contracts reworked together with the backend, response time from ~500 to ~400 ms.
- Analytics for a developer with 11 residential complexes: FastAPI over ClickHouse, ~50 fields per project, many of them derived by the customer's formulas; replaced 20+ spreadsheet processes.

**Sirius Future** · Fullstack developer · 2022 – 2024
- Online school with 5,000+ students: subscriptions and recurring payments (T-Bank acquiring, Stripe, Apple Pay) with idempotent webhooks.
- Public pages on Next.js: organic traffic from 10k to 12.5k visits a month. Kids' games on PixiJS.

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,redux,vite,webpack,tailwind,jest,python,fastapi,postgres,redis,docker,gitlab,linux,figma&perline=8" alt="TypeScript, React, Next.js, Redux, Vite, Webpack, Tailwind, Jest, Python, FastAPI, PostgreSQL, Redis, Docker, GitLab, Linux, Figma" />
</p>

| Area | Technologies |
| :-- | :-- |
| Frontend | TypeScript, React 19, Next.js 15 (App Router, SSR / ISR), TanStack Query, Redux Toolkit, MobX, Vite, Webpack / Module Federation, FSD, Playwright, Jest, Storybook |
| Backend | Python, FastAPI, PostgreSQL, ClickHouse, SQLAlchemy, Celery + Redis, pytest |
| Delivery | Docker, GitLab CI, Helm, Argo CD |
| AI | Claude Code, Codex, Claude Agent SDK, MCP |

## Selected repositories

| Repository | What it is | Stack |
| :-- | :-- | :-- |
| [payment-service](https://github.com/flavokrkkk/payment-service) | Take-home assignment: payments service with a transactional outbox, RabbitMQ retries and a dead-letter queue | Python, FastAPI, PostgreSQL, RabbitMQ |
| [sber-case](https://github.com/flavokrkkk/sber-case) | IT Purple Hack 2025, Sber case: project schedule optimization under time and resource constraints | TypeScript, NestJS, Next.js |
| [mts-vm-case](https://github.com/flavokrkkk/mts-vm-case) | IT Purple Hack 2025, MTS case: placing virtual machines on physical hosts round by round | TypeScript |
| [alpha_copilot_2025](https://github.com/flavokrkkk/alpha_copilot_2025) | Alfa-Future hackathon, 3rd place: AI copilot for micro-businesses. My part is the frontend with streamed answers (SSE); Go and Python services are the team's | React, Vite, TypeScript, TanStack Query |

## Hackathons

<table>
  <tr>
    <td align="center" width="33%"><a href="./assets/certs/hack-it-purple-2025-winner.jpg"><img src="./assets/certs/hack-it-purple-2025-winner.jpg" height="170" alt="IT Purple Hack 2025 winner certificate" /></a><br /><b>IT Purple Hack 2025</b><br /><sub>MIPT · winning team, I led three of five cases</sub></td>
    <td align="center" width="33%"><a href="./assets/certs/hack-alfa-budushchee-3rd-place.jpg"><img src="./assets/certs/hack-alfa-budushchee-3rd-place.jpg" height="170" alt="Alfa-Future 2025 3rd place diploma" /></a><br /><b>Alfa-Future 2025</b><br /><sub>Alfa-Bank · 3rd place, AI copilot for micro-businesses</sub></td>
    <td align="center" width="33%"><a href="./assets/certs/hack-mts-true-tech-participant.jpg"><img src="./assets/certs/hack-mts-true-tech-participant.jpg" height="170" alt="MTS True Tech Hack 2025 certificate" /></a><br /><b>MTS True Tech Hack 2025</b><br /><sub>MTS · participant, AI case</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="./assets/certs/hack-t1-participant.jpg"><img src="./assets/certs/hack-t1-participant.jpg" height="170" alt="T1 Hackathon Moscow certificate" /></a><br /><b>T1 Hackathon, Moscow</b><br /><sub>T1 · participant, «VibeCode Jam: interview of the future»</sub></td>
    <td align="center"><a href="./assets/certs/hack-mosprom-participant.jpg"><img src="./assets/certs/hack-mosprom-participant.jpg" height="170" alt="Open#Mosprom 2025 diploma" /></a><br /><b>Open#Mosprom 2025</b><br /><sub>Moscow Government · participant, hiring and internship platform for Technopolis Moscow residents</sub></td>
    <td align="center"><a href="./assets/certs/hack-biv-participant.jpg"><img src="./assets/certs/hack-biv-participant.jpg" height="170" alt="BIV Hack Challenge certificate" /></a><br /><b>BIV Hack Challenge</b><br /><sub>BIV · participant, insurance product configurator</sub></td>
  </tr>
</table>

## Talks

Speaker of three webinars on AI-assisted development: ~500, ~250 and ~150 attendees.

---

<p align="center"><sub>Telegram <a href="https://t.me/egoryaaa">@egoryaaa</a> · <a href="mailto:egoryarovitsyn1@gmail.com">egoryarovitsyn1@gmail.com</a></sub></p>
