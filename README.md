<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Welcome+To+Book+Vibes+📚;" />
</h1>

<p align="center">
  <img src="Logo.png" alt="" width="200" />
</p>

<p><em>Momo'r Golpo Kotha is a personal digital notebook and blog designed to share creative journeys, technical ideas, and thoughtful stories. It provides a clean, distraction-free space for readers to explore reflections on technology, learning, and life experiences.</em></p>

---

## What is inside

- Bangla and English posts with language filtering
- A fast, static Astro site with minimal client-side JavaScript
- Markdown-based content workflow
- Responsive layout for desktop, tablet, and mobile
- Command palette with `Ctrl+K` or `Cmd+K`
- A notebook-inspired homepage and reading experience

## Quick start

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

## Available commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the production site into `dist/` |
| `npm run preview` | Preview the production build locally |

## Write a new post

Create a Markdown file inside `src/content/posts/`:

```md
---
title: "A small thought"
description: "A short description for the post list and metadata."
date: 2026-10-06
lang: en
tags:
    - thoughts
    - learning
---

Write your story here.
```

Use `bn` for Bangla posts and `en` for English posts. The site automatically discovers new Markdown files and adds them to the blog.

## Project structure

```text
src/
├── components/       Reusable Astro components
├── content/posts/     Markdown blog posts
├── layouts/           Shared page shell and navigation
├── pages/             Homepage and blog routes
└── styles/            Global styles and responsive UI
public/                Static assets such as the logo and favicon
```

## Content schema

Every post supports these frontmatter fields:

| Field | Type | Required |
| --- | --- | --- |
| `title` | string | Yes |
| `description` | string | Yes |
| `date` | date | Yes |
| `lang` | `bn` or `en` | Yes |
| `tags` | string array | No |

## Build and deploy

Generate the static site with:

```bash
npm run build
```

The output is written to `dist/`. It can be deployed to any static hosting provider, including Vercel, Netlify, or GitHub Pages.

## Tech stack

- [Astro](https://astro.build/)
- Markdown content collections
- CSS with responsive breakpoints
- Google Fonts: DM Sans, Fraunces, Geist Mono, and Hind Siliguri

## A note from Momo

লেখা হোক বাংলায়, English-এ, কিংবা দুটো মিশিয়ে। গুরুত্বপূর্ণ হলো, কিছু সত্যি মনে হলে সেটাকে লিখে রাখা।

<p><em>Built with ❤️ by Mahia Momo</em></p>
