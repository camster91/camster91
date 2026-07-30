# Cameron Ashley · `camster91`

Toronto builder — web apps, AI agents, and tools that ship. Currently shipping across a 60+ repo fleet (wellness, fitness, K-12 SaaS, personal JW utilities). Runs on [Hermes Agent](https://github.com/camster91/hermes-agent).

---

## 🚀 What I'm building

| Domain | Repos |
|---|---|
| **AI & Agents** | [hermes-agent](https://github.com/camster91/hermes-agent) · [ai-chief-of-staff](https://github.com/camster91/ai-chief-of-staff) |
| **Wellness & Fitness** | [fernly](https://github.com/camster91/fernly) · [calisthenics-tree](https://github.com/camster91/calisthenics-tree) · [kettlebell-ab](https://github.com/camster91/kettlebell-ab) · [lull](https://github.com/camster91/lull) · [contraction-tracker](https://github.com/camster91/contraction-tracker) |
| **SaaS & Platforms** | [jw-video](https://github.com/camster91/jw-video) · [edusupervise](https://github.com/camster91/edusupervise) · [ashbi-platform](https://github.com/camster91/ashbi-platform) |
| **Personal JW Utilities** | [jw-habits](https://github.com/camster91/jw-habits) · [jw-meeting-companion](https://github.com/camster91/jw-meeting-companion) · [jw-rag-pipeline](https://github.com/camster91/jw-rag-pipeline) · [jw-music](https://github.com/camster91/jw-music) |
| **Agency Toolkit** | [ashbi-deploy](https://github.com/camster91/ashbi-deploy) · [data-broker-removal](https://github.com/camster91/data-broker-removal) · [creative-studio](https://github.com/camster91/creative-studio) |

---

## 📖 Personal JW utilities

A family of small apps I built for my own spiritual routine. All are **ToS-safe** — they use officially-published public APIs or local files, never scrape jw.org HTML, never re-host copyrighted content.

| App | What it does | Live | Status |
|---|---|---|---|
| **[jw-habits](https://github.com/camster91/jw-habits)** | Daily habit tracker — daily text, Bible reading, meeting prep. Tapping a habit opens the official jw.org page in a new tab. Mobile (iOS/Android/PWA) via Capacitor. | [jwhabits.ashbi.ca](https://jwhabits.ashbi.ca/) | 🟢 Active — flagship, 294 tests |
| **[jw-video](https://github.com/camster91/jw-video)** | Netflix-style streaming UI for JW.org videos. Uses JW.org's public Mediator API; streams from JW.org's CDN. | [jw-video.ashbi.ca](https://jw-video.ashbi.ca/) | 🟢 Active |
| **[jw-rag-pipeline](https://github.com/camster91/jw-rag-pipeline)** | Local RAG search over JW publications. Reads EPUBs from JW Library's official export — embeds locally with sentence-transformers, no API calls. | [study.ashbi.ca](https://study.ashbi.ca/) | 🟢 Active — **ToS-safe template** |
| **[jw-meeting-companion](https://github.com/camster91/jw-meeting-companion)** | Midweek meeting + Watchtower study with comment inspiration. Scraper extracts structure only (titles, questions, song numbers) — never paragraph text. | not deployed | 🟡 Active, needs deploy |
| **[jw-music](https://github.com/camster91/jw-music)** | Kingdom Songs catalog. Originally streamed audio; reframed 2026-07-29 to be a JW Library launcher (no audio streaming). | not deployed | 🟡 Reframed 2026-07-29 |

**Compliance pattern**: all active apps follow `jw-habits` (link-only) or `jw-rag-pipeline` (officially-downloaded EPUBs) patterns. None scrape jw.org HTML, none re-host content. The archived `JW-Newsfeed` was retired for ToS §4 violation (HTML scraping) — its description in the repo still serves as a public acknowledgment.

### Archived JW repos

- **[JW-Newsfeed](https://github.com/camster91/JW-Newsfeed)** — *2026-06-08*: scraped jw.org content. ToS §4 violation. Replaced by `jw-rag-pipeline` which uses officially-exported EPUBs.
- **[JW-Download](https://github.com/camster91/JW-Download)** — *2026-05-31*: download manager. Replaced by `jw-rag-pipeline` (better pattern: EPUBs you own, not files you fetch).
- **[jw-hub](https://github.com/camster91/jw-hub)** — *2026-06-12*: tried to bundle all JW apps into one PWA. App-per-capability split worked better. Apps split into the 5 active repos.
- **[jw-monorepo](https://github.com/camster91/jw-monorepo)** — *2026-06-30*: 6-app Python monorepo (792 MB). Solo-dev monorepo overhead wasn't paying off; same apps split into their own repos.

---

## 📌 Pinned

- **[jw-video](https://github.com/camster91/jw-video)** — Netflix-style streaming app for JW.org videos. React + TypeScript + Capacitor.
- **[edusupervise](https://github.com/camster91/edusupervise)** — Multi-tenant SaaS for K-12 teacher supervision scheduling. React Router 7, Postgres, Drizzle, BullMQ.
- **[fernly](https://github.com/camster91/fernly)** — Wellness companion for Gen Z. Mixed CBT/ACT, hybrid text+voice, pastel UI.
- **[ai-chief-of-staff](https://github.com/camster91/ai-chief-of-staff)** — Daily Telegram-pipelined AI brief — calendar, tasks, email, money, GitHub.
- **[calisthenics-tree](https://github.com/camster91/calisthenics-tree)** — A real skill tree for calisthenics — planche, front lever, handstand, smart regressions.
- **[data-broker-removal](https://github.com/camster91/data-broker-removal)** — Pi coding-agent skill: scaffold data broker removal apps (Incogni-like).

---

## 🛠 Stack

**Languages:** TypeScript, Python, JavaScript, PHP, Shell, HTML, CSS, Liquid, SQL
**Frontend:** React, Next.js, Vite, Capacitor, Tailwind, WordPress (FSE + ACF blocks)
**Backend:** Node.js, Postgres, Drizzle, BullMQ, Supabase, Stripe, WooCommerce
**AI / Agents:** Hermes Agent, Maton, ChromaDB, RAG pipelines, MCP, prompt orchestration
**Infra:** Docker, GitHub Actions, Coolify, VPS deploy templates, ghcr.io
**Domains:** Toronto SaaS, JW personal utilities, agency client work (Ashbi Design)

---

## 📫 Reach me

- 🌐 [ashbi.ca](https://www.ashbi.ca)
- 📧 cameron@ashbi.ca
- 💼 [Ashbi Design](https://github.com/camster91) — agency ops
- 🤖 [hermes-agent.nousresearch.com](https://hermes-agent.nousresearch.com/docs) — the agent I run on

---

<p align="left">
  <a href="https://github.com/camster91?tab=repositories&sort=stargazers"><img src="https://img.shields.io/github/stars/camster91?style=flat" alt="total stars"/></a>
  <a href="https://github.com/camster91?tab=repositories"><img src="https://img.shields.io/github/repos/camster91?style=flat" alt="total repos"/></a>
</p>