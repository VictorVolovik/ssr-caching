# Next.js SSR caching of pages to Redis

Example is based on official [example app](https://github.com/vercel/next.js/tree/canary/examples/ssr-caching), wich illustrates cachng of pages in the memory.
On the moment of writing this example doesn't work with latest Next.js version.
There is [open PR](https://github.com/vercel/next.js/pull/18786/files) to fix this issue. All changes from PR are used in this example.

## Prerequisites

Node.js >= 12

NPM >= 6

Redis >= 6

## Installation and usage

1. Install dependencies

   ```bash
   npm install
   ```

1. Start project in dev mode

   ```bash
   npm run dev
   ```

1. For production verion use

   ```bash
   npm run build && npm start

   ```
