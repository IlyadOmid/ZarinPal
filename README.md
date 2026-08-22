# ZarinPal Growth Intelligence

Production-oriented foundation for fintech analytics SaaS for ZarinPal merchants. Analytics logic is intentionally deferred for the hackathon foundation.

## Setup
Copy `.env.example` to `.env`, set `DATABASE_URL`, run `npm install`, `npm run db:generate`, `npm run db:migrate`, then `npm run dev`.

## Stack
Next.js App Router, TypeScript, Tailwind CSS, shadcn/ui conventions, Recharts, Prisma and PostgreSQL. The architecture leaves a clear boundary for Vercel AI SDK integration.

## Structure
Routes live in `src/app`; reusable UI in `src/components`; infrastructure in `src/lib`; domain boundaries in `src/analytics`, `src/ai`, `src/charts`, and `src/insights`; persistence in `prisma/`.