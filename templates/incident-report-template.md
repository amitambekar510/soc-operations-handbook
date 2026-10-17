---
template: Incident Report
version: 1.0
use_case: P1/P2 formal incident documentation
---

# Incident Report

**Classification**: CONFIDENTIAL
**Incident ID**: INC-YYYY-NNNN
**Report Version**: 1.0

---

## 1. Executive Summary

> *Non-technical summary for CISO and management. Maximum 1 page.*

**What Happened**: [2-3 sentence description of the incident]

**Impact**: [Business impact — systems affected, data involved, operational disruption]

**Current Status**: [Contained / Remediated / Under Investigation]

**CERT-In Reported**: [Yes — Reference: XXXXXX / No / Not Required]

---

## 2. Incident Details

| Field | Value |
|---|---|
| Detection Date/Time | DD-MM-YYYY HH:MM IST |
| Containment Date/Time | DD-MM-YYYY HH:MM IST |
| Closure Date/Time | DD-MM-YYYY HH:MM IST |
| Severity | P1 / P2 |
| MITRE ATT&CK Category | [Tactic — Technique] |
| Incident Lead | [Name] |
| Investigating Analyst | [Name] |

---

## 3. Affected Systems

| System | IP Address | Role | Impact |
|---|---|---|---|
| | | | |

---

## 4. Attack Timeline

| Timestamp (IST) | Event | Source | Confidence |
|---|---|---|---|
| | [Earliest attacker activity] | [Log source] | High/Medium/Low |
| | [Detection event] | SIEM Alert | High |
| | [Containment action] | SOC | Confirmed |

---

## 5. Root Cause Analysis

**Immediate Cause**: [What directly caused the incident]

**Root Cause**: [Why the immediate cause was able to occur]

**5 Whys Analysis**:
1. Why did [incident] occur? → [Answer]
2. Why did [answer 1] occur? → [Answer]
3. Why did [answer 2] occur? → [Answer]
4. Why did [answer 3] occur? → [Answer]
5. Why did [answer 4] occur? → [Root cause]

---

## 6. Indicators of Compromise (IOCs)

| Type | Value | Confidence | First Seen |
|---|---|---|---|
| IP Address | | High/Medium/Low | |
| Domain | | | |
| File Hash (SHA256) | | | |
| Registry Key | | | |

---

## 7. Actions Taken

| Timestamp | Action | Taken By | Outcome |
|---|---|---|---|
| | | | |

---

## 8. Recommendations

| Priority | Recommendation | Owner | Target Date |
|---|---|---|---|
| Critical | | | |
| High | | | |
| Medium | | | |

---

## 9. Evidence Package

| Evidence ID | Description | Storage Location | SHA256 |
|---|---|---|---|
| INC-YYYY-NNNN-E001 | | | |

---

*Report prepared by: [Name, Role]*
*Reviewed by: [SOC Manager Name]*
*Based on SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
