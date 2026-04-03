# UniVerse
<<<<<<< HEAD
Campus networking app with Auth0 sign-in, student profiles, search, and resource sharing. Next.js + Express + MongoDB monorepo.
=======

UniVerse is a campus networking product organized as a single npm workspace monorepo. The codebase combines the original client and core services into one publish-ready repository while keeping the frontend and backend clearly separated.

## Workspace Layout

- `apps/client`: Next.js frontend with Auth0-based sign-in and campus-facing UI.
- `apps/core`: Express + MongoDB backend for student, admin, and campus data flows.

## Getting Started

1. Install dependencies from the repository root with `npm install`.
2. Create environment files from the examples in `apps/client/.env.example` and `apps/core/.env.example`.
3. Start the backend with `npm run dev:core`.
4. Start the frontend with `npm run dev:client`.

## Common Commands

- `npm run dev:client`
- `npm run dev:core`
- `npm run build`
- `npm run typecheck`
- `npm run format`

## Collaboration Notes

- The frontend and backend still deploy independently, but they now share one repository, one lockfile, and one set of setup docs.
- This repository is licensed under MIT. Before publishing it publicly, make sure every contributor to the original code agrees to the MIT release.
>>>>>>> 5f9ed77 (Create UniVerse monorepo)
