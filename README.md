## Hi, I'm Muhammad Hozaif

I build full-stack web and mobile apps, mostly for healthcare, and I like adding AI that is actually useful: grounded, testable, and honest when it can't answer.

Right now I'm working on **MedScribe** (private), an ambient clinical-scribe EHR. You record a visit and get a live transcript and an AI-drafted SOAP note with decision support, which a clinician reviews and signs. It has a Next.js web app, a NestJS API and an Expo mobile app on one Postgres database, with role-based access and a hash-chained audit log.

### Tech I use

- **Frontend:** React, Next.js (App Router), TypeScript, Tailwind CSS, Storybook
- **Backend:** Node.js, Express, NestJS, FastAPI, Django, Flask
- **Data:** PostgreSQL, Prisma, SQLAlchemy, Alembic, MongoDB, Redis, Celery
- **Mobile:** React Native, Expo
- **AI:** Claude API, Model Context Protocol, RAG (BM25 + embeddings)
- **Testing and CI:** Vitest, Jest, Playwright, CircleCI, GitLab CI

### Selected projects

| Project | What it is |
| --- | --- |
| [mcp-document-chat](https://github.com/MuhammadHozaif-Bitsol/mcp-document-chat) | CLI chat where Claude reads and edits documents through an MCP server and client I wrote |
| [hybrid-rag-search](https://github.com/MuhammadHozaif-Bitsol/hybrid-rag-search) | Hybrid retrieval written by hand: BM25 and Voyage AI embeddings merged with Reciprocal Rank Fusion |
| [medical-app-nextjs](https://github.com/MuhammadHozaif-Bitsol/medical-app-nextjs) | Clinic booking system: patient portal with an AI assistant, staff dashboard, JWT role-based auth |
| [agent-clinic](https://github.com/MuhammadHozaif-Bitsol/agent-clinic) | Satirical clinic for AI agents, built spec-first with Playwright, accessibility and Lighthouse checks |
| [claude-api-features](https://github.com/MuhammadHozaif-Bitsol/claude-api-features) | Extended thinking, vision, citations and prompt caching with the Claude API |
| [nodejs-memory-leak](https://github.com/MuhammadHozaif-Bitsol/nodejs-memory-leak) | Finding a memory leak in an Express app with V8 heap snapshots |
