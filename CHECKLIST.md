# ARM-26: Operational Readiness Checklist

The 26-point operational diagnostic used to evaluate enterprise workflows for autonomous AI agent deployment.

## Scoring Rubric
- `0`: Not met or unverified
- `1`: Partially met / in progress
- `2`: Fully documented and verified in production

---

### Pillar 1: Value & Economic Impact (Max: 6 pts)
- [ ] **1.1 Volume:** Workflow consumes 20+ hours/week or directly impacts critical revenue/churn.
- [ ] **1.2 Target Metric:** Explicit quantitative metric defined and tracked in operational software.
- [ ] **1.3 Historical Baseline:** Audited 14-day pre-deployment baseline established.

### Pillar 2: Workflow Determinism & Scope (Max: 6 pts)
- [ ] **2.1 Process Describability:** Documented step-by-step SOP with clear decision rules.
- [ ] **2.2 Judgment Ratio:** At least 70% deterministic execution vs. subjective judgment.
- [ ] **2.3 Observable Done State:** Completion recorded via an unambiguous software state change.

### Pillar 3: Systems & Data Accessibility (Max: 6 pts)
- [ ] **3.1 Interface Programmability:** Documented REST/GraphQL APIs or database connections available.
- [ ] **3.2 Historical Ground Truth:** 500+ historical completed cases available for test harnesses.
- [ ] **3.3 Credential Velocity:** Service credentials and staging access grantable within 14 days.

### Pillar 4: People, Governance & Safety (Max: 8 pts)
- [ ] **4.1 Workflow Owner:** Designated operational lead with decision-making authority.
- [ ] **4.2 Frontline Alignment:** Operators view agents as operational leverage.
- [ ] **4.3 Security Contact:** Assigned security point-of-contact for threat modeling.
- [ ] **4.4 Human Approval Gates:** Explicit human sign-off rules defined for high-risk actions.

---

### Interpretation
- **20–26 Points:** Ready for production forward-deployed engineering sprint.
- **12–19 Points:** Targeted preparation needed (fix data baseline or approval gates).
- **Under 12 Points:** Foundation remediation required before deploying autonomous systems.

Developed by [Kodense](https://kodense.ai).
