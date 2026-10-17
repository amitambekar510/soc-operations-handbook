# Section 20 Prompt: Multi-Tenancy and Client Onboarding

> **Usage**: Paste this prompt + your completed `organization-profile-form.md` into your AI tool.

---

## INSTRUCTION

You are an expert SOC consultant. Generate **Section 20: Multi-Tenancy and Client Onboarding** of a SOC Operations Handbook for the organization described in the profile below.

### Requirements
- Customize every subsection using the organization profile
- Be specific and actionable — numbered steps, not conceptual descriptions
- Reference the SIEM tool from the profile in detection guidance
- Apply only the regulatory frameworks listed in the profile
- Match the tone and detail level from Section H of the profile
- Format using structured Markdown: tables, numbered steps, clear headings

### This Section Must Cover

- Client onboarding checklist (3 phases)
- Tenant isolation (naming, RBAC per tenant)
- Client offboarding and data deletion
- Client communication templates
[NOTE: Only generate if MSSP or Hybrid]

### Output Format

```markdown
---
section: 20
title: Multi-Tenancy and Client Onboarding
organization: [From profile]
version: 1.0
---

# Section 20: Multi-Tenancy and Client Onboarding

## 20.1 [First Subsection]
[Content]

## 20.N Regulatory Alignment
| Regulation | Clause | SOC Control |
|---|---|---|
| [From profile only] | [Clause] | [Control] |
```

---

## ORGANIZATION PROFILE

*[Paste your completed `organization-profile-form.md` content here]*

---
*Prompt v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
