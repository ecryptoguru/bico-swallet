## Smart Wallet based on Account Abstraction

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

## using biconomy dependencies

Have created a Full-stack Smart Wallet using Nextjs 13, Tailwind and Typescript.
Account abstraction technology has been used using biconomy paymaster and bundlers and the project has been deployed on Polygon Mumbai.

Have implemented two things
1-Social login
2-Sending ERC20 tokens using ERC20(without paying gas in matic)

Currently configured for transfering USDC

npm run dev