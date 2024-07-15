<h1>MyFood - The Food Delivery App</h1>

<p>
<b>MyFood</b> is a streamlined food delivery app designed to connect hungry customers with their favorite local restaurants. Whether you're craving a quick bite or planning a family feast, <b>MyFood</b> brings a diverse selection of cuisines right to your doorstep. With an easy-to-use interface and essential features, our app ensures a seamless and delightful food ordering experience
</p>

## Overview

This is a starter template using the following stack:

- Framework - [Next.js 14](https://nextjs.org/)
- Language - [TypeScript](https://www.typescriptlang.org)
- Auth - [Auth.js](https://authjs.dev)
- ORM - [Drizzle ORM](https://orm.drizzle.team/learn)
- Database - [Postgres](https://vercel.com/postgres)
- Deployment - [Vercel](https://vercel.com/docs/concepts/next.js/overview)
- Styling - [Tailwind CSS](https://tailwindcss.com)
- Components - [Shadcn UI](https://ui.shadcn.com/)
- Formatting - [Prettier](https://prettier.io)

## Local Development setup

create `.env` file the project root directory with the below variables

```
POSTGRES_URL=<Add value>
POSTGRES_USER=<Add value>
POSTGRES_HOST=<Add value>
POSTGRES_PASSWORD=<Add value>
POSTGRES_DATABASE=<Add value>

NEXTAUTH_URL=http://localhost:3000
AUTH_SECRET=shSzZzF9x0PSJaE1dkj7F7jdRjE13qYtZ+G03NmAHzxq7Jbs6v6hE5Ykre0EcQLI
```

Finally, run the following commands to start the development server:

```
pnpm install
pnpm dev
```

You should now be able to access the application at http://localhost:3000.
