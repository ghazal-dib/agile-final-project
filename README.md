# 🧩 Agile Final Project – Sprint Planning & Execution

This repository contains my **Final Project** for the Agile Development course.  
It demonstrates how to apply **Scrum and Agile principles** using **GitHub Projects** to manage and simulate a sprint — from backlog creation to sprint execution and burndown tracking.

---

## 📘 Project Overview

In this project, I played the roles of:
- **Product Owner** – Created and prioritized user stories based on stakeholder requirements.  
- **Scrum Master** – Organized the sprint milestone, refined the backlog, and tracked progress.  
- **Developer** – Executed and simulated sprint activities by moving stories across the Kanban board.

The main objective was to develop the **back-end product catalog** for an e-commerce website.  
The catalog allows users to create, retrieve, update, and delete products (CRUD operations),  
as well as like or dislike products. The system is hosted in the cloud with automated deployment features.

---

## 🧠 Stakeholder Requirements

| # | Requirement |
|---|--------------|
| 1 | Need the ability to create a product in the catalog |
| 2 | Need the ability to retrieve a product from the catalog |
| 3 | Need the ability to update a product in the catalog |
| 4 | Need the ability to delete a product from the catalog |
| 5 | Need the ability to Like a product in the catalog |
| 6 | Need the ability to Dislike a product in the catalog |
| 7 | Need the ability to list all products in the catalog |
| 8 | Need the ability to query a subset of products in the catalog |
| 9 | Must be hosted in the cloud |
| 10 | Must have automation to deploy new changes to the cloud |

---

## 🗂️ Agile Artifacts

### 🗃️ Product Backlog
All 10 stakeholder requirements were converted into **user stories** and added to the Kanban board.  
Each story followed the standard user story format:

> **As a [type of user]**,  
> **I need [a goal or feature]**,  
> **So that [reason or value]**.

All stories were labeled according to their type:  
- `enhancement` → new or improved functionality  
- `technical debt` → infrastructure or automation work  

---

### 🧩 Sprint Setup
- **Sprint Name:** Sprint 1  
- **Duration:** 2 weeks  
- **Milestone Goal:** Implement core catalog CRUD features (Create, Retrieve, Update, Delete).  
- **Total Story Points:** 19  

| Story | Story Points | Label |
|--------|---------------|--------|
| Create a product | 8 | enhancement |
| Retrieve a product | 5 | enhancement |
| Update a product | 3 | enhancement |
| Delete a product | 3 | enhancement |

---

## 🏗️ Sprint Execution

The sprint simulation was conducted as follows:
1. The first story (*Create a product*) was assigned to myself and moved to **In Progress**.  
2. After completion, it was moved to **Review/QA**.  
3. The second story (*Retrieve a product*) was started and moved to **In Progress**, while the first was marked **Done**.  
4. The cycle continued with *Update* and *Delete* stories, leaving one story **In Progress** at the end.  

This simulated a real sprint environment with continuous flow and parallel work.

---

## 📉 Burndown Chart

A **Burndown Chart** was generated under *Insights → Charts* in GitHub Projects.

- **Layout:** Stacked Area  
- **X-axis:** Sprint  
- **Group by:** Status  
- **Y-axis:** Sum of field → Estimate  
- **Filter:** `sprint:Sprint 1`  

The chart shows:
- ✅ 13 Story Points **Done**  
- 🔧 3 Story Points **In Progress**  
- 🗂️ 3 Story Points still in **Sprint Backlog**

This visualization confirms consistent progress toward the sprint goal.

---

## 📊 Kanban Board

👉 [**View the Kanban Board Here**](https://github.com/users/ghazal-dib/projects/2/views/1)

The board includes six columns:
- **Icebox** – Deferred stories or ideas  
- **Product Backlog** – Stories ready for prioritization  
- **Sprint Backlog** – Stories committed for Sprint 1  
- **In Progress** – Ongoing development tasks  
- **Review/QA** – Stories under verification  
- **Done** – Completed stories  

---

## 🏁 Sprint Summary

- **Sprint Duration:** 2 weeks  
- **Planned Velocity:** 19 story points  
- **Completed:** 13 SP (68%)  
- **In Progress:** 3 SP (16%)  
- **Pending:** 3 SP (16%)  

**Sprint Goal Achieved:** ✅ Core CRUD functionality delivered and validated through simulation.

---

## ✍️ Author
**Ghazal Dib**  
GitHub: [@ghazal-dib](https://github.com/ghazal-dib)

---

## 💡 Key Takeaways
- A well-structured **product backlog** ensures clarity and prioritization.  
- **Sprint planning** aligns workload with realistic team velocity.  
- **Burndown charts** provide clear visual feedback on progress.  
- Agile tools in GitHub make project tracking smooth and transparent.

---

