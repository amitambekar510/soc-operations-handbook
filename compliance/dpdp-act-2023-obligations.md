---
title: DPDP Act 2023 SOC Obligations
regulation: Digital Personal Data Protection Act 2023
applicability: Organizations processing personal data of Indian citizens
---

# Digital Personal Data Protection Act 2023 — SOC Obligations

> **Source**: Digital Personal Data Protection Act, 2023 (Act No. 22 of 2023)
> **Note**: Detailed rules are pending notification by the Data Protection Board of India. This reference is based on the Act's stated requirements and international best practice.

---

## SOC Role Under DPDP Act

The SOC operates in two capacities under the DPDP Act:

| Role | Description |
|---|---|
| **Data Processor** | Processing client employee and customer data within security logs on behalf of client Data Fiduciaries |
| **Data Fiduciary** | For its own staff data and internal operations |

---

## Key DPDP Obligations for SOC Operations

| Obligation | Requirement | SOC Implementation |
|---|---|---|
| Lawful Basis | Personal data processed only with consent or for legitimate purpose (security monitoring qualifies as legitimate use where disclosed) | Client SSA documents lawful basis; client confirms employment contracts disclose monitoring |
| Data Minimization | Only collect personal data necessary for security purposes | Log pipeline reviewed for unnecessary PII; HTTP request bodies not logged by default |
| Purpose Limitation | Security log data cannot be used for HR performance, marketing, or commercial analytics | SIEM RBAC prevents access by non-security roles; documented in DPA |
| Data Principal Rights | Rights to access, correction, and erasure of personal data | Data Principal Request process; erasure via SIEM delete-by-query; 30-day processing SLA |
| Data Localisation | Personal data of Indian citizens must remain within India | All SIEM nodes in Indian data centers; S3 in ap-south-1 (Mumbai) |
| Breach Notification | Notify Data Protection Board and affected individuals of personal data breaches | DPDP breach notification template; SOC notifies client DPO within 24-72 hours |
| Processor Obligations | Process only per client instructions; assist client in DPDP compliance; delete data after contract; allow audits | DPA signed with all clients; data deletion procedure (Section 20.3) |

---

## PII Categories in SOC Logs — Handling Guide

| PII Category | Presence in SOC Logs | Handling |
|---|---|---|
| Usernames / Employee IDs | Authentication, application logs | Retained in full; RBAC restricted |
| IP Addresses (personal devices) | Network, firewall logs | Full IP in investigation; masked in bulk analytics |
| Email Addresses | Email gateway, application logs | Local part masked in dashboards; full visible to L2+ during investigation |
| Financial Transaction Data | Trading/payment logs | Restricted index; L3+ access only; never in public dashboards |
| Aadhaar / PAN | May appear in application logs | Never indexed in standard indices; masked at pipeline level |
| Biometric References | Access control logs | Event type/timestamp retained; biometric template never stored |

---

## Data Processing Agreement — Key Clauses for SOC

Every client must sign a DPA before onboarding. Key clauses:

1. Scope of processing (which personal data, for what security purpose)
2. Security measures implemented (encryption, access control, audit logging)
3. Breach notification timeline (SOC notifies client within 24-72 hours of discovering breach)
4. Sub-processor disclosure (cloud providers, SIEM vendor)
5. Data deletion on contract termination (Section 20.3)
6. Right to audit SOC's processing activities
7. Data localisation confirmation (India-only storage)

---
*Reference: DPDP Act 2023 | github.com/amitambekar510/soc-operations-handbook*
