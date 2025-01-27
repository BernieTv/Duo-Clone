# 🌟 Duolingo Clone Built with Next.js, React, Drizzle, and Stripe 🚀

A fun, gamified language-learning platform inspired by Duolingo, built with modern technologies to provide an immersive experience. This project leverages AI voices, gamification features, and a robust backend system to help users learn new languages while having fun. 🎉📚

---

### 📋 **Table of Contents** 🔗

1. [Project Description](#project-description) 📝
2. [Tech Stack](#tech-stack) 💻
3. [Key Features](#key-features) ✨
4. [Prerequisites](#prerequisites) ⚙️
5. [Cloning the Repository](#cloning-the-repository) 🔥
6. [Install Packages](#install-packages) 📦
7. [Setup .env File](#setup-env-file) 🔑
8. [Setup Drizzle ORM](#setup-drizzle-orm) 🗄️
9. [Seed the App](#seed-the-app) 🌱
10. [Start the App](#start-the-app) 🚀

---

### 📝 **Project Description** 📚

This project is a Duolingo clone built using Next.js, React, Drizzle, and Stripe, offering a fully functional language-learning experience. It includes various gamification elements like hearts ❤️, points 🌟, and leaderboards 🏆, plus additional features such as AI-generated voices 🗣️ and a premium tier 💳 with Stripe for unlimited hearts 💖.

---

### 💻 **Tech Stack** 🛠️

- **Next.js 14** 🌐 - Framework for building fast, server-rendered React applications 🚀
- **React** ⚛️ - Library for building user interfaces 💻
- **DrizzleORM** 🌧️ - Lightweight ORM for database interaction 💾
- **PostgresDB (NeonDB)** 🗄️ - Database used for storing user data and progress 🔒
- **Stripe** 💳 - Payment processing for Pro Tier subscription 💰
- **Clerk** 🔐 - Authentication and user management 👤
- **ElevenLabs AI** 🧠 - AI voices for dynamic and personalized language lessons 🎙️
- **Shadcn UI** 🎨 - Component system for a modern, responsive design 🌟
- **React Admin** 🛠️ - Admin dashboard for managing the app ⚙️
- **Vercel** 🌐 - Platform for fast and reliable deployment 🌎
- **Tailwind CSS** 🪶 - Utility-first CSS framework for rapid UI development 🎨

---

### ✨ **Key Features** 🔑

- 🌐 **Next.js 14** & server actions for optimal performance 🚀
- 🗣️ **AI Voices** powered by ElevenLabs AI for dynamic language learning 🧠
- 🎨 **Beautiful Component System** using Shadcn UI for seamless UI/UX ✨
- 🎭 **Amazing Characters** designed by KenneyNL for an engaging experience 👾
- 🔐 **Authentication** via Clerk for secure sign-in and user management 🔑
- 🔊 **Sound Effects** to enhance the learning atmosphere 🎧
- ❤️ **Hearts System** for in-game challenges and progression 💖
- 🌟 **Points / XP System** to track and motivate user progress 📈
- 💔 **No Hearts Left Popup** when hearts run out, creating urgency ⏳
- 🚪 **Exit Confirmation Popup** to prevent accidental exits ⚠️
- 🔄 **Practice Old Lessons** to regain hearts and keep progressing 💪
- 🏆 **Leaderboard** to encourage friendly competition 🥇
- 🗺️ **Quests Milestones** for a gamified learning experience 🛤️
- 🛍️ **Shop System** to exchange points for hearts 💰
- 💳 **Pro Tier** unlocking unlimited hearts with Stripe for premium access 💎
- 🏠 **Landing Page** for easy navigation and access 🧭
- 📊 **Admin Dashboard** powered by React Admin for smooth management 🧑‍💼
- 🌧️ **ORM Integration** using DrizzleORM for database handling 🔄
- 💾 **PostgresDB** via NeonDB for robust data storage 🗃️
- 🚀 **Deployment** on Vercel for fast and reliable hosting 🌎
- 📱 **Mobile Responsiveness** ensuring accessibility on all devices 📲

---

### ⚙️ **Prerequisites** 🛠️

Ensure you have **Node version 14.x** installed on your system. 💻🔧

---

### 🔥 **Cloning the Repository** 💾

To clone the repository, run the following command:

```shell
git clone https://github.com/BernieTv/Duo-clone.git
```

---

### 📦 **Install Packages** 🧩

Install the required packages using npm:

```shell
npm i
```

---

### 🔑 **Setup .env File** 🔒

Create your `.env` file and configure the following environment variables:

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
CLERK_SECRET_KEY=""
DATABASE_URL="postgresql://..."
STRIPE_API_KEY=""
NEXT_PUBLIC_APP_URL="http://localhost:3000"
STRIPE_WEBHOOK_SECRET=""
```

---

### 🗄️ **Setup Drizzle ORM** 🌧️

To set up the database schema, run:

```shell
npm run db:push
```

---

### 🌱 **Seed the App** 🌾

To seed the application with data, run:

```shell
npm run db:seed
```

Or for production setup:

```shell
npm run db:prod
```

---

### 🚀 **Start the App** 🎉

To run the app in development mode, execute:

```shell
npm run dev
```
