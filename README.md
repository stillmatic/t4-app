<p align="center">
  <a href="https://t4stack.com" target="_blank" rel="noopener noreferrer">
    <picture>
      <img src="https://github.com/timothymiller/t4-app/blob/main/apps/next/public/t4-logo-large.png?raw=true" width="200" alt="Logo of Create T4 App">
    </picture>
  </a>
</p>

<h1 align="center">
  create-t4-app
</h1>

<p align="center">
  Interactive CLI to start a full-stack, typesafe, universal Expo & Next.js app on Cloudflare's edge platform.
</p>

<p align="center">
  Get started with the <a rel="noopener noreferrer" target="_blank" href="https://t4stack.com">T4 Stack</a> by running <code>yarn create t4-app@latest</code>
</p>

<p align="center">
  <a href = "https://discord.gg/U7AsdbSS">
    <img src="https://img.shields.io/discord/1117289587472081016?color=%235865F2&label=Discord&logo=discord&logoColor=%23fff" alt="Join the T4 discord community">
  </a>
  <a href = "https://www.npmjs.com/package/create-t4-app">
    <img src="https://img.shields.io/npm/dw/create-t4-app" alt="Weekly downloads for create-t4-app on npmjs.org">
  </a>
  <a href = "https://www.npmjs.com/package/create-t4-app">
    <img src="https://img.shields.io/npm/v/create-t4-app" alt="View create-t4-app on npmjs.org">
  </a>
</p>

## 🍔 The T4 Stack

