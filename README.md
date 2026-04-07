```
 ___       _     _ _   ___ _
/ __| __ _| |__ (_) | |_ _(_)__ _ ___
\__ \ (_` | '_ \| | |  | || / _` |_ /
|___/\__,_|_.__/|_|_| |___|_\__,_/__|

  Full Stack Developer  ·  Next.js  ·  Node.js  ·  TypeScript
  Lahore, Pakistan  ·  hssahil2913@gmail.com  ·  @SahilIjaz
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahil-ijaz-a75b15281/)
[![Twitter](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/sahilijaz99)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hssahil2913@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E1306C?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/sahil._.mehar)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/SahilIjaz)

![Profile Views](https://komarev.com/ghpvc/?username=SahilIjaz&label=profile+views&color=0e75b6&style=flat-square)
![Status](https://img.shields.io/badge/status-open_to_work-3fb950?style=flat-square)
![Experience](https://img.shields.io/badge/experience-2%2B_years-58a6ff?style=flat-square)
![Location](https://img.shields.io/badge/location-Lahore,_PK-f0883e?style=flat-square)
![Role](https://img.shields.io/badge/role-Full_Stack_Dev-d2a8ff?style=flat-square)

</div>

---

## `$ cat developer.config.ts`

```typescript
import type { Developer } from '@types/world';

const sahil: Developer = {
  name:     "Sahil Ijaz",
  location: "Lahore, Pakistan 🇵🇰",
  started:  "2023",                   // self-taught → industry Jan 2024
  role:     "Full Stack Developer",   // since Oct 2025

  stack: {
    frontend:  ["Next.js", "React", "TypeScript", "TailwindCSS", "React Query"],
    backend:   ["Node.js", "Express.js", "NestJS", "Socket.io", "REST APIs"],
    database:  ["MongoDB", "PostgreSQL", "Prisma", "Mongoose", "Supabase"],
    cloud:     ["AWS (EC2, S3, Lambda)", "Vercel", "Firebase", "Nginx"],
    tools:     ["Git", "Postman", "Zod", "JWT", "pnpm", "Swagger"],
  },

  currentlyBuilding: "Production-grade SaaS applications",
  learning:          ["System Design", "DevOps & CI/CD", "AI integration"],
  contact:           () => "hssahil2913@gmail.com",
  available:         true,
};

export default sahil;
```

---

## `$ cat system.architecture`

```
┌─── Client Layer ──────────────────────────────────────┐
│   Next.js App Router  ·  React  ·  TailwindCSS        │
│   React Query  ·  TypeScript  ·  Zod (client)         │
└───────────────────────┬───────────────────────────────┘
                        │  HTTPS / REST / WebSocket
┌───────────────────────▼───────────────────────────────┐
│   Node.js / Express.js / NestJS                       │
│   JWT Auth  ·  Rate Limiting  ·  Zod Validation       │
│   Middleware  ·  Error Handling  ·  Swagger Docs      │
└──────────┬────────────────────────────┬───────────────┘
           │                            │
┌──────────▼──────────┐    ┌────────────▼──────────────┐
│  MongoDB / Mongoose │    │  PostgreSQL / Prisma ORM  │
│  Document store     │    │  Relational data layer    │
│  Aggregation pipes  │    │  Migrations & Relations   │
└──────────┬──────────┘    └────────────┬──────────────┘
           └────────────────────────────┘
                           │
┌──────────────────────────▼────────────────────────────┐
│  AWS  ·  Vercel  ·  Nginx  ·  Firebase  ·  Redis      │
│  EC2 · S3 · Lambda  ·  CDN  ·  CI/CD pipelines       │
└───────────────────────────────────────────────────────┘
```

---

## `$ git log --oneline --graph --all`

```
* a9f3d21 (HEAD → main, origin/main) feat: real-time notifications via Socket.io
* c82e14b refactor: migrate auth middleware to NestJS guards
* f1d7c93 fix: resolve N+1 query issue in product listings
* 3b8a047 (tag: v2.1.0) feat: Stripe webhook handler with idempotency keys
* 71e2c85 chore: Prisma migrations for multi-tenant schema design
* 90d4f31 perf: Redis caching layer — API latency reduced 40%
* 2a9c18e docs: OpenAPI/Swagger spec for all endpoints
* b7d183c test: integration tests for JWT auth flow
* 4e9c271 feat: role-based access control (RBAC) middleware
* 17fa832 (tag: v2.0.0) chore: migrate to Next.js App Router
* e3c910f feat: Socket.io rooms with presence & typing indicators
* a12b45f fix: Mongoose aggregation pipeline optimization
```

---

## `$ ls -la ~/tech-stack/`

### ⬛ Frontend
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

### ⬛ Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-404d59?style=flat-square&logo=express&logoColor=61DAFB)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io)
![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens)
![Zod](https://img.shields.io/badge/Zod-3068B7?style=flat-square&logo=zod&logoColor=white)
![Nodemon](https://img.shields.io/badge/Nodemon-323330?style=flat-square&logo=nodemon&logoColor=BBDEAD)

### ⬛ Database & ORM
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=flat-square&logo=prisma&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

### ⬛ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

---

## `$ cat experience.log`

```
[Oct 2025 → now]  Full Stack Developer ─── Industry
                  ├── Next.js App Router (SSR, SSG, ISR, API routes)
                  ├── End-to-end feature ownership: UI → API → DB → deploy
                  ├── REST API design & Swagger/OpenAPI documentation
                  ├── MongoDB + PostgreSQL — schema design & optimization
                  ├── AWS deployment — EC2, S3, Lambda, Nginx, CloudFront
                  └── Full lifecycle: spec → architecture → code → ship

[Jan 2024 → Sep 2025]  Backend Developer ─── Industry
                       ├── Node.js / Express.js — production REST API dev
                       ├── JWT auth, RBAC, session management from scratch
                       ├── Mongoose ODM, Prisma ORM, aggregation pipelines
                       ├── Socket.io real-time systems & WebSocket architecture
                       ├── Rate limiting, Zod validation, structured error handling
                       └── API versioning, security hardening & documentation

[2023]  Started the Journey ─── Self-taught
        ├── C++ & algorithms — learned to think like an engineer
        ├── HTML · CSS · JavaScript — web fundamentals
        ├── Node.js & Express.js — first backend projects
        └── Discovered backend dev, fell in love with it
```

> **Backend-first.** I spent Jan 2024 – Sep 2025 mastering the server-side craft in a real production environment before going full-stack in October 2025. That foundation makes the difference in everything I build.

---

## `$ ls -la ~/projects/ --sort=stars`

```
drwxr-xr-x  REST-API-Framework/      ★ 62   Express · Prisma · Zod · Swagger
drwxr-xr-x  SaaS-Boilerplate/        ★ 48   Next.js · Node · MongoDB · Stripe
drwxr-xr-x  Real-Time-Chat/          ★ 31   Socket.io · React · Node · MongoDB
drwxr-xr-x  E-Commerce-Platform/     ★ 27   Next.js · AWS S3 · Stripe · TS
```

### ◈ [REST API Framework](https://github.com/SahilIjaz)

> Opinionated, batteries-included Express.js API boilerplate. Rate limiting, Zod input validation, Swagger/OpenAPI docs, JWT auth middleware, Prisma ORM with PostgreSQL, structured error handling, and a modular folder architecture — production-ready from day one.

```typescript
// Typed, validated route — clean, safe, auto-documented
router.post('/users', validate(createUserSchema), async (req: ValidatedReq, res) => {
  const user = await UserService.create(req.body); // body fully typed + validated
  res.status(201).json({ success: true, data: user });
});
```

`Express.js` `TypeScript` `Prisma` `PostgreSQL` `Zod` `Swagger` `JWT` `Jest`

---

### ◈ [SaaS Boilerplate](https://github.com/SahilIjaz)

> Production-ready Next.js + Node.js starter kit. Ships with JWT auth, Stripe payments, MongoDB + Mongoose, email verification, role-based access control, and a clean admin dashboard. Go from zero to production in days.

```bash
git clone https://github.com/SahilIjaz/saas-boilerplate
cd saas-boilerplate && pnpm install
cp .env.example .env   # configure your secrets
pnpm dev               # http://localhost:3000
```

`Next.js` `Node.js` `TypeScript` `MongoDB` `Stripe` `JWT` `Nodemailer` `TailwindCSS`

---

### ◈ [Real-Time Chat App](https://github.com/SahilIjaz)

> Scalable real-time messaging platform. Private DMs, group rooms, typing indicators, presence, read receipts, and media sharing. Socket.io event architecture handles thousands of concurrent connections.

```typescript
// Typed Socket.io event handler
socket.on('message:send', async (payload: MessagePayload) => {
  const message = await MessageService.create(payload);
  io.to(payload.roomId).emit('message:received', message);
  await NotificationService.push(message);
});
```

`Socket.io` `React` `Node.js` `MongoDB` `Express.js` `TypeScript`

---

### ◈ [E-Commerce Platform](https://github.com/SahilIjaz)

> Full-featured e-commerce web app — product catalog, cart, order management, admin dashboard, Stripe checkout, AWS S3 media. Next.js App Router for performance. Built to handle real production traffic.

`Next.js` `Node.js` `MongoDB` `AWS S3` `Stripe` `TailwindCSS` `TypeScript`

---

## `$ npm run github-stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SahilIjaz&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=58a6ff&icon_color=d2a8ff&text_color=768390&ring_color=1f6feb" height="165"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SahilIjaz&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=768390" height="165"/>

<br/><br/>

<img src="https://nirzak-streak-stats.vercel.app/?user=SahilIjaz&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=1f6feb&ring=8b5cf6&fire=f0883e&currStreakLabel=58a6ff&sideLabels=768390" width="60%"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SahilIjaz&bg_color=0d1117&color=58a6ff&line=8b5cf6&point=f0883e&area=true&area_color=1f6feb&hide_border=true&custom_title=Contribution+Graph" width="100%"/>

</div>

---

## `$ cat trophies.json`

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=SahilIjaz&theme=algolia&no-frame=true&no-bg=true&row=1&column=7&margin-w=4"/>
</div>

---

## `$ cat philosophy.md`

```markdown
# Engineering principles

1. Backend-first mindset — I understand what happens server-side deeply.
   That foundation makes me a better full-stack developer, not just a faster one.

2. Architecture before features — clean foundations are cheaper than refactors.
   A well-designed system is easier to extend than a fast one that's broken.

3. Document everything — an undocumented API is an incomplete API.
   Swagger specs, README files, and inline comments are first-class deliverables.

4. Security by default — auth, validation, rate limiting, input sanitization.
   These are not added at the end. They are designed in from day one.

5. Ship, then iterate — working software beats perfect software that never ships.
   Get to production, collect real feedback, improve in the open.

6. Types everywhere — TypeScript is how we communicate intent across a codebase.
   Untyped code is undocumented code with extra steps.

7. Always be learning — the ecosystem moves fast.
   Investing in fundamentals, not just frameworks, is how you stay relevant.
```

---

## `$ contact --open-to-work`

```bash
# Currently open to:
#   Full-time remote roles (full stack / backend-focused)
#   Freelance & contract projects
#   Open source collaborations
#   Technical discussions & coffee chats

curl -X POST https://api.sahil.dev/contact \
  -H "Content-Type: application/json" \
  -d '{
    "from":    "your@email.com",
    "subject": "Let'\''s work together",
    "message": "Hi Sahil..."
  }'

# Or just email directly:
echo "hssahil2913@gmail.com"
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sahil-ijaz-a75b15281/)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hssahil2913@gmail.com)
[![Twitter](https://img.shields.io/badge/Follow_on_X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/sahilijaz99)

</div>

---

<div align="center">

```bash
sahil@dev:~/portfolio $ echo "thanks for visiting — let's build something great"
thanks for visiting — let's build something great
sahil@dev:~/portfolio $ █
```

*© 2025 Sahil Ijaz · Lahore, Pakistan*

</div>
