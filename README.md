# Вадим Genze

Студент Software Engineering в TPU. Работаю с backend-разработкой,
инфраструктурой, Linux/VPS, Docker, PostgreSQL, технической поддержкой
AI-платформ, AI-агентами и инженерной документацией.

Мне интересны проекты, где важен не только код, но и то, как система
запускается, конфигурируется, обслуживается и объясняется другим людям.

## Чем занимаюсь

- Backend-сервисы и API.
- Docker-окружения для локальной разработки и VPS.
- Приложения на PostgreSQL/Redis.
- Linux, Nginx, systemd, базовая эксплуатация серверов.
- README, runbook, deployment-документация и заметки по архитектуре.
- Telegram-боты, AI-assisted инструменты и агентные процессы.

## Стек

Python, FastAPI, Django, Node.js, NestJS, Express, TypeScript, React, Vite,
PostgreSQL, Redis, Prisma, SQLAlchemy/Alembic, Docker, Docker Compose, Linux,
Nginx, systemd, MkDocs, Markdown.

Сейчас углубляюсь в Kubernetes, observability, инфраструктурную безопасность и
AI-агентов.

## Проекты

### ProjectFlow

Платформа для совместной работы над проектами с diagram-first подходом.

Репозиторий: [MrAlchemist74/ProjectFlow](https://github.com/MrAlchemist74/ProjectFlow)

Стек: React, Vite, TypeScript, NestJS, Prisma, PostgreSQL, Redis, Socket.IO,
LiveKit, Docker Compose.

Что сделал:

- Собрал monorepo-структуру: frontend, backend, shared types, infra и docs.
- Реализовал backend-модули для auth, users, workspaces, invites, boards,
  files, search, voice, admin и health.
- Подключил хранение `.drawio` XML-досок и realtime-события через Socket.IO.
- Собрал React UI для workspace, board editor, file explorer, preview и voice
  room panel.
- Подготовил Docker Compose окружение с API, web, PostgreSQL, Redis и LiveKit.
- Описал архитектуру, API, deployment и demo flow.

### OwnCord VPS Deployment

Self-hosted мессенджер, развернутый на VPS.

Стек: Node.js, Express, Socket.IO, SQLite, React, Vite, WebRTC, Web Push,
Nginx, systemd.

Что сделал на сервере:

- Проанализировал и описал production-развертывание на VPS.
- Проверил systemd-сервис, рабочую директорию, runtime-пользователя и порт.
- Описал Nginx reverse proxy и WebSocket forwarding для домена.
- Зафиксировал storage layout, env-переменные без секретов и заметки по деплою.
- Подготовил безопасное описание для README/портфолио.

### Quest Bot

Telegram-бот для групповых квестов, отчетов, голосования, достижений,
статистики и admin exports.

Стек: Python, aiogram, asyncpg, PostgreSQL, Docker Compose, Google Generative
Language API.

Что сделал:

- Организовал handlers для quest flow, reports, voting, profile, stats, menu,
  membership и admin-команд.
- Добавил PostgreSQL-схему для users, quests, attempts, reports, votes,
  achievements, cooldowns и exports.
- Реализовал scheduler для дедлайнов, закрытия голосований, reminders,
  cooldowns и выдачи достижений.
- Упаковал bot + database через Docker Compose.
- Добавил README, `.env.example`, `.gitignore` и убрал локальный `.env` из Git
  tracking.
