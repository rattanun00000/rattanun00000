## Hi, I'm Bank (Rattanun Rodchawang) 👋

Full Stack Software Engineer based in Bangkok. I build backend-heavy products with **NestJS, Next.js, and PostgreSQL**, and I care most about the parts users never see: transaction safety, payment correctness, and systems that keep running at 3 a.m.

Currently at **Siam Orchard Group**, where I own features end-to-end — from stakeholder requirements to production.

### 🚧 Now building — Petcare Assistant
An AI assistant + CRM on LINE for pet shops (vet, grooming, boarding). Multi-tenant SaaS, live demo:
**[petcare.rattanun.dev](https://petcare.rattanun.dev)** — chat with the bot on LINE, browse the dashboard read-only.

- Customers book, pay deposits and cancel on LINE LIFF pages; the AI answers from the shop's own data and hands off to staff when it should
- Health facts the AI picks up from chat wait for staff to confirm — the bot never invents them
- Every tenant isolated by PostgreSQL row-level security; 2,300+ tests on real Postgres
- Eval suite on real models: 96% main / 88% hold-out · ~390 webhooks/s on a 2 vCPU box · runs on a $28.80/year server

### 🛠 Stack
| | |
|---|---|
| **Backend** | Node.js, NestJS, Express, Python, REST API design, BullMQ |
| **Data** | PostgreSQL (Prisma, Drizzle, row-level security), Redis, MongoDB, MySQL |
| **Frontend** | React, Next.js, TypeScript, Zustand, Redux, Tailwind CSS, Ant Design |
| **AI** | OpenAI API, Anthropic Claude API, OpenRouter, RAG, evals, LLM cost optimization |
| **Messaging** | LINE Messaging API, LINE LIFF, Flex Messages |
| **Infra** | Docker, GitHub Actions, Caddy, Tencent Cloud, Cloudflare R2, Stripe, Socket.io, Sentry, Linux |

### 📌 Featured projects
| Project | What it is |
|---|---|
| **Petcare Assistant** ([demo](https://petcare.rattanun.dev)) | LINE AI chatbot + CRM for pet shops — booking, deposits, staff inbox, AI memory with human review |
| [nestjs-stripe-webhooks](...) | Idempotent, signature-verified Stripe webhook handling for NestJS with a verify-session fallback |
| [pg-backup-r2-action](...) | GitHub Action that dumps PostgreSQL with integrity checks to Cloudflare R2 |
| [llm-partial-json](...) | Recover usable JSON from truncated LLM output, with tests |


## 📫 Contact

- Email: rattanun901@gmail.com
- LinkedIn: [linkedin.com/in/rattanun](https://www.linkedin.com/in/rattanun)
