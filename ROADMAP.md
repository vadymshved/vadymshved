# Applied AI & Scientific Computing — Development Roadmap 2026–2027

> A public professional-development roadmap for building practical skills at the intersection of **chemistry, scientific computing, education, applied AI and automation**.

## Direction

My goal for 2026–2027 is to develop from a chemistry educator and scientist into a professional who can **design, evaluate and implement AI-assisted systems for education, research and knowledge-intensive workflows**.

This roadmap documents the skills I intend to develop and the kinds of projects I plan to build. It is deliberately separated from private implementations: early-stage code, datasets, teaching materials, research methods and potentially commercial logic may remain private until they are ready for a deliberate publication decision.

## Development principles

- **Domain first:** start from a real scientific, educational or workflow problem.
- **Build to learn:** every learning block should produce a small working artifact.
- **Understand the code:** AI-assisted development is welcome, but I should be able to explain the architecture and main modules.
- **Validate before publishing:** chemistry/scientific correctness, reproducibility and limitations matter as much as code generation.
- **Publish progressively:** private prototype → tested implementation → sanitized portfolio edition / demo / open-source release when appropriate.
- **Protect sensitive IP:** unpublished research, proprietary prompts, private datasets, student data and third-party educational materials stay private unless explicitly cleared for release.

---

## Learning tracks

### 1. Applied AI & Evaluation

**Skills to develop**

`Python` · `Pandas` · `JSON` · `REST APIs` · `LLM APIs` · `Pydantic` · `structured outputs` · `evaluation metrics` · `testing` · `prompt/version management`

**Planned projects**

- **Chemistry LLM Evaluation** — benchmark LLM reliability on chemistry reasoning tasks.
- **Chemistry AI Safety Benchmark** — test hallucination, ambiguity and contradiction handling.
- **AI Textbook Evaluator** — compare AI-generated evaluation with an evidence-informed human rubric.

### 2. Scientific Computing & Data

**Skills to develop**

`NumPy` · `Pandas` · `SciPy` · `Matplotlib` · `Streamlit` · `data validation` · `statistics` · `scientific data workflows`

**Planned projects**

- **Scientific Data Dashboard** — validate, analyse and visualise chemistry/nanoscience datasets.
- **Molecular Structure Toolkit** — basic coordinate, distance, angle and dihedral operations for molecular structures.

### 3. AI Applications & Automation

**Skills to develop**

`Telegram API` · `FastAPI` · `Supabase` · `PostgreSQL` · `SQLite` · `Playwright` · `GitHub Actions` · `webhooks` · `scheduling` · `logging` · `error handling`

**Planned projects**

- **AI Research Telegram Bot** — Markdown-protocol-driven assistant with interchangeable LLM providers.
- **Multi-source Monitoring Agent** — structured search, validation, state tracking and alerts.
- **TutorOps** — tutor workflow, student, lesson and payment management with automation.

### 4. AI for Education

**Skills to develop**

`document processing` · `rubrics` · `diagnostic systems` · `human-in-the-loop AI` · `knowledge graphs` · `adaptive workflows` · `educational evaluation`

**Planned projects**

- **Chemistry Assessment Analyzer** — identify topics, prerequisites, difficulty and recurring task patterns.
- **Adaptive Chemistry Tutor** — diagnose likely knowledge gaps and recommend targeted practice.
- **Multilingual STEM Explainer** — adapt STEM explanations across languages and educational contexts.
- **AI Teacher Feedback Assistant** — rubric-controlled analysis of student answers.
- **Chemistry Knowledge Graph** — model prerequisite relationships between chemistry concepts.

---

## 2026–2027 roadmap

### Phase 1 — Foundations · Sep–Nov 2026

**Objective:** become comfortable reading, modifying, testing and documenting small Python applications.

**Learning focus**

`Git & GitHub` · `Python fundamentals` · `virtual environments` · `functions/classes` · `CSV/JSON` · `Pandas` · `REST APIs` · `basic tests` · `README/documentation`

**Minimum project milestones**

| Project | Minimum publishable prototype | Estimated minimum workload |
| --- | --- | ---: |
| Scientific Data Dashboard | CSV → validation → statistics → plots → simple Streamlit UI | **6–8 h** |
| Chemistry LLM Evaluation v0.1 | 20 questions → 2–3 models → reference answers → evaluation table/charts | **8–12 h** |
| Chemistry Assessment Analyzer v0.1 | text/PDF input → structured topic/prerequisite/difficulty analysis | **8–12 h** |

**Target project workload:** ~22–32 h  
**Suggested learning/support workload:** ~25–35 h

### Phase 2 — Applied AI & APIs · Dec 2026–Feb 2027

**Objective:** move from scripts to reusable AI-assisted applications.

**Learning focus**

`LLM APIs` · `structured outputs` · `Pydantic` · `prompt/version management` · `evaluation` · `FastAPI basics` · `environment variables` · `API authentication`

**Candidate milestones**

| Project | Minimum publishable prototype | Estimated minimum workload |
| --- | --- | ---: |
| AI Research Telegram Bot | Telegram + Python + protocol.md + one LLM provider | **8–12 h** |
| AI Textbook Evaluator | one chapter + 5 criteria + structured scoring + limitations | **10–15 h** |
| Chemistry AI Safety Benchmark | 15 adversarial chemistry tasks + reliability metrics | **8–12 h** |

### Phase 3 — Automation & Data Infrastructure · Mar–May 2027

**Objective:** learn persistence, automation and more robust application workflows.

**Learning focus**

