<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=DM+Sans&weight=700&size=28&pause=1000&color=FF3B5C&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Mo-Ibra!;Shipping+products+from+the+browser+to+the+edge;Local-first%2C+tested%2C+and+built+to+last" alt="Typing SVG" />
  </a>
</div>

<div align="center">

[![Profile](https://img.shields.io/badge/profile-Mo--Ibra-ff3b5c?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mo-Ibra)
[![Open Source](https://img.shields.io/badge/open--source-enthusiast-2ea44f?style=for-the-badge&logo=opensourceorg&logoColor=white)](https://github.com/Mo-Ibra?tab=repositories)
[![Local First](https://img.shields.io/badge/local--first-advocate-f59e0b?style=for-the-badge&logo=electron&logoColor=white)](https://github.com/Mo-Ibra?tab=repositories)

</div>

---

I build for the web, then I make it survive production. My day-to-day is **TypeScript end to end** — React and Next.js on the front, Prisma and Postgres behind it, deployed to the edge. Everything I ship is written to be **tested, typed, and readable six months later**.

What I'm chasing right now is the layer *under* the app: **system engineering, Docker, CI/CD, and Linux internals** — because I don't want to just ship features, I want to understand exactly how they run.

### Cracking on:

#### [open-seo-extension](https://github.com/Mo-Ibra/open-seo-extension)
![type](https://img.shields.io/badge/type-browser%20extension-ff3b5c?style=flat-square) ![status](https://img.shields.io/badge/status-live-brightgreen?style=flat-square) ![stack](https://img.shields.io/badge/stack-WXT%20|%20React%20|%20Tailwind%20v4-3178c6?style=flat-square) ![tests](https://img.shields.io/badge/tests-70%20passing-2ea44f?style=flat-square)

**A local-first SEO inspector for Chrome, Edge, and Firefox.** No account, no server, no page URL ever leaves your machine.

- Audits titles, meta descriptions, canonicals, indexability, Open Graph / Twitter cards, heading order, links, and word count — with a live SERP preview.
- **Site mode** discovers pages from `sitemap.xml` (internal-link crawl as fallback), then scans up to 1000 in the background with a progress bar that survives a service-worker restart.
- Polite by design: `robots.txt` and `Crawl-delay` are respected, 4 parallel requests, hard page cap. Reports export to CSV/JSON.
- One self-contained DOM extractor is shared between the live tab and the crawler, so a page is never audited twice by two different sets of rules.

#### [us-state-flag-icons](https://github.com/Mo-Ibra/us-state-flag-icons)
![type](https://img.shields.io/badge/type-npm%20library-ff3b5c?style=flat-square) ![status](https://img.shields.io/badge/status-published%20%40%20npm-brightgreen?style=flat-square) ![stack](https://img.shields.io/badge/stack-SVGO%20|%20%40svgr%20|%20Node%20test-f59e0b?style=flat-square) ![license](https://img.shields.io/badge/license-MIT-8b5cf6?style=flat-square)

**Every US state and territory flag as code** — because no Unicode/emoji equivalent exists for them.

- Ships as **raw SVG, React components, JS strings, and CSS classes** from one generated source of truth.
- Preserves each flag's **native aspect ratio** — state flags are not uniform (Ohio is a swallowtail pennant, Rhode Island is nearly square). 16 distinct ratios, handled correctly by every entry point.
- A build pipeline that goes from curated source SVGs → optimized assets → generated React/CSS/string bundles → a validated `exports` map.
- Ships behind a real quality gate: unit tests, [`publint`](https://publint.dev), [Are The Types Wrong](https://arethetypeswrong.github.io), and an install-the-tarball test — all wired into `prepublishOnly` and CI.

#### Also on the bench
`open-editor` — a local-first video editor. No account, no upload, no render farm. Planning the architecture: one Canvas 2D + WebCodecs renderer shared by preview and export, flat-JSON projects instead of a compiler, and FFmpeg scoped to *decode only* so an LGPL build never poisons the license.

---

### Tech Stack & Tools

#### Frontend & Interface
[![My Skills](https://skillicons.dev/icons?i=react,nextjs,astro,tailwind,html,css,js,ts&theme=dark)](https://skillicons.dev)

#### Backend & Data
[![My Skills](https://skillicons.dev/icons?i=nodejs,prisma,postgres,python,ts,git&theme=dark)](https://skillicons.dev)

#### Tooling, Testing & Shipping
[![My Skills](https://skillicons.dev/icons?i=vite,vitest,cloudflare,docker,githubactions,linux,bash,npm&theme=dark)](https://skillicons.dev)

<div align="center">

| | |
|---|---|
| **Languages** | TypeScript · JavaScript · SQL · Bash · Python |
| **Frontend** | React 19 · Next.js · Astro · Tailwind CSS v4 · Vite |
| **Backend** | Prisma · PostgreSQL · Node.js · REST & background workers |
| **Edge & Infra** | Cloudflare · Docker · GitHub Actions · Linux |
| **Quality** | Vitest · Oxlint · typed public APIs · CI gates before publish |

</div>

### Currently

- 🔧 Learning **system engineering** properly — processes, signals, networking, and what actually happens between `npm run dev` and a running container.
- 🐳 Getting hands-on with **Docker**: multi-stage builds, slim images, compose, and why your image is 1.2 GB.
- ⚙️ Building **CI/CD pipelines** that actually gate: tests, lint, typecheck, build, publish.
- 🐚 Deepening **Linux fundamentals** — because debugging at 3 a.m. is easier when you know what the kernel is doing.
- 📐 Reading and planning around `open-editor`, a local-first video editor built on WebCodecs.

---
### 🕹️ Contribution Lab
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mo-Ibra/Mo-Ibra/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mo-Ibra/Mo-Ibra/output/github-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Mo-Ibra/Mo-Ibra/output/github-snake.svg">
</picture>

---
> "Ship it local-first, test the parts that scare you, and never make the user wait on a server they didn't ask for."
