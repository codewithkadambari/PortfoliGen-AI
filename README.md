# PortfoliGen AI

> Transform Your Resume into a Professional Portfolio with AI.

PortfoliGen AI is a Next.js application designed to turn resume information into a professional portfolio experience.

## Features

- PDF resume upload with validation
- Resume analysis workflow
- AI-ready architecture
- Responsive landing page
- Portfolio generation workflow foundation
- Light/dark UI foundation

## Agent workflow

```text
Resume PDF → Reader → Analyzer → Resume Data → Planner → Portfolio Plan → Generator → Reviewer → Portfolio Preview
```

## Tech stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- Lucide React
- Next.js API Routes
- OpenAI API integration can be added through environment variables

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Environment variables

Copy `.env.example` to `.env.local` and add your own API key if you implement live AI analysis.

Never commit `.env.local`.

## GitHub

This repository excludes `node_modules`, `.next`, and environment files through `.gitignore`.
