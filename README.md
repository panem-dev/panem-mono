# Panem monorepo

## What's inside?

This turborepo uses [Yarn](https://classic.yarnpkg.com/lang/en/) as a package manager. It includes the following packages/apps:

### Apps and Packages

- `web`: another [Next.js](https://nextjs.org) app
- `ui`: a stub React component library shared by all applications
- `eslint-config-custom`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

## Setup

This repository is used in the `npx create-turbo` command, and selected when choosing which package manager you wish to use with your monorepo (Yarn).

### Build

To build all apps and packages, run the following command:

```
cd my-turborepo
yarn run build
```

### Develop

To develop all apps and packages, run the following command:

```
cd my-turborepo
yarn run dev
```

### Tech stack

- NextJs (Client facing PWA, Serverless functions for Backend)
- Supabase (Authentication, Database)
- ThirdWeb to manage (Minting of shares as NFT tokens based on Ethereum)
- Vercel (Hosting, Domain)
- Turborepo (Manage application repo)

### Architectural Diagram

- https://drive.google.com/file/d/1bmBhDI8E9EygLGFyp3A5zWKnz8Ed_9dX/view?usp=sharing

### ERD

- https://drive.google.com/file/d/1jUOeRthPPFvB7cqdBnt2e2GU7ve9P8fy/view?usp=sharing
