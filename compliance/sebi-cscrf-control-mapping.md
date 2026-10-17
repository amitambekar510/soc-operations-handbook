---
title: SEBI CSCRF 2024 Control Mapping
regulation: SEBI Cyber Security and Cyber Resilience Framework 2024
applicability: All SEBI registered intermediaries
---

# SEBI CSCRF 2024 — SOC Control Mapping

> **Source**: Securities and Exchange Board of India (SEBI) Circular on Cyber Security and Cyber Resilience Framework, 2024
> **Applicability**: All SEBI registered entities including stock brokers, DPs, AMCs, portfolio managers, and Market Infrastructure Institutions

---

## SEBI Entity Categories

| Category | Entity Type | Key SOC Requirements |
|---|---|---|
| MII (Market Infrastructure Institution) | NSE, BSE, NSDL, CDSL, CCIL | Highest requirements; dedicated SOC mandatory; real-time M-SOC sharing |
| Qualified Registered Entity (QRE) | Large brokers, large AMCs | SOC mandatory (own or outsourced); SIEM required; 365-day log retention |
| Mid-size Regulated Entity | Medium brokers, mid-size AMCs | SOC recommended; SIEM recommended; 180-day log retention |
| Small Regulated Entity | Small brokers, distributors | Minimum controls; 90-day log retention |

---

## CSCRF Domain to SOC Control Mapping

| CSCRF Domain | NIST Function | Key SEBI Requirement | SOC Control |
|---|---|---|---|
| Asset Management | Identify | IT asset inventory; criticality classification | Asset register maintained in SIEM; quarterly review |
| Risk Management | Identify | Annual risk assessment; risk register | Risk register (Section 12); monthly CISO review |
| Access Control | Protect | Least privilege; MFA for privileged access; PAM | PAM monitoring; MFA enforcement alerts; quarterly access review |
| Security Operations Centre | Detect | 24x7 monitoring mandatory for MII/QRE; SIEM deployment | This SOC service; 24x7 alert monitoring; SIEM platform |
| Cyber Incident Management | Detect/Respond | IR plan documented and tested; report within 6 hours | IR lifecycle (Section 9); CERT-In workflow; annual tabletop |
| Data Security | Protect | Encrypt sensitive data; data classification; DLP | Log encryption; PII masking; DLP integration alerts |
| Third-Party Risk | Identify | Vendor cybersecurity assessment; vendor monitoring | Vendor risk register; vendor log monitoring (Section 17) |
| Business Continuity | Recover | DR site; tested BCP; annual DR drill | SOC BCP (Section 15); annual DR drill; RTO/RPO tracking |
| Vulnerability Management | Identify/Protect | Annual VAPT by CERT-In empanelled auditor; critical patches 48 hours | VAPT integration; patch compliance monitoring (Section 19.16) |
| Audit Trail | Detect | Immutable audit logs; 1 year retention for QRE+ | Immutable SIEM indices; 365-day ILM; audit dashboard |

---

## SEBI Annual Compliance Calendar

| Activity | Deadline | SOC Evidence Required |
|---|---|---|
| Annual Cybersecurity Compliance Certificate | June 30 | Monitoring evidence, incident register, CERT-In submissions |
| Annual VAPT by CERT-In empanelled auditor | Per SEBI schedule | VAPT report, remediation tracking |
| NSE/BSE Technology Audit | Per exchange schedule | Evidence package (Section 10.4) |
| DR Drill | Before November 30 | DR drill report; RTO/RPO achievement |

---
*Reference: SEBI CSCRF 2024 | github.com/amitambekar510/soc-operations-handbook*
