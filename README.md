## Fullstack JS web application stater

## Description

A fullstack javascript web application with minimal setup, built up on Next.js and Nest.js framework for consistency, simplicity, type safety.

#### Benefit

- Sharing reusable code across server(Nest.js) and client(Next.js) - which would be DTOs, helper function, constants(custom status code)
- Keeping default framework configuration
- No need infrastructure setup (database, database admin, prisma(optional))
- Quickly start development

#### Technologies

- PostgresSQL
- Typescript
- Nest.js
  - Prisma
- Next.js
  - Tailwind
- Docker

#### NOTE

You could create your own database credential by editing enviroment variables inside `docker-compose.dev.yaml`. Then modify `.env` file by replacing respectively values.

## Required

```bash

node >= 18.17.0
pnpm >= 8.11.0
```

## Installation

```bash
$ pnpm install
```

## Running the app

```bash
$ Rename .env.example --> .env

# database (postgres, pgAdmin)
$ pnpm dev:backend
  -> localhost:4000

# frontend
$ pnpm dev:frontend
  -> localhost:3000

# backend
$ pnpm dev:infrastructure

```

## Stay in touch

- Author - Tomiez
- Linkedin - [@tomiez](https://www.linkedin.com/in/tomiez)
