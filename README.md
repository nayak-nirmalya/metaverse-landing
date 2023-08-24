# Metaversus Landing with Next.js 13, React, Tailwind & Framer Motion.

Features:

- Tailwind design
- Full responsiveness
- Beautiful Design
- Awesome Animation

Credits: [Antonio Erdeljac](https://github.com/adrianhajdin)

### Prerequisites

**Node version 18.x.x**

### Cloning the Repository

```shell
git clone https://github.com/nayak-nirmalya/ai-companion.git
```

### Install Packages

```shell
npm i
```

### Setup .env File

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

PINECONE_INDEX=
PINECONE_ENVIRONMENT=
PINECONE_API_KEY=

UPSTASH_REDIS_REST_URL=
UPSTASH_REDIS_REST_TOKEN=

OPENAI_API_KEY=

REPLICATE_API_TOKEN=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_APP_URL=
```

### Setup Prisma

Add MySQL Database URL in .env file, then run:

```shell
npx prisma db push
```

Seed Categories to DB:

```shell
node scripts/seed.ts
```

### Start the App

```shell
npm run dev
```

## Available Commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
| `lint`  | Run lint check                           |
| `build` | Start building app for deployment        |
| `start` | Run build version of app                 |
