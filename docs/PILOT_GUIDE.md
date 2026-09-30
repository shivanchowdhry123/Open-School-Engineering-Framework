# OSEF School Pilot Implementation Guide
**A 6-Week Framework for Implementing Logic-First CS Labs in High Schools (Classes 9–12)**

---

## 1. Overview & Objectives
This guide outlines a low-friction, 6-week pilot program for school principals, IT department heads, and Computer Science teachers looking to adopt the **Open School Engineering Framework (OSEF)**.

* **Target Audience:** Classes 9 to 12 (CS / IP / IT Skill Subjects)
* **Hardware Requirements:** Existing school lab PCs (No GPUs required; minimum 4GB RAM)
* **Software Requirements:** Node.js / Python, Git, Ollama (with Phi-3 / Llama-3B), self-hosted Gitea (local LAN)
* **Cost:** ₹0 (Fully Open-Source & Offline)

---

## 2. Infrastructure Setup (Pre-Pilot Week 0)

1. **Local LAN Git Forge (Gitea/Forgejo):**
   * Install Gitea on the teacher's desktop or a single main lab system.
   * Connect all student PCs via local network (LAN / Wi-Fi) to host student repositories without requiring cloud internet access.
2. **Offline AI Completion Engine (Ollama):**
   * Install Ollama on lab PCs.
   * Pull the lightweight `phi3:mini` or `llama3.2:1b` model for single-line inline code completions.
3. **IDE Setup:**
   * Install VS Code or any standard text editor with standard Git extensions.

---

## 3. 6-Week Pilot Curriculum Roadmap

### Week 1: Terminal Literacy & Version Control Logbooks
* **Focus:** Basic CLI navigation (`cd`, `ls`, `mkdir`) and local Git operations.
* **Deliverable:** Students create a local Git repository replacing traditional paper lab files. Every exercise is saved as a commit with meaningful commit messages.

### Week 2: Logic Auditing & Pseudocode Execution
* **Focus:** Reading code logic, flowchart mapping, and debugging pre-written code snippets.
* **Deliverable:** Patching intentional bugs introduced in a sample program without using AI assistance.

### Week 3: Contract-First Development & API Specs
* **Focus:** Designing REST API endpoints and data JSON structures before writing code logic.
* **Deliverable:** Writing a `schema.json` and endpoint specification document for a basic school management tool.

### Week 4: SLM Integration & Prompt Architecture
* **Focus:** Utilizing local Small Language Models (SLMs) responsibly.
* **Deliverable:** Prompting the local SLM to generate boilerplate functions, followed by a security and logic audit of the generated code.

### Week 5: Local Database & Architecture Wiring
* **Focus:** Relational schemas (PostgreSQL / SQLite) and lightweight service connections.
* **Deliverable:** Connecting a backend script to a local database and handling basic CRUD operations.

### Week 6: Pull Request (PR) Code Reviews & Capstone
* **Focus:** Code reviews, static security checks, and collaborative git merges.
* **Deliverable:** Submitting a Pull Request (PR) to the lab's local Gitea instance and conducting peer reviews.

---

## 4. Evaluation & Grading Matrix

| Component | Traditional Lab Assessment | OSEF Pilot Assessment |
| :--- | :--- | :--- |
| **Primary Artifact** | Handwritten paper lab notebook | Public / Local Git Repository |
| **Logic Evaluation** | Rote memorization of syntax | Pull Request code reviews & debugging tests |
| **AI Assessment** | Unregulated / Ban on AI | Logic auditing of SLM-generated code |
| **Final Term Project** | Static code printouts | Functional REST API / Deployed App |

---

## 5. Frequently Asked Questions for Educators

* **Q: Will this interfere with CBSE / Board Exam preparation?**  
  *A: No. OSEF map directly onto existing practical syllabus windows (30-mark internal practicals) and enhances theoretical understanding through hands-on logic execution.*
* **Q: What if the school lab loses internet connectivity?**  
  *A: OSEF is fully offline-first. Local LAN Gitea and offline SLMs via Ollama run without active internet access.*
