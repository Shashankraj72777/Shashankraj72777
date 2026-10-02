<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./light.svg">
  <img src="./dark.svg" alt="Shashank Raj — Full Stack Engineer" width="100%">
</picture>

<br>

<h1>Shashank Raj</h1>

<h3>Full Stack Engineer · React · Next.js · Node.js · TypeScript · PostgreSQL</h3>

<p>
  Building production-ready full-stack applications with a focus on backend systems,
  API performance, real-time applications, and scalable architecture.
</p>

<p>
  <a href="https://portfolio-iota-eight-coskywto4u.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/shashankraj72777/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/Shashankraj72777">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://leetcode.com/u/shashankraj72777/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode">
  </a>
</p>

<p>
  <a href="mailto:shashankraj72777@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

</div>

---

## 👋 About Me

I'm a **Full Stack Engineer** with **1+ year of production experience** building React/Next.js frontends and Node.js/PostgreSQL backends.

My engineering work focuses on:

- Building production-ready full-stack applications
- Backend APIs and performance optimization
- Real-time applications
- Microservices and event-driven systems
- Authentication and role-based access control
- PostgreSQL and Redis
- CI/CD and containerized deployments
- AI-powered applications using LLM APIs

I've shipped **10+ production features**, improved API response times by approximately **40%**, implemented JWT/RBAC across **5+ roles**, built **3 live full-stack projects**, and solved **200+ LeetCode problems in C++**.

> **Build. Optimize. Ship.**

---

## ⚡ Engineering Focus

<div align="center">

| Area | Focus |
|---|---|
| 🚀 Full Stack | React.js · Next.js · Node.js |
| ⚙️ Backend | Express.js · REST APIs · Microservices |
| ⚡ Real-Time | Socket.IO · Redis |
| 📨 Distributed Systems | RabbitMQ · Event-Driven Architecture |
| 🗄️ Data | PostgreSQL · Redis · Supabase |
| 🔐 Security | JWT · RBAC |
| 🐳 DevOps | Docker · GitHub Actions · CI/CD |
| 🤖 AI | LLM APIs · Prompt Engineering |

</div>

---

# 🛠️ Technical Stack

### 💻 Languages

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,cpp" alt="TypeScript JavaScript C++">
</p>

`TypeScript` · `JavaScript` · `SQL` · `C++`

### 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind" alt="React Next.js Tailwind CSS">
</p>

`React.js` · `Next.js` · `Tailwind CSS`

### ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express" alt="Node.js Express">
</p>

`Node.js` · `Express.js` · `REST APIs` · `Socket.IO` · `Microservices` · `RabbitMQ` · `JWT` · `RBAC`

### 🗄️ Databases

<p>
  <img src="https://skillicons.dev/icons?i=postgres,redis" alt="PostgreSQL Redis">
</p>

`PostgreSQL` · `Redis` · `Supabase`

### 🐳 DevOps

<p>
  <img src="https://skillicons.dev/icons?i=docker,git,githubactions" alt="Docker Git GitHub Actions">
</p>

`Docker` · `Git` · `GitHub Actions` · `CI/CD`

### 🤖 AI / Cloud

`LLM APIs` · `Prompt Engineering` · `Vercel` · `Render`

---

# 🚀 Featured Projects

## 🤖 AI Mock Interview Platform

<a href="https://github.com/Shashankraj72777/ai-mock-interview">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code">
</a>
<a href="https://ai-mock-interview-eight-blond.vercel.app/">
  <img src="https://img.shields.io/badge/Live%20Demo-58A6FF?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo">
</a>

AI-powered real-time mock interview platform supporting interview flows across **30 engineering roles**.

### Key Features

- Real-time interview sessions using **Socket.IO**
- In-browser **Monaco code editor**
- Redis-backed live-session state
- PostgreSQL checkpoints for session recovery
- Integrated multiple LLM providers
- Built with Next.js and TypeScript
- Deployed using Vercel, Render, and Upstash

### Technology

`Next.js` · `TypeScript` · `Node.js` · `Socket.IO` · `PostgreSQL` · `Redis` · `LLM APIs` · `Vercel` · `Render` · `Upstash`

### Architecture

```text
┌─────────────────────────────┐
│         Next.js UI          │
│     Interview Platform      │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│         Socket.IO            │
│       Real-Time Layer        │
└──────────────┬──────────────┘
               │
        ┌──────┴──────┐
        ▼             ▼
┌─────────────┐ ┌─────────────┐
│    Redis    │ │ PostgreSQL  │
│ Live Session│ │ Checkpoints │
│    State    │ │             │
└──────┬──────┘ └──────┬──────┘
       │                │
       └───────┬────────┘
               ▼
       ┌───────────────┐
       │    LLM APIs   │
       │ AI Interviewer│
       └───────────────┘
```

---

## ⚙️ Scalr — Distributed Order System

<a href="https://github.com/Shashankraj72777/scalr-distributed-order-system">
  <img src="https://img.shields.io/badge/Source%20Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code">
</a>

Distributed order system built around microservices, asynchronous messaging, caching, PostgreSQL, and containerized development.

### Key Features

- Microservice-based architecture
- RabbitMQ event-driven communication
- Retry and dead-letter queue handling
- Redis caching with database fallback
- PostgreSQL persistence
- Docker Compose for local development

### Technology

