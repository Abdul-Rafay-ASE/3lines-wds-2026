# 3lines Advanced Technologies — WDS 2026 Presentation

> **Live Site:** https://3lines-wds-2026.vercel.app

Official digital presentation for **3lines Advanced Technologies Company** at the **World Defense Show 2026** (WDS 2026), held in Riyadh, Saudi Arabia — February 8–12, 2026.

---

## What Is This?

This repository contains the web-based presentation built to showcase 3lines' AI capabilities and infrastructure at WDS 2026. It is a fully responsive, interactive HTML/CSS/JS site deployed on Vercel.

The presentation highlights:
- **Three AI Agents** built for defense companies
- **Own LLM Infrastructure** — servers, models, and full-stack built in Saudi Arabia
- **Company overview** and team

---

## Why Was It Created?

The presentation was built to replace static slides (PowerPoint) with a **live, interactive web experience** that could be displayed at the defense exhibition booth. Key goals:

- Fast, professional, and visually impressive on large screens
- Mobile-responsive for tablets and phones at the booth
- Easy to share as a URL with visitors and partners
- Deployable and updatable instantly without reprinting materials

---

## Repository Structure

```
3lines-wds-2026/
├── index.html                    # Main landing page (Premium version — Vercel entry point)
├── 3Lines_WDS2026_Premium.html   # Full premium presentation (AI agents, infra, team)
├── 3Lines_WDS2026_Simple.html    # Simplified slider version for quick demos
├── logo-removebg-preview.png     # 3lines company logo (transparent background)
├── vercel.json                   # Vercel deployment configuration
├── .gitignore                    # Excludes reports, node_modules, and dev files
└── README.md                     # This file
```

---

## Pages / Versions

### `index.html` — Premium Version (Main)
The primary presentation. Deployed as the homepage at https://3lines-wds-2026.vercel.app

**Sections:**
1. **Header** — Logo, company name, WDS 2026 badge, auto-scroll button
2. **Hero** — Main title "Advanced AI Technologies by 3lines"
3. **Three AI Agents** — Procurement AI, HR Intelligence, Sales & CRM
4. **Our AI Infrastructure** — Own servers, trained models, full-stack, data sovereignty
5. **Meet Our Team** — AI department team members
6. **Footer** — Booth info, contact, links

### `3Lines_WDS2026_Simple.html` — Slider Version
A simpler auto-sliding presentation format, useful for unattended booth displays. Includes manual controls, keyboard navigation, and auto-play.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 | Structure and styling |
| Vanilla JavaScript | Slider, auto-scroll, interactivity |
| CSS Grid / Flexbox | Responsive layout |
| CSS Custom Properties | Blue color theme matching logo |
| Google Fonts (Inter, Space Grotesk) | Typography |
| Font Awesome 6 | Icons |
| Vercel | Hosting and deployment |

---

## Color Theme

Colors are based on the **3lines logo** (blue tones):

| Variable | Hex | Usage |
|---|---|---|
| Primary Blue | `#0066CC` | Buttons, badges, borders, accents |
| Light Blue | `#00A3E0` | Gradients, hover states |
| Dark Blue | `#004B99` | Deep accents |
| Cyan | `#00D4FF` | Highlights, tech accents |

---

## Deployment

The site is deployed on **Vercel** with automatic production deployment.

- **Production URL:** https://3lines-wds-2026.vercel.app
- **Vercel Project:** `abdul-rafays-projects-6ed5de06/3lines-wds-2026`
- **GitHub Repo:** https://github.com/Abdul-Rafay-ASE/3lines-wds-2026

Every push to `main` triggers an automatic Vercel deployment.

### Manual Deploy (CLI)
```bash
vercel --prod --yes
```

---

## Local Development

No build tools required. Open directly in browser:

```bash
# Clone the repo
git clone https://github.com/Abdul-Rafay-ASE/3lines-wds-2026.git

# Open in browser
open index.html
# or just double-click index.html
```

---

## Key Features

- **Fully Responsive** — Works on phones (320px+), tablets, and large screens
- **Blue Theme** — Matches 3lines logo colors exactly
- **Fast Scrolling** — Instant scroll behavior, optimized animations
- **Auto-Scroll** — One-click auto-scroll through entire presentation
- **Slider Controls** — Manual prev/next, keyboard arrows, dot navigation, auto-play
- **Live Demo Links** — Direct links to https://dashboard.ai3lines.com/
- **Arabic-Ready** — Structure supports bilingual content

---

## Project Background

**Company:** 3lines Advanced Technologies Company
**Department:** AI & Automation Department
**Developer:** Abdul Rafay (Software Engineer)
**Supervisor:** Khaled bin Salman (Head of AI Department)
**Event:** World Defense Show 2026 — Riyadh, Saudi Arabia
**Booth:** Saudi Supply Chain Zone

3lines is **Saudi Arabia's first GAMI-licensed AI company** with fully owned LLM infrastructure built and operated entirely within Saudi Arabia.

---

## Contact

- **Website:** www.3lines.com.sa
- **Dashboard:** dashboard.ai3lines.com
- **Email:** info@3lines.com.sa
- **Careers:** careers.ai3lines.com
