# Business Hub — starter project

React + Vite starter for an internal business operations dashboard. Includes a responsive overview, sample product catalogue, interactive hamper builder with budget and bulk-cost calculations, and a basic task list.

## Run locally

1. Install Node.js 20 or later.
2. Extract this ZIP and open a terminal in the `business-hub` folder.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL printed in the terminal.
5. Run `npm run build` to verify a production build.

## Supabase

A starter SQL schema is included at `supabase/schema.sql`, and `.env.example` shows the required environment variables. Create a Supabase project, run the SQL in its SQL Editor, copy `.env.example` to `.env`, and add your project URL and anon key. Restart Vite afterwards.

**Important:** this is a frontend starter with sample/demo data. The Supabase client and starter schema are included, but authentication, database CRUD, storage, role-based access, realtime collaboration, and production finance/order workflows are not yet wired up. Configure Row Level Security policies before using real business data.

## GitHub

```bash
git init
git add .
git commit -m "Initial Business Hub project"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```
