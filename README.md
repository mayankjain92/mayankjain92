# Hi — I'm Mayank 👋

I build polished web and mobile experiences driven by thoughtful APIs and pragmatic engineering. I ship prototypes fast and iterate them into production-ready apps — with a focus on TypeScript-first stacks, API-first design, and clear UX.

---

## Spotlight projects

### mysterymessage — mysterious, delightful messaging (LIVE)
🔗 https://mysterymessage-bice.vercel.app  
A TypeScript + Next.js app (Next 16, React 19) built as a full-stack messaging playground that emphasizes privacy, message verification and modern email/notifications. Key tech and deps: Next.js, React, TypeScript, next-auth, Mongoose/MongoDB, OpenAI & Google generative AI integrations, Nodemailer/Resend for email, Tailwind/Shadcn UI.

What stands out
- Full Next.js app with TypeScript-first config (strict TS, path aliases).
- AI/LLM-ready: openai + generative AI packages configured.
- Email flows and verification (resend / nodemailer + react-email components).
- Deployed to Vercel (link above).

Quick local dev
```bash
# from repo root
npm install
npm run dev        # runs: next dev --webpack
```

---

### prep-os — monorepo in progress (your current focus)
🔗 https://github.com/mayankjain92/prep-os  
Monorepo scaffold using pnpm workspaces. The repository contains `apps/` and `packages/` folders, a workspace file, and a docker-compose to run supporting services. This is the multi-package foundation for a multi-app system — ideal for composing shared UI, API and infra tooling.

What stands out
- pnpm workspace (pnpm-workspace.yaml + pnpm-lock.yaml).
- Docker Compose provided for local infra orchestration.
- Structured for multiple apps & packages (apps/ & packages/).

Quick local dev (typical for this layout)
```bash
# from monorepo root
pnpm install
# inspect apps/ to pick which app to run, e.g.:
cd apps/<app-name>
pnpm install
pnpm dev
# or run workspace scripts if defined
```

---

### chat-app — classic client/server chat demo (report included)
🔗 https://github.com/mayankjain92/chat-app  
A JavaScript-first chat demo with separate `client/` and `server/` directories and a detailed PROJECT_REPORT. Great for demonstrating real-time flows and basic messaging architectures.

What stands out
- Clear client / server split for chat logic, sockets, and API endpoints.
- In-repo project report describing design decisions and architecture.
- Lightweight, easy to run and iterate.

Quick local dev
```bash
# inspect /client and /server for start scripts
cd client && npm install && npm run dev
cd server && npm install && npm run dev
```

---

### portfolio — personal site (Next.js)
🔗 https://mayankajain-portfolio.vercel.app  
Your public portfolio built with Next.js + Tailwind, showcasing projects and contact info.

Quick local dev
```bash
npm install
npm run dev
# open http://localhost:3000
```

---

## Tech snapshot
- Primary languages: TypeScript (majority), JavaScript, CSS/Tailwind
- Frontend: Next.js, React, shadcn UI, Tailwind
- Backend/databases: Node.js, Express-style APIs, MongoDB (Mongoose)
- AI & integrations: openai, @google/generative-ai, ai (client libs)
- Monorepo & tooling: pnpm workspaces, Docker Compose, TypeScript strict config

---

## How I approach projects
- API-first: design the contract, then implement and test.
- Prototyping fast: ship a minimal, usable flow, then iterate.
- Practical infra: local dev with docker/pnpm; deploy on Vercel or container hosts.
- Testing & validation: strict typing, schema validation (zod), and small, testable components.

---

## Want to explore specific things in these repos?
- mysterymessage: I can highlight the authentication & email verification flow, or document LLM integration points (OpenAI + Google Generative AI).
- prep-os: I can list the workspace packages and recommend workspace-level scripts for dev/test/deploy.
- chat-app: I can extract the real-time architecture (socket choices, message persistence) and produce a minimal run & test guide.
- portfolio: I can add screenshots, CI/Vercel badges, and a “What I built” showcase section that links to specific commits or demos.

Thanks for trusting me with your profile — explore the links above and feel free to copy this README into your profile repo to make it the landing page for visitors. 🚀
