<div align="center">

# 📊 Business Analysis Internship Portfolio

**Research · Product Analysis · UI Prototype**

Work produced during my internship at **Evatro**

![Role](https://img.shields.io/badge/Role-Business_Analyst_Intern-2E75B6?style=for-the-badge)
![Company](https://img.shields.io/badge/Company-Evatro-1F3A5F?style=for-the-badge&logo=evatro&logoColor=red)

<div align="center">
  <img src="images/evatro_logo.jpg" alt="Evatro" width="500">
</div>
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
| 📚 | [**Business Analysis Research**](Business_Analysis_Research.pdf) | Core BA concepts + a YouTube subtitles case study |
| 🔎 | [**FieldPie Application Analysis**](docs/FieldPie_Application_Analysis.pdf) | 7 UX findings, from root cause to test case |
| 🖥️ | [**Bulk Schedule & Dispatch**](BulkSchedule.html) | Interactive UI prototype, no build step |

---

## 📚 1. Business Analysis Research

Requirements (business / user / system, functional / non-functional) · Elicitation techniques · As-Is vs To-Be · User Stories & Acceptance Criteria · Use Cases · INVEST · Impact analysis · Bug vs Improvement

**Case study: YouTube subtitles.** Auto-captions exist only in the video's original language. The proposal adds an automatic translation layer so users can watch any video in their own language.

---

## 🔎 2. FieldPie Application Analysis

Every finding goes through the same **10-step loop**:

`Problem` → `Current State` → `User Impact` → `Root Cause` → `Solution` → `Priority` → `Requirement` → `User Story` → `Acceptance Criteria` → `Test Cases`

| # | Finding | Proposed Solution |
|:-:|---------|-------------------|
| 1 | AI chat window blocks the UI it points to | Make the chat window resizable and movable |
| 2 | "Send" and "AI Chat" buttons overlap | Add enough spacing between the two buttons |
| 3 | Chart editor's Save/Cancel buttons hidden below the fold | Pin Save, Cancel, Delete, Clear in a fixed top bar |
| 4 | "Add Table" copies existing data instead of creating an empty table | Create a truly empty table and auto-sync entered data to related modules |
| 5 | Generic "An error occurred." on column selection | Show a specific error naming the failing column(s) |
| 6 | "Auto E-mail" never explains trigger or content | Add an info icon explaining trigger, frequency, and content |
| 7 | "Task" notification filter returns nothing | Fix the mapping between the filter label and the backend category value |

---

## 🖥️ 3. Bulk Schedule & Dispatch Prototype

A single-file prototype for scheduling and dispatching field work in bulk.

- 🔀 **Clients and Jobs** mode
- 🔍 Search, quick filters, advanced filters, pagination
- 📅 **Specific, range, or recurring** schedules
- 👷 Technician picker (region, skill, team, availability)
- 💾 Reusable **templates**
- 🚀 `Select → Optimize → Preview → Schedule / Dispatch`

                  | 🖥️ | [**Bulk Schedule & Dispatch**](BulkSchedule.html) | Interactive UI prototype, no build step |

<div align="center">
  <img src="images/bulk_schedule.png" alt="Bulk" width="600">
</div>

> ℹ️ Uses mock data and a simulated optimization step. No backend. Internet needed for CDN scripts.

---

## 🧠 Key Learnings

**Requirements writing** · **Root cause analysis** · **Producing solutions** · **Test design** · **React UI prototyping**

---

<div align="center">

**Ceren Naz Dervişoğlu** · [LinkedIn](https://www.linkedin.com/in/ceren-naz-dervi%C5%9Fo%C4%9Flu-413b54244/?isSelfProfile=true) 

<sub>Internship portfolio. Views are my own, not an official Evatro publication.</sub>

</div>