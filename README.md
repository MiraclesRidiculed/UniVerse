# UniVerse

UniVerse is a campus networking platform that enables students to connect, discover peers, and share resources within their campus ecosystem.

It is built as a **monorepo** using modern full-stack technologies, combining a scalable backend with a responsive frontend.

---

## 🚀 Tech Stack

* **Frontend:** Next.js (Auth0 authentication)
* **Backend:** Express.js
* **Database:** MongoDB
* **Architecture:** npm workspace monorepo

---

## 📁 Workspace Layout

* `apps/client`
  Next.js frontend with Auth0-based sign-in and campus-facing UI.

* `apps/core`
  Express + MongoDB backend handling student, admin, and campus data flows.

---

## ⚙️ Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Setup environment variables:

   * Copy `.env.example` files in:

     * `apps/client`
     * `apps/core`

3. Run backend:

   ```bash
   npm run dev:core
   ```

4. Run frontend:

   ```bash
   npm run dev:client
   ```

---

## 🧰 Common Commands

* `npm run dev:client` → Start frontend
* `npm run dev:core` → Start backend
* `npm run build` → Build all apps
* `npm run typecheck` → Type checking
* `npm run format` → Code formatting

---

## 🤝 Collaboration Notes

* Frontend and backend are developed in a unified monorepo but can be deployed independently.
* Shared dependencies and a single lockfile simplify development.
* Licensed under MIT — ensure all contributors approve before public release.

---

## 🎯 Vision

UniVerse aims to become a **central digital hub for campus life**, enabling:

* Student discovery & networking
* Resource sharing
* Campus-specific communities
* Admin-student interaction

---
