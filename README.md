## Avaz Qudratov · Kenneth

AI and full-stack engineer in Suwon, Korea. Since 2023 I've shipped TypeScript, React, Next.js, NestJS and Python, in product teams and on my own live products. I care about two things: pages that load fast, and AI answers you can check.

```text
$ git log --oneline        # my career, newest first

c4e19a2  2026  Parsimony: LoRA Qwen 73/100 vs hosted 85, kept hosted
a8f2c1e  2026  Indesk: agent team, every claim checked in code
7d41b09  2026  Onestep: CRM search 4.5 s → <300 ms (pgvector, Redis)
3c90e7a  2025  Onestep: RAG assistant, 450+ asks/week, cites sources
91be44d  2025  Onestep: release testing hours → 10 min (Playwright)
5e17d2a  2024  Bast: first load 3.8 s → 2.1 s (code splitting)
0b3a6f1  2023  Bast: booking UI, 4,000+ visitors a month
```

### Things I built and run myself

**[Indesk](https://github.com/avazqudratovv-k/Indesk)** · [indesk.uz](https://indesk.uz)<br>
Ask a question about a CSV or PDF. Owl plans, Hound retrieves, Beaver runs the numbers in a sandbox with no internet, and Cat checks every claim against the data. The report shows only claims that pass, or flags them.<br>
`FastAPI` `Next.js` `pgvector` `Redis` · 2,135 tests

**[Parsimony](https://github.com/avazqudratovv-k/Parsimony)** · [parsimony.duckdns.org](https://parsimony.duckdns.org)<br>
An expense tracker in English, Korean and Uzbek. Type it, say it or snap a receipt, and my parsing pipeline returns a schema-validated entry. Unsure entries go to review, and daily AI caps keep the bill small. Try it as a guest.<br>
`React` `FastAPI` `PostgreSQL` `LoRA` · 152 backend + 121 frontend tests

**[Ticketzy](https://github.com/avazqudratovv-k/Ticketzy)** · [ticketzy.uz](https://ticketzy.uz)<br>
Oversell-proof ticketing: reserved seats with holds, signed QR tickets, refunds that can't run twice, and an admin app. [Next.js client here](https://github.com/avazqudratovv-k/Ticketzy-next).<br>
`NestJS` `GraphQL` `MongoDB` `Next.js` · 105 GraphQL operations · 1,675 backend tests

**[Golfy](https://github.com/avazqudratovv-k/Golfy-Frontend-User)** · [golfy.uz](https://golfy.uz)<br>
Hourly booking for golf courses, simulators and ranges in Korea, with double-booking protection. Player app, admin app and two [APIs](https://github.com/avazqudratovv-k/Golfy-backend), deployed with Docker and nginx.<br>
`React` `Express` `MongoDB` `Docker` · 124 tests

**Zentr** · [zentr-frontend.vercel.app](https://zentr-frontend.vercel.app) · *in development*<br>
Korea-first community platform. I build the Next.js frontend: real-time notifications, voice messages, four languages.<br>
`Next.js 16` `React 19`

### How I work

- **Measure first.** I find where the time or the bug is before changing anything.
- **Prove it with tests.** Race conditions and edge cases get a test, not a promise.
- **Say what isn't built.** Simulated payments and unfinished parts are stated up front.
- **The better model wins.** My fine-tuned model lost to the hosted one, so production keeps the hosted one.

---

<sub>TypeScript · Python · React · Next.js · NestJS · Express · FastAPI · GraphQL · PostgreSQL · MongoDB · Redis · RAG · LangGraph · PyTorch · LoRA · Playwright · Docker</sub><br>
<sub>English (fluent) · Korean (conversational)</sub>

Open to full-time roles → [full-stack portfolio](https://avaz-fullstack.avazqudratovv.workers.dev) · [AI portfolio](https://avaz-ai.avazqudratovv.workers.dev) · avazqudratovv@gmail.com
