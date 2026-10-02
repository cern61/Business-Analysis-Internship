<div align="center">

# 📊 Business Analysis Internship Portfolio

**Research · Product Analysis · UI Prototype**
Work produced during my internship at **Evatro**

![Role](https://img.shields.io/badge/Role-Business_Analyst_Intern-2E75B6?style=for-the-badge)
![Company](https://img.shields.io/badge/Company-Evatro-1F3A5F?style=for-the-badge)
![React](https://img.shields.io/badge/React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

---

## ✨ At a Glance

| 🔍 Findings | 📝 Requirements | 📖 User Stories | ✅ Acceptance Criteria | 🧪 Test Cases |
|:---:|:---:|:---:|:---:|:---:|
| **7** | **7** | **7** | **21** | **23** |

---

## 📁 What's Inside

| | Deliverable | What it is |
|---|---|---|
| 📚 | [**Business Analysis Research**](docs/Business_Analysis_Research.pdf) | Core BA concepts + a YouTube subtitles case study |
| 🔎 | [**FieldPie Application Analysis**](docs/FieldPie_Application_Analysis.pdf) | 7 UX findings, from root cause to test case *(Turkish)* |
| 🖥️ | [**Bulk Schedule & Dispatch**](prototype/index.html) | Interactive UI prototype, no build step |

```
├── docs/
│   ├── Business_Analysis_Research.pdf
│   └── FieldPie_Application_Analysis.pdf
└── prototype/
    └── index.html
```

---

## 📚 1. Business Analysis Research

Requirements (business / user / system, functional / non-functional) · Elicitation techniques · As-Is vs To-Be · User Stories & Acceptance Criteria · Use Cases · INVEST · Impact analysis · Bug vs Improvement

**Case study: YouTube subtitles.** Auto-captions exist only in the video's original language. The proposal adds an automatic translation layer so users can watch any video in their own language.

---

## 🔎 2. FieldPie Application Analysis

Every finding goes through the same **10-step loop**:

`Problem` → `Current State` → `User Impact` → `Root Cause` → `Solution` → `Priority` → `Requirement` → `User Story` → `Acceptance Criteria` → `Test Cases`

| # | Finding | Priority |
|:-:|---------|:--------:|
| 1 | AI chat window blocks the UI it points to | 🟠 High |
| 2 | "Send" and "AI Chat" buttons overlap | 🟠 High |
| 3 | Chart editor's Save/Cancel buttons hidden below the fold | 🟠 High |
| 4 | "Add Table" copies existing data instead of creating an empty table | 🔴 Critical |
| 5 | Generic "An error occurred." on column selection | 🟠 High |
| 6 | "Auto E-mail" never explains trigger or content | 🟡 Medium |
| 7 | "Task" notification filter returns nothing | 🔴 Critical |

---

## 🖥️ 3. Bulk Schedule & Dispatch Prototype

A single-file prototype for scheduling and dispatching field work in bulk.

- 🔀 **Clients or Jobs** mode
- 🔍 Search, quick filters, advanced filters, pagination
- 📅 **Specific, range, or recurring** schedules
- 👷 Technician picker (region, skill, team, availability)
- 💾 Reusable **templates**
- 🚀 `Select → Optimize → Preview → Schedule / Dispatch`

```bash
open prototype/index.html      # or: python3 -m http.server 8000
```

> ℹ️ Uses mock data and a simulated optimization step. No backend. Internet needed for CDN scripts.

---

## 🧠 Key Learnings

**Requirements writing** · **Root cause analysis** · **Test design** · **Stakeholder communication** · **React UI prototyping**

---

<div align="center">

**[Your Name]** · [LinkedIn](https://www.linkedin.com/in/your-profile) · [Email](mailto:your.email@example.com)

<sub>Internship portfolio. Views are my own, not an official Evatro publication.</sub>

</div>