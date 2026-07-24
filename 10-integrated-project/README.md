
# 10 — Integrated Project: Enterprise IAM Architecture

Capstone project — everything from 90 weeks connected in one design.

---

## 📂 Structure

- 10-integrated-project/README.md
- 10-integrated-project/01-business-context.md
- 10-integrated-project/02-current-state.md
- 10-integrated-project/03-target-architecture.md
- 10-integrated-project/04-gap-analysis.md
- 10-integrated-project/05-implementation-roadmap.md
- 10-integrated-project/06-governance-model.md
- 10-integrated-project/07-kpis-metrics.md
- 10-integrated-project/08-cost-roi.md
- 10-integrated-project/diagrams/enterprise-architecture.drawio
- 10-integrated-project/diagrams/enterprise-architecture.png
- 10-integrated-project/appendix/vendor-selection.md
- 10-integrated-project/appendix/nhi-policy.md

---

## 🎯 What Goes Here

- PROJECT 5 — Full enterprise IAM architecture (end-to-end)
- Business context and requirements definition
- AS-IS vs TO-BE architecture
- Gap analysis and implementation roadmap
- Governance model (RACI, cadence, ownership)
- KPIs and ROI justification
- Architecture diagrams

---

## ❌ What Does NOT Go Here

- Individual vendor deep-dives → goes in vendor folders (03, 04, 05, 06)
- Isolated scripts → goes in 07-automation
- Protocol explanations → goes in 02-protocols-and-federation
- Multi-vendor comparison (Project 2) → goes in 08-comparatives

---

## 📌 This Project Connects ALL Blocks

| Block | Represented As |
|-------|---------------|
| A-C (SailPoint) | IGA Layer |
| B (Protocols) | Integration protocols (SAML, SCIM, OIDC) |
| D (AD) | On-prem directory target |
| E (Cloud) | Multi-cloud federation |
| F (IIQ) | Hybrid architecture mention |
| G (Okta) | Authentication Layer |
| H (Keycloak) | Alternative analysis in vendor selection |
| I (Saviynt) | Vendor decision rationale |
| J, O (GRC) | Compliance mapping (SOX, LGPD, GDPR) |
| K (PowerShell) | AD automation layer |
| L-M (CyberArk) | PAM Layer |
| N (Python/SQL) | Reporting and automation |
| P (NHI/AI/ITDR) | Cross-cutting security layers |

---

## 📜 Project Deliverables

| # | Deliverable | Description |
|---|------------|-------------|
| 1 | Business Context | Fictional company, challenges, regulations |
| 2 | Current State (AS-IS) | Assessment across 7 IAM domains |
| 3 | Target Architecture (TO-BE) | Desired end-state with vendor stack |
| 4 | Gap Analysis | AS-IS vs TO-BE gaps identified |
| 5 | Implementation Roadmap | 4-phase rollout plan |
| 6 | Governance Model | RACI, cadence, ownership |
| 7 | KPIs & ROI | 10+ measurable success metrics |
| 8 | Cost & ROI | Budget justification |

---

## 💡 Key Insight

> "This project proves you can THINK like an architect — not just configure tools. It connects governance (SailPoint), authentication (Okta/Entra), privilege (CyberArk), automation (Python/PS), and compliance (GRC) into one coherent strategy."

---

## ⚠️ Status

🔴 Not Started — This folder will be populated at Week 89 (Block Q).

---

## 🔗 Related

- SailPoint (IGA layer) → ../03-sailpoint
- CyberArk (PAM layer) → ../04-cyberark
- Entra ID (Auth layer) → ../05-microsoft-entra
- Okta (Auth layer) → ../06-okta
- Automation (scripts) → ../07-automation
- Comparatives (vendor selection) → ../08-comparatives
- Diagrams (architecture) → ../09-diagrams
