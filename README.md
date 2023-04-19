This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with all default options at 2023 April 19.

```bash
npx create-next-app@latest --experimental-app
```

It automatically install tailwindcss, postcss, autoprefixer etc.

## My environment

* [Volta](https://github.com/volta-cli/volta/releases)

```
> volta list
⚡️ Currently active tools:

    Node: v18.16.0 (default)
    npm: v9.6.4 (default)
    Yarn: v4.0.0-rc.36 (default)
    Tool binaries available:
        vue (default)
```

## My Reference links

* [新しいNext.jsの入門 ─ App DirectoryによるWeb開発をハンズオンで理解しよう](https://eh-career.com/engineerhub/entry/2023/04/18/093000)
  * [nextjs-app-directory-demo](https://github.com/Tim0401/nextjs-app-directory-demo)
* [ts-node で TypeScript + node をサクッと実行する](https://qiita.com/mangano-ito/items/75e65071c9c482ddc335)
* [Next 13 App Router (beta) docs](https://beta.nextjs.org/docs/getting-started)
* [SWR - データ取得のための React Hooks ライブラリ](https://swr.vercel.app/ja)
  * [SWRを使おうぜという話2022](https://zenn.dev/mast1ff/articles/5b48a87242f9f0)
  * メモ: Vue は [Kong/swrv](https://docs-swrv.netlify.app/) ⇒ [両方使ってわかった Vercel/SWR と Kong/swrv の違い](https://zenn.dev/visasq/articles/difference-between-swr-and-swrv)

***

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

[http://localhost:3000/api/hello](http://localhost:3000/api/hello) is an endpoint that uses [Route Handlers](https://beta.nextjs.org/docs/routing/route-handlers). This endpoint can be edited in `app/api/hello/route.ts`.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
