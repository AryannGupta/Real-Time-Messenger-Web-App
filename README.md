# Real-Time Messenger Clone: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher

**Google and Github Auth are working perfectly fine now!**

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/AryannGupta/Messenger-Clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |

**Declaration:**

`This Web Application has been made with complete help from the internet just for educational purpose for my AWS Cloud Project as an intern at Ericsson, to learn, understand and implement the various components and features of AWS.This project can be easily deployed to Vercel, by adding the Environment Secrets into the deployment section.`
