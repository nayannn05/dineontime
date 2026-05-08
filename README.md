## Face Recon (Lumaire funnel MVP)

This repo contains:
- `client/`: Next.js funnel + on-screen Lumaire-branded report
- `server/`: Fastify + TypeScript API (OpenRouter-backed report generation + Mongo lead capture)

### Setup

1) Configure backend env

Create `server/.env` (already scaffolded) and set:
- `OPENROUTER_API_KEY`
- `MONGODB_URL_DEVELOPMENT`

2) Start backend

```bash
cd server
npm run dev
```

3) Start client

```bash
cd client
npm run dev
```

Client expects API at `NEXT_PUBLIC_API_BASE` (default `http://localhost:8080`).

