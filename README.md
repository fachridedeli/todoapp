This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

ini adalah fullstack todo-app, menggunakan create-next-app@14, drizzleorm, tailwindcss.

Pertama, install postgresql dan buat database lalu configurasi di file .env sesuai nama database nya.

Kedua, buat schema dengan menjalankan perintah berikut:

```bash
npx drizzle-kit push:pg
```

Ketiga, jalankan web app nya di development mode:

```bash
npm run dev
```

Buka [http://localhost:3000](http://localhost:3000) menggunakan browser anda
