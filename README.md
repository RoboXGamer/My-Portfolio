# Ishrit Madaan — Portfolio

Personal portfolio built with **Astro 5 + React + GSAP + Tailwind CSS**, deployed on Netlify.

## Sections

- **Hero** — Introduction, roles, and contact CTA with animated SVG icons
- **About** — Bio with typography and an interactive scribble accent
- **Mission** — Full-screen text reveal using GSAP SplitText + ScrollTrigger
- **Works** — Project showcase with pinned scroll cards

## Tech Stack

| Category | Tools |
|---|---|
| Framework | Astro 5 |
| UI | React 19, Tailwind CSS v4 |
| Animation | GSAP (ScrollTrigger, SplitText) |
| Deployment | Netlify (via @astrojs/netlify) |
| Package Manager | pnpm |

## Commands

```sh
pnpm install        # Install dependencies
pnpm dev            # Start dev server at localhost:4321
pnpm build          # Build to ./dist/
pnpm preview        # Preview production build
```

## Project Structure

```
/
├── public/
├── src/
│   ├── assets/icons/    — SVG icon assets
│   ├── components/
│   │   └── Sections/    — Hero, About, Section2, Works
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
├── package.json
└── tsconfig.json
```
