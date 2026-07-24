
# SailPoint — IIQ (on-prem) + ISC (cloud) + SCIM Provisioning

> Identity Governance & Administration — the "brain" of IAM.

---

## 📂 Structure

- 03-sailpoint/README.md
- 03-sailpoint/isc/isc-overview.md
- 03-sailpoint/isc/identity-cube.md
- 03-sailpoint/isc/sources-connectors.md
- 03-sailpoint/isc/access-profiles-roles.md
- 03-sailpoint/isc/lifecycle-workflows.md
- 03-sailpoint/isc/cert-campaigns.md
- 03-sailpoint/isc/sod-policies.md
- 03-sailpoint/iiq/iiq-overview.md
- 03-sailpoint/iiq/iiq-vs-isc.md
- 03-sailpoint/iiq/rules-beanshell.md
- 03-sailpoint/iiq/task-definitions.md
- 03-sailpoint/certifications/leader/study-notes.md
- 03-sailpoint/certifications/professional/study-notes.md
- 03-sailpoint/certifications/expert/study-notes.md
- 03-sailpoint/labs/lab-01-first-source.md

---

## 🎯 What Goes Here

- ISC concepts (identity cube, sources, roles, workflows, cert campaigns)
- IIQ architecture & differences vs ISC
- Certification study notes (Leader, Professional, Expert)
- Lab documentation (what I configured, what I learned)

---

## 📌 SailPoint Hierarchy

Entitlement (atomic permission in target system) → Access Profile (bundle of entitlements for 1 source) → Role (business meaning, spans multiple sources) → Identity (person who holds roles)

---

## 📜 Certifications

| Cert | Status | Score | Date |
|------|--------|-------|------|
| Identity Security Leader | ✅ Obtained | 73.3% (22/30) | Jul 2026 |
| Identity Security Professional | 🟡 In Progress | — | — |
| Identity Security Expert | 🔴 Planned | — | — |

---

## 💡 Key Insight

> "SailPoint is the BRAIN (governs access). Okta is the DOOR (authenticates). CyberArk is the VAULT (protects admins). They complement — never compete."

---

## 🔗 Related

- API scripts → ../07-automation/python/sailpoint-api/
- Comparison with vendors → ../08-comparatives/
- Architecture diagrams → ../09-diagrams/
- Protocols (SAML, SCIM) → ../02-protocols-and-federation/
