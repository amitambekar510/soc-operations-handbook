---
checklist: DR Failover
version: 1.0
use_case: Disaster recovery site activation and return to primary
---

# DR Failover Checklist

**Failover Date/Time**: _______________ IST
**Reason for Failover**: _______________
**Platform Engineer**: _______________
**SOC Manager**: _______________

---

## Pre-Failover Verification

| # | Task | Done |
|---|---|---|
| 1 | DR activation decision made by SOC Manager / Crisis Commander | ☐ |
| 2 | Clients notified: brief monitoring gap possible | ☐ |
| 3 | All on-call analysts given DR platform URL and VPN profile | ☐ |

## DR Activation Steps

| # | Task | Owner | Done | Time |
|---|---|---|---|---|
| 1 | DR SIEM nodes started and healthy | Platform Engineer | ☐ | |
| 2 | Log ingestion pipelines active on DR (verify EPS flowing) | Platform Engineer | ☐ | |
| 3 | Detection rules verified active (compare count vs primary) | L3 Analyst | ☐ | |
| 4 | All open Cases accessible on DR platform | L3 Analyst | ☐ | |
| 5 | Fleet/agent management confirmed active on DR | Platform Engineer | ☐ | |
| 6 | All contracted agents checking in to DR (< 5 min) | Platform Engineer | ☐ | |
| 7 | Client read-only access to DR platform confirmed | Platform Engineer | ☐ | |
| 8 | Data gap calculated and documented | L3 Analyst | ☐ | |
| 9 | Retroactive IOC hunt for gap period completed | L3 Analyst | ☐ | |
| 10 | Clients notified: DR active, full monitoring restored | CSM | ☐ | |

## Return to Primary

| # | Task | Owner | Done |
|---|---|---|---|
| 1 | Primary site confirmed stable (30+ min) | Platform Engineer | ☐ |
| 2 | Data indexed in DR-only period synced to primary | Platform Engineer | ☐ |
| 3 | Primary Cases reflect all DR period updates | L3 Analyst | ☐ |
| 4 | Client URLs switched back to primary | Platform Engineer | ☐ |
| 5 | Platform health check completed on primary | Platform Engineer | ☐ |
| 6 | Clients notified: primary restored | CSM | ☐ |
| 7 | DR event documented in BCP register | Compliance Analyst | ☐ |

---

**Total Failover Duration**: _______________ minutes/hours

**RTO Target Met**: ☐ Yes  ☐ No — Reason: _______________

---
*Checklist v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
