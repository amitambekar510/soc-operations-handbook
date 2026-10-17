---
template: SLA Framework
version: 1.0
use_case: Service level agreement documentation
---

# SOC SLA Framework

**Organization**: [Client/Organization Name]
**SOC Provider**: [SOC Organization Name]
**Effective Date**: DD-MM-YYYY
**Review Date**: DD-MM-YYYY

---

## SLA Tiers

### Tier 1 — Premium (MII / QRE / Critical Clients)

| Metric | Target | Measurement Method |
|---|---|---|
| MTTA — P1 Alert | < 5 minutes | Alert timestamp to first analyst action |
| MTTA — P2 Alert | < 10 minutes | Alert timestamp to first analyst action |
| MTTR — P1 Containment | < 2 hours | Case open to containment confirmed |
| MTTR — P2 Containment | < 4 hours | Case open to containment confirmed |
| P1 Client Notification | < 15 minutes | Alert detection to first client call |
| CERT-In Draft Delivery | < 2 hours | Detection to draft delivered to CISO |
| Platform Availability | > 99.9% monthly | Heartbeat monitor monthly average |
| Log Source Coverage | > 99% | (Active agents / Contracted agents) × 100 |
| Monthly Report | By 5th of month | ITSM report delivery ticket closure |

### Tier 2 — Standard

| Metric | Target |
|---|---|
| MTTA — P1 | < 5 minutes |
| MTTA — P2 | < 15 minutes |
| MTTR — P1 | < 4 hours |
| MTTR — P2 | < 8 hours |
| Platform Availability | > 99.5% |
| Log Source Coverage | > 98% |

---

## SLA Exclusions

The following are excluded from SLA calculations:
- Scheduled maintenance windows (48-hour advance notice required)
- Client-side network outages affecting log forwarding
- Client failure to respond within agreed timeframes
- Force majeure events

---

## SLA Breach Process

| Breach Type | Immediate Action | Client Communication |
|---|---|---|
| MTTA Breach (P1/P2) | SOC Manager notified; RCA initiated | Proactive disclosure within 30 minutes |
| MTTR Breach (P1/P2) | Resources augmented; revised ETA provided | Client CISO notified immediately |
| Availability Breach | Platform Engineer RCA | Disclosed in monthly report |

---

*Template v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
