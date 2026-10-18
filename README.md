# Prepzo

Prepzo is an AI-powered interview preparation and evaluation platform built with React, Vite, TypeScript, Tailwind CSS, and Supabase. It helps users practice interviews for different job roles, improve weak skills, and receive structured feedback based on their responses.

## Overview

The application includes:
- AI-generated interview questions tailored to job roles and difficulty
- Interview practice flows for text and speech-based responses
- Instant evaluation and performance insights
- Personalized recommendations to improve communication and technical skills
- Learning resources and curated guidance for career growth
- User authentication, profiles, dashboard tracking, and result history

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui components
- Framer Motion
- Supabase for auth and backend services
- Vitest for testing

## Features

### Interview preparation
- Browse available job roles and career paths
- Start practice sessions with role-based questions
- Receive AI-driven feedback and evaluation summaries
- Review interview history and performance improvements

### Learning experience
- Access learning content and skill resources
- Explore relevant topics by domain and role
- Follow guided preparation paths before interviews

### User experience
- Protected routes for authenticated users
- Theme support with light/dark styling
- Responsive, modern UI optimized for desktop and mobile screens

## Project Structure

```text
src/
  App.tsx
  components/
  data/
  hooks/
  integrations/
  lib/
  pages/
  assets/
public/
  favicon.ico
  favicon.png
  placeholder.svg
supabase/
  functions/
  migrations/
```

## Prerequisites

- Node.js 18 or later
- npm

## Getting Started

1. Install dependencies:

```bash
npm install
```

If you run into the Windows Vite/Rollup optional dependency issue, use:

```bash
npm install --include=optional
```

2. Create a local environment file named `.env.local` in the project root with your Supabase configuration:

```bash
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_anon_key
```

3. Start the development server:

```bash
npm run dev -- --host 0.0.0.0
```

The app will run at:

```text
http://localhost:8080/
```

## Available Scripts

```bash
npm run dev
npm run build
npm run build:dev
npm run preview
npm run test
npm run lint
```

## Production Build

```bash
npm run build
```

## Notes

- The app uses protected routes, so login/signup flows are required for interview and dashboard access.
- Supabase configuration is required for authentication and environment-dependent features.
- Styling and UX are built around a polished onboarding and learning experience for job seekers.

## License

This project is currently distributed without a separate license file. Please check with the repository owner for licensing terms before reuse or redistribution.
