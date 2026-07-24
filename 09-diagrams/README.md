
# 09 — Architecture Diagrams

Visual representations of IAM architectures and flows.

---

## 📂 Structure

- 09-diagrams/README.md
- 09-diagrams/iam-reference-architecture.drawio
- 09-diagrams/saml-flow.drawio
- 09-diagrams/oidc-flow.drawio
- 09-diagrams/jml-lifecycle.drawio
- 09-diagrams/sailpoint-integration.drawio
- 09-diagrams/cyberark-architecture.drawio
- 09-diagrams/conditional-access-logic.drawio
- 09-diagrams/nhi-governance-framework.drawio
- 09-diagrams/enterprise-project.drawio
- 09-diagrams/exports/iam-reference-architecture.png
- 09-diagrams/exports/saml-flow.png
- 09-diagrams/exports/oidc-flow.png

---

## 🎯 What Goes Here

- Architecture diagrams (draw.io files)
- Protocol flow diagrams (SAML, OIDC, OAuth sequences)
- Integration diagrams (how vendors connect to each other)
- PNG exports for quick viewing (in exports/ subfolder)

---

## ❌ What Does NOT Go Here

- Written explanations of protocols → goes in 02-protocols-and-federation
- Vendor-specific documentation → goes in vendor folders (03, 04, 05, 06)
- Code or scripts → goes in 07-automation

---

## 🛠️ Tools Used

| Tool | Format | Use Case |
|------|--------|----------|
| draw.io | .drawio | Complex architecture diagrams (visual, drag-and-drop) |
| Mermaid | inside .md files | Simple flows (renders directly in GitHub) |
| PNG export | .png | Quick preview without opening draw.io |

---

## 📌 Diagrams Built Progressively

| When | Diagram | File |
|------|---------|------|
| After Block B | Protocol flows (SAML, OIDC) | saml-flow.drawio, oidc-flow.drawio |
| After Block D-E | Entra ID + AD + Cloud architecture | conditional-access-logic.drawio |
| After Block F | SailPoint integration map | sailpoint-integration.drawio |
| After Block I | Multi-vendor stack diagram | iam-reference-architecture.drawio |
| After Block M | CyberArk architecture | cyberark-architecture.drawio |
| After Block P | NHI governance framework | nhi-governance-framework.drawio |
| After Block Q | Full enterprise architecture (PROJECT 5) | enterprise-project.drawio |

---

## 💡 Key Insight

> "A picture is worth a thousand words. In IAM interviews, being able to DRAW an architecture on a whiteboard separates senior from junior. These diagrams are your whiteboard practice."

---

## 🔗 Related

- Protocol context → ../02-protocols-and-federation
- SailPoint architecture → ../03-sailpoint
- CyberArk architecture → ../04-cyberark
- Entra ID architecture → ../05-microsoft-entra
- Enterprise project (final diagram) → ../10-integrated-project
