# LENS — Learning Effectiveness & Navigation System

> A structured, logic-driven framework for measuring training effectiveness — connecting baseline capability to behavioural change and business performance outcomes.

---

## The Problem

Most organisations invest heavily in training. Few can answer the question that actually matters to the business:

**Did it work?**

Post-training surveys measure satisfaction, not learning. Completion rates measure attendance, not application. LENS was built to close that gap — connecting what employees knew before training to what changed after, and whether that change reached the business.

---

## Live Demo

**[→ Open LENS](https://blaah00.github.io/LENS-Project)**


---

## What LENS Measures

LENS evaluates training across four stages:

| Stage | What It Captures |
|---|---|
| **Baseline** | Employee capability before training begins |
| **Learning** | Knowledge or perception shift post-training |
| **Application** | On-the-job behavioural change via multi-rater feedback |
| **Impact** | Business KPI movement (Technical training only) |

---

## Training Types & Evaluation Logic

LENS uses differentiated evaluation logic for each training category — because not all training is the same.

| Type | Rater Sources | KPI Measurement |
|---|---|---|
| Technical / Functional | Employee test + Manager | ✓ Yes |
| Behavioural | Self + Manager + Peer | — |
| Leadership | Self + Manager + Reportee (LDR Index) | — |
| Organizational | Self + Manager | — |

---

## How It Works

**Step 1 — Select training type**
Choose from Technical, Behavioural, Leadership, or Organizational. LENS routes to the appropriate evaluation logic automatically.

**Step 2 — Enter pre-assessment scores**
Baseline scores are recorded before training begins. All inputs are out of 10.

**Step 3 — Enter post-assessment scores**
Same sources, same scale — entered after training is completed.

**Step 4 — KPI measurement** *(Technical only)*
Manager enters before/after KPI scores across Productivity, Quality, and one custom metric.

**Step 5 — Calculate**
LENS applies decision logic and returns a Learning Impact Score with a verdict and a specific recommended action.

---

## Score Thresholds

| Verdict | Condition |
|---|---|
| ✅ Effective | Change > 0.5 points |
| 🟡 Moderate Impact | Change 0 – 0.5 points |
| 🔴 No Impact | Change ≤ 0 |

---

## Technical Training — Decision Matrix

| Knowledge | KPI | Verdict | Recommended Action |
|---|---|---|---|
| Improved | Improved | Effective | Scale this program |
| Improved | Unchanged | Learning not applied | Reinforcement coaching |
| Unchanged | Improved | Practical learning | Experiential design |
| Unchanged | Unchanged | Ineffective | Needs analysis required |

---

## Key Features

- **Differentiated evaluation logic** — each training type uses its own measurement pathway
- **Multi-source scoring** — Self, Manager, Peer, and Reportee inputs weighted by training type
- **Fast-track detection** — pre-assessment score ≥ 9/10 triggers a flag for potential training redundancy
- **Decision engine** — every result includes a specific recommended action, not just a verdict
- **Edge case handling** — missing data, conflicting feedback, and absent rater sources are flagged explicitly rather than silently dropped
- **Inline questionnaire viewer** — full questionnaires accessible within the dashboard without leaving the interface

---

## Files in This Repository

| File | Description |
|---|---|
| `index.html` | Interactive LENS dashboard — open in any browser, no setup required |
| `LENS-Blueprint.pdf` | Full system design document — logic, decision matrices, and evaluation flows |
| `LENS-Questionnaires.pdf` | Structured questionnaires for Behavioural, Leadership, and Organizational training |
| `README.md` | This file |

---

## Who This Is For

LENS is designed for HR professionals, L&D teams, and senior managers who need to evaluate training ROI. It is not intended for direct employee self-service use.

---

## About

LENS was designed as an HR portfolio project demonstrating systems thinking applied to Learning & Development — treating L&D as a data-driven decision function rather than a program delivery function.

Built with vanilla HTML, CSS, and JavaScript. No frameworks. No dependencies. No build step. Open in a browser and it works.

---

*LENS — Turning training spend into a defensible decision.*
