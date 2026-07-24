
# 14 — GRC (Governance, Risk & Compliance)

Regulatory frameworks and compliance applied to IAM.

---

## 📂 Structure

- 14-grc/README.md
- 14-grc/frameworks/nist-csf-overview.md
- 14-grc/frameworks/iso-27001-overview.md
- 14-grc/frameworks/cobit-overview.md
- 14-grc/regulations/sox-overview.md
- 14-grc/regulations/lgpd-overview.md
- 14-grc/regulations/gdpr-overview.md
- 14-grc/iam-compliance/iam-audit-checklist.md
- 14-grc/iam-compliance/sox-iam-controls.md
- 14-grc/iam-compliance/lgpd-identity-data.md
- 14-grc/iam-compliance/access-review-evidence.md
- 14-grc/risk/risk-scoring-models.md
- 14-grc/risk/iam-risk-register.md

---

## 🎯 What Goes Here

- Framework overviews (NIST CSF, ISO 27001, COBIT)
- Regulation summaries focused on IAM impact (SOX, LGPD, GDPR)
- IAM-specific compliance controls and audit checklists
- Risk scoring models applied to identity
- Mapping: regulation requirement → IAM control → tool/config

---

## ❌ What Does NOT Go Here

- Vendor-specific compliance configurations → goes in vendor folders (03, 04, 05, 06)
- Generic IAM concepts (SoD, cert campaigns) → goes in 01-fundamentals
- Comparatives between vendors → goes in 08-comparatives
- Scripts for audit automation → goes in 07-automation

---

## 📌 Framework Quick Reference

| Framework/Regulation | Type | IAM Relevance |
|---------------------|------|---------------|
| NIST CSF | Framework | Identify → Protect → Detect → Respond → Recover |
| ISO 27001 | Standard | A.9 Access Control (annex) |
| COBIT | Framework | Governance of enterprise IT (DSS05, DSS06) |
| SOX | Regulation (US) | Quarterly cert campaigns, SoD enforcement |
| LGPD | Regulation (Brazil) | Identity data protection, consent, data minimization |
| GDPR | Regulation (EU) | Right to erasure, data protection by design |

---

## 📌 How GRC Connects to IAM

| GRC Requirement | IAM Control | Tool |
|----------------|-------------|------|
| SOX segregation of duties | SoD policies (preventive + detective) | SailPoint ISC |
| SOX quarterly attestation | Certification campaigns | SailPoint ISC |
| LGPD data minimization | Least privilege + access reviews | Entra ID + SailPoint |
| LGPD consent management | Identity data governance | SailPoint + custom |
| ISO 27001 A.9.2.1 | User registration and de-registration | JML lifecycle |
| NIST PR.AC-1 | Identities and credentials managed | Okta/Entra + CyberArk |

---

## 💡 Key Insight

> "GRC is the WHY behind IAM. Without compliance requirements, companies wouldn't invest in IGA. SOX forces cert campaigns. LGPD forces data minimization. Understanding GRC = understanding why your job exists."

---

## 🔗 Related

- SoD and cert campaigns (tools) → ../03-sailpoint
- Conditional Access (NIST controls) → ../05-microsoft-entra
- PAM controls (SOX privileged access) → ../04-cyberark
- Enterprise project (compliance layer) → ../10-integrated-project
