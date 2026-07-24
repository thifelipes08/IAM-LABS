
# 13 — Cloud IAM

Multi-cloud identity — AWS IAM, GCP IAM, and cloud-native security.

---

## 📂 Structure

- 13-cloud-iam/README.md
- 13-cloud-iam/aws/aws-iam-overview.md
- 13-cloud-iam/aws/iam-policies.md
- 13-cloud-iam/aws/iam-roles.md
- 13-cloud-iam/aws/iam-best-practices.md
- 13-cloud-iam/aws/aws-sso.md
- 13-cloud-iam/gcp/gcp-iam-overview.md
- 13-cloud-iam/gcp/iam-roles-bindings.md
- 13-cloud-iam/gcp/workload-identity.md
- 13-cloud-iam/multi-cloud/cloud-iam-comparison.md
- 13-cloud-iam/multi-cloud/federation-patterns.md
- 13-cloud-iam/ciem/ciem-overview.md

---

## 🎯 What Goes Here

- AWS IAM concepts (policies, roles, SSO, Organizations)
- GCP IAM concepts (roles, bindings, workload identity)
- Multi-cloud federation patterns
- CIEM (Cloud Infrastructure Entitlement Management) fundamentals
- Cloud-native identity best practices

---

## ❌ What Does NOT Go Here

- Microsoft Entra ID / Azure AD → goes in 05-microsoft-entra
- Generic IAM concepts → goes in 01-fundamentals
- Vendor comparisons (AWS vs Azure vs GCP) → goes in 08-comparatives
- Python scripts for cloud APIs → goes in 07-automation

---

## 📌 Cloud IAM Models Compared

| Aspect | AWS IAM | GCP IAM | Azure (Entra ID) |
|--------|---------|---------|-------------------|
| Policy model | JSON policy documents | IAM Roles + Bindings | RBAC + Conditional Access |
| Identity type | IAM Users, Roles | Google accounts, Service accounts | Users, Groups, Service Principals |
| Federation | AWS SSO / IAM Identity Center | Workload Identity Federation | Entra ID External Identities |
| Privilege escalation control | Permission Boundaries | Deny Policies | PIM (eligible roles) |
| NHI approach | IAM Roles for services | Service Accounts + WIF | Managed Identities |
| Zero Trust | VPC + IAM + SCPs | VPC SC + IAM + Org Policies | Conditional Access + PIM |

---

## 💡 Key Insight

> "Each cloud has its OWN IAM model — they don't speak the same language. AWS thinks in policies (JSON). GCP thinks in bindings (role → member → resource). Azure thinks in assignments (role → principal → scope). Understanding all three is what makes you a multi-cloud IAM professional."

---

## 🔗 Related

- Microsoft Entra ID (Azure IAM) → ../05-microsoft-entra
- CIEM in Saviynt → ../11-saviynt
- Multi-cloud comparison → ../08-comparatives
- Federation protocols → ../02-protocols-and-federation
