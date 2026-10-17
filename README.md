# 📘 SOC Operations Handbook

<div align="center">

![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-Custom--Open--Use-green?style=for-the-badge)
![Sections](https://img.shields.io/badge/Sections-21-orange?style=for-the-badge)
![AI Ready](https://img.shields.io/badge/AI--Ready-Yes-purple?style=for-the-badge)
![Regulatory](https://img.shields.io/badge/Regulatory-CERT--In%20%7C%20SEBI%20%7C%20RBI%20%7C%20DPDP-red?style=for-the-badge)

**A comprehensive, SIEM-agnostic SOC Operations Handbook framework — designed to help security teams build, update, or audit their own SOC playbooks in a fraction of the time.**

[📖 Read the Handbook](#-handbook-sections) · [🤖 AI Builder](#-ai-builder) · [📋 Templates](#-templates) · [🏛️ Compliance](#-indian-regulatory-compliance) · [🤝 Contribute](#-contributing)

</div>

---

## 🎯 What Is This Project?

The **SOC Operations Handbook** is an open-source framework that gives security professionals a **complete, structured, ready-to-customize** foundation for building their own Security Operations Centre documentation.

Whether you are:
- **Building a SOC from scratch** and need a complete operational framework
- **Updating an existing SOC handbook** that has grown outdated
- **Preparing for a SEBI, CERT-In, or RBI audit** and need structured compliance evidence
- **Running an MSSP** and need a scalable, client-ready documentation framework
- **Using an AI tool** to generate your handbook automatically

— this project gives you everything you need.

> 💡 **AI-Ready Design**: Every section is structured so you can feed it to any AI tool (Claude, ChatGPT, Microsoft Copilot, Gemini) along with your organization profile and generate a **complete, customized SOC handbook in a single session**. See the [AI Builder](#-ai-builder) section.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🏗️ **21 Complete Sections** | Covers every domain of SOC operations from governance to training |
| 🤖 **AI Builder** | Master prompt + org profile form → complete handbook in one shot |
| 🏛️ **Indian Regulatory Aligned** | CERT-In, SEBI CSCRF, RBI IT Framework, DPDP Act 2023 |
| 🔧 **SIEM-Agnostic** | Works with Splunk, Microsoft Sentinel, IBM QRadar, ELK, or any SIEM |
| 💼 **Financial Sector Focus** | Deep coverage of trading, broking, banking, and NBFC operations |
| 📋 **Ready-to-Use Templates** | Chain of custody, incident report, CERT-In notification, and more |
| ✅ **Operational Checklists** | Onboarding, audit readiness, BCP activation, shift handover |
| 🎯 **MITRE ATT&CK Integrated** | Detection guidance mapped to ATT&CK techniques throughout |
| 🌐 **GitHub Pages** | Read online at [amitambekar510.github.io/soc-operations-handbook](https://amitambekar510.github.io/soc-operations-handbook) |

---

## 📂 Repository Structure

```
soc-operations-handbook/
│
├── README.md                          ← You are here
├── LICENSE.md                         ← Usage terms
├── CONTRIBUTING.md                    ← How to contribute
├── CHANGELOG.md                       ← Version history
│
├── handbook-sections/                 ← 21 complete handbook sections (Markdown)
│   ├── 01-soc-overview-architecture.md
│   ├── 02-roles-responsibilities.md
│   └── ... (all 21 sections)
│
├── ai-builder/                        ← AI-powered handbook generation
│   ├── README.md                      ← How to use the AI builder
│   ├── master-prompt.md               ← Single prompt to generate full handbook
│   ├── organization-profile-form.md   ← Fill this → AI customizes for you
│   └── section-prompts/               ← Per-section AI generation prompts
│
├── templates/                         ← Ready-to-use document templates
├── checklists/                        ← Standalone operational checklists
├── compliance/                        ← Indian regulatory reference material
├── mitre-attack/                      ← MITRE ATT&CK coverage guides
└── docs/                              ← GitHub Pages website source
```

---

## 📖 Handbook Sections

All 21 sections are available in the [`handbook-sections/`](./handbook-sections/) folder. Each section is written in structured Markdown — readable directly on GitHub and AI-friendly for customization.

| # | Section | Key Topics |
|---|---|---|
| 01 | [SOC Overview & Architecture](./handbook-sections/01-soc-overview-architecture.md) | SOC purpose, architecture models, SIEM design, HA, multi-tenancy |
| 02 | [Roles & Responsibilities](./handbook-sections/02-roles-responsibilities.md) | L1-L3 analyst roles, RACI, shift model, MSSP dual roles |
| 03 | [Threat Intelligence](./handbook-sections/03-threat-intelligence.md) | TI lifecycle, IOC management, MISP, TLP, threat actor profiling |
| 04 | [Network & Connectivity](./handbook-sections/04-network-connectivity.md) | Log forwarding architecture, VPN, encryption, NTP, segmentation |
| 05 | [SIEM Integration & Log Sources](./handbook-sections/05-siem-integration-log-sources.md) | Log source onboarding, parsers, enrichment, cloud, EDR, IAM |
| 06 | [SIEM Operations & Alert Management](./handbook-sections/06-siem-operations-alert-management.md) | Alert lifecycle, triage, dashboards, rule tuning, shift operations |
| 07 | [Threat Intelligence Operations](./handbook-sections/07-threat-intelligence-operations.md) | TI platform ops, sharing framework, PIR, hunt hypothesis |
| 08 | [Threat Hunting](./handbook-sections/08-threat-hunting.md) | Hunt methodology, data sources, ATT&CK integration, KPIs |
| 09 | [Incident Response & Playbooks](./handbook-sections/09-incident-response-playbooks.md) | IR lifecycle, playbooks, CERT-In workflow, War Room, evidence |
| 10 | [Regulatory Reporting & Compliance](./handbook-sections/10-regulatory-reporting-compliance.md) | SEBI CSCRF, CERT-In reporting, RBI, DPDP Act, audit calendar |
| 11 | [Financial Fraud & Abuse Monitoring](./handbook-sections/11-financial-fraud-monitoring.md) | Mule accounts, market manipulation, HFT, insider threat, UPI |
| 12 | [SOC Governance](./handbook-sections/12-soc-governance.md) | Governance structure, policy framework, risk management, RACI |
| 13 | [Digital Forensics & Evidence Handling](./handbook-sections/13-digital-forensics-evidence.md) | Evidence collection, CoC, memory analysis, retention, reporting |
| 14 | [SOC Service Management](./handbook-sections/14-soc-service-management.md) | SLA framework, reporting, breach handling, CSAT, SIP |
| 15 | [SOC Business Continuity](./handbook-sections/15-soc-business-continuity.md) | BCP, DR, failover, crisis communication, RTO/RPO, MTTD/MTTR |
| 16 | [Knowledge Management & Runbooks](./handbook-sections/16-knowledge-management-runbooks.md) | Runbook lifecycle, KB architecture, search, governance |
| 17 | [Vendor & Third-Party Monitoring](./handbook-sections/17-vendor-third-party-monitoring.md) | Vendor logs, API monitoring, risk assessment, access review |
| 18 | [SOC Metrics & Reporting](./handbook-sections/18-soc-metrics-reporting.md) | KPI framework, FPR analysis, analyst productivity, monthly report |
| 19 | [Best Practices in SOC](./handbook-sections/19-best-practices.md) | 25 best practice domains: zero-day, cloud, ZTA, SOAR, ELK hardening |
| 20 | [Multi-Tenancy & Client Onboarding](./handbook-sections/20-multi-tenancy-client-onboarding.md) | Tenant isolation, onboarding checklist, offboarding, templates |
| 21 | [SOC Training & Simulation](./handbook-sections/21-training-simulation.md) | Tabletop exercises, Red/Blue team, Purple team, drill schedule |

---

## 🤖 AI Builder

The AI Builder is what makes this project unique. It allows you to generate a **complete, customized SOC handbook** for your organization using any AI tool — in a single session.

### How It Works

```
Step 1: Fill in your organization profile
        ↓
Step 2: Copy the master prompt + your profile into any AI tool
        ↓
Step 3: AI generates all 21 sections customized for your organization
        ↓
Step 4: Your complete SOC handbook is ready
```

### Files

| File | Purpose |
|---|---|
| [`ai-builder/organization-profile-form.md`](./ai-builder/organization-profile-form.md) | Fill this with your org details |
| [`ai-builder/master-prompt.md`](./ai-builder/master-prompt.md) | Single prompt to generate full handbook |
| [`ai-builder/section-prompts/`](./ai-builder/section-prompts/) | Individual prompts per section |
| [`ai-builder/output-templates/`](./ai-builder/output-templates/) | Structured output formats |

> 📖 See the full [AI Builder Guide](./ai-builder/README.md) for step-by-step instructions.

---

## 📋 Templates

Ready-to-use document templates you can copy directly into your handbook:

| Template | Use Case |
|---|---|
| [Chain of Custody Form](./templates/chain-of-custody-form.md) | Digital forensics evidence tracking |
| [Incident Report Template](./templates/incident-report-template.md) | P1/P2 formal incident documentation |
| [CERT-In Notification Template](./templates/cert-in-notification-template.md) | Mandatory 6-hour regulatory notification |
| [Monthly SOC Report Template](./templates/monthly-soc-report-template.md) | Client/management monthly reporting |
| [Risk Register Template](./templates/risk-register-template.md) | Cybersecurity risk tracking |
| [SLA Framework Template](./templates/sla-framework-template.md) | Service level agreement documentation |
| [Vendor Risk Assessment Template](./templates/vendor-risk-assessment-template.md) | Third-party vendor security assessment |

---

## ✅ Checklists

Standalone operational checklists for key SOC processes:

| Checklist | Use Case |
|---|---|
| [Client Onboarding Checklist](./checklists/client-onboarding-checklist.md) | 20-item onboarding process |
| [Audit Readiness Checklist](./checklists/audit-readiness-checklist.md) | SEBI/CERT-In/ISO audit preparation |
| [Analyst Shift Handover](./checklists/analyst-shift-handover.md) | Clean shift transition |
| [SOC BCP Activation](./checklists/soc-bcp-activation.md) | Business continuity activation |
| [DR Failover Checklist](./checklists/dr-failover-checklist.md) | Disaster recovery switchover |

---

## 🏛️ Indian Regulatory Compliance

This framework is aligned with Indian cybersecurity regulations applicable to financial sector organizations:

| Regulation | Coverage |
|---|---|
| [CERT-In April 2022 Directions](./compliance/cert-in-incident-categories.md) | 20 mandatory incident categories, 6-hour reporting |
| [SEBI CSCRF 2024](./compliance/sebi-cscrf-control-mapping.md) | Full control domain mapping for regulated entities |
| [DPDP Act 2023](./compliance/dpdp-act-2023-obligations.md) | Data protection obligations for SOC operations |
| [RBI IT Framework](./compliance/rbi-it-framework-reference.md) | IS audit, cyber security return, incident reporting |

---

## 🎯 MITRE ATT&CK Integration

| Resource | Description |
|---|---|
| [Financial Sector Techniques](./mitre-attack/financial-sector-techniques.md) | ATT&CK techniques most relevant to financial sector SOCs |
| [Detection Coverage Guide](./mitre-attack/detection-coverage-guide.md) | How to measure and improve ATT&CK detection coverage |

---

## 🚀 Getting Started

### Option A — Use the AI Builder (Fastest)
```
1. Open ai-builder/organization-profile-form.md
2. Fill in your organization details
3. Open ai-builder/master-prompt.md
4. Paste both into Claude / ChatGPT / Copilot
5. Your handbook is generated automatically
```

### Option B — Manual Customization
```
1. Clone this repository
   git clone https://github.com/amitambekar510/soc-operations-handbook.git

2. Navigate to handbook-sections/
3. Open each section .md file
4. Replace [PLACEHOLDER] values with your organization details
5. Add your SIEM-specific query examples
6. Save and compile into your final document
```

### Option C — Pick and Choose
```
1. Browse the section index above
2. Download only the sections relevant to your SOC
3. Use templates/ and checklists/ as standalone resources
4. Reference compliance/ for regulatory alignment
```

---

## 👥 Who Is This For?

| Role | How to Use This Project |
|---|---|
| **SOC Manager** | Build or audit your complete SOC operational framework |
| **L3 / Senior Analyst** | Reference playbooks, detection guidance, and best practices |
| **MSSP** | Scalable handbook framework for multi-client service delivery |
| **Compliance Officer** | CERT-In, SEBI, RBI regulatory mapping and evidence templates |
| **Security Consultant** | Accelerate SOC assessment and documentation engagements |
| **SOC Architect** | Architecture patterns, integration guides, multi-tenancy design |
| **New SOC Team** | Complete foundation to build your SOC operations from Day 1 |

---

## 📊 Project Stats

- **21 Handbook Sections** covering the complete SOC operations lifecycle
- **7 Ready-to-use Templates** for common SOC documents
- **5 Operational Checklists** for critical processes
- **4 Indian Regulatory Frameworks** mapped and referenced
- **25 Best Practice Domains** in Section 19
- **6 Tabletop Exercise Scenarios** in Section 21
- **12-Week Analyst Onboarding Plan** in Section 21

---

## 🤝 Contributing

Contributions are welcome! If you have improvements, additional sections, or SIEM-specific examples to add:

1. Read [CONTRIBUTING.md](./CONTRIBUTING.md)
2. Fork the repository
3. Create a feature branch (`git checkout -b improvement/section-name`)
4. Commit your changes
5. Open a Pull Request

See [open issues](https://github.com/amitambekar510/soc-operations-handbook/issues) for areas where contributions are needed.

---

## 📜 License

This project is published under a **Custom Open-Use License**. See [LICENSE.md](./LICENSE.md) for full terms.

**In summary:**
- ✅ Free to use for internal SOC documentation
- ✅ Free to use for educational and non-profit purposes
- ✅ Free to fork and modify
- ✅ Contributions welcome via Pull Request
- ⚠️ Credit required: *"Based on soc-operations-handbook by Amit Ambekar"*
- ❌ Cannot be resold as a standalone product or course
- ❌ Cannot be rebranded as original work

---

## 👤 Author

**Amit Ambekar**
- GitHub: [@amitambekar510](https://github.com/amitambekar510)
- Project: [soc-operations-handbook](https://github.com/amitambekar510/soc-operations-handbook)

---

## ⭐ Support This Project

If this project helped you build or improve your SOC handbook, please consider:
- ⭐ **Starring this repository** — helps others discover it
- 🍴 **Forking it** — to build your own customized version
- 🐛 **Opening issues** — to suggest improvements
- 🤝 **Contributing** — to make it better for everyone

---

<div align="center">

**Built for the Indian cybersecurity community. Open for the world.**

*Helping security teams spend less time documenting and more time defending.*

</div>
