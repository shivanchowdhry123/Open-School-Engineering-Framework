# Open School Engineering Framework (OSEF) 🚀

> **A Modern, Logic-First, and Infrastructure-Light Computer Science & Tech Curriculum for High Schools (Classes 9–12)**
>
> *Aligned with NEP 2020 | Built for Real-World Industry Readiness | Zero High-End Hardware Required*

## 📌 Executive Summary

The **Open School Engineering Framework (OSEF)** is an open-source, modernized tech curriculum specification designed for Indian high schools (CBSE/NCERT model).

Traditional high school CS education relies heavily on syntax memorization, paper-based lab notebooks, and outdated programming paradigms. OSEF shifts the focus to **computational logic, system design, logic auditing, and full-stack engineering orchestration**, using Small Language Models (SLMs) as coding assistants—mirroring how modern software engineering works in the industry.

## 🎯 Core Principles

1. **Logic-First & Architecture-First:** Syntax memorization is secondary; system design, state management, data modeling, and algorithmic reasoning come first.

2. **AI-Assisted Workflow:** Students learn to use SLMs (Phi-3, Llama-3B) for code generation while acting as **Logic Auditors** who inspect, verify, and patch bugs.

3. **Infrastructure-Light & Zero-Cost:** Designed to run entirely on low-spec school lab computers using offline local tools (Ollama, local LAN Gitea forges) or lightweight cloud sandboxes.

4. **NEP 2020 Compliant:** Replaces static paper lab practical files with live **Public GitHub Graduation Portfolios**, satisfying CBSE practical mandates without disrupting board exam preparation.

5. **Dual-Stack Readiness:** Core concepts transfer seamlessly across Web Stacks, Game Engines (Unity/Unreal), Embedded Systems, and Low-Level Systems Engineering.

## 🎓 Grade-by-Grade Progression Matrix

```
Class 9: Terminal Literacy & Computational Logic
    │
Class 10: System Architecture, API Specs & Code Auditing
    │
Class 11: Databases, Backend APIs & Self-Hosting
    │
Class 12: Full-Stack Orchestration & Live Public Portfolio

```

### 📍 Class 9: CLI & Logic Fundamentals

* **Terminal & Shell Literacy:** Navigation (`cd`, `ls`, `mkdir`), process management, environment variables, I/O redirection, piping.

* **Pure Computational Logic:** Conditionals, loops, state tracking, and functions taught via CLI mini-games and interactive terminal tools.

* **Pseudocode & Algorithms:** Writing structured flow control before touching syntax.

* **Version Control Core:** Basic Git usage (`git init`, `add`, `commit`, `log`). Commits replace traditional lab logbooks.

### 📍 Class 10: System Design & Code Auditing

* **System Architecture:** Component diagrams, data flowcharts, specs for client-server models.

* **REST API Specifications:** JSON contracts, HTTP methods, status codes, request/response cycles.

* **Structured Prompt Engineering:** Few-Shot, Chain-of-Thought (CoT), and constraint-based prompting for SLMs.

* **Pull Requests & Code Auditing:** Inspecting AI-generated code, finding deliberate security/logic bugs, and writing patches.

### 📍 Class 11: Databases & Infrastructure

* **Relational Database Schemas:** SQL fundamentals, PostgreSQL data modeling, foreign keys, normalization, and indexing.

* **Backend API Contracts:** Building REST/gRPC endpoints, routing, middleware, and authentication flow.

* **Self-Hosting Basics:** Understanding servers, ports, local networks, DNS basics, and LAN deployment.

* **Lightweight Containers:** Docker fundamentals, writing basic `Dockerfile`s, running multi-container setups via Docker Compose, and local CI/CD pipelines.

### 📍 Class 12: Production Full-Stack & Capstone

* **Full-Stack Orchestration:** Connecting relational backends to lightweight frontend interfaces.

* **AI API Integration:** Embedding local or cloud AI endpoints into applications.

* **Security & Logic Auditing:** OWASP Top 10 basics, input validation, environment secret management, and system stress-testing.

* **Live Cloud Deployment:** Publishing live projects using free-tier VPS, GitHub Pages, Render, or Vercel.

* **Public Graduation Portfolio:** Replacing paper lab files with a production-ready GitHub repository containing live project links, documentation, and commit histories.

## 🛠️ Infrastructure & Hardware Blueprint

OSEF is engineered specifically to run in **budget-constrained school computer labs**:

| Component | Cloud-Connected Setup | Offline / Low-Bandwidth Setup | 
 | ----- | ----- | ----- | 
| **Development Sandbox** | GitHub Codespaces / Replit | Local VS Code / Neovim / Terminal | 
| **Version Control** | GitHub / GitLab | Self-Hosted Gitea / Forgejo on School LAN | 
| **AI Coding Assistant** | Open-Router / Cloud APIs | Local Offline SLMs (`Phi-3-Mini`, `Llama-3.2-1B/3B` via Ollama) | 
| **Database** | Supabase / Neon (Free Tiers) | Local PostgreSQL / SQLite | 
| **Deployments** | Render / Vercel / GitHub Pages | Local LAN Server / Raspberry Pi | 

## 📝 Examination & Evaluation Framework

### Practical & Board Exam Adaptation

To ensure zero disruption to official CBSE/NCERT theory exams while measuring practical competence:

1. **Restricted AI Usage in Exams:** During practical exams, students use fine-tuned local SLMs set to **single-line autocomplete only**. Full end-to-end code generation is disabled.

2. **Logic-Auditing Practical Tests:** Students are given broken or bug-ridden codebases generated by AI and evaluated on their ability to locate, explain, and patch logic errors.

3. **Oral Vivas:** Compulsory live code defense where students explain architectural choices, data flow, and database schema designs.

4. **Portfolio Assessment:** The CBSE 30-mark internal practical grade is awarded based on the student's live GitHub Graduation Portfolio.

## 🏫 Real-World Implementation Options for Schools

Schools can implement OSEF in three non-disruptive ways:

* **Option A: Internal Skill Elective / Club (Recommended):** Run as a 1-hour/week after-school or Saturday Tech Club for Class 9 & 11 students.

* **Option B: CBSE Skill Subject Track:** Integrate into existing CBSE Skill Education subjects (e.g., Information Technology Code 402/802 or AI Code 417/843).

* **Option C: CBSE Practical Lab Replacement:** Use OSEF projects to fulfill the mandatory internal project/practical requirement for Computer Science (083) and Informatics Practices (065).

## 🤝 How to Contribute & Adopt

We welcome contributions from software engineers, educators, and curriculum researchers!

* **Educators & Principals:** Read our [School Pilot Implementation Guide](./docs/PILOT_GUIDE.md) to launch a free 6-week pilot in your school.

* **Developers:** Help us refine lab exercises, build sample logic-auditing bug suites, or optimize local SLM prompt templates in the `/curriculum` folder.

* **Policy Think Tanks:** Review our [Policy Working Paper](./docs/POLICY_BRIEF.md) for NCERT/CBSE alignment.

## 📜 License & Accreditation

This project is open-source under the **MIT License**. Schools, educators, and students are free to use, modify, and distribute this curriculum without royalty.
