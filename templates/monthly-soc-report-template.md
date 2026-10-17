---
template: Monthly SOC Report
version: 1.0
use_case: Monthly client/management security operations report
delivery: By 5th of each month
---

# Monthly SOC Report

**Organization**: [Client/Organization Name]
**Report Period**: [Month Year] (DD-MM-YYYY to DD-MM-YYYY)
**Prepared By**: [SOC Manager Name] | [CSM Name]
**Classification**: CONFIDENTIAL
**Version**: 1.0

---

## 1. Executive Summary

> *Half-page maximum. Written for CISO/CEO — no technical jargon.*

[2-3 paragraph summary covering: key security events, overall risk posture (improving/stable/deteriorating), top recommendation]

**Risk Posture This Month**: 🟢 Improving / 🟡 Stable / 🔴 Deteriorating

---

## 2. KPI Scorecard

| KPI | Target | Actual | Status | Trend |
|---|---|---|---|---|
| MTTA — P1 Alerts | < 5 min | | 🟢/🟡/🔴 | ↑↓→ |
| MTTA — P2 Alerts | < 15 min | | 🟢/🟡/🔴 | ↑↓→ |
| MTTR — P1 Incidents | < 4 hours | | 🟢/🟡/🔴 | ↑↓→ |
| False Positive Rate | < 15% | | 🟢/🟡/🔴 | ↑↓→ |
| Platform Availability | > 99.5% | | 🟢/🟡/🔴 | ↑↓→ |
| Log Source Coverage | > 98% | | 🟢/🟡/🔴 | ↑↓→ |
| CERT-In Compliance Rate | 100% | | 🟢/🟡/🔴 | ↑↓→ |
| Monthly Report On-Time | 100% | | 🟢/🟡/🔴 | ↑↓→ |

---

## 3. Alert Statistics

| Metric | This Month | Last Month | Change |
|---|---|---|---|
| Total Alerts | | | |
| P1 Alerts | | | |
| P2 Alerts | | | |
| P3 Alerts | | | |
| Closed as TP | | | |
| Closed as FP | | | |
| False Positive Rate | | | |

**Top 5 Alert Types This Month**:
| # | Alert Type | Count | % of Total |
|---|---|---|---|
| 1 | | | |
| 2 | | | |

---

## 4. Incident Summary

| Incident ID | Date | Severity | Description | MTTD | MTTR | CERT-In | Status |
|---|---|---|---|---|---|---|---|
| | | | | | | Yes/No/NA | Closed |

---

## 5. Threat Intelligence Highlights

- **Top Threat This Month**: [Threat actor or campaign relevant to sector]
- **New IOCs Added**: [Count] IOCs added to monitoring
- **Relevant CERT-In Advisories**: [List any relevant advisories]
- **Critical CVEs Affecting Your Environment**: [List any]

---

## 6. Platform Health

| Component | Availability | Notes |
|---|---|---|
| SIEM Platform | % | |
| Log Source Coverage | % | |
| Agent Health | % healthy | |

**Log Sources with Issues**:
| Log Source | Issue | Status | ETA |
|---|---|---|---|
| | | | |

---

## 7. Open Recommendations

| Rec-ID | Description | Priority | Date Raised | Status |
|---|---|---|---|---|
| REC-001 | | Critical/High/Medium | | Open/In Progress/Completed |

---

## 8. Next Month Outlook

- **Planned Activities**: [VAPT, maintenance windows, new integrations]
- **Upcoming Deadlines**: [Regulatory, audit, SLA review]
- **Anticipated Threats**: [Based on current TI]

---

## Appendix A: Full Alert Log

*[Attach complete alert listing if contracted]*

## Appendix B: CERT-In Register

| Detection Time | Submission Time | CERT-In Ref | Compliance |
|---|---|---|---|
| | | | Compliant/Breach |

---

*Report prepared using SOC Operations Handbook Framework*
*github.com/amitambekar510/soc-operations-handbook*
