# 📋 Organization Profile Form
## SOC Operations Handbook — AI Builder

> **Instructions**: Fill in every field below. The more detail you provide, the more customized your generated handbook will be. Fields marked **[Required]** must be completed. Fields marked **[Optional]** improve output quality but are not mandatory.
>
> Once complete, copy this entire filled form and paste it along with the `master-prompt.md` into your AI tool.

---

## SECTION A: Organization Identity

```
Organization Name [Required]:
_________________________________

Short Name / Abbreviation [Required]:
(Used in index names, document headers, etc.)
_________________________________

Industry Sector [Required — select one]:
[ ] Stock Broker / Trading Member
[ ] Depository Participant
[ ] Asset Management Company (AMC / Mutual Fund)
[ ] Bank (Commercial / Cooperative / Payment)
[ ] Non-Banking Financial Company (NBFC)
[ ] Insurance Company
[ ] Payment System Operator
[ ] Financial Technology (FinTech)
[ ] Market Infrastructure Institution (NSE / BSE / NSDL / CDSL)
[ ] IT / Technology Services
[ ] Healthcare
[ ] Manufacturing
[ ] Government / PSU
[ ] Other: _________________

Organization Size [Required]:
[ ] Small (< 100 employees)
[ ] Medium (100–1,000 employees)
[ ] Large (1,000–10,000 employees)
[ ] Enterprise (> 10,000 employees)

Headquarters Location [Required]:
City: _________________ State: _________________ Country: India

Number of Office Locations / Branches [Optional]:
_________________________________
```

---

## SECTION B: Regulatory & Compliance Profile

```
Applicable Indian Regulations [Required — select all that apply]:
[ ] CERT-In April 2022 Directions (mandatory for all IT intermediaries)
[ ] SEBI CSCRF 2024 (SEBI-regulated entities)
[ ] RBI IT Framework / Cyber Security Framework (RBI-regulated entities)
[ ] DPDP Act 2023 (organizations processing personal data of Indians)
[ ] NSE / BSE Technology Audit requirements
[ ] IRDAI Cyber Security Guidelines (insurance sector)
[ ] Other: _________________

SEBI Entity Category [If SEBI regulated]:
[ ] Market Infrastructure Institution (MII)
[ ] Qualified Registered Entity (QRE)
[ ] Mid-size Regulated Entity
[ ] Small Regulated Entity
[ ] Not applicable

ISO / International Certifications [Optional]:
[ ] ISO 27001 certified
[ ] ISO 27001 in progress
[ ] SOC 2 Type II
[ ] PCI DSS
[ ] None currently
[ ] Other: _________________

Regulatory Audit Schedule [Optional]:
Annual SEBI audit month: _________________
NSE/BSE audit month: _________________
RBI IS audit month: _________________
```

---

## SECTION C: SOC Structure & Operations

```
SOC Type [Required — select one]:
[ ] Internal SOC (monitoring own organization only)
[ ] MSSP / Managed SOC (monitoring multiple client organizations)
[ ] Hybrid (internal SOC + some MSSP services)

SOC Operating Hours [Required]:
[ ] 24x7x365 (fully continuous)
[ ] Business hours only (Mon–Fri, 09:00–18:00)
[ ] Business hours + on-call for P1 (after hours pager/phone)
[ ] Other: _________________

Number of SOC Analysts [Required]:
L1 Analysts: _____
L2 Analysts: _____
L3 Analysts: _____
Threat Hunters: _____
SOC Manager(s): _____
Total SOC Staff: _____

Shift Model [Required]:
[ ] 3 shifts × 8 hours (24x7)
[ ] 2 shifts × 12 hours (24x7)
[ ] Single shift + on-call
[ ] Other: _________________

Number of Client Environments Monitored [For MSSP]:
_________________________________

Geographic Monitoring Scope [Required]:
[ ] Single location / campus
[ ] Multiple offices across India
[ ] India + international offices
[ ] Cloud-only environment
[ ] Hybrid on-premise + cloud
```

---

## SECTION D: Technology Stack

```
Primary SIEM Tool [Required]:
[ ] Splunk Enterprise / Splunk ES
[ ] Microsoft Sentinel
[ ] IBM QRadar
[ ] Elastic SIEM (ELK Stack)
[ ] Securonix
[ ] LogRhythm
[ ] ArcSight
[ ] Sumo Logic
[ ] Other: _________________
[ ] Not yet selected / Evaluating

EDR / Endpoint Security [Required]:
[ ] CrowdStrike Falcon
[ ] Microsoft Defender for Endpoint
[ ] SentinelOne
[ ] Elastic Defend
[ ] Symantec / Broadcom
[ ] Trend Micro
[ ] Other: _________________
[ ] None currently deployed

Threat Intelligence Platform [Optional]:
[ ] MISP
[ ] ThreatConnect
[ ] Anomali
[ ] Recorded Future
[ ] Manual / spreadsheet-based
[ ] None
[ ] Other: _________________

SOAR / Automation Tool [Optional]:
[ ] Palo Alto XSOAR / Cortex
[ ] Splunk SOAR (Phantom)
[ ] Microsoft Sentinel Automation
[ ] IBM Resilient
[ ] Custom / In-house
[ ] None currently
[ ] Other: _________________

ITSM / Ticketing Tool [Required]:
[ ] ServiceNow
[ ] Jira Service Management
[ ] Freshservice
[ ] Zendesk
[ ] ManageEngine
[ ] Other: _________________

PAM Tool [Optional]:
[ ] CyberArk
[ ] BeyondTrust
[ ] Thycotic / Delinea
[ ] None
[ ] Other: _________________

Cloud Platforms in Scope [Select all that apply]:
[ ] AWS
[ ] Microsoft Azure
[ ] Google Cloud Platform (GCP)
[ ] Oracle Cloud
[ ] Private Cloud / On-premise only
[ ] Not applicable
```

