---
title: RBI IT Framework and Cyber Security Framework Reference
regulation: RBI IT Framework 2011 / RBI Cyber Security Framework 2016 / RBI CSITE
applicability: Banks, NBFCs, Payment System Operators regulated by RBI
---

# RBI IT Framework — SOC Reference

> **Sources**:
> - RBI Guidelines on Information Security, Electronic Banking, Technology Risk Management and Cyber Frauds (2011)
> - RBI Cyber Security Framework for Banks (2016)
> - RBI Directions for Payment System Operators

---

## RBI Cyber Security Framework Key Requirements

| Domain | Requirement | SOC Control |
|---|---|---|
| SOC/ISOC | Banks must establish a Security Operations Centre (in-house or outsourced) | This SOC service; 24x7 monitoring |
| Threat Intelligence | Banks must subscribe to threat intelligence feeds; participate in information sharing | TI platform (Section 3); CERT-In feeds; financial sector TI sharing |
| Incident Response | Documented and tested IR plan; report cyber incidents to RBI within 2-6 hours | IR lifecycle (Section 9); RBI CSITE notification workflow |
| Log Management | Maintain security logs for minimum 5 years for banks | SIEM 5-year retention ILM policy for RBI clients |
| VAPT | Conduct VAPT minimum annually; critical systems more frequently | VAPT integration (Section 19.4); CERT-In empanelled auditor |
| Patch Management | Critical patches applied within 30 days | Patch monitoring (Section 19.16); vulnerability dashboard |
| Network Segmentation | DMZ architecture; separation of internet-facing systems | Network architecture review; segmentation monitoring |
| Privileged Access | PAM for all privileged accounts; session recording | PAM integration; privileged activity monitoring (Section 19.22) |

---

## RBI Incident Reporting to CSITE

| Severity | RBI Reporting Deadline | Submission Channel |
|---|---|---|
| Critical (affecting customer data/operations) | Within 2-6 hours | RBI CSITE portal |
| High | Within 24 hours | RBI CSITE portal |
| Annual Cyber Security Return | June 30 | RBI CSITE portal |
| IS Audit Report | Within 3 months of year end | RBI CSITE portal |

**RBI CSITE Portal**: https://csite.rbi.org.in

---

## RBI IS Audit Requirements

| Requirement | Detail | SOC Evidence |
|---|---|---|
| Annual IS Audit | Conducted by RBI-approved IS auditor | SOC provides monitoring evidence, incident register, access review records |
| IS Audit Report | Submitted to RBI within 3 months of financial year end | SOC evidence package delivered to client before audit |
| Compliance Certificate | Annual cybersecurity compliance certificate | SOC contributes monitoring and compliance metrics |
| Concurrent Audit | Real-time/near-real-time monitoring of critical transactions | SOC 24x7 monitoring fulfils this for cyber events |

---
*Reference: RBI IT Framework 2011, RBI Cyber Security Framework 2016 | github.com/amitambekar510/soc-operations-handbook*
