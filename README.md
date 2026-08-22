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

Open https://portfoligen-ai.vercel.app/<img width="1672" height="941" alt="Codex Image Aug 21, 2026, 06_35_49 PM" src="https://github.com/user-attachments/assets/bc397ef0-0ce2-4214-b679-493695296658" />

## Environment variables

Copy `.env.example` to `.env.local` and add your own API key if you implement live AI analysis.

Never commit `.env.local`.

## GitHub

This repository excludes `node_modules`, `.next`, and environment files through `.gitignore`.
