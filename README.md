# learn-next

A learning dashboard based on the Next.js App Router course, with invoice, customer, and revenue views.

[Repository](https://github.com/MirzaAlbab/learn-next)

## Features

- App Router layouts and loading/error states
- Invoice create and edit pages
- PostgreSQL data queries
- NextAuth authentication configuration and Zod dependencies

## Technology

`next` 15.0.0-canary.56 · `react` 19.0.0-rc-f38c22b244-20240704 · `typescript` 5.5.2

## Getting started

Install a Node.js version compatible with the pinned Next.js release and pnpm.

```bash
git clone https://github.com/MirzaAlbab/learn-next.git
cd learn-next
```

```bash
pnpm install
```

Create `.env.local` with PostgreSQL settings for `@vercel/postgres` and the authentication settings required by `auth.ts` and `auth.config.ts`. Set up the customer, invoice, revenue, and user tables expected by `app/lib/data.ts` and the course data model.

```bash
pnpm dev
```

Open the address printed by Next.js. Follow the [course setup guide](https://nextjs.org/learn/dashboard-app) for the original database and authentication walkthrough.

## Development and checks

```bash
pnpm build
```

No dedicated test script is configured in the reviewed package manifest.

## Project structure

- `app/` — Application source
- `public/` — Public web assets and entry points

## Project notes

Based on the [Next.js Learn dashboard course](https://nextjs.org/learn). The manifest pins a Next.js canary release, a React release candidate, and a NextAuth beta; use compatible versions when reproducing the project.

## Original documentation

<details>
<summary>Preserved original README and credits</summary>

## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

</details>

## License

No root `LICENSE` file was present in the reviewed repository. Consult the repository owner about reuse; dependencies and third-party assets retain their own terms.
