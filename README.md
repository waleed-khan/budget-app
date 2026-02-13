# Budget App (Vite + React + Fastify)

This repository includes a concrete architecture baseline for building a budgeting app.

## Core Requirements

- mobile and desktop compatible UI
- CSV upload and parsing
- user-defined budgets and expense tracking
- authentication for persistent user data

## Optional Enhancements

- AI purchase categorization with user approval
- bank API connection and secure transaction sync

## Architecture Artifacts

- Project structure: `docs/project-structure.md`
- Implementation roadmap: `docs/implementation-roadmap.md`
- Database schema: `prisma/schema.prisma`

## Suggested Stack

- Frontend: React + Vite + TypeScript
- Backend: Fastify + TypeScript
- Database: PostgreSQL + Prisma
- Background jobs: BullMQ + Redis
- Cloud: Azure Static Web Apps + Container Apps + PostgreSQL + Redis + Blob Storage
