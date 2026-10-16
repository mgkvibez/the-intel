# the-intel

A snapshot of **BlogVault**, a full-stack blog application, stored here as `BlogVault.zip` (the full project including its git history).

## What's inside the archive

BlogVault is a Replit-style full-stack app:

- `client/` — React frontend (with shadcn-style components, `components.json`)
- `server/` — Express API
- `shared/` — types shared between client and server
- Drizzle ORM config (`drizzle.config.ts`) with the schema and migration scripts
- `design_guidelines.md` / `replit.md` — project notes and conventions

## Why a zip

This repo stores the project as a single archive to keep the snapshot portable — extract it with `unzip BlogVault.zip` and run `npm install && npm run dev` in the extracted folder. The archive includes BlogVault's own `.git`, so its history comes along with it.
