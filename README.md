# Saulo Cruz

**Restaurateur & Hospitality Entrepreneur** · Seattle, WA 🇧🇷→🇺🇸

![AWS](https://img.shields.io/badge/AWS-Certified_SA-FF9900?logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Certified_SA-0078D4?logo=microsoftazure&logoColor=white)
![OCI](https://img.shields.io/badge/OCI-Certified_SA-F80000?logo=oracle&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-Agentic_AI-D97757?logo=anthropic&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-Parametric_CAD-FF6B00?logo=autodesk&logoColor=white)

I run restaurants and build the systems that make them profitable. Former cloud infrastructure architect (AWS, Azure, OCI) applying data-driven operations to one of the toughest-margin industries there is.

---

## 🍝 What I Do

Partner in three independent Seattle venues:

- **[La Fontana Siciliana](https://www.lafontanasiciliana.com)** — Sicilian-inspired Italian in Belltown since 1994, with a historic courtyard and fountain. *(Partnership with Rodrigo Parisi)*
- **[Tavern Law](https://www.tavernlaw.com)** — Capitol Hill craft cocktail bar & gastropub, home to the upstairs speakeasy **Needle & Thread**. *(The Hidden Door Ventures LLC — Cruz & Jones Hospitality Group)*
- **[Poquitos](https://poquitosseattle.com)** — Mexican restaurant and bar on Capitol Hill's E Pike St. *(Salt Holdings LLC)*

My focus: preserving each venue's character while driving sustainable, profitable growth — cutting operating costs, improving workforce retention, and engaging guests both in person and digitally.

## 🔧 Featured Project

### [TipPool](https://github.com/SauloCruz/TipPool) — multi-venue tip pool management

In production across all three venues, replacing the spreadsheets that used to decide real people's pay.

Three venues run three genuinely different rule sets — an hourly pool, a percentage tip-out, and a points × hours model — behind one login. The calculation engine is pure Python with no I/O: money is integer cents, splits use deterministic largest-remainder rounding, and every pool is covered by conservation invariants asserted in the engine itself. Finalizing a day writes an immutable snapshot; edits require an explicit reopen and keep the history. Sales, tips, and timecards come from the Square APIs, and anything unmapped *blocks* the day rather than being guessed at.

FastAPI · SQLite · no-build vanilla JS · Docker · 452 tests · Elastic License 2.0

## 🛠️ Tech Meets Hospitality

Before restaurants, I spent years in cloud infrastructure — Support Engineer, Infrastructure Solutions Architect, and Technical Account Manager roles across **AWS, Azure, and OCI**, with Solutions Architect certifications on all three platforms. Now I put that background to work on:

- **Agentic AI operations** — Claude-based assistants and sub-agents for ops, finance, and marketing workflows
- **POS & financial analytics** — Square and QuickBooks data pipelines for food cost, labor, and margin visibility
- **Payroll-grade tooling** — systems where being off by a cent is a real problem, built and tested accordingly
- **Process automation** — eliminating waste and streamlining service without sacrificing guest experience
- **Parametric CAD & 3D printing** — Fusion 360 + Bambu Lab X1C for custom fixtures and branded assets

## 📐 How I Operate

- **Data over gut feel** — metrics, POS analytics, and guest feedback drive decisions
- **Transparency** — with team, vendors, and guests
- **Contracts & risk done right** — law degree (Brazil) informing compliance and negotiation
- **Sustainable growth** — thriving venues without burnout, for me and my team

## 🌎 Background

Brazilian expat blending relationship-focused hospitality with American efficiency and innovation. Native Portuguese speaker, working in English, living in both worlds.

## 📊 GitHub Stats

<p>
<img src="https://streak-stats.demolab.com?user=SauloCruz&theme=gruvbox&hide_border=true" height="165" />
<img src="https://ghchart.rshah.org/SauloCruz" alt="Contribution graph" />
</p>

---

💬 Open to connecting on hospitality tech, restaurant operations, and AI-driven small business tooling.
