# 🗂️ Agile Final Project — E-Commerce Product Catalog

> **IBM Agile Development and Scrum** · Final Project  
> Simulating a real Agile sprint end-to-end: backlog creation, sprint planning, and sprint execution on a Kanban board.

---

## 📌 Project Overview

This project demonstrates the full Agile/Scrum workflow applied to the back-end development of an **e-commerce product catalog**. The catalog needs to support CRUD operations, product interactions (likes/dislikes), and cloud deployment with automated pipelines.

Rather than building the application itself, this project focuses on the **planning and execution process** — the kind of work a real Scrum team does before and during a sprint.

---

## 🎯 Stakeholder Requirements

| # | Requirement |
|---|---|
| 1 | Ability to **create** a product in the catalog |
| 2 | Ability to **retrieve** a product from the catalog |
| 3 | Ability to **update** a product in the catalog |
| 4 | Ability to **delete** a product from the catalog |
| 5 | Ability to **like** a product in the catalog |
| 6 | Ability to **dislike** a product in the catalog |
| 7 | Ability to **list all** products in the catalog *(Icebox)* |
| 8 | Ability to **query a subset** of products in the catalog *(Icebox)* |
| 9 | Must be **hosted in the cloud** *(Technical Debt)* |
| 10 | Must have **automated deployments** to the cloud *(Technical Debt)* |

---

## 🏗️ What Was Built (Process-wise)

### 1. GitHub Kanban Board
A project board with the following columns:

```
New Issues → Icebox → Product Backlog → Sprint Backlog → In Progress → Review/QA → Done
```

### 2. User Stories
10 issues were created using a structured issue template following the format:

```
As a [role],
I need [functionality],
So that [benefit].
```

### 3. Backlog Refinement
- Requirements 7 and 8 were moved to the **Icebox** (deprioritized for this sprint)
- The remaining 8 stories were ranked and moved to the **Product Backlog**
- The top 5 stories received **acceptance criteria** written in Gherkin syntax:

```gherkin
Given [context]
When [action]
Then [expected outcome]
```

### 4. Story Labels
- Requirements 9 & 10 → labeled **`technical debt`**
- All other stories → labeled **`enhancement`**

### 5. Sprint Planning
- A **2-week Sprint milestone** was created
- The **top 4 stories** were pulled into the Sprint Backlog and assigned story point estimates
- Stories were assigned to the developer (myself)

### 6. Sprint Simulation
The sprint was simulated by moving stories across the board:

| Story | Final State |
|---|---|
| Create a product | ✅ Done |
| Retrieve a product | ✅ Done |
| Update a product | 🔄 In Progress (sprint ended) |
| Delete a product | 📋 Sprint Backlog |

---

## 📁 Repository Structure

```
agile-final-project/
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── user-story.md      # Issue template for all user stories
└── README.md
```

---

## 🧰 Tools & Methodology

| Tool / Concept | Usage |
|---|---|
| **GitHub Projects** | Kanban board for backlog and sprint management |
| **GitHub Issues** | User stories and backlog items |
| **GitHub Milestones** | Sprint tracking and burndown chart |
| **Scrum** | Framework guiding the entire process |
| **Gherkin syntax** | Acceptance criteria for user stories |

---

## 📚 Course

**IBM Agile Development and Scrum** — offered via [Coursera](https://www.coursera.org)  
Part of the IBM DevOps and Software Engineering Professional Certificate.

---

## 👤 Author

**Moloko Chris Poopedi**
[GitHub](https://github.com/molokochris)
