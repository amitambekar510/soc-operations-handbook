# 🤖 Master Prompt — Full SOC Handbook Generation

> **How to use**: Copy everything below this line, then paste your completed `organization-profile-form.md` after it into your AI tool. The AI will generate all 21 sections of your customized SOC Operations Handbook.

---

## MASTER INSTRUCTION FOR AI

You are an expert SOC (Security Operations Centre) consultant and technical writer. Your task is to generate a complete, professional SOC Operations Handbook for the organization described in the profile below.

### Your Output Requirements

1. **Generate all 21 sections** listed in the section index below, in order
2. **Customize every section** using the organization profile provided — do not use generic placeholders
3. **Use the organization's actual SIEM tool name** throughout detection and query guidance
4. **Apply only the regulatory frameworks** listed in the organization's profile
5. **Scale procedures to the team size** described in the profile
6. **Use the correct SOC type perspective** — Internal SOC sections differ from MSSP sections
7. **Format every section** using the structure template at the bottom of this prompt
8. **Be specific and actionable** — every procedure must be step-by-step, not conceptual

### Writing Standards
- Professional, clear English — no jargon without explanation
- Procedures written in numbered steps
- Tables used for reference information
- Bold used for critical terms and action items
- Regulatory references cited with section/clause numbers where known
- MITRE ATT&CK technique IDs referenced where relevant (e.g., T1078, T1566)

### Section Index — Generate All 21

| # | Section Title | Key Content to Cover |
|---|---|---|
| 01 | SOC Overview & Architecture | SOC purpose, architecture model, SIEM design principles, high availability, security zones, multi-tenancy (if MSSP) |
| 02 | Roles & Responsibilities | All SOC roles with JDs, RACI matrix, shift schedule, escalation hierarchy |
| 03 | Threat Intelligence | TI lifecycle, IOC management, TLP framework, threat actor profiling, TI sources |
| 04 | Network & Connectivity | Log forwarding architecture, network requirements, encryption, NTP, VPN/tunnel design |
| 05 | SIEM Integration & Log Sources | Log source onboarding procedure, parser development, field normalization, enrichment pipeline, all major log source types |
| 06 | SIEM Operations & Alert Management | Alert lifecycle, triage procedure, dashboard design, detection rule management, shift operations, handover |
| 07 | Threat Intelligence Operations | TI platform operations, IOC lifecycle, hunt hypothesis library, PIR, sharing framework |
| 08 | Threat Hunting | Hunt methodology, data sources, ATT&CK integration, sector-specific hunt queries, KPIs |
| 09 | Incident Response & Playbooks | Full IR lifecycle, alert playbooks, escalation matrix, CERT-In 6-hour workflow, War Room, evidence handling, closure criteria |
| 10 | Regulatory Reporting & Compliance | All applicable regulatory frameworks, reporting workflows, audit evidence, compliance calendar |
| 11 | Financial Fraud & Abuse Monitoring | Include only if organization profile indicates financial sector |
| 12 | SOC Governance | Governance structure, policy framework, risk management, asset classification, documentation management |
| 13 | Digital Forensics & Evidence Handling | Evidence collection, chain of custody, memory analysis, forensic reporting |
| 14 | SOC Service Management | SLA framework, reporting catalogue, breach handling, customer feedback, SIP |
| 15 | SOC Business Continuity | BCP, DR architecture, failover, crisis communication, RTO/RPO, MTTD/MTTR |
| 16 | Knowledge Management & Runbooks | Runbook lifecycle, runbook template, knowledge base architecture |
| 17 | Vendor & Third-Party Monitoring | Vendor log monitoring, API monitoring, risk assessment, access review |
| 18 | SOC Metrics & Reporting | KPI framework, FPR analysis, analyst productivity, monthly report template |
| 19 | Best Practices in SOC | Key best practices relevant to organization's sector and technology stack |
| 20 | Multi-Tenancy & Client Onboarding | Include only if SOC type is MSSP or Hybrid |
| 21 | SOC Training & Simulation | Tabletop exercises, Red/Blue/Purple team, drill schedule, analyst onboarding plan |

### Section Output Format

For each section, use this exact structure:

```markdown
---
section: [NN]
title: [Section Title]
organization: [Organization Name from profile]
version: 1.0
generated: [Current Date]
applicable_regulations: [From profile]
---

# Section [NN]: [Title]

> **Organization**: [Organization Name]
> **Document Classification**: [From profile preferences]
> **Version**: 1.0

---

## [NN.1] [First Subsection Title]

[Content — specific, actionable, customized to org profile]

### [Sub-subsection if needed]

[Content]

---

## [NN.N] Regulatory Alignment

| Regulation | Applicable Clause / Requirement | SOC Control |
|---|---|---|
| [Only regulations from org profile] | [Specific clause] | [How this section addresses it] |

---
*Section [NN] of [Organization Name] SOC Operations Handbook v1.0*
```

### Customization Rules

Apply these rules throughout every section:

1. **Organization Name**: Use exact org name from profile everywhere a generic reference would appear
2. **SIEM Queries**: Provide query examples in the syntax of the SIEM tool from profile; if "not yet selected" use generic pseudocode
3. **Regulatory Filtering**: Only reference regulations the org has selected in their profile; do not add others
4. **Team Sizing**: Shift schedules, escalation paths, and capacity models must reflect the exact team size from profile
5. **Financial Fraud Section**: Only generate Section 11 if org is financial sector; skip entirely for non-financial orgs
6. **Multi-Tenancy Section**: Only generate Section 20 if SOC type is MSSP or Hybrid; adapt for Internal SOC otherwise
7. **SLA Values**: Use the SLA tier from profile throughout all service management and IR sections
8. **Tone**: Match the tone selected in Section H of the profile

### Final Output Format

After generating all sections, provide:

```
## Handbook Generation Summary

Organization: [Name]
Sections Generated: [List]
Sections Skipped: [List with reason]
Regulatory Frameworks Applied: [List]
SIEM Tool: [Tool name]
Total Sections: [Count]

## Recommended Next Steps
1. Review each section for organizational accuracy
2. Replace any remaining [PLACEHOLDER] values
3. Add organization logo and branding
4. Have senior SOC analyst review technical procedures
5. Obtain CISO or SOC Manager sign-off before operational use
6. Schedule first tabletop exercise using Section 21 scenarios
```

---

## ORGANIZATION PROFILE

*[Paste your completed organization-profile-form.md content here]*

---

*Prompt version 1.0 | SOC Operations Handbook Framework | github.com/amitambekar510/soc-operations-handbook*
