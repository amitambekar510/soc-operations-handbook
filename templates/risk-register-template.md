---
template: Risk Register
version: 1.0
use_case: Cybersecurity risk tracking and management
---

# SOC Risk Register

**Organization**: [Organization Name]
**Register Scope**: [Internal SOC / Client: Name]
**Owner**: [CISO / SOC Manager]
**Last Updated**: DD-MM-YYYY
**Next Review**: DD-MM-YYYY

---

## Risk Scoring Matrix

| Likelihood \ Impact | Low | Medium | High | Critical |
|---|---|---|---|---|
| **Rare** | Low | Low | Medium | Medium |
| **Unlikely** | Low | Medium | Medium | High |
| **Possible** | Medium | Medium | High | Critical |
| **Likely** | Medium | High | Critical | Critical |
| **Almost Certain** | High | Critical | Critical | Critical |

---

## Active Risk Register

| Risk ID | Title | Category | Likelihood | Impact | Risk Level | Owner | Treatment | Status | Review Date |
|---|---|---|---|---|---|---|---|---|---|
| RISK-001 | [Risk title] | Technical | Possible | High | Critical | [Name] | Mitigate | Open | DD-MM-YYYY |
| RISK-002 | [Risk title] | Process | Unlikely | Medium | Medium | [Name] | Accept | Accepted | DD-MM-YYYY |
| RISK-003 | [Risk title] | People | Possible | Low | Medium | [Name] | Mitigate | In Treatment | DD-MM-YYYY |

---

## Risk Detail Record

### RISK-001: [Risk Title]

| Field | Value |
|---|---|
| Risk ID | RISK-001 |
| Category | Technical / Process / People / Third-Party / Regulatory |
| Description | [Full description of risk scenario, threat source, vulnerability] |
| Likelihood | Rare / Unlikely / Possible / Likely / Almost Certain |
| Impact | Low / Medium / High / Critical |
| Inherent Risk | [Before controls] |
| Existing Controls | [Current controls reducing risk] |
| Residual Risk | [After existing controls] |
| Treatment Strategy | Mitigate / Accept / Transfer / Avoid |
| Treatment Actions | [Specific actions with owner and deadline] |
| Risk Owner | [Named individual] |
| Status | Open / In Treatment / Accepted / Closed |
| Last Reviewed | DD-MM-YYYY |
| Next Review | DD-MM-YYYY |
| Linked Records | [Incident, audit finding, VAPT finding references] |

---

*Template v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
