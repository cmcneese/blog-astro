---
title: "Migrating from Jekyll to Astro: A Fresh Start"
pubDate: 2026-09-05
description: "Why I migrated my blog from Jekyll to Astro and what I'm building with it"
tags: ["astro", "migration", "blogging", "static-site-generation"]
categories: ["web-development", "personal"]
---

# Welcome! 🚀

I'm excited to relaunch my blog—this time powered by **Astro**. After running Jekyll with the Chirpy theme, I made the jump to Astro for more flexibility and control. This is where I'll share my journey through full-stack development, backend architecture, and all the technical challenges I'm solving.

## Why Migrate from Jekyll to Astro?

I spent time with Jekyll and Chirpy, but Astro offered something I needed:

- **Markdown-first content** with full control over rendering via `render()` from `astro:content`
- **Component-based architecture** — mix Markdown with custom React/Astro components
- **Single-page app potential** — static site generation plus interactive features when needed
- **TypeScript out of the box** — type-safe configuration and content collections
- **Tailwind CSS integration** — easy styling without framework bloat
- **Zero JavaScript by default** — ship only what you need
- **Fast builds and deployments** — Netlify handles it seamlessly

## What Changed

I migrated all my Markdown posts from Jekyll and rebuilt the site with:

* Custom Astro layouts replacing the Chirpy theme
* Tailwind CSS for a clean, dark aesthetic with custom gradients
* Content collections for organized blog posts and categories
* A single-page portfolio design with interactive components
* Full control over styling and theming without theme constraints

## What to Expect

This blog will feature:

* Deep dives into backend architecture and API design
* Technical posts on Laravel, Node.js, and DevOps
* Automation and scripting case studies (like the CMS bulk-update project)
* Learning notes from full-stack development
* Lessons from working with enterprise CMS platforms

## The Stack

- **Framework:** Astro 7.3.1
- **Styling:** Tailwind CSS
- **Content:** Markdown with `astro:content`
- **Hosting:** Netlify
- **Language:** TypeScript
- **Package Manager:** pnpm

---

Thanks for visiting, and I hope you find the posts useful. Let me know if you have any feedback or thoughts!
