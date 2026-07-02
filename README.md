# Vadim Genze

Software Engineering student at Tomsk Polytechnic University. I work around
backend development, infrastructure, Linux/VPS operations, Docker, PostgreSQL,
technical support for AI platforms, AI agents, and engineering documentation.

I like projects where the code, environment, deployment notes, and runbooks are
clear enough for another engineer to continue the work.

## Focus

- Backend services and API design
- Docker-based local and server environments
- PostgreSQL/Redis application stacks
- Linux, Nginx, VPS operations, and infrastructure notes
- Technical documentation: README files, runbooks, API and architecture docs
- AI-assisted tools, Telegram bots, and agent workflows

## Stack

Python, FastAPI, Django, Node.js, NestJS, Express, TypeScript, React, Vite,
PostgreSQL, Redis, Prisma, SQLAlchemy/Alembic, Docker, Docker Compose, Linux,
Nginx, MkDocs, Markdown.

Currently learning: Kubernetes, observability, infrastructure security, and AI
agent engineering.

## Featured Projects

### ProjectFlow

Diagram-first collaboration platform for my diploma project.

Stack: React, Vite, TypeScript, NestJS, Prisma, PostgreSQL, Redis, Socket.IO,
LiveKit, Docker Compose.

Work done:

- Set up the monorepo structure for frontend, backend, shared types, infra, and
  docs.
- Built workspace, invite, board, file, search, auth, voice, and admin backend
  modules.
- Connected `.drawio` XML board storage with real-time board events.
- Built the React workspace UI with board editor, file explorer, previews, and
  voice-room panel.
- Added a local Docker Compose stack with PostgreSQL, Redis, LiveKit, API, and
  web app.
- Wrote architecture, API, deployment, and demo documentation.

Status: active diploma project. Public repository setup is in progress.

### Quest Bot

Telegram bot for group quests, reports, voting, achievements, stats, and admin
exports.

Stack: Python, aiogram, asyncpg, PostgreSQL, Docker Compose, optional Google
Generative Language API integration.

Work done:

- Organized handlers for quest creation, reports, voting, profile, stats, menu,
  membership, and admin commands.
- Added PostgreSQL schema for users, quests, attempts, reports, votes,
  achievements, cooldowns, and exports.
- Added scheduler logic for deadlines, vote closure, reminders, cooldowns, and
  achievement grants.
- Packaged the bot and database with Docker Compose.
- Added README, `.env.example`, and `.gitignore`; removed local `.env` from Git
  tracking.

Status: private repository, cleanup branch prepared.

### VLESS Reality Telegram Bot Docs

Documentation for a VPS-based Xray/VLESS Reality setup with a Telegram bot.

Stack described in docs: Linux VPS, Docker Compose, Xray, VLESS Reality,
Python/aiogram.

Work done:

- Documented architecture, service boundaries, and connection flow.
- Wrote runbook steps for health incidents, key rotation, and releases.
- Added security notes for secrets, logs, firewall exposure, and Docker
  hardening.

Status: documentation-only repository.

### MAXYA

SFU MAX Mini App repository with a Python-first migration path and split-service
target architecture.

Work I can publicly describe from the local branch:

- Delivery and operations documentation.
- Server sizing and MVP delivery baseline notes.
- Runtime shape, target architecture, and operational checkpoints.

Status: private or access-limited repository; details stay conservative.

## Russian

Я Вадим, студент Software Engineering в TPU. Мне интересны backend,
инфраструктура, DevOps, Linux, Docker, PostgreSQL, Kubernetes, AI-агенты и
техническая документация. Люблю доводить проекты до состояния, где понятны код,
запуск, окружение и эксплуатация.
