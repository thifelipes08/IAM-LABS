
# 06 — Okta

Identity-as-a-Service — the "front door" of IAM.

---

## 📂 Structure

- 06-okta/README.md
- 06-okta/concepts/okta-overview.md
- 06-okta/concepts/universal-directory.md
- 06-okta/concepts/sso-configuration.md
- 06-okta/concepts/mfa-policies.md
- 06-okta/concepts/oin.md
- 06-okta/concepts/workflows.md
- 06-okta/okta-vs-entra.md
- 06-okta/labs/lab-01-sso-setup.md
- 06-okta/certifications/professional-notes.md

---

## 🎯 What Goes Here

- Okta concepts (Universal Directory, SSO, MFA, OIN, Workflows)
- Configuration documentation from labs
- Sign-On Policy designs and examples
- Okta Identity Governance (OIG) overview

---

## ❌ What Does NOT Go Here

- Generic protocol explanations (SAML, OIDC) → goes in 02-protocols-and-federation
- IGA governance (cert campaigns, SoD) → goes in 03-sailpoint
- Comparison Okta vs Entra ID → goes in 08-comparatives
- Python scripts for Okta API → goes in 07-automation

---

## 📌 Okta Key Concepts

| Concept | What it is | Analogy |
|---------|-----------|---------|
| OIN | Okta Integration Network — 7,000+ pre-built apps | "App Store" for SSO |
| Universal Directory | Cloud user store | "Central address book" |
| Sign-On Policy | Rules for how users authenticate | "Smart doorman" |
| Okta Workflows | No-code automation for identity events | "IFTTT for IAM" |
| OIG | Okta Identity Governance (IGA lite) | "SailPoint lite" |

---

## 📜 Certifications

| Cert | Status | Date |
|------|--------|------|
| Okta Certified Professional | 🔴 Planned (Post-plan) | — |

---

## 💡 Key Insight

> "Okta is the DOOR (authenticates with excellent UX). SailPoint is the BRAIN (governs who should have what). They complement — Okta handles the 'how you get in', SailPoint handles the 'what you should access'."

---

## 🔗 Related

- Protocols (SAML, OIDC used by Okta) → ../02-protocols-and-federation
- Governance layer above Okta → ../03-sailpoint
- Comparison Okta vs Entra → ../08-comparatives
- Okta API scripts → ../07-automation/python/okta-api
