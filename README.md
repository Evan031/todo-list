This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

Run

```npx prisma init --datasource-provider postgresql```

// Create schema 
Go to schema.prisma

All this can be seen here:
[https://www.prisma.io/docs/getting-started/quickstart](Prisma Docs)

// How you migrate your changes to your DB
```npx prisma migrate dev --name init```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


