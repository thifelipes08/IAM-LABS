
# 05 — Microsoft Entra ID & Active Directory

Microsoft identity stack — from on-prem AD to cloud Entra ID.

---

## 📂 Structure

- 05-microsoft-entra/README.md
- 05-microsoft-entra/active-directory/ad-overview.md
- 05-microsoft-entra/active-directory/users-groups-ous.md
- 05-microsoft-entra/active-directory/group-policy.md
- 05-microsoft-entra/active-directory/powershell-ad/get-users.ps1
- 05-microsoft-entra/active-directory/powershell-ad/bulk-create.ps1
- 05-microsoft-entra/active-directory/powershell-ad/group-management.ps1
- 05-microsoft-entra/entra-id/entra-overview.md
- 05-microsoft-entra/entra-id/conditional-access.md
- 05-microsoft-entra/entra-id/pim.md
- 05-microsoft-entra/entra-id/identity-protection.md
- 05-microsoft-entra/entra-id/app-registration.md
- 05-microsoft-entra/entra-id/managed-identity.md
- 05-microsoft-entra/entra-id/entra-connect.md
- 05-microsoft-entra/entra-id/access-reviews.md
- 05-microsoft-entra/sc-300/study-notes.md
- 05-microsoft-entra/sc-300/practice-labs.md
- 05-microsoft-entra/entra-vs-ad.md

---

## 🎯 What Goes Here

- AD concepts (on-prem directory, LDAP, Kerberos, GPOs)
- Entra ID concepts (cloud identity platform)
- PowerShell scripts for AD user/group management
- Conditional Access policy designs
- PIM (Privileged Identity Management) documentation
- SC-300 certification study notes
- Hybrid identity (Entra Connect: PHS, PTA, Federation)

---

## ❌ What Does NOT Go Here

- Generic protocol explanations (SAML, OIDC) → goes in 02-protocols-and-federation
- SailPoint integration with Entra → goes in 03-sailpoint
- CyberArk integration with AD → goes in 04-cyberark
- Comparison Entra vs Okta → goes in 08-comparatives
- Python/PowerShell scripts (general) → goes in 07-automation

---

## 📌 AD vs Entra ID (Quick Reference)

| Aspect | Active Directory | Entra ID |
|--------|-----------------|----------|
| Location | On-premises | Cloud |
| Protocols | LDAP, Kerberos | OAuth, OIDC, SAML |
| Policies | GPOs | Conditional Access |
| Privileged | Domain Admin (always-on) | PIM (eligible → activate → expire) |
| Auth type | Password + Kerberos ticket | MFA + Passwordless + CA |
| Hybrid | Source of truth (synced up) | Synced via Entra Connect |

---

## 📜 Certifications

| Cert | Status | Score | Date |
|------|--------|-------|------|
| SC-900 (Fundamentals) | ✅ Obtained | — | 2025 |
| SC-300 (Administrator) | 🔴 Planned (Week 91-99) | — | — |

---

## 💡 Key Insight

> "AD is NOT 'Entra ID on-prem'. They are DIFFERENT platforms that coexist via Entra Connect. AD = LDAP/Kerberos world. Entra ID = OAuth/OIDC world. Understanding both is what makes you valuable."

---

## 🔗 Related

- Protocols (LDAP, Kerberos, SAML) → ../02-protocols-and-federation
- PowerShell scripts → ../07-automation/powershell
- Comparison Entra vs Okta → ../08-comparatives
- Architecture diagrams → ../09-diagrams
- Enterprise project (Entra as Auth layer) → ../10-integrated-project
