# Real Chat

A pnpm workspace containing a Vue web app and a Fastify API.

## Requirements

- Node.js `^22.18.0` or `>=24.12.0`
- pnpm 11

## Development

Install all workspace dependencies once from the repository root:

```sh
pnpm install
```

Start both applications:

```sh
pnpm dev
```

Or start them separately:

```sh
pnpm dev:web
pnpm dev:api
```

The web app uses Vite's default address (`http://localhost:5173`) and the API
uses Fastify's default address (`http://localhost:3000`).

## Validation

```sh
pnpm type-check
pnpm test
pnpm build
```

Application packages are located in `apps/`. Reusable workspace packages can
be added under `packages/` when a real shared module is needed.