The T4 Stack is a universal web and native stack made by [Tim Miller](https://twitter.com/ogtimothymiller) focused on **developer experience**, **rapid development**, and **performance**.

Easy integration with **Cloudflare** services, such as R2 & D1 enable developers to build apps with **AI-powered features** at a **lower cost** compared to AWS.

<p align="center">
  <picture>
    <img src="https://img.shields.io/badge/Cloudflare%20Pages-F38020?style=for-the-badge&logo=Cloudflare%20Pages&logoColor=white" alt="T4 is compatible with Cloudflare Pages">
  </picture>
  <picture>
    <img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="T4 uses Next.js">
  </picture>
  <picture>
    <img src="https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white" alt="T4 uses Expo">
  </picture>
  <picture>
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="T4 is written in TypeScript">
  </picture>
</p>

### 📐 UI Kit

- 🎨 [Tamagui](https://tamagui.dev)

### 📡 Data Fetching

- 🔄 [tRPC](https://trpc.io)
- ⏲️ [Tanstack Query](https://tanstack.com/query/latest)

### 🔮 Frontend

- 🔗 [Next.js](https://nextjs.org)
- 📱 [Expo](https://expo.io)

### Navigation

- ☀️ [Solito](https://solito.dev)

### Global State Management

- 🧩 [Jotai](https://jotai.org)

### ⚙️ Backend

- 🔥 [Hono](https://hono.dev)
- 💚 [Cloudflare Workers](https://workers.cloudflare.com)
- 📁 [Cloudflare D1](http://d1.cloudflare.com)
  - [SQLite](<(https://sqlite.org)>) database for the edge
- 🗄️ [Drizzle](https://drizzle.dev)

### 🔒 Authentication

- 🔑 [Clerk](https://clerk.dev)

## 📖 Background

T4 is a project starter kit for building **type-safe**, **native** & **web** applications in TypeScript using Tamagui, tRPC, and Turborepo. Deploy to Cloudflare for a global edge network. All at a fraction of the cost of AWS, Vercel, or Azure.

It provides a unified, opinionated, & minimalistic setup for quickly getting started with building native & web apps, using the same code, without having to worry about the complexities of setting up a development environment.

### 💪 Build Apps for All Platforms

- 📱 iOS
- 🤖 Android
- 🕸️ Web
  - Progressive Web App (PWA) support
  - 💻 macOS
  - 🪟 Windows
  - 🐧 Linux

Build native apps for iOS, Android, macOS, Windows, and Linux using the same codebase.

#### Never worry about using XCode or Android Studio again.

<p align="center">
  <picture>
    <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white" alt="Android Studio">
  </picture>
  <picture>
    <img src="https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white" alt="XCode">
  </picture>
</p>

## ❓ Why T4?

- Small learning curve
- Instant feedback, rapid development
- Universal across **React Native** & **React Web**
  - [Data fetching](https://tanstack.com/query/latest)
  - [Styling](https://tamagui.dev)
  - [Authentication](https://clerk.dev)
  - [Navigation](https://solito.dev)
- High code re-use
- Low bundle size
- Edge compatible
- Fast startup time
- Simple setup
- Allows for platform-specific code when needed.
- Type-safety

## 📦 What's Included

- [Tamagui](https://tamagui.dev) - A UI kit for building beautiful and responsive user interfaces.
- [Turborepo](https://turbo.build/) - A high performance build system for TypeScript, built in Rust.
- [tRPC](https://trpc.io) - A TypeScript framework for building end-to-end typesafe APIs.
- [TypeScript](https://www.typescriptlang.org) - A typed superset of JavaScript that compiles to plain JavaScript.

## 🚀 Quick Start

> Yarn v3 is required to use `create-t4-app`

<p align="left">
  <picture>
    <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white" alt="Yarn is required to use `create-t4-app`">
  </picture>
</p>

To scaffold an app using `create-t4-app`, run any of the following commands.

### **yarn**

```bash
yarn create t4-app
```

👉 Further documentation can be found on the [T4 Stack website](https://t4stack.com). 👈

## ✨ Features

- ✅ Uses Next.js for building web apps.
- ✅ Uses Expo for building native mobile apps.
- ✅ PWA by default for native desktop support. No Electron required.
- ✅ Tamagui UI kit across all platforms.
- ✅ Uses Cloudflare Workers for serverless functions.
- ✅ No Docker containers required.
- ✅ Uses tRPC & Tanstack Query for fetching & caching across all platforms.
- ✅ Authentication across all platforms.
- ✅ Powered by TypeScript for type safety and better developer experience.
- ✅ Comes with pre-configured ESLint and Prettier for code consistency.

## ⭐ Wish List

I would like to add the following features to `create-t4-app` in the future:

- [ ] Github Action publishing for Expo apps
- ✅ Database migration in CI/CD
- [ ] GraphQL (type-safe) data fetching
  - ⏲️ [GQty](https://gqty.dev) - A No-GraphQL client for TypeScript.
  - 🔄 [Garph](https://garph.dev) - Fullstack GraphQL Framework for TypeScript
- [ ] Supabase Auth
- [ ] Firebase Auth
- [ ] PNPM support
- [ ] 📚 [Storybook](https://storybook.js.org) support
- [ ] 🖌️ [Chromatic](https://chromatic.com) support

## 💬 Community

For help, discussion about best practices, or any other conversation that would benefit `create-t4-app`:

[Join the T4 Discord Server](https://discord.gg/U7AsdbSS)

## 🫶 Contributors

We welcome contributions from anyone and everyone. Please read our [contributing guidelines](https://github.com/timothymiller/t4-app/blob/main/CONTRIBUTING.md) for more information on how to get started.

## 👏 Special Thanks

- [Cloudflare Developers](https://twitter.com/CloudflareDev)
- [Shopify Developers](https://twitter.com/ShopifyDevs)
- [Drizzle Developers](https://twitter.com/DrizzleOrm)
- [Yusuke Wada](https://twitter.com/yusukebe) - Creator of Hono.js
- [Tanner Linsley](https://twitter.com/tannerlinsley) - Creator of TanStack
- [Nate Birdman](https://twitter.com/natebirdman) - Creator of Tamagui
- [Tim Neutkens](https://twitter.com/timneutkens) - Co-author of Next.js
- [Guillermo Rauch](https://twitter.com/rauchg) - Co-author of Next.js
- [Fernando Rojo](https://twitter.com/fernandotherojo) - Creator of Solito
- [Daishi Kato](https://twitter.com/dai_shi) Creator of Jotai
- [Jared Palmer](https://twitter.com/jaredpalmer) - Creator of Turborepo
- [Evan Bacon](https://twitter.com/evanbacon) - Maintainer of Expo

## ⚖️ License

**Create T4 App** is licensed under the [Apache License](https://github.com/timothymiller/t4-app/blob/main/LICENSE).
