# Minimal Personal Website

A lightweight, content-focused personal website built with [Astro](https://astro.build) and [Tailwind CSS v4](https://tailwindcss.com).

## 🎯 Project Goals

- **Minimalistic Design**: Clean typography, neutral colors, and generous whitespace.
- **Content First**: Focused on blog posts and project portfolios using Markdown/MDX.
- **High Performance**: Static site generation with zero client-side JavaScript by default.
- **Simplicity**: No complex component libraries or heavy runtime dependencies.

## ✨ Features

- **Tech Stack**: Astro 5.0 + Tailwind CSS v4 (via `@tailwindcss/vite`).
- **Content Collections**:
  - `src/content/blog`: Technical blog posts.
  - `src/content/projects`: Portfolio/Project showcase.
- **Pages**:
  - **Home**: Introduction and featured projects.
  - **Blog**: Chronological list of thoughts and tutorials.
  - **Projects**: Dedicated portfolio listing.
  - **About**: Static biographical page.
- **SEO Ready**: Includes sitemap, RSS feed, and canonical URLs.
- **Type Safe**: Full TypeScript support for content schemas and components.

## 🚀 Project Structure

```text
├── public/             # Static assets (fonts, favicon, images)
├── src/
│   ├── assets/         # Optimized assets (images)
│   ├── components/     # UI components (Header, Footer, Meta)
│   ├── content/        # Markdown content sources
│   │   ├── blog/       # Blog post files (.md, .mdx)
│   │   └── projects/   # Project files (.md, .mdx)
│   ├── layouts/        # Page layouts (Layout.astro, BlogPost.astro)
│   ├── pages/          # Route definitions
│   └── styles/         # Global styles & Tailwind imports
├── astro.config.mjs    # Astro configuration
└── package.json        # Project dependencies
```

## 🧞 Commands

All commands are run from the root of the project:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `pnpm install`    | Installs dependencies                        |
| `pnpm dev`        | Starts local dev server at `localhost:4321`  |
| `pnpm build`      | Builds the production site to `./dist/`      |
| `pnpm preview`    | Preview the build locally                    |
| `pnpm check`      | Runs `astro check` for type validation       |

## 📝 Adding Content

### Blog Posts
Create a new file in `src/content/blog/`:

```markdown
---
title: "My New Post"
description: "A short summary."
pubDate: "2024-03-15"
heroImage: "./cover.jpg" # Optional
---

Write your content here using Markdown...
```

### Projects
Create a new file in `src/content/projects/`:

```markdown
---
title: "Project Name"
description: "Brief description of the project."
pubDate: "2024-01-20"
tags: ["Astro", "React"]
link: "https://github.com/..."
---

Project details...
```

## 📄 License

This project is licensed under the MIT License.