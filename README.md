# Karan Rathod — Living Portfolio

A portfolio built like a product: live proof of work (GitHub, DSA), case studies that show decisions, niche ERPNext/manufacturing writing, and an AI assistant grounded only in real experience.

## Stack
TanStack Start · Cloudflare Workers (R2, KV, Cron, Access, Turnstile) · Neon Postgres + pgvector · Drizzle · TypeScript · Gemini / Workers AI (behind a provider interface)

## How this repo is run
- `main` is protected — every change lands through a pull request.
- Commits follow [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, `chore:` …).
- Every significant decision is recorded as an ADR in [`docs/adr`](docs/adr).

## Docs
1. [PRD](docs/01-prd.md)
2. [User flows](docs/02-flows.md)
3. [Architecture & threat model](docs/03-architecture.md)
4. [Decision records](docs/adr)
