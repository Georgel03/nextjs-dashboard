# nextjs-dashboard
A modern full-stack dashboard built with Next.js App Router. Features include Server Actions for mutations, streaming with Suspense, authentication, and a PostgreSQL database.

# Acme Dashboard - Next.js Full Stack App

A comprehensive financial dashboard built to demonstrate the capabilities of the modern **Next.js App Router**. This project implements server-side rendering, streaming data, and robust form handling using the latest React features.

![Dashboard Preview](public/hero-desktop.png)

## Key Features

* **App Router**: Built completely on the new Next.js routing paradigm.
* **Server Actions**: Mutations (Create, Update, Delete) are handled via Server Actions without separate API routes.
* **Streaming & Suspense**: Critical UI components load instantly while data-heavy components stream in, preventing page blocking.
* **Authentication**: Secure user login using NextAuth.js.
* **Database Integration**: Direct database querying with Vercel Postgres / PostgreSQL.
* **Responsive Design**: Styled with **Tailwind CSS** (mobile-first approach).
* **Search & Pagination**: URL-based state management for shareable and bookmarkable views.

## Tech Stack

* **Framework:** Next.js 14+ (App Router)
* **Language:** TypeScript / JavaScript
* **Styling:** Tailwind CSS
* **Database:** PostgreSQL
* **Forms:** React Server Actions & `useActionState`
* **UI Components:** Custom components with Shadcn/UI patterns (optional, if used).

## Getting Started

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR-USERNAME/nextjs-dashboard.git](https://github.com/YOUR-USERNAME/nextjs-dashboard.git)
    cd nextjs-dashboard
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

3.  Set up environment variables:
    Create a `.env` file in the root directory and add your database and auth secrets (see `.env.example`).

4.  Run the development server:
    ```bash
    npm run dev
    ```

5.  Open the app:
    Visit `http://localhost:3000` in your browser.

## What I Learned

This project was built to master:
* Partial Prerendering (PPR) and Dynamic Rendering.
* Using `useActionState` and `useTransition` for optimistic UI updates.
* Handling form validation on the server with Zod.
* Optimizing fonts and images with `next/font` and `next/image`.