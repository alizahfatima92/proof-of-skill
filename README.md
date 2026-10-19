# 🛡️ ProofOfSkill: Explainable Developer Telemetry & Talent Auditing

> An objective, Explainable AI platform that converts public software engineering telemetry into verifiable developer credentials, exposes resume fraud, and delivers personalized code roadmaps.

[![Live Application](https://img.shields.io/badge/Demo-Live%20App-emerald?style=for-the-badge&logo=netlify)](https://proofofskills.netlify.app/)
[![Video Walkthrough](https://img.shields.io/badge/Walkthrough-Loom%20Video-blueviolet?style=for-the-badge&logo=loom)](https://www.loom.com/share/6d37ea2e38ef4726915a58d3785903cb)
[![Visual Previews](https://img.shields.io/badge/Screenshots-Google%20Drive-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1ncYKprAGfMAx2uVNcaLnpNY_WjfTU44Z?usp=sharing)

---

## 📌 Problem Statement & Proposed Solution

### Problem Statement
In technical recruitment and developer evaluation, over 70% of entry-level resumes, online certificates, and portfolio repositories contain tutorial-cloned templates, boilerplate forks, or synthetic scripts. Recruiters waste hundreds of manual screening hours filtering inflated profiles, while self-taught developers lack structured, objective feedback on why their code fails production benchmarks.

### Proposed Solution
**ProofOfSkill** replaces resume buzzwords with automated, Explainable AI audits directly from live GitHub codebase telemetry. It detects bot/cloned code, matches self-reported resume skills against concrete commits, diagnoses production blind-spots, and executes head-to-head developer evaluations with zero demographic bias.

---

## 🤖 AI Methodology, Model Names & API Usage

* **AI Architecture & Methodology:** 
  * **Explainable AI (XAI) Framework:** Implements transparent heuristic scoring trees and deterministic telemetry auditing, ensuring zero black-box rejections.
  * **Natural Language Semantic Matcher:** Performs tokenization and fuzzy-match verification between claimed CV skills and repository metadata (package manifests, repository descriptions, linguistic distributions).
  * **Syntactic Authenticity Detection:** Evaluates parent-child commit lineage and repository source-to-fork ratios to compute code authenticity.

* **Models, Engines & APIs Used:**
  * **GitHub REST API v3:** Ingests live telemetry, commit history, repository trees, and linguistic byte arrays.
  * **Gemini Flash 1.5 Architecture (Target Ingestion Pipeline):** Powers the contextual code-review heuristics and dynamic technical interview generation.
  * **Sepolia Testnet Hash Engine:** Cryptographic hashing layer simulating tamper-evident on-chain verification logs.
  * **Responsible AI & Fairness Guardrail:** Complete data isolation preventing demographical, gender, age, or institutional bias during candidate scoring.

---

## 🚀 Core Features

1. **Authenticity & Anti-Cheat Engine:** Evaluates original source vs. forked repositories, calculating an Authenticity Score with a transparent root-cause breakdown.
2. **AI Code Blind-Spot Mentor:** Automatically identifies missing production engineering standards (testing frameworks, CI/CD pipelines, containerization) and provides a career improvement roadmap.
3. **Resume Claim vs. Reality Matcher:** Cross-checks claimed CV skills against verifiable commits to calculate an accurate Skill Match Percentage.
4. **Head-to-Head Comparison:** Enables side-by-side candidate evaluations with automated AI verdicts and downloadable PNG scorecards.
5. **On-Chain Cryptographic Proof:** Simulates tamper-proof proof hashes on Ethereum Sepolia testnet architecture.

---

## 🛠️ Technology Stack

* **Frontend:** React 19, Vite, Tailwind CSS
* **Data Layer:** GitHub REST API v3 (Asynchronous client pipeline)
* **Visuals & UI:** Lucide React, Canvas Confetti
* **Export Engine:** HTML-to-Image (PNG generation)
* **Hosting & CI/CD:** Netlify Edge Network

---

## ⚡ Setup & Installation Instructions

Follow these steps to run the project locally on your machine:

### 1. Clone the repository
```bash
git clone [https://github.com/alizahfatima92/proof-of-skill.git](https://github.com/alizahfatima92/proof-of-skill.git)
cd proof-of-skill
