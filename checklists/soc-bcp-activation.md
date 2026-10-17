---
checklist: SOC BCP Activation
version: 1.0
use_case: Business continuity plan activation
---

# SOC BCP Activation Checklist

**Activation Date/Time**: _______________ IST
**Activating Authority**: _______________
**Disruption Type**: [ ] Facility  [ ] Platform  [ ] Connectivity  [ ] Staffing  [ ] Ransomware  [ ] Power  [ ] Other
**Crisis Commander**: _______________

---

## Immediate Actions (0–15 Minutes)

| # | Task | Owner | Done | Time |
|---|---|---|---|---|
| 1 | BCP activation declared and documented | Crisis Commander | ☐ | |
| 2 | Kibana Case created: BCP-[date] | Incident Lead | ☐ | |
| 3 | All SOC staff notified via OOB channel | SOC Manager | ☐ | |
| 4 | CISO briefed on activation | Crisis Commander | ☐ | |
| 5 | All clients notified (monitoring continuity status + ETA) | CSM | ☐ | |

## Platform Failover (15–60 Minutes)

| # | Task | Owner | Done | Time |
|---|---|---|---|---|
| 6 | DR SIEM platform activated | Platform Engineer | ☐ | |
| 7 | Log source failover to DR endpoint confirmed | Platform Engineer | ☐ | |
| 8 | All detection rules confirmed active on DR platform | L3 Analyst | ☐ | |
| 9 | All open Cases visible on DR platform | L3 Analyst | ☐ | |
| 10 | Agent/endpoint coverage confirmed on DR platform | Platform Engineer | ☐ | |

## Operations Continuity

| # | Task | Owner | Done |
|---|---|---|---|
| 11 | Monitoring gap period documented (last primary event to first DR event) | L3 | ☐ |
| 12 | Retroactive IOC search for gap period completed | L3 | ☐ |
| 13 | SITREP issued to all clients every 2 hours | CSM | ☐ |
| 14 | CERT-In capability verified operational | Compliance Analyst | ☐ |

## Return to Primary

| # | Task | Owner | Done |
|---|---|---|---|
| 15 | Primary site stable for 30+ minutes | Platform Engineer | ☐ |
| 16 | DR events synced back to primary platform | Platform Engineer | ☐ |
| 17 | Client access URLs switched back to primary | Platform Engineer | ☐ |
| 18 | Clients notified of primary restoration | CSM | ☐ |
| 19 | Full platform health check completed | Platform Engineer | ☐ |
| 20 | BCP event Kibana Case closed; PIR scheduled | SOC Manager | ☐ |

---
*Checklist v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
