This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

### Tutorial - Intro

create a new nextJS app: `npx create-next-app next-app`

```bash
Would you like to use TypeScript with this project? -> Yes
Would you like to use ESLint with this project? -> Yes
Would you like to use `src/` directory with this project? -> Yes
Would you like to use experimental `app/` directory with this project? -> no
What import alias would you like configured? -> @/*
```

(optional) disable telemetry collection: `npx next telemetry disable`

(optional) check status of telemetry collection: `npx next telemetry status`

ESlint: `npm run lint`

Hot reload: `npm run dev`

Build: `npm run build`

Launch production site: `npm run start`

### Tutorial - Update NextJS

Latest releases: https://github.com/vercel/next.js/releases

- check installed version: `npx next --version`
- install the latest version: `npm install next@latest`
- install a specific version: `npm install next@version-number`, example: `npm install next@13.4.2`

### Tutorial - Statically Created Routes

Example: `src/pages/about.tsx`

Demo: https://next-app.pilinux.me/about

### Tutorial - Dynamically Created Routes

Example: `src/pages/posts/[pid].tsx`

Demo:
- https://next-app.pilinux.me/posts/hello
- https://next-app.pilinux.me/posts/hello-world

### Tutorial - Fetch Data from a Remote API

Example: `src/pages/api/gorest-example-posts.ts`

Demo: https://next-app.pilinux.me/api/gorest-example-posts

### Tutorial - Render Data Fetched from a Remote API

Example: `src/pages/gorest-example/posts.tsx`

Demo: https://next-app.pilinux.me/gorest-example/posts

### Tutorial - HTTP POST

Example:
- `src/pages/api/gorest-example-login.ts`
- `src/pages/gorest-example/http-post.tsx`

Demo: https://next-app.pilinux.me/gorest-example/http-post

```JSON
{
    "email": "killua@example.com",
    "password": "1234.."
}
```

### Tutorial - Redux Toolkit Intro

redux provides global state to set/get data at any point in the app

Doc: https://redux-toolkit.js.org/tutorials/quick-start

`npm install @reduxjs/toolkit react-redux`

- 1: `src/store.ts`, `src/slices/counterSlice.ts`
- 2: `src/pages/_app.tsx`
- 3: `src/pages/counter.tsx`

Demo: https://next-app.pilinux.me/counter

See [commit](https://github.com/pilinux/next-app/commit/c7b9fd2)
