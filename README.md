# THE WAY × ADOL — Cambodia Sanitation Campaign

<div align="center">

**A full-stack IMC campaign for a real NGO — from strategy to deployed code.**

[![Impact Dashboard](https://img.shields.io/badge/📊_Impact_Dashboard-Live-00A9E0?style=for-the-badge)](https://beltran12138.github.io/the-way-impact-dashboard/)
[![Monopoly Game](https://img.shields.io/badge/🎮_Monopoly_Game-Play_Now-5EAB78?style=for-the-badge)](https://cambodia-toilet-monopoly.vercel.app)
[![Client](https://img.shields.io/badge/Client-ADOL_NGO-FFD166?style=for-the-badge)](https://adropoflife.org)

*CUHK COMM3400B · World Toilet Day 2026 · Real client, real deliverables*

</div>

---

## What is THE WAY?

**THE WAY** reframes toilet donation as product ownership.  
Instead of "donate to faceless cause," donors **buy a named toilet** — with GPS coordinates, a certificate, and a wall mural. This is **TaaP (Toilet as a Product)**.

Built for **ADOL (A Drop of Life)**, a Hong Kong NGO building sanitation infrastructure in rural Cambodia, where 74% of rural residents lack safe toilet access.

---

## Products Built

| Product | Stack | Live |
|---|---|---|
| **Impact Dashboard** | HTML/JS · Supabase · Chart.js · Canvas 2D · DeepSeek AI | [GitHub Pages →](https://beltran12138.github.io/the-way-impact-dashboard/) |
| **Monopoly Game** | React 18 · TypeScript · Vite · Tailwind · Canvas API | [Vercel →](https://cambodia-toilet-monopoly.vercel.app) |

---

## Campaign Architecture

```
THE WAY Growth Flywheel
                    ┌─────────────────────────────────┐
                    ▼                                 │
REACH ──→ SHARE ──→ CONNECT ──→ GIVE ──→ TRACK ──→ FEEL ──→ CELEBRATE
  │          │                    │          │
EXE 05    EXE 02               EXE 04     EXE 03
GEO    #IAmToiletOwner          CaaS     Monopoly ◄ this game
```

| Execution | Channel | Role in Flywheel |
|---|---|---|
| EXE 01 · 60s AI Film | Video | FEEL — pixel→real emotional hook |
| EXE 02 · #IAmToiletOwner | Social Media | SHARE — viral challenge |
| EXE 03 · Monopoly Game | Web/Events | TRACK — gamified education |
| EXE 04 · CaaS Subscription | Direct | GIVE — HK$50/300/3,500/mo |
| EXE 05 · GEO Strategy | AI Search | REACH — LLM citation targeting |
| TaaP · Toilet Naming | Physical | CELEBRATE — ownership proof |

---

## Three Original Frameworks

### CaaS — Charity as a Service
Donor subscription model mapping to SaaS pricing logic:

| Tier | Price | What You Get |
|---|---|---|
| Supporter | HK$50/mo | Monthly impact report |
| Builder | HK$300/mo | Named brick + certificate |
| Owner | HK$3,500 one-off | Full toilet: GPS + mural + certificate |

### TaaP — Toilet as a Product
Each donated toilet becomes a named asset:
- 📜 **Ownership Certificate** — serial TW-2026-XXXX
- 📍 **Google Maps listing** — GPS-tagged, searchable
- 🎨 **Custom wall mural** — donor's message in Khmer

### GEO — Generative Engine Optimisation
JSON-LD structured data (schema: `NGO` + `Event` + `FAQPage`) designed so that when donors ask ChatGPT/Gemini *"how can I help Cambodia sanitation?"*, ADOL gets cited — not just ranked.

Most nonprofits are still doing traditional SEO. This is the next layer.

---

## Technical Highlights

- **K-line candlestick chart** — built with raw Canvas 2D API (no library)
- **DALY trend visualisation** — Chart.js with real Cambodia health data
- **Bloomberg-style ticker** — CSS animation
- **Supabase Realtime** — live donor activity feed
- **DeepSeek AI** — campaign Q&A assistant
- **GitHub Actions CI/CD** — auto-deploy on push
- **Mobile responsive** — CSS Grid + media queries, tested on 375px

---

## Repositories

| Repo | Description |
|---|---|
| [the-way-impact-dashboard](https://github.com/Beltran12138/the-way-impact-dashboard) | Donor microsite · CaaS tiers · TaaP gallery · GEO schema · Impact charts |
| [cambodia-toilet-monopoly](https://github.com/Beltran12138/cambodia-toilet-monopoly) | React board game · 4-player · difficulty modes · achievement system |

---

## Context

Produced as the final project for **CUHK COMM3400B: Integrated Strategic Campaign II** (JLM Pinpoint Practicum), in partnership with ADOL.  
The course requires real-client deliverables evaluated by industry professionals.

---

<div align="center">
<sub>Built end-to-end by one person — strategy, design, and code.</sub>
</div>
