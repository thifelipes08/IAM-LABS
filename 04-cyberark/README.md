
# 04 — CyberArk PAM

Privileged Access Management — the "vault" of IAM.

---

## 📂 Structure

- 04-cyberark/README.md
- 04-cyberark/concepts/pam-overview.md
- 04-cyberark/concepts/vault-architecture.md
- 04-cyberark/concepts/session-isolation.md
- 04-cyberark/concepts/credential-rotation.md
- 04-cyberark/concepts/zero-standing-privilege.md
- 04-cyberark/concepts/epm.md
- 04-cyberark/concepts/conjur-secrets.md
- 04-cyberark/privilege-cloud/cloud-overview.md
- 04-cyberark/privilege-cloud/connector-setup.md
- 04-cyberark/certifications/cde-access-notes.md
- 04-cyberark/certifications/cde-epm-notes.md
- 04-cyberark/certifications/cde-cloud-notes.md
- 04-cyberark/certifications/cde-conjur-notes.md
- 04-cyberark/certifications/cde-identity-notes.md
- 04-cyberark/labs/lab-01-basic-vault.md

---

## 🎯 What Goes Here

- PAM concepts explained with the "bank analogy"
- CyberArk architecture (components and how they interact)
- CDE certification study notes (5 certs)
- Privilege Cloud specifics
- Lab documentation

---

## ❌ What Does NOT Go Here

- IGA governance (cert campaigns, SoD) → goes in 03-sailpoint
- SSO / MFA configuration → goes in 05-microsoft-entra or 06-okta
- Python scripts for CyberArk API → goes in 07-automation
- CyberArk vs other vendors → goes in 08-comparatives

---

## 📌 CyberArk as a Bank (Analogy)

| Component | Bank Analogy | Function |
|-----------|-------------|----------|
| Vault | Safe room | Stores credentials encrypted |
| CPM | Lock changing service | Rotates passwords automatically |
| PSM | Security camera | Records all privileged sessions |
| PVWA | Bank counter | Web interface for users |
| Safe | Locked folder inside vault | Logical container for credentials |
| EPM | Building security | Removes local admin from endpoints |
| Conjur | Robot vault | Secrets for machines/apps (NHI) |

---

## 📜 Certifications

| Cert | Status | Date |
|------|--------|------|
| CDE Access | 🔴 Planned | — |
| CDE EPM | 🔴 Planned | — |
| CDE Cloud | 🔴 Planned | — |
| CDE Conjur | 🔴 Planned | — |
| CDE Identity | 🔴 Planned | — |

---

## 💡 Key Insight

> "CyberArk protects the TOP 1% of accounts (admin/root). SailPoint governs 100%. They don't compete — they complement. SailPoint decides WHO should have privileged access. CyberArk protects HOW that access is used."

---

## 🔗 Related

- Governance of privileged accounts → ../03-sailpoint
- PowerShell/Python scripts → ../07-automation
- PAM vs IGA comparison → ../08-comparatives
- Architecture diagrams → ../09-diagrams
