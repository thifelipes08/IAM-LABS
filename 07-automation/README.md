
# 07 — IAM Automation

Scripts, APIs, and automation for identity management.

---

## 📂 Structure

- 07-automation/README.md
- 07-automation/powershell/ad-user-management.ps1
- 07-automation/powershell/ad-group-audit.ps1
- 07-automation/powershell/bulk-operations.ps1
- 07-automation/powershell/ad-dormant-accounts.ps1
- 07-automation/python/sailpoint-api/auth.py
- 07-automation/python/sailpoint-api/list-accounts.py
- 07-automation/python/sailpoint-api/orphan-detector.py
- 07-automation/python/sailpoint-api/cert-expiry-report.py
- 07-automation/python/okta-api/list-users.py
- 07-automation/python/utils/pagination.py
- 07-automation/python/utils/csv-export.py
- 07-automation/rest-api/api-fundamentals.md
- 07-automation/rest-api/authentication-flows.md
- 07-automation/rest-api/error-handling.md
- 07-automation/sql/identity-queries.md
- 07-automation/sql/reporting-examples.sql

---

## 🎯 What Goes Here

- PowerShell scripts for AD on-prem operations
- Python scripts for cloud API integrations (SailPoint, Okta, CyberArk)
- REST API concepts, auth flows, error handling patterns
- SQL queries for identity reporting

---

## ❌ What Does NOT Go Here

- Vendor concepts/theory → goes in vendor folders (03, 04, 05, 06)
- Protocol explanations (OAuth, OIDC) → goes in 02-protocols-and-federation
- Architecture diagrams → goes in 09-diagrams
- Comparative analysis → goes in 08-comparatives

---

## 📌 When to Use What

| Tool | Use Case | Example |
|------|----------|---------|
| PowerShell | AD on-prem operations | Get-ADUser, Set-ADUser, New-ADGroup |
| Python | Cloud API integrations | SailPoint ISC API, Okta API, CyberArk PVWA API |
| SQL | Reporting & analysis | Dormant accounts, SoD violation queries |
| REST API | Interface (called by Python/PS) | GET /v3/accounts, POST /oauth/token |

---

## 📜 Projects in This Folder

| Project | Type | Output |
|---------|------|--------|
| Project 3 — Orphan Account Detector | Python + SailPoint API | orphan-detector.py |

---

## 💡 Key Insight

> "Automation is what separates a BUTTON-CLICKER from an IAM ENGINEER. If you can script it, you can scale it. If you can scale it, you're valuable."

---

## 🔗 Related

- SailPoint API context → ../03-sailpoint
- CyberArk API context → ../04-cyberark
- Okta API context → ../06-okta
- AD PowerShell context → ../05-microsoft-entra
