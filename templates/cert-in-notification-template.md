---
template: CERT-In Incident Notification
version: 1.0
use_case: Mandatory 6-hour regulatory notification to CERT-In
regulatory: CERT-In April 2022 Directions
deadline: Within 6 hours of detection
submission: incident@cert-in.org.in
---

# CERT-In Incident Notification

> ⚠️ **DEADLINE**: This notification must be submitted within **6 hours** of incident detection.
> Submit to: incident@cert-in.org.in
> Also report via CERT-In portal: https://www.cert-in.org.in

---

## Part A: Reporting Organization

| Field | Value |
|---|---|
| Organization Name | |
| Organization Type | [Bank / Broker / NBFC / IT Company / Other] |
| SEBI/RBI Registration Number | |
| Reporting Official Name | |
| Reporting Official Designation | |
| Contact Email | |
| Contact Phone | |
| Organization Address | |

---

## Part B: Incident Classification

| Field | Value |
|---|---|
| CERT-In Incident Category | [Select from 20 mandatory categories] |
| Incident Severity | [Critical / High / Medium] |
| Attack Type | [Ransomware / Phishing / Data Breach / DDoS / Other] |
| MITRE ATT&CK Tactic | |

**CERT-In Mandatory Category Selected** (check one):
- [ ] Targeted scanning/probing of critical networks/systems
- [ ] Compromise of critical systems/information
- [ ] Unauthorised access to IT systems/data
- [ ] Defacement of website or intrusion into a website
- [ ] Malicious code attacks (virus, worm, trojan, ransomware, spyware)
- [ ] Attack on servers (database, mail, DNS) and network devices
- [ ] Identity theft, spoofing and phishing attacks
- [ ] Denial of Service (DoS) and Distributed DoS (DDoS) attacks
- [ ] Attacks on critical infrastructure, SCADA, OT systems
- [ ] Attacks on Internet of Things (IoT) devices
- [ ] Data breach / data leak
- [ ] Attacks via malicious mobile apps
- [ ] Fake mobile apps
- [ ] Unauthorised access to social media accounts
- [ ] Attacks or incidents affecting digital payment systems
- [ ] Attacks via malicious/fraudulent domain names
- [ ] Attacks on eGovernance / Government data
- [ ] Tampering with source code of digital products
- [ ] Supply chain attacks
- [ ] Cyber espionage

---

## Part C: Incident Details

| Field | Value |
|---|---|
| Date/Time of Detection (IST) | DD-MM-YYYY HH:MM |
| Date/Time Incident Occurred (if known) | DD-MM-YYYY HH:MM |
| Date/Time of This Notification | DD-MM-YYYY HH:MM |
| Number of Systems Affected | |
| Geographic Scope | [Single site / Multiple sites / Pan-India / International] |

**Systems/Services Affected**:
[Describe which systems, services, or infrastructure were affected]

**Description of Incident**:
[Factual description of what occurred — what was detected, what systems were accessed or affected, what data may have been involved]

---

## Part D: Impact Assessment

| Field | Value |
|---|---|
| Data Compromised | [Yes / No / Under Investigation] |
| Type of Data | [PII / Financial / Trading Data / Credentials / Other] |
| Estimated Number of Records | |
| Business Operations Impact | [None / Limited / Significant / Critical] |
| Financial Impact (if known) | |

---

## Part E: Actions Taken

[Describe containment and remediation actions taken as of notification time]

1. [Action 1 — e.g., affected systems isolated]
2. [Action 2 — e.g., credentials reset]
3. [Action 3 — e.g., enhanced monitoring activated]

---

## Part F: Technical Indicators (if available)

| IOC Type | Value |
|---|---|
| Source IP Address(es) | |
| Malware Hash (MD5/SHA256) | |
| Malicious Domain(s) | |
| Attack Tool(s) Used | |

---

*Template v1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
*This template is for reference. Verify current CERT-In submission format at www.cert-in.org.in*
