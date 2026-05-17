# PathNorth


**AI-guided professional development for complex work.**

PathNorth is a privately funded concept under development. It explores how AI-guided learning can help professionals read, think, test understanding, receive feedback, and apply knowledge in complex domains.

The initial pilot uses **Uncrewed Aerial Systems (UAS)** as a bounded, unclassified test case for the Canadian military intelligence community.

---

## Status

> Concept development and pilot design. Not yet open to learners.

See [pathnorth.ca](https://www.pathnorth.ca) for public-facing status.

---

## Repository Structure
---
pathnorth/

├── README.md          # This file

├── docs/              # Architecture decisions, design notes, governance

├── platform/          # Learner-facing interface (in development)

├── prompts/           # AI dialogue logic and question sets

└── content/           # UAS course material index (references only — no classified content)


## Core Concept

The model is built on three principles from the v5.6 concept paper:

1. **Reading first** — the AI does not replace content; it directs the learner to curated approved material
2. **Structured dialogue** — AI-supported questioning checks understanding, not just completion
3. **Human-set standards** — progression rules, content, and oversight remain with qualified humans

---

## Notices

- PathNorth is **not** an official CAF, DND, Government of Canada, NATO, or CMIA program
- Do not store classified, protected, or operationally sensitive content in this repository
- This repository is **private** during concept development

---

## Contact

Project inquiries: contact@pathnorth.ca

# /docs — Architecture & Design

This folder contains architecture decisions, design notes, and governance documentation for the PathNorth platform.

---

## Contents (evolving)

| File | Purpose |
|---|---|
| `architecture.md` | System architecture overview and stack decisions |
| `governance.md` | Oversight model, data handling, COI status |
| `design-principles.md` | Learning model foundations from concept paper v5.6 |
| `pilot-plan.md` | UAS pilot scope, cohort design, evaluation criteria |

---

## Conventions

- All decisions should be documented with a date and brief rationale
- Link to relevant sections of the concept paper where applicable
- Flag open questions with `> ⚠️ OPEN:` prefix
