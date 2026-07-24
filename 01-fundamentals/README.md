
# 01 — IAM Fundamentals

Core concepts of Identity and Access Management.

---

## 📂 Structure

- 01-fundamentals/README.md
- 01-fundamentals/iam-core-concepts.md
- 01-fundamentals/access-models.md
- 01-fundamentals/identity-lifecycle.md
- 01-fundamentals/governance-basics.md
- 01-fundamentals/glossary.md

---

## 🎯 What Goes Here

- Concept explanations in my own words (not copied from docs)
- Analogies and mnemonics that helped me understand
- Connections between concepts (how they relate)
- Quick-reference tables

---

## ❌ What Does NOT Go Here

- Vendor-specific content → goes in vendor folders (03, 04, 05, 06)
- Protocol deep-dives → goes in 02-protocols-and-federation
- Scripts or code → goes in 07-automation

---

## 📌 Key Concepts Covered

| Concept | One-liner |
|---------|-----------|
| IAM | "Who are you?" + "What can you do?" |
| IGA | IAM + governance layer (compliance, audit) |
| Least Privilege | Minimum access needed — nothing more |
| Zero Trust | Never trust, always verify |
| SoD | Prevent toxic access combinations |
| JML | Joiner → Mover → Leaver (full lifecycle) |
| Cert Campaign | Periodic review: "Do you still need this access?" |
| Orphan Account | Account without an owner — security risk |
| Privilege Creep | Access accumulates over time beyond need |
| RBAC | Access based on role/function, not individual |
| ABAC | Access based on attributes (context-aware) |
| Birthright Access | Automatic Day 1 access based on role |

---

## 🔗 Related

- Protocols → ../02-protocols-and-federation
- SailPoint governance → ../03-sailpoint
- Entra ID governance → ../05-microsoft-entra
- NHI Governance Policy (Project 4) → this folder
