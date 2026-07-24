
# 02 — Protocols & Federation

Authentication and authorization protocols used in IAM.

---

## 📂 Structure

- 02-protocols-and-federation/README.md
- 02-protocols-and-federation/saml/saml-overview.md
- 02-protocols-and-federation/saml/saml-flow-diagram.md
- 02-protocols-and-federation/saml/saml-vs-oidc.md
- 02-protocols-and-federation/oauth-oidc/oauth2-overview.md
- 02-protocols-and-federation/oauth-oidc/oidc-overview.md
- 02-protocols-and-federation/oauth-oidc/flows.md
- 02-protocols-and-federation/oauth-oidc/jwt-anatomy.md
- 02-protocols-and-federation/scim/scim-overview.md
- 02-protocols-and-federation/ldap-kerberos/ldap-overview.md
- 02-protocols-and-federation/ldap-kerberos/kerberos-overview.md
- 02-protocols-and-federation/comparison-table.md

---

## 🎯 What Goes Here

- Protocol explanations with flow diagrams
- Comparison tables (SAML vs OIDC vs OAuth)
- Real-world use cases ("when to use what")
- JWT decoded examples (sanitized)

---

## ❌ What Does NOT Go Here

- Vendor-specific configurations → goes in vendor folders (03, 04, 05, 06)
- General IAM concepts → goes in 01-fundamentals
- Scripts for API calls → goes in 07-automation

---

## 📌 Protocol Quick Reference

| Protocol | Category | Use Case | Format |
|----------|----------|----------|--------|
| SAML 2.0 | AuthN (SSO) | Enterprise SSO (legacy) | XML |
| OAuth 2.0 | AuthZ | Delegated authorization | JSON |
| OIDC | AuthN + AuthZ | Modern SSO + identity | JSON/JWT |
| SCIM | Provisioning | Automated user sync | JSON |
| LDAP | Directory | Query identity stores | Binary |
| Kerberos | AuthN | On-prem ticket auth | Binary |

---

## 💡 Key Insights

> "SAML = enterprise grandpa (XML). OIDC = modern grandson (JSON). Both do SSO, different era."

> "OAuth is NOT authentication. OAuth = authorization. OIDC adds identity ON TOP of OAuth."

> "SCIM = the postman. Delivers identity data between systems automatically."

---

## 🔗 Related

- Fundamentals (AuthN vs AuthZ concept) → ../01-fundamentals
- SAML config in Okta → ../06-okta
- SAML/OIDC config in Entra ID → ../05-microsoft-entra
- SCIM provisioning in SailPoint → ../03-sailpoint
