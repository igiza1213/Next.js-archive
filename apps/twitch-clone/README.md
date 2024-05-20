This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

env

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_ZXhjaXRlZC1tb2xseS03Ni5jbGVyay5hY2NvdW50cy5kZXYk
CLERK_SECRET_KEY=sk_test_t8FcxoNwC244yAa7N9ymBTi8PLLL2tGhlF0jNdpuyV
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
DATABASE_URL="postgres://postgres.prerdxontofjgcacunip:X69LxIWgegujwA4B@aws-0-ap-northeast-2.pooler.supabase.com:6543/postgres?pgbouncer=true"
DIRECT_URL="postgres://postgres.prerdxontofjgcacunip:X69LxIWgegujwA4B@aws-0-ap-northeast-2.pooler.supabase.com:5432/postgres"
NEXT_PUBLIC_SUPABASE_URL=https://prerdxontofjgcacunip.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InByZXJkeG9udG9mamdjYWN1bmlwIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MTYxODU3ODksImV4cCI6MjAzMTc2MTc4OX0.sQj74bnmm7rcw0Ng9PPgrNG7AIdmXjRLF6P5amoEzGU
```
