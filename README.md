# Next.js SSR caching of pages to Redis

Example is based on official [example app](https://github.com/vercel/next.js/tree/canary/examples/ssr-caching), wich illustrates cachng of pages in the memory.
On the moment of writing this example doesn't work with latest Next.js version.
There is [opem PR](https://github.com/vercel/next.js/pull/18786/files) to fix this issue. All changes are used in this example.

## Prerequisites

Node.js >= 12

NPM >= 6

Redis >= 6

## Installation

1. Install dependencies

```bash
npm install
```

2. Create `.env` file in the root of the project using `.default_env` as example

3. Start project

for dev mode

```bash
npm run dev
```

4. For production verion use

```bash
npm run build && npm start

```

