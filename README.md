# Pedlar e-Commerce Store + Admin App

**Serverless e-Commerce Store with Multivendor Admin App**

> Deployed:
>
> - **e-commerce Store**: [pedlar.sarthak.app](https://pedlar.sarthak.app)
> - **Admin App**: [admin.pedlar.sarthak.app](https://admin.pedlar.sarthak.app)
>   - demo user email: `demo@sarthak.app`
>   - demo user's password: `demopass`
>
> _use the ☝️above demo user data to checkout the application_

### Core Features:

#### Admin App

- 🌟 Multivendor Admin App
- Dashboard
- Stripe link
- Database connect
- Order management
- sync with store

#### Store

- Products Page
- Featured Route
- Filters
- Image optimisaion from NextJS `Image` componets
- Server Componets
- app router

---

### Tech Stack

- NextJS 13
- Typescript
- Tailwind CSS
- Plnetscale
- Clerk Authentication
- Stripe

---

### Package Install

```shell
npm install
```

### Setting up the `.env` file

```js
# clerk-api
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard
```

```
DATABASE_URL=
```

```
STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=
```

```
NEXT_PUBLIC_APP_URL="http://localhost:3000"
```

### Setup Prisma

- use `Prisma` with any Platform you want.

### Starting both the apps

- in their respective directories:⏬

```shell
npm run dev
```

---

[-- Sarthak Mohanty](https://sarthak.app)