---

## SECTION E: Log Sources & Monitoring Scope

```
Log Sources Currently Monitored [Select all that apply]:
[ ] Windows Server event logs (Active Directory, Member Servers)
[ ] Windows Workstation event logs
[ ] Linux / Unix server syslogs
[ ] Firewall logs (brand: _________________)
[ ] IDS / IPS logs (brand: _________________)
[ ] Web Application Firewall (WAF)
[ ] DNS query logs
[ ] DHCP logs
[ ] VPN / Remote access logs
[ ] Email gateway logs
[ ] Web proxy / Secure web gateway logs
[ ] Cloud platform audit logs (CloudTrail, Activity Log, etc.)
[ ] EDR telemetry (endpoint process, network, file events)
[ ] Database audit logs
[ ] Application logs (custom applications)
[ ] OMS / Trading platform logs (financial sector)
[ ] Payment gateway logs
[ ] Network flow logs (NetFlow / sFlow)
[ ] Other: _________________

Approximate Total Daily Log Volume [Optional]:
[ ] < 1 GB/day
[ ] 1–10 GB/day
[ ] 10–100 GB/day
[ ] > 100 GB/day
[ ] Unknown

Number of Monitored Endpoints [Optional]:
Servers: _____
Workstations: _____
Network devices: _____
Cloud workloads: _____
```

---

## SECTION F: Incident Response & SLA

```
SLA Service Tier [Required — select one]:
[ ] Tier 1 — Premium (P1 MTTA < 5 min, MTTR < 2 hours)
[ ] Tier 2 — Standard (P1 MTTA < 5 min, MTTR < 4 hours)
[ ] Tier 3 — Basic (P1 MTTA < 5 min, MTTR < 8 hours)
[ ] Custom (describe below)

Custom SLA Details [If applicable]:
_________________________________

Incident Severity Levels Used [Required]:
[ ] P1 / P2 / P3 / P4 (Critical / High / Medium / Low)
[ ] Critical / High / Medium / Low / Informational
[ ] Sev 1 / Sev 2 / Sev 3
[ ] Other: _________________

IR Plan Current Status [Required]:
[ ] Formal IR plan exists and is tested annually
[ ] Formal IR plan exists but not recently tested
[ ] IR plan is being developed (this handbook will be first)
[ ] No formal IR plan currently

CERT-In Reporting Capability [Required]:
[ ] Process in place and tested
[ ] Process documented but not tested
[ ] Process needs to be built (this handbook will define it)
```

---

## SECTION G: Financial Sector Specifics

*(Complete only if applicable to your organization)*

```
Trading / Market Operations [If applicable]:
[ ] Algo / HFT trading operations in scope
[ ] Client order management system (OMS) monitored
[ ] Market data feed monitoring required
[ ] Exchange co-location systems in scope
[ ] FIX protocol connectivity monitored
[ ] Not applicable

Payment Operations [If applicable]:
[ ] UPI payment flows monitored
[ ] Payment gateway API monitoring required
[ ] Settlement system monitoring required
[ ] Not applicable

Financial Fraud Monitoring Priority [Select all that apply]:
[ ] Mule account detection
[ ] Market manipulation detection
[ ] Insider threat (dealer / admin monitoring)
[ ] Payout API fraud
[ ] Client account takeover
[ ] Not applicable
```

---

## SECTION H: Handbook Customization Preferences

```
Handbook Tone [Required]:
[ ] Formal / Corporate (suitable for regulatory submission)
[ ] Operational / Practical (day-to-day analyst reference)
[ ] Balanced (formal structure, practical content)

Level of Technical Detail [Required]:
[ ] Executive level (management-focused, less technical)
[ ] Operational level (analyst-ready, step-by-step procedures)
[ ] Technical level (deep technical, query examples included)

Sections to Prioritize [Select top 5]:
[ ] 01 SOC Overview & Architecture
[ ] 02 Roles & Responsibilities
[ ] 09 Incident Response & Playbooks
[ ] 10 Regulatory Reporting & Compliance
[ ] 11 Financial Fraud Monitoring
[ ] 12 SOC Governance
[ ] 13 Digital Forensics
[ ] 15 Business Continuity
[ ] 18 SOC Metrics & Reporting
[ ] 21 Training & Simulation

Sections to Exclude [If not applicable]:
[ ] 11 Financial Fraud (non-financial sector)
[ ] 20 Multi-Tenancy (internal SOC only)
[ ] Other: _________________

Document Header Preferences [Optional]:
Organization Logo Placeholder: [ ] Yes [ ] No
Document Classification Label: [ ] Yes [ ] No
Classification Level: [ ] CONFIDENTIAL [ ] INTERNAL [ ] PUBLIC
Version Numbering: [ ] Yes, start at v1.0 [ ] No
```

---

## SECTION I: Key Contacts (for Document Headers)

```
SOC Manager Name [Optional]:
_________________________________

CISO Name [Optional]:
_________________________________

Document Owner [Optional]:
_________________________________

Organization Website [Optional]:
_________________________________
```

---

## ✅ Pre-Submission Checklist

Before pasting this form into your AI tool, confirm:

- [ ] All [Required] fields are completed
- [ ] Industry sector is selected
- [ ] Regulatory frameworks are selected
- [ ] SIEM tool is identified (or "not yet selected")
- [ ] SOC type and size are filled in
- [ ] SLA tier is selected

---

*Once complete, copy this entire filled form and paste it after the content of `master-prompt.md` in your AI tool session.*
