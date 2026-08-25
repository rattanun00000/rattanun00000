# Hi, I'm Bank (Rattanun Rodchawang) 👋

Full Stack Software Engineer based in Bangkok. I build backend-heavy products with **NestJS, Next.js, and PostgreSQL**, and I care most about the parts users never see: transaction safety, payment correctness, and systems that keep running at 3 a.m.

Currently at **Siam Orchard Group**, where I own features end-to-end — from stakeholder requirements to production.

## ⚡ What I'm building

**[Horo Stellar](https://horostellar.com)** — an AI tarot reading SaaS I designed, built, and operate solo, live in production.

- **Financially-safe billing** — credit deduction, AI call, and result persistence in a single ACID transaction with pessimistic locking. No double-spends, no charges on AI failure.
- **Resilient LLM layer** — routes between OpenAI and Claude per request type, falls back to OpenRouter, scales timeouts and token budgets by complexity, and recovers partial JSON from truncated output.
- **Payments** — Stripe credit packs and subscriptions (Card + PromptPay) fulfilled via idempotent, signature-verified webhooks.
- **Security** — Google/LINE OAuth with CSRF state, refresh-token rotation with reuse detection, Redis-backed lockout, rate limiting.
- **Operations** — daily PostgreSQL backups to Cloudflare R2 via GitHub Actions, Sentry, health probes, structured logging, 127 unit tests + e2e suites.

## 🛠 Stack

| | |
|---|---|
| **Backend** | Node.js, NestJS, Express, Python, REST API design |
| **Data** | PostgreSQL (Prisma), Redis, MongoDB, MySQL |
| **Frontend** | React, Next.js, TypeScript, Zustand, Redux, Tailwind CSS |
| **AI** | OpenAI API, Anthropic Claude API, prompt engineering, LLM cost optimization |
| **Infra** | Docker, GitHub Actions, Stripe, Socket.io, Sentry, Linux |

## 📌 Featured projects

<!-- Replace these with the public repos you extract from Horo Stellar -->

| Repo | What it is |
|---|---|
| [nestjs-stripe-webhooks](https://github.com/rattanun00000/nestjs-stripe-webhooks) | Idempotent, signature-verified Stripe webhook handling for NestJS with a verify-session fallback |
| [pg-backup-r2-action](https://github.com/rattanun00000/pg-backup-r2-action) | GitHub Action that dumps PostgreSQL with integrity checks to Cloudflare R2 |
| [llm-partial-json](https://github.com/rattanun00000/llm-partial-json) | Recover usable JSON from truncated LLM output, with tests |

## 📫 Contact

- Email: rattanun901@gmail.com
- LinkedIn: [linkedin.com/in/rattanun](https://www.linkedin.com/in/rattanun)
