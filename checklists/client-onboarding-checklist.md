---
checklist: Client Onboarding
version: 1.0
use_case: 20-item SOC client onboarding process
phases: 3
---

# Client Onboarding Checklist

**Client Name**: ___________________
**Client Code**: ___________________
**Go-Live Target Date**: ___________________
**CSM**: ___________________
**Platform Engineer**: ___________________

---

## Phase 1: Pre-Onboarding (Weeks 1–2)

| # | Task | Owner | Done | Date |
|---|---|---|---|---|
| 1 | SSA reviewed, countersigned, and filed | CSM + Legal | ☐ | |
| 2 | Client code assigned and registered | CSM + PE | ☐ | |
| 3 | Client technical profile collected (assets, topology, log sources, contacts) | CSM | ☐ | |
| 4 | Data Processing Agreement (DPA) signed | Legal + CSM | ☐ | |
| 5 | Client kickoff call completed; go-live date confirmed | CSM + SOC Manager | ☐ | |

## Phase 2: Technical Setup (Weeks 2–4)

| # | Task | Owner | Done | Date |
|---|---|---|---|---|
| 6 | SIEM Space/Tenant created for client | Platform Engineer | ☐ | |
| 7 | RBAC roles created and tested (L1/L2/L3/client read-only) | Platform Engineer | ☐ | |
| 8 | Log ingestion pipelines configured for all contracted log sources | Platform Engineer | ☐ | |
| 9 | Network connectivity (VPN/tunnel) tested end-to-end | PE + Client IT | ☐ | |
| 10 | Endpoint agents deployed on contracted endpoints | PE + Client IT | ☐ | |
| 11 | Network device syslog forwarding configured and verified | PE + Client IT | ☐ | |
| 12 | Asset inventory index created and loaded | PE + CSM | ☐ | |
| 13 | ILM/retention policy applied per regulatory requirement | Platform Engineer | ☐ | |
| 14 | Detection rules imported and enabled for client environment | L3 Analyst | ☐ | |
| 15 | Standard dashboards deployed in client SIEM space | Platform Engineer | ☐ | |

## Phase 3: Validation & Go-Live (Week 4–5)

| # | Task | Owner | Done | Date |
|---|---|---|---|---|
| 16 | Integration validation testing completed (all log sources verified) | Platform Engineer | ☐ | |
| 17 | Log source coverage matrix delivered to client CISO | Platform Engineer | ☐ | |
| 18 | Client SPOC and CISO read-only access provided and tested | CSM + PE | ☐ | |
| 19 | Regulatory notification workflow configured and tested | CSM + Compliance | ☐ | |
| 20 | Go-Live joint sign-off: SOC Manager + Client CISO | SOC Manager | ☐ | |

---

**Go-Live Confirmed**: ☐ Yes — Date: _______________ Time: _______________ IST

**Signed by SOC Manager**: _________________________ Date: _______________

**Signed by Client CISO**: _________________________ Date: _______________

---
*Checklist v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
