# Next.js Creative Portfolio Tutorial: Build Amazing Portfolio Website with Next.js, Three.js, and Tailwind CSS 🔥

![GitHub stars](https://img.shields.io/github/stars/codebucks27/Next.js-Creative-Portfolio-Website?style=social&logo=ApacheSpark&label=Stars)&nbsp;&nbsp;
![GitHub forks](https://img.shields.io/github/forks/codebucks27/Next.js-Creative-Portfolio-Website?style=social&logo=KashFlow&maxAge=3600)&nbsp;&nbsp;
![Github Followers](https://img.shields.io/github/followers/codebucks27.svg?style=social&label=Follow)&nbsp;&nbsp;<br />

This repository contains **final code** for Next.js Creative Portfolio website built using Next.js and Three.js. <br />

For Demo checkout following link👇: <br />
[Nextjs Creative Portfolio Website Demo](https://next-js-creative-portfolio-website.vercel.app/) <br />

---


---

Starter Code Files👇: <br />
➡ Link 💚: [Nextjs Creative Portfolio Website Starter Code](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files) <br />
<!--- ➡ Link 2💚(If you want to support): [Nextjs Creative Portfolio Website Final Code](https://codebucks.gumroad.com/l/ypzlu) <br /> --->

If you want to learn how to create it please follow below tutorial👇: <br />
➡ Tutorial Link 💚: [Personal Portfolio Website with Next.js, Three.js & Tailwind CSS Tutorial](https://youtu.be/T5t46vuW8fo) 
[![YouTube Video Views](https://img.shields.io/youtube/views/T5t46vuW8fo
)](https://youtu.be/T5t46vuW8fo) <br />

💚 Checkout my personal website [DevDreaming](https://devdreaming.com) <br />

---
# ⭐DO NOT FORGET TO STAR THIS REPO⭐
---

## Images of The Portfolio Website:

#### Home
![Nextjs Creative Portfolio Website](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/Home-desktop.png)

#### About
![Nextjs Creative Portfolio Website About Page](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/About-desktop-full.png)

#### Projects
![Next.js Creative Portfolio Website Projects Page](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/Projects-desktop.png)

#### Contact
![Next.js Creative Portfolio Website Contact Page](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/Contact-desktop.png)

#### Mobile Version
![Next.js Creative Portfolio Website Contact Page](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/Home-mobile.png)
![Next.js Creative Portfolio Website Contact Page](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/About-mobile.png)
![Next.js Creative Portfolio Website Contact Page](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/Projects-mobile.png)
![Next.js Creative Portfolio Website Contact Page](https://github.com/codebucks27/Nextjs-Creative-Portfolio-Starter-Code-Files/blob/main/website%20images/Contact-mobile.png)

## Resources Used in This Project

#### 3D Models

- ["Tim Mckee - Boy Wizard"](https://skfb.ly/6YATu) by [elbertwithane is licensed under Creative Commons Attribution ](http://creativecommons.org/licenses/by/4.0/).
- ["Stylized wizard hat"](https://skfb.ly/ozxOQ) by [Enkarra is licensed under Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
- ["Wizard Staff"](https://skfb.ly/6QYZw) by [Toymancer Studio is licensed under Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).

#### AI Images

- Created with the help of [Playground AI](https://playgroundai.com/)

#### Github Stats & Details

- [Github ReadMe Stats](https://github.com/anuraghazra/github-readme-stats)
- [Skills Icons](https://github.com/tandpfun/skill-icons)
- [Github Readme Streak Stats](https://github.com/denvercoder1/github-readme-streak-stats)

#### Development Resources

- Fonts from [Google Fonts](https://fonts.google.com/) <br />
- Icons from [Lucide Icons](https://lucide.dev/) <br />
- Notifications from [Sonner](https://sonner.emilkowal.ski/) <br />
- Form created using [react-hook-form](https://react-hook-form.com/) <br />
- Animations using [framer-motion](https://www.framer.com/motion/) <br />
- Emails using [Emailjs](https://www.emailjs.com/) <br />
- Convert 3d models to JSX using [Gltf JSX](https://github.com/pmndrs/gltfjsx)

#### Audio 

- Music by <a href="https://pixabay.com/users/shidenbeatsmusic-25676252/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=20772">Shiden Beats Music</a> from <a href="https://pixabay.com/music//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=20772">Pixabay</a>

---

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

This repo now uses [**Bun**](https://bun.sh/) as the package manager. Install Bun, then:

```bash
bun install   # install all dependencies
bun dev       # start the dev server
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 2026 Dependency Upgrade

The project has been refreshed to run on the latest stable versions of every major dependency. Headline changes:

- **Next.js** `14.2` → `16.2` (Turbopack builds, removal of `next lint` — replaced with `eslint .`)
- **React / React DOM** `18` → `19`
- **Tailwind CSS** `3` → `4` (new `@tailwindcss/postcss` plugin, `@import "tailwindcss"` + `@config` directive in `globals.css` to keep the existing JS config)
- **@react-three/fiber** `8` → `9` and **@react-three/drei** `9` → `10` (React 19 compatible)
- **framer-motion** `11` → `12`, **three** `0.162` → `0.184`, **sonner** `1` → `2`, **@emailjs/browser** `4.2` → `4.4`, **react-hook-form**, **lucide-react**, **sharp** all bumped to latest
- **ESLint** `8` → `9` with flat config (`eslint.config.mjs`) and `eslint-config-next` `16`
- **Package manager**: switched from npm to **Bun** — `package-lock.json` removed, `bun.lock` checked in

### Code changes required by the upgrade

- Next.js 15+ disallows `dynamic(..., { ssr: false })` inside Server Components, so the three model imports (`Wizard`, `HatModel`, `Staff`) are now wrapped in tiny `*Client.jsx` files marked `"use client"`.
- `globals.css` switched from `@tailwind base/components/utilities` to `@import "tailwindcss"` + `@config "../../tailwind.config.js"` (legacy JS config kept as-is via the v4 `@config` directive).
- `postcss.config.js` now uses `@tailwindcss/postcss` instead of the `tailwindcss` PostCSS plugin.
- `.eslintrc.json` replaced with `eslint.config.mjs` (flat config) using `eslint-config-next/core-web-vitals`.
- `package.json` `lint` script changed from `next lint` to `eslint .`.

### Want the original tutorial code?

The pre-upgrade version (Next.js 14, React 18, Tailwind 3, npm) is preserved in git history. To check it out locally:

```bash
git checkout 3b313c4   # last commit before the upgrade
```

Or browse it on GitHub: [commit 3b313c4](https://github.com/codebucks27/Next.js-Creative-Portfolio-Website/tree/3b313c484d2bdf853c8db72a2ba54995b50faf46).

## Other project

From the creator: [SmartHeadshots AI — AI headshot generator](https://www.smartheadshots.ai/).
