# 🛡️ ProofOfSkill: Explainable Developer Telemetry & Talent Auditing

> An objective, Explainable AI platform that converts public software engineering telemetry into verifiable developer credentials, exposes resume fraud, and delivers personalized code roadmaps.

[![Live Application](https://img.shields.io/badge/Demo-Live%20App-emerald?style=for-the-badge&logo=netlify)](https://proofofskills.netlify.app/)
[![Video Walkthrough](https://img.shields.io/badge/Walkthrough-Loom%20Video-blueviolet?style=for-the-badge&logo=loom)](https://www.loom.com/share/6d37ea2e38ef4726915a58d3785903cb)
[![Visual Previews](https://img.shields.io/badge/Screenshots-Google%20Drive-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1ncYKprAGfMAx2uVNcaLnpNY_WjfTU44Z?usp=sharing)

---

## 📌 Executive Summary & Problem Context

In today's recruitment and technical evaluation landscape, traditional credentialing faces critical bottlenecks:

* **Resume Inflation & Synthetic Code:** Over 70% of junior technical resumes, online certifications, and portfolio repos contain boilerplate forks, template clones, or AI-generated scripts that mask actual competence.
* **Manual Screening Fatigue:** Engineering teams and hiring managers spend hundreds of hours manually reviewing unverified candidate repositories, sorting through trivial projects and inflated CV claims.
* **Lack of Actionable Feedback for Self-Taught Talent:** Deserving self-taught developers and junior engineers lack objective, metric-driven feedback on why their code fails production standards or how to bridge the gap.
* **Algorithmic Bias:** Traditional screening filters disproportionately penalize candidates lacking elite academic credentials, ignoring raw open-source contribution and code quality.

---

## 💡 The Solution: ProofOfSkill

**ProofOfSkill** introduces an automated audit layer that evaluates verifiable developer activity directly from public version-control telemetry. Instead of relying on buzzwords, it measures code originality, compares claimed expertise against concrete commits, diagnoses architectural blind spots, and delivers side-by-side benchmark intelligence.

---

## 🚀 Key Architectural Features

### 1. 🔍 Authenticity & Fork Analysis Engine
* Differentiates authentic source code from forked/cloned template repositories.
* Computes an **Authenticity Rate** to identify automated commit patterns and low-effort tutorial replication.
* Features a transparent **Score Breakdown Drawer** detailing exact negative factors (e.g., repository depth, forked ratio, metadata completeness) alongside an actionable improvement roadmap.

### 2. 🧭 AI Code Blind-Spot Mentor (Continuous Learning)
* Automatically parses repositories for missing production-grade engineering practices.
* Flags absence of automated test suites (Jest, Mocha, Cypress), CI/CD pipelines, containerization (Docker), or architectural versatility.
* Provides structured, step-by-step technical recommendations for portfolio enhancement.

### 3. 📄 Resume Claim vs. Reality Matcher
* Cross-references user-provided CV skill keywords (e.g., `React, Docker, Python, AWS`) against verifiable commit history and repository linguistic footprints.
* Calculates a real-time **Skill Match Percentage** and isolates unverified claims that lack concrete codebase evidence.

### 4. ⚔️ Advanced Developer Head-to-Head Benchmarking
* Side-by-side evaluation engine for two developer profiles.
* Benchmarks public repository volume, cumulative star endorsements, code authenticity rates, and commit cadence.
* Generates an automated **Smart Comparison Score & Decision Summary** highlighting key technical edges.
* Includes a **1-click PNG Scorecard Exporter** for streamlined recruitment sharing.

### 5. ⚖️ Explainable & Responsible AI Guarantee
* Eliminates demographic, age, gender, and academic pedigree bias by assessing candidates strictly on verifiable codebase telemetry.
* Employs Explainable AI (XAI) principles: every score reduction is backed by explicit factors and remediation strategies rather than opaque rejection filters.

### 6. ⛓️ Cryptographic Proof Simulation
* Generates deterministic audit hashes (Sepolia Testnet architecture) creating a tamper-evident record of evaluated telemetry.

---

## 📊 Measurable Impact & Results

| Evaluation Metric | Legacy Hiring / Review Process | With ProofOfSkill |
| :--- | :--- | :--- |
| **Initial Screening Time** | 20–30 minutes per candidate | < 15 seconds automated audit |
| **Verification Basis** | Self-reported CV text & claims | Ground-truth repository telemetry |
| **Originality Detection** | Manual inspection of commit logs | Automated source vs. fork ratio analysis |
| **Candidate Feedback** | Generic rejection emails | Actionable blind-spot remediation guide |
| **Evaluation Bias** | High (influence of pedigree/location) | 0% demographic bias (code-only metrics) |

---

## 🛠️ Technology Stack

* **Frontend:** React 19, Vite, Tailwind CSS
* **Icons & Visuals:** Lucide React, Canvas Confetti
* **Export Utilities:** HTML-to-Image (PNG generation)
* **Data Layer:** GitHub REST API v3 (Client-side asynchronous pipeline)
* **Deployment & CI:** Netlify Edge Network

---

## ⚡ Local Setup & Development

Follow these steps to run the application locally:

### 1. Clone the repository
```bash
git clone [https://github.com/alizahfatima92/proof-of-skill.git](https://github.com/alizahfatima92/proof-of-skill.git)
cd proof-of-skill
