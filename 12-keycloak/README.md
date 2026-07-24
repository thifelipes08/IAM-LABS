# 12 — Keycloak

Open-source IAM — federation, brokering, and self-hosted identity.

---

## 📂 Structure

- 12-keycloak/README.md
- 12-keycloak/concepts/keycloak-overview.md
- 12-keycloak/concepts/realms.md
- 12-keycloak/concepts/clients.md
- 12-keycloak/concepts/authentication-flows.md
- 12-keycloak/concepts/user-federation.md
- 12-keycloak/concepts/identity-brokering.md
- 12-keycloak/labs/lab-01-docker-setup.md
- 12-keycloak/labs/lab-02-realm-config.md
- 12-keycloak/labs/lab-03-saml-app.md
- 12-keycloak/keycloak-vs-okta.md

---

## 🎯 What Goes Here

- Keycloak concepts (Realms, Clients, Auth Flows, Federation, Brokering)
- Docker/container setup documentation
- Lab documentation (configs, outputs, lessons learned)
- Comparison Keycloak vs commercial vendors (Okta, Entra ID)

---

## ❌ What Does NOT Go Here

- Generic protocol explanations (SAML, OIDC) → goes in 02-protocols-and-federation
- Commercial vendor configs (Okta, Entra) → goes in their folders (05, 06)
- Multi-vendor comparisons → goes in 08-comparatives
- Scripts or automation → goes in 07-automation

---

## 📌 Keycloak Key Concepts

| Concept | What it is | Commercial Equivalent |
|---------|-----------|---------------------|
| Realm | Isolated identity space | Tenant (Entra) / Org (Okta) |
| Client | App registered for auth | App Registration (Entra) |
| Authentication Flow | Configurable auth sequence | Sign-On Policy (Okta) |
| User Federation | Real-time LDAP/AD integration | AD Connector |
| Identity Brokering | Delegate auth to external IdPs | External Identities (Entra) |

---

## 📌 Keycloak Positioning

| Aspect | Detail |
|--------|--------|
| Category | Open-source IAM (Auth + SSO + Federation) |
| Model | Self-hosted (Quarkus Java runtime, Docker/K8s) |
| Cost | FREE (Apache 2.0 license) |
| Best for | Budget zero + Java dev team + full control needed |
| Trade-off | Zero license cost but YOU operate everything |

---

## 💡 Key Insight

> "Keycloak is Okta for free — same features (SSO, MFA, OIDC, SAML, brokering) but you operate everything. No devs = no maintenance = disaster waiting to happen."

---

## 🔗 Related

- Protocols used by Keycloak → ../02-protocols-and-federation
- Comparison with Okta → ../08-comparatives
- Comparison with Entra ID → ../08-comparatives
- Architecture diagrams → ../09-diagrams
