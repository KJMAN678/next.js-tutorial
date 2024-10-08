## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

```sh
# インストール
pnpm install

# ローカルサーバーの立ち上げ
pnpm dev

http://localhost:3000/seed

# DB初期データ作成(.env ファイルの設定必要)
pnpm run dev
```

- 下記の２つのファイルは除いた
  - [app/lib/placeholder-data.ts](https://github.com/vercel/next-learn/blob/main/dashboard/final-example/app/lib/placeholder-data.ts)
  - [app/seed/route.ts](https://github.com/vercel/next-learn/blob/main/dashboard/final-example/app/seed/route.ts)

### Local Server

- [/](http://localhost:3000/)
  - [/dashboard](http://localhost:3000/dashboard)
    - [/dashboard/customers](http://localhost:3000/dashboard/customers)
    - [/dashboard/invoices](http://localhost:3000/dashboard/invoices)

### Vercel
- [/](https://next-js-tutorial-mu-dusky.vercel.app/)
  - [/dashboard](https://next-js-tutorial-mu-dusky.vercel.app/dashboard)
    - [/dashboard/customers](https://next-js-tutorial-mu-dusky.vercel.app/dashboard/customers)
    - [/dashboard/invoices](https://next-js-tutorial-mu-dusky.vercel.app/dashboard/invoices)
