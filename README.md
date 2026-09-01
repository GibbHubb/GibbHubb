## Hi, I'm Max 👋

Infrastructure developer and systems engineer, building tools where **engineering data**, **AI retrieval** and **operational software** meet.

By day I run Odoo environments, RAG pipelines and a multi-tenant requirements-management platform for engineering teams working on Dutch grid and offshore infrastructure programmes. By night I build full-stack projects to keep the craft sharp.

---

### What I'm working on

- **Requirements management on Odoo 16** — a multi-tenant platform for infrastructure projects: historical requirement library, verification & validation tracking, AI-assisted applicability scoring. Two live client tenants, promoted through a dev → tenant pipeline with an automated smoke harness.
- **Per-client RAG cluster** — eight Proxmox LXC containers serving retrieval-augmented generation over project document collections, with vLLM inference on a dedicated GPU host and a forked Open WebUI front end.
- **AI ProjectDesk** — an assistant embedded *inside* Odoo. It reads the requirement record you're standing on, injects it as context, and streams reasoning and answer back into the form for the engineer to accept.
- **Repurpose** — a content-repurposing micro-SaaS: one long source in, a multi-channel content pack out, on-brand via saved voice profiles. Next.js 15, streaming AI, background workers, metered billing. Live; repo private.

---

### Portfolio

| Project | Stack | What it does |
|---------|-------|-------------|
| [Our_Menu](https://github.com/GibbHubb/Our_Menu) | Next.js 14 · Supabase · Claude API | Shared recipe collection with AI chat, a "what do we eat tonight" decision maker and shopping lists — [live](https://our-menu-omega.vercel.app) |
| [Poly_Tracker](https://github.com/GibbHubb/Poly_Tracker-) | React 18 · Vite · TypeScript · MapLibre GL · PostGIS | Offline-first field GIS for cattle-station water infrastructure — draw poly-pipe runs, troughs and bores on satellite imagery, export the map view to PDF |
| [finly](https://github.com/GibbHubb/finly) | FastAPI · React 18 · TypeScript · Zustand | Personal finance tracker — transactions, categories, budget progress |
| [GymPal](https://github.com/GibbHubb/GymPal) | React Native · Expo · Node.js · Socket.IO | Dual-portal fitness app — client tracking plus live trainer session streaming |
| [Bright-Beer](https://github.com/GibbHubb/Bright-Beer) | TypeScript · Web Workers · Turf.js · SunCalc | *Sunny Amsterdam* — finds the terrace that's in the sun right now by projecting building shadows off 149k real footprints — [live](https://gibbhubb.github.io/Bright-Beer/) |
| [Tara_Station_3D](https://github.com/GibbHubb/Tara_Station_3D) | Unreal Engine 5 · C++ | Cattle-station life sim. The whole simulation — grazing, water, breeding, economy, wildlife — is engine-free C++ behind a Blueprint bridge, so it's testable without the editor |
| [ai-learning-path-generator](https://github.com/GibbHubb/ai-learning-path-generator) | Python · FastAPI · React | Turns a goal statement into a structured learning roadmap; rate-limited API with full docs |

---

### Tech

```
Languages    Python · TypeScript · JavaScript · SQL · C++ · Bash
Backend      FastAPI · Node.js/Express · Odoo (Python ORM) · SQLAlchemy · Alembic · Drizzle
Frontend     React 18 · React Native · Next.js · Zustand · Tailwind · OWL (Odoo)
AI / RAG     vLLM · Open WebUI · Chroma · Claude & OpenAI APIs · SSE streaming
Data         PostgreSQL · PostGIS · Supabase · XML-RPC integrations
Infra        Proxmox · LXC · Docker · Vercel · Cloudflare Workers/R2 · Gitea · GitHub Actions
Testing      pytest · Playwright · automated deployment smoke harnesses
```

---

### Connect

- Work: Huracán Technical Advisory — [huracan-tech.nl](https://www.huracan-tech.nl)
- GitHub: you're already here
