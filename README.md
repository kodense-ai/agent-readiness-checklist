<div align="center">

# ARM-26: Enterprise AI Agent Readiness Matrix

**The 26-Point Pre-Deployment Operational Diagnostic for Autonomous AI Agents**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Maintained by Kodense](https://img.shields.io/badge/Maintained%20by-Kodense.ai-indigo.svg)](https://kodense.ai)

</div>

---

### Overview

The **ARM-26** is an open diagnostic framework designed by [Kodense](https://kodense.ai) to assess whether an enterprise workflow has the structural, operational, and safety maturity required for autonomous AI agent deployment.

Most enterprise AI pilot failures stem from deploying models onto undefined or broken workflows. ARM-26 evaluates workflows across 4 core pillars to ensure teams only automate processes with measurable ROI and deterministic boundaries.

### Core Evaluation Pillars

1. **Value & Economic Impact (6 pts):** Volume, quantitative metric, baseline measurements.
2. **Workflow Determinism (6 pts):** Process describability, judgment vs. execution ratio, observable done state.
3. **Systems & Data Access (6 pts):** API programmability, historical ground truth logs, credential velocity.
4. **People, Governance & Safety (8 pts):** Accountable owner, frontline alignment, security sign-off, human approval gates.

---

### Quick Start (Interactive CLI)

Clone the repository and run the zero-dependency assessment CLI:

```bash
git clone https://github.com/kodense-ai/agent-readiness-checklist.git
cd agent-readiness-checklist
python arm26.py
```

The CLI walks through the 13 criteria, calculates your operational readiness score (0 to 26), and outputs a timestamped evaluation report in Markdown.

---

### Printable / Fillable Matrix

See [CHECKLIST.md](./CHECKLIST.md) for a quick markdown checklist you can include in PRs, design docs, or architectural reviews.

### Reference & Engineering Analysis

Read the in-depth technical analysis and case studies on the [Kodense Engineering Blog](https://kodense.ai/blog/ai-agent-readiness-checklist/).

### License

Distributed under the MIT License. Copyright &copy; 2026 [KODENSE PRIVATE LIMITED](https://kodense.ai).
