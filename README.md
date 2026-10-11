# Celebque — Application Iteration

This repository contains a Next.js implementation of the Celebque creator-platform concept, including authentication routes, protected pages, API helpers and a Prisma data layer.

**Repository:** [Aestheticsgods/celebquefinal](https://github.com/Aestheticsgods/celebquefinal)

## Included areas

- App Router pages and account workflows
- NextAuth sign-in and registration routes
- Protected application views
- Prisma schema and database access helpers
- Shared creator-platform interface components

The repository also contains sample content and project documentation. Confirm the required environment variables and database setup for the current branch before deployment.

## Technology

- Next.js, React and TypeScript
- Prisma and MySQL
- NextAuth
- Tailwind CSS and reusable UI components

## Run locally

Requirements: Node.js 20 or newer, npm and a configured database.

```bash
git clone https://github.com/Aestheticsgods/celebquefinal.git
cd celebquefinal
npm install
```

Configure local environment variables, then prepare the database and start the development server:

```bash
npx prisma generate
npx prisma migrate dev
npm run dev
```

## Project layout

```text
src/app/       Application pages and API routes
src/components/Shared interface and layout components
src/contexts/  Authentication and navigation state
src/lib/       Database and API helpers
prisma/        Data model and migration files
```
