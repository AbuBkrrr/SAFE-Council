# SAFE Council Digital Platform

Digital infrastructure for the SAFE Council Islamic Marriage Counselling Program.

> **Status:** Pre-launch. Code in progress.

## Tech Stack

- Next.js 14 (App Router) + React 18
- PostgreSQL 16 (Supabase free tier)
- Prisma 5
- NextAuth v5
- Supabase Storage + Google Drive URLs
- Resend (email), Termii (SMS/WhatsApp)
- Vercel (frontend) + Render (backend)
- Node >= 20

## Quick Start

    npm install
    cp .env.example .env
    npx prisma migrate dev --name init
    npm run dev

## Scripts

- npm run dev - local dev server
- npm run build - Prisma generate + Next build
- npm run typecheck - TypeScript check
- npm test - run tests
- npm run prisma:migrate - create migration
- npm run prisma:studio - DB GUI

## Contact

- Website: https://www.safefoundationafrica.org
- Email: safefoundation1@gmail.com
