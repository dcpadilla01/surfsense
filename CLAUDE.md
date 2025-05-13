# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build/Lint/Test Commands

### Backend (Python)
- Runtime: Python >=3.12
- Package manager: uv

### Frontend (Next.js)
- Build/Run: `pnpm dev`, `pnpm build`, `pnpm start`
- Lint: `pnpm lint`
- Debug: `pnpm debug`

### Browser Extension
- Build/Run: `pnpm dev`, `pnpm build`, `pnpm package`

## Code Style Guidelines

### General
- Use pnpm as default package manager (Cursor rule)

### Backend
- FastAPI for API development
- PostgreSQL with pgvector for vector storage
- LangChain and LangGraph for agent workflows

### Frontend/Extension
- TypeScript with strict mode enabled
- React hooks pattern
- Tailwind CSS for styling
- Use Radix UI components
- Path aliases: `@/*` maps to root directory
- ESLint with Next.js core-web-vitals rules