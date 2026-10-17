---
template: Vendor Risk Assessment
version: 1.0
use_case: Third-party vendor security assessment
---

# Vendor Risk Assessment

**Vendor Name**: [Vendor Organization Name]
**Assessment Date**: DD-MM-YYYY
**Assessed By**: [Name, Role]
**Next Assessment Due**: DD-MM-YYYY (annual)

---

## Vendor Profile

| Field | Value |
|---|---|
| Vendor Type | [IT MSP / Cloud Provider / Market Data / Payment Gateway / VAPT / Other] |
| Services Provided | |
| Contract Start Date | |
| Contract End Date | |
| Data Access Level | [None / Limited / Full access to client data] |
| System Access Level | [None / Read-only / Admin / Root] |
| Access Method | [VPN / Direct / API / Physical] |

---

## Assessment Domains

### 1. Information Security Program (Score: __ / 25)

| Question | Yes | No | Partial | Score |
|---|---|---|---|---|
| ISO 27001 certified or equivalent? | | | | /5 |
| Dedicated CISO or security lead? | | | | /5 |
| Annual VAPT by independent auditor? | | | | /5 |
| Security awareness training for all staff? | | | | /5 |
| Formal incident response plan and tested? | | | | /5 |

### 2. Data Handling (Score: __ / 25)

| Question | Yes | No | Partial | Score |
|---|---|---|---|---|
| Client data stored only in India? | | | | /5 |
| Encryption at rest (AES-256 or equivalent)? | | | | /5 |
| Encryption in transit (TLS 1.2+)? | | | | /5 |
| Data deletion procedure on contract end? | | | | /5 |
| Data Processing Agreement signed? | | | | /5 |

### 3. Access Controls (Score: __ / 25)

| Question | Yes | No | Partial | Score |
|---|---|---|---|---|
| MFA for all privileged access? | | | | /5 |
| PAM solution deployed? | | | | /5 |
| Access reviewed quarterly? | | | | /5 |
| Background checks for staff with our access? | | | | /5 |
| Principle of least privilege enforced? | | | | /5 |

### 4. Business Continuity (Score: __ / 25)

| Question | Yes | No | Partial | Score |
|---|---|---|---|---|
| DR site available? | | | | /5 |
| DR tested in last 12 months? | | | | /5 |
| RTO < 4 hours for critical services? | | | | /5 |
| Sub-contractor dependencies documented? | | | | /5 |
| Business continuity plan documented? | | | | /5 |

---

## Overall Risk Score

| Domain | Score | Max |
|---|---|---|
| Information Security | | 25 |
| Data Handling | | 25 |
| Access Controls | | 25 |
| Business Continuity | | 25 |
| **Total** | | **100** |

**Risk Rating**: 80-100 = Low | 60-79 = Medium | 40-59 = High | < 40 = Critical

---

## Assessment Outcome

**Overall Risk Rating**: [ ] Low  [ ] Medium  [ ] High  [ ] Critical

**Recommendation**: [ ] Approve  [ ] Approve with conditions  [ ] Reject  [ ] Re-assess in 90 days

**Conditions / Required Actions**:
1. [Action required before/after approval]

---

*Template v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
