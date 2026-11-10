## Avaz Qudratov · Kenneth

Full-stack and AI engineer in Suwon, Korea. I mostly write TypeScript and Python, and I care about two things: pages that load fast, and AI answers you can check.

```text
$ git log --oneline        # my career, newest first

c4e19a2  2026  Parsimony: LoRA Qwen 73/100 vs Gemini 85, kept Gemini
a8f2c1e  2026  Indesk: 4 agents, cited reports, claims checked in code
7d41b09  2026  Onestep: CRM search 4.5 s → <300 ms (pgvector, Redis)
3c90e7a  2025  Onestep: RAG assistant, 450+ asks/week, cites sources
91be44d  2025  Onestep: release testing hours → 10 min (Playwright)
5e17d2a  2024  Bast: first load 3.8 s → 2.1 s (code splitting)
0b3a6f1  2023  Bast: booking UI, 4,000+ visitors a month
```

### Things I built and run myself

**[Indesk](https://github.com/avazqudratovv-k/Indesk)** · [indesk.uz](https://indesk.uz)<br>
Upload a CSV or PDF and ask a question. A planner, a data analyst, a retriever and a verifier work through it, and the report marks every claim verified or unverified. The checks run in code, not in the model.<br>
`FastAPI` `Next.js` `pgvector` `Gemini` · 2,140 tests

**[Parsimony](https://github.com/avazqudratovv-k/Parsimony)** · [parsimony.duckdns.org](https://parsimony.duckdns.org)<br>
An expense tracker you can type to, talk to or show a receipt. One Gemini parser returns schema-validated entries, unsure ones go to review, and daily AI caps keep the bill small. Try it as a guest, no sign-up.<br>
`React` `FastAPI` `Postgres` `LoRA` · 152 backend + 100+ frontend tests

**[Ticketzy](https://github.com/avazqudratovv-k/Ticketzy)** · [ticketzy.uz](https://ticketzy.uz)<br>
Ticketing with 3D seat selection, QR tickets and live messaging over WebSocket. [Next.js client here](https://github.com/avazqudratovv-k/Ticketzy-next).<br>
`NestJS` `GraphQL` `MongoDB` `Next.js` · 1,287 backend tests

**[Golfy](https://github.com/avazqudratovv-k/Golfy-Frontend-User)** · [golfy.uz](https://golfy.uz)<br>
Hourly golf-venue booking in Korea time, with double-booking protection. Player app, admin app and two [APIs](https://github.com/avazqudratovv-k/Golfy-backend), deployed with Docker and nginx on my own server.<br>
`React` `Express` `MongoDB` `Docker` · 124 tests

**Zentr** · [zentr-frontend.vercel.app](https://zentr-frontend.vercel.app) · *in development*<br>
Community app frontend with real-time notifications, voice messages and four languages.<br>
`Next.js 16` `React 19`

### How I work

- **Numbers or it didn't happen.** Every result above is a before/after or a test score I measured.
- **The better model wins, even if it isn't mine.** I fine-tuned a small model for Parsimony, it lost, so production stays on Gemini.
- **I write down the limits.** My READMEs say what doesn't work yet, not just what does.
- **AI writes with me, not for me.** I use Claude Code and Cursor every day, but I make the design calls and review every change.

---

<sub>TypeScript · Python · React · Next.js · NestJS · Express · FastAPI · PostgreSQL · MongoDB · Redis · RAG · LangGraph · PyTorch · LoRA · Playwright · Docker</sub><br>
<sub>English · Korean</sub>

Open to full-time roles → [portfolio](https://avaz-fullstack.avazqudratovv.workers.dev) · [AI portfolio](https://avaz-ai.avazqudratovv.workers.dev) · avazqudratovv@gmail.com
