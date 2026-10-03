# Noggin Labs 🧠

**Open-source research systems at the intersection of computational neuroscience, closed-loop neural engineering, and neuroadaptive educational technology.**


---

## 🎯 Mission

Noggin Labs develops lightweight, local-first computational systems for studying and optimizing closed-loop cognitive interactions.

Our work focuses on two complementary areas:

1. **Neural Engineering** — Quantifying end-to-end feedback latency and temporal constraints in closed-loop neural systems.
2. **Neuroadaptive Education** — Building deterministic, rule-based Socratic tutoring systems with configurable accommodations for neurodivergent learning profiles, including ADHD, autism, and dyslexia.

Our goal is to make experimental cognitive-computing systems **measurable, reproducible, inspectable, and openly accessible.**

---

## 📂 Active Repositories

### ⚛️ [Neural-Feedback-Optimization-Theory (NFOT)](https://github.com/Noggin-Labs/Neural-Feedback-Optimization-Theory)

> **The Write-Back Gap as a Trial-Level Temporal Variable in Closed-Loop Learning Systems.**

NFOT investigates the **Write-Back Gap**,

$$
L \equiv t_{\mathrm{fb}} - t_0
$$

as an empirical, trial-level temporal variable rather than treating feedback latency solely as an engineering overhead.

**Core components:**

- **NFOT Preprint v3**
- Pre-registered test protocols (**PTSP**)
- Trial-level data extraction and validation workflows
- Cross-sectional audits of public EEG/BCI datasets, including **BCI-FIT** and data from **Chandravadia et al.**
- Computational models for evaluating feedback-timing relationships

**Stack:** `Python 3` · `MNE-Python` · `NumPy` · `pandas` · `SciPy`

---

### 🤖 [noggimigo](https://github.com/Noggin-Labs/noggimigo)

> **Local Socratic AI Tutoring Engine & Neuroadaptive Scaffolding Loop.**

Noggimigo is a local-first tutoring engine designed to guide learners through mathematical and logical problems in the [Noggin](https://github.com/Noggin-Labs/Noggin) and [PenPal](https://github.com/Noggin-Labs/PenPal) platforms using structured Socratic micro-questions rather than directly generating completed solutions.

**Core components:**

- Deterministic Socratic tutoring loops
- Structured **Misconception Error Taxonomy**
  - `INVERSION_ERROR`
  - `HALVING_ERROR`
  - `INVERSE_ERROR`
- Algorithmic fallback and recovery logic
- Response-latency logging through $L_{\text{edu}}$
- Configurable scaffolding and pacing mechanisms
- Based on the paper "**Your LLM is an Incompetent AI Tutoring System**".

**Accessibility:** Feature-flagged accommodation adapters can modify text density, reading level, and pacing for different learning profiles.

---

## 🔬 Publications & Preprints

Noggin Labs' software systems provide computational and runtime components for the following research:

### 1. Neural Feedback Optimization Theory (NFOT)

**Kassim, F. A. (2026).**  
*Neural Feedback Optimization Theory (NFOT): The Write-Back Gap as a Trial-Level Temporal Variable in Closed-Loop Learning Systems.* Zenodo Preprint, v3.

**DOI:** [10.5281/zenodo.21378901](https://doi.org/10.5281/zenodo.21378901)

### 2. Your LLM is an Incompetent AI Tutoring System

**Kassim, F. A. (2026).**  
*Your LLM is an Incompetent AI Tutoring System: A Survey of AI Tutoring Paradigms, Neural Solvers, and Student Simulation Frameworks.* Zenodo Preprint.

**DOI:** [10.5281/zenodo.22975179](https://doi.org/10.5281/zenodo.22975179)

---

## 🧪 Research Principles

Noggin Labs emphasizes:

- **Local-first computation**
- **Reproducible experiments**
- **Explicit measurement over implicit assumptions**
- **Deterministic system behavior where appropriate**
- **Open-source tooling**
- **Trial-level and event-level data analysis**
- **Transparent experimental protocols**
- **Accessibility-aware system design**
- **Safety-first AI**

---

## 📬 Contact & Collaboration

Noggin Labs is an independent research workspace open to technical collaboration and critical feedback.

We welcome:

- Data-sharing collaborations
- Open-source contributions and pull requests
- Research discussion and reading groups
- Reproducibility reviews
- Technical feedback from computational neuroscience, neural engineering, and educational technology researchers

**Principal Lead:** Folarera Ayobami Kassim  
**Contact:** folarera.kassim@gmail.com