`Node.js` · `TypeScript` · `PostgreSQL` · `Redis` · `RabbitMQ` · `Docker`

### Architecture

```text
                  ┌──────────────────┐
                  │    API Gateway   │
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │     RabbitMQ     │
                  │  Event Messaging │
                  └────────┬─────────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
   ┌────────────┐   ┌────────────┐   ┌────────────┐
   │    Auth    │   │    User    │   │   Order    │
   │   Service  │   │   Service  │   │   Service  │
   └────────────┘   └────────────┘   └─────┬──────┘
                                           │
                                           ▼
                                  ┌────────────────┐
                                  │   Notification │
                                  │    Service     │
                                  └───────┬────────┘
                                          │
                         ┌────────────────┴──────────────┐
                         ▼                               ▼
                  ┌─────────────┐                ┌─────────────┐
                  │ PostgreSQL  │                │    Redis    │
                  │   Database  │                │    Cache    │
                  └─────────────┘                └─────────────┘
```

---

## 💰 TrackMint — AI-Assisted Expense Dashboard

`Next.js 15` · `TypeScript` · `Supabase` · `PostgreSQL` · `OpenAI/Gemini` · `Tailwind CSS`

A responsive expense dashboard with dark/light themes and secure per-user data isolation.

### Key Features

- Dark/light themed responsive UI
- Skeleton loading states
- Supabase authentication
- PostgreSQL Row-Level Security
- Secure CRUD operations
- Month-over-month calculations
- Category aggregation
- Composite-indexed queries
- Next.js Server Components and Actions
- Targeted cache invalidation

---

# 💼 Professional Experience

## Junior Full Stack Developer

### R2VFX Studios Pvt. Ltd.

**Jul 2025 – Sep 2026 · Remote**

```text
React.js / Next.js
        ↓
Node.js / Express.js
        ↓
PostgreSQL / Redis
        ↓
JWT / RBAC
        ↓
Docker / GitHub Actions / CI/CD
```

### Engineering Impact

- Built reusable React/Next.js UI components and internal dashboards.
- Shipped **10+ production features** across React/Next.js and Node.js/Express.
- Reduced reported bugs by approximately **30%**.
- Reduced API response times by approximately **40%** on high-traffic endpoints.
- Added PostgreSQL indexes and eliminated N+1 query patterns.
- Implemented JWT authentication and RBAC for **5+ user roles**.
- Maintained GitHub Actions CI/CD pipelines for production deployments.
- Credited as part of the R2VFX Studios technology team on **Dhurandhar 2 (2026)**.

---

## Cloud Research Analyst Intern — Software Development

### CLARCHS.com

**Jan 2025 – Apr 2025 · Remote**

### Engineering Impact

- Built **8+ reusable React/Next.js components**.
- Integrated **4 REST APIs**.
- Reduced duplicate frontend code by approximately **25%**.
- Improved page responsiveness by approximately **20%**.

---

# 🧠 Data Structures & Algorithms

<p align="center">

<a href="https://leetcode.com/u/shashankraj72777/">
  <img src="https://img.shields.io/badge/LeetCode-200%2B%20Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode 200+">
</a>

</p>

I regularly practice **Data Structures & Algorithms using C++**.

```text
Arrays
Trees
Graphs
Dynamic Programming
Binary Search
```

```cpp
while (learning) {
    solve();
    analyze();
    optimize();
    repeat();
}
```

---

# 🎓 Education

<div align="center">

### Chandigarh University, Mohali

**B.Tech in Computer Science Engineering — AI & ML**

`2021 – 2025`

**CGPA: 7.91 / 10**

</div>

---

# 📊 Engineering Highlights

<div align="center">

| Metric | Impact |
|---|---|
| 🚀 **10+** | Production features shipped |
| ⚡ **~40%** | API response-time improvement |
| 🐞 **~30%** | Reduction in reported bugs |
| 🔐 **5+** | RBAC roles |
| 🧩 **8+** | Reusable React/Next.js components |
| 🔌 **4** | REST API integrations |
| 🚀 **3** | Live full-stack projects |
| 🧠 **200+** | LeetCode problems solved |

</div>

---

# 🎯 Current Focus

<div align="center">

`Full-Stack Development`

`Backend Engineering`

`API Performance`

`Real-Time Applications`

`Distributed Systems`

`Microservices`

`AI-Powered Applications`

`CI/CD`

</div>

---

# 📈 GitHub

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Shashankraj72777&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&rank_icon=github&theme=transparent" alt="GitHub Stats">

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shashankraj72777&layout=compact&langs_count=8&hide_border=true&theme=transparent" alt="Top Languages">

<br><br>

<img src="https://streak-stats.demolab.com?user=Shashankraj72777&hide_border=true&theme=transparent" alt="GitHub Streak">

</div>

---

# 🌐 Connect

<div align="center">

<a href="https://portfolio-iota-eight-coskywto4u.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio">
</a>

<a href="https://www.linkedin.com/in/shashankraj72777/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>

<a href="https://github.com/Shashankraj72777">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

<a href="https://leetcode.com/u/shashankraj72777/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode">
</a>

<a href="mailto:shashankraj72777@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

<br><br>

**Open to Remote, Hybrid & Relocation opportunities within India.**

</div>

---

<div align="center">

### Build. Optimize. Ship.

⭐ Thanks for visiting my profile!

</div>
