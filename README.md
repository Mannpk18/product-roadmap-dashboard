# 📊 Product Feature Prioritization & Roadmap Dashboard

An interactive, single-page dashboard that models how a PM would plan, score, and ship a B2B SaaS analytics product across four quarters — from weighted feature scoring to stakeholder-ready release notes.

> **Core philosophy:** *Score tells you importance, sequencing tells you order.*

## 🖥️ Live Demo

👉 **[View Live Dashboard](https://mannpk18.github.io/product-roadmap-dashboard/)**

## ✨ What This Dashboard Does

The dashboard manages **17 features** across **6 product themes** for a fictional SaaS analytics platform, organized into 5 interactive views:

| View | What it shows |
|------|--------------|
| **Feature Scoring** | Weighted scoring matrix — User Impact (40%) + Business Value (35%) + Technical Feasibility (25%) — with auto-ranked priority tiers |
| **Backlog** | Filterable user story cards with context, story points, status badges, and PM notes (risk flags, blockers) |
| **Roadmap** | Quarter-by-theme grid (Q1–Q4 2025) showing feature placement with story point sizing |
| **Sprint Board** | Kanban board (To Do → In Progress → Done) with velocity metrics, progress tracking, and blocker visibility |
| **Stakeholder View** | Release-level summaries (v1.0 → v2.5) with shipping rationale written in the voice of a PM talking to leadership |

## 🧠 Product Thinking Demonstrated

This isn't just a pretty UI — it models real PM decision-making:

- **Scoring framework** — RICE/WSJF-inspired weighted formula that balances user needs, business impact, and engineering cost
- **Sequencing logic** — Features ordered so that foundation ships first, monetizable features second, enterprise-readiness last
- **Dependency resolution** — SSO ships before audit logs; analytics v1 before custom reports
- **Risk communication** — Blocker flags, feasibility warnings, and honest stakeholder rationale ("co-editing is genuinely hard")
- **Sprint-level execution** — Velocity tracking, story points, team capacity, and days remaining

## 🛠️ Tech Stack

- **HTML5** — semantic markup, single-file architecture
- **CSS3** — CSS custom properties, responsive grid, mobile-first breakpoints
- **Vanilla JavaScript** — dynamic rendering, filtering, tab navigation — zero dependencies

## 🚀 Getting Started

**Option 1: Open locally**
```bash
git clone https://github.com/Mannpk18/product-roadmap-dashboard.git
cd product-roadmap-dashboard
open index.html
```

**Option 2: View the GitHub Pages deployment** (see Live Demo link above)

## 📁 Project Structure

```
product-roadmap-dashboard/
├── index.html       # Complete dashboard (HTML + CSS + JS in one file)
└── README.md
```

## 📱 Responsive

The dashboard is fully responsive — metric cards, kanban columns, and roadmap grid adapt to mobile viewports.

## 📄 License

MIT — free to use, modify, and distribute.

## 👤 Author

**Mann Kaniyawala**
- GitHub: [@Mannpk18](https://github.com/Mannpk18)
- LinkedIn: [mann-kaniyawala](https://linkedin.com/in/mann-kaniyawala)
- Email: kaniyawm@mcmaster.ca