`PostgreSQL` · `Supabase` · `Playwright` · `GitHub Actions` · `schedulers` · `logging` · `retries` · `state` · `deduplication`

**Choose one primary project**

| Project | Minimum publishable prototype | Estimated minimum workload |
| --- | --- | ---: |
| Scientific Literature Agent v0.1 | query → scholarly API → 10 papers → structured comparison | **15–20 h** |
| Monitoring Agent v0.1 | one source → parser → SQLite → status/price change → alert | **12–18 h** |
| Molecular Structure Toolkit v0.1 | XYZ reader + distance/angle/dihedral calculations | **8–15 h** |

### Phase 4 — Flagship · Jun–Aug 2027

**Objective:** select the direction that proved most interesting and build one deeper portfolio project.

Possible flagship paths:

- **AI Quality:** extend Chemistry LLM Evaluation into a larger reproducible benchmark.
- **EdTech:** build Adaptive Chemistry Tutor.
- **Scientific AI:** extend Scientific Literature Agent with PDF/RAG/citation validation.
- **Product & Automation:** develop TutorOps beyond a personal prototype.

A flagship is expected to require substantially more work than the early prototypes; the goal is depth rather than project count.

---

## Project backlog

| Project | Track | MPP workload | Portfolio-ready estimate | Current status |
| --- | --- | ---: | ---: | --- |
| Scientific Data Dashboard | Scientific Computing | **6–8 h** | 18–30 h | 🔵 Learning |
| Chemistry LLM Evaluation | AI Evaluation | **8–12 h** | 25–40 h | ⚪ Planned |
| Chemistry Assessment Analyzer | AI + EdTech | **8–12 h** | 20–35 h | ⚪ Planned |
| AI Research Telegram Bot | Automation | **8–12 h** | 25–45 h | ⚪ Planned |
| Chemistry AI Safety Benchmark | Responsible AI | **8–12 h** | 20–35 h | ⚪ Planned |
| AI Textbook Evaluator | AI Evaluation + EdTech | **10–15 h** | 25–45 h | ⚪ Planned |
| Molecular Structure Toolkit | Scientific Computing | **8–15 h** | 25–45 h | ⚪ Planned |
| Multilingual STEM Explainer | AI + NLP + EdTech | **8–12 h** | 20–35 h | ⚪ Planned |
| AI Teacher Feedback Assistant | EdTech | **10–15 h** | 25–40 h | ⚪ Planned |
| Scientific Literature Agent | Scientific AI / RAG | **15–20 h** | 40–70 h | ⚪ Future |
| Multi-source Monitoring Agent | Automation | **12–18 h** | 45–80 h | ⚪ Future |
| Adaptive Chemistry Tutor | EdTech Product | **15–25 h** | 50–90 h | ⚪ Future flagship |
| TutorOps | Product / Automation | **20–30 h** | 60–100+ h | ⚪ Future flagship |
| Chemistry Knowledge Graph | Knowledge / AI | **15–25 h** | 40–70 h | ⚪ Future |

### Status legend

- 🟢 **Published** — public, documented and ready to show.
- 🟡 **Building** — active implementation.
- 🔵 **Learning** — current skills/research phase.
- ⚪ **Planned / Future** — documented idea, implementation not yet started.
- 🔒 **Private development** — implementation exists but is intentionally not public.

---

## Standard project case-study structure

When a project becomes public, its repository should explain more than the code itself:

1. **Problem** — what real-world problem exists?
2. **Goal** — what should the project achieve?
3. **Task** — what concrete requirements were defined?
4. **Solution** — how does the system address the problem?
5. **Architecture** — input → processing → model/API → validation → output.
6. **Output / Demo** — screenshots, examples, report or live demo.
7. **Validation** — how correctness and reliability were tested.
8. **Tech Stack** — technologies actually used.
9. **Limitations** — what the current version does not solve.
10. **Roadmap** — next versions and improvements.
11. **What I Learned** — technical and domain lessons from the project.

---

## Publication & IP strategy

Early implementations are intended to be **private by default**.

For each completed project, I will deliberately choose one of four publication modes:

1. **Open-source release** — full implementation is public under an explicit software license.
2. **Sanitized portfolio edition** — public code/demo uses synthetic or cleared data and excludes proprietary logic or restricted materials.
3. **Demo/documentation only** — architecture, screenshots and outputs are public while implementation remains private.
4. **Proprietary/private** — project remains private when publication would expose valuable IP, confidential data, unpublished research or third-party material.

### Materials that stay private unless explicitly cleared

- student or client data;
- private messages and credentials;
- unpublished research or manuscripts;
- confidential references or institutional documents;
- proprietary prompts, protocols or evaluation logic intended for later commercial use;
- copyrighted school, university, textbook or examination materials that are not mine to redistribute;
- original teaching datasets or assignments before a publication decision.

Public demonstrations should prefer **synthetic, self-created or explicitly licensed examples**.

Individual project repositories will define their own licensing. The existence of a project in this roadmap does not mean that its implementation, dataset or educational content is open source.

---

## Professional target

This roadmap is intended to build evidence for roles and collaborations around:

`Applied AI` · `AI Evaluation` · `EdTech` · `AI Automation` · `Scientific Software` · `Scientific Data` · `Research Technology` · `Knowledge Workflows`

The long-term objective is not to replace my scientific background with a generic software profile, but to add a strong technical layer to **chemistry, research and education domain expertise**.

---

*Roadmap started: August 2026 · Target horizon: August 2027*

**Copyright © 2026 Vadym Shved. All rights reserved.** Individual software projects may use different licenses when published.