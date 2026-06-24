<a name="readme-top"></a>

# TogetherHub - Modern Video Collaboration Platform

A modern video collaboration platform built with Next.js 15, React 19, Clerk Authentication, and Stream Video SDK. TogetherHub enables users to securely create, schedule, join, and manage online meetings with an intuitive and responsive interface.

## 🌐 Live Demo

https://zoom-clone-main-av2m.vercel.app/

## 📂 Repository

https://github.com/Kiran111L/Zoom-clone-Main

---

## ✨ Features

- Secure Authentication using Clerk
- Instant Video Meetings
- Schedule Future Meetings
- Personal Meeting Room
- Meeting History
- Meeting Recordings
- Responsive UI
- Google Sign-In
- Stream Video SDK Integration
- Modern Next.js App Router Architecture

---

## 🛠 Tech Stack

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- Clerk Authentication
- Stream Video SDK
- Radix UI
- Vercel

---

## 🚀 Live Website

https://zoom-clone-main-av2m.vercel.app/

---

## 📁 Folder Structure
</details>

## :bangbang: Folder Structure

Here is the folder structure of this app.

<!--- FOLDER_STRUCTURE_START --->
```bash
zoom-clone/
  |- actions/
    |-- stream.actions.ts
  |- app/
    |-- (auth)/
    |-- (root)/
    |-- apple-icon.png
    |-- favicon.ico
    |-- globals.css
    |-- icon1.png
    |-- icon2.png
    |-- layout.tsx
  |- components/
    |-- modals/
    |-- ui/
    |-- call-list.tsx
    |-- end-call-button.tsx
    |-- home-card.tsx
    |-- loader.tsx
    |-- meeting-card.tsx
    |-- meeting-room.tsx
    |-- meeting-setup.tsx
    |-- meeting-type-list.tsx
    |-- mobile-nav.tsx
    |-- navbar.tsx
    |-- sidebar.tsx
  |- config/
    |-- index.ts
  |- constants/
    |-- index.ts
  |- hooks/
    |-- use-get-call-by-id.ts
    |-- use-get-calls.ts
  |- lib/
    |-- utils.ts
  |- providers/
    |-- stream-client-provider.tsx
  |- public/
  |- types/
    |-- styles.d.ts
  |- .env.example
  |- .env/.env.local
  |- .eslintrc.json
  |- .gitignore
  |- .prettierrc.json
  |- bun.lockb
  |- components.json
  |- environment.d.ts
  |- middleware.ts
  |- netlify.toml
  |- next.config.mjs
  |- package-lock.json
  |- package.json
  |- postcss.config.mjs
  |- tsconfig.json
```
<!--- FOLDER_STRUCTURE_END --->

<br />

## :toolbox: Getting Started

1. Make sure **Git** and **NodeJS** is installed.
2. Clone this repository to your local computer.
3. Create `.env.local` file in **root** directory.
4. Contents of `.env.local`:

```env
# .env.local
