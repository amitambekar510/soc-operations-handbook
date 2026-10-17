---
title: CERT-In Mandatory Incident Categories
regulation: CERT-In April 2022 Directions
deadline: 6 hours from detection
submission: incident@cert-in.org.in
---

# CERT-In Mandatory Incident Reporting

> **Source**: Ministry of Electronics and Information Technology (MeitY) / CERT-In Directions under Section 70B of the IT Act, 2000
> **Effective**: April 28, 2022
> **Deadline**: All 20 categories must be reported within **6 hours** of noticing/detecting the incident.

---

## Reporting Obligation

Any organization (service provider, intermediary, data centre, body corporate, government organisation) that experiences any of the following 20 incident types **must** report to CERT-In within 6 hours.

**Submission channels**:
- Email: incident@cert-in.org.in
- CERT-In Portal: https://www.cert-in.org.in
- Phone: 1800-11-4949

---

## 20 Mandatory Incident Categories

| # | Category | SOC Detection Methods |
|---|---|---|
| 1 | Targeted scanning/probing of critical networks/systems | IDS/IPS alerts; firewall anomalies; port scan detection |
| 2 | Compromise of critical systems/information | SIEM correlation; EDR alerts; authentication anomalies |
| 3 | Unauthorised access to IT systems/data | Authentication failure patterns; anomalous access logs |
| 4 | Defacement of website or intrusion into website | WAF alerts; file integrity monitoring; web server logs |
| 5 | Malicious code attacks (virus, worm, trojan, ransomware, spyware) | EDR/AV alerts; SIEM behavioral rules; mass file change detection |
| 6 | Attack on servers (database, mail, DNS) and network devices | Server log anomalies; database audit alerts; DNS anomaly detection |
| 7 | Identity theft, spoofing, and phishing attacks | Email gateway alerts; authentication anomalies; URL reputation |
| 8 | Denial of Service (DoS) and Distributed DoS (DDoS) attacks | Network flow anomalies; bandwidth spike alerts; IPS rules |
| 9 | Attacks on critical infrastructure, SCADA, and OT systems | OT/ICS protocol anomalies; network segmentation violations |
| 10 | Attacks on Internet of Things (IoT) devices | Network anomalies from IoT segments; unusual device behavior |
| 11 | Data breach / data leak | DLP alerts; large outbound data transfer; dark web intelligence |
| 12 | Attacks via malicious mobile apps | Mobile MDM alerts; unusual app behavior |
| 13 | Fake mobile apps | Brand monitoring; app store intelligence |
| 14 | Unauthorised access to social media accounts | SSO anomalies; brand monitoring alerts |
| 15 | Attacks or incidents affecting digital payment systems | Payment gateway anomalies; fraud detection alerts; UPI anomalies |
| 16 | Attacks via malicious/fraudulent domain names | DNS intelligence; typosquat monitoring; phishing feed |
| 17 | Attacks on eGovernance / Government data | Targeted threat intelligence; government network anomalies |
| 18 | Tampering with source code of digital products | Code repository integrity monitoring; FIM on build systems |
| 19 | Supply chain attacks | Build system monitoring; software update anomalies; vendor IOCs |
| 20 | Cyber espionage | APT behavioral indicators; long-term dwell time patterns; data staging |

---

## SOC CERT-In Compliance Workflow

```
T+0   : Incident detected in SIEM
T+5m  : L1 escalates to L2/L3 — CERT-In clock starts
T+15m : Incident declared; CERT-In category confirmed
T+2h  : CERT-In notification draft prepared by L3
T+2h  : Draft delivered to client CISO for review
T+4h  : Client CISO submits to CERT-In
T+6h  : HARD DEADLINE — notification must be submitted
```

---

## Key Additional CERT-In Requirements (April 2022)

| Requirement | Detail |
|---|---|
| Log Retention | All ICT system logs retained for minimum 180 days within Indian jurisdiction |
| NTP Synchronization | All systems synchronized with NIC or NPCI NTP servers |
| Virtual Assets | Crypto exchange and wallet providers have additional reporting requirements |
| Data Localization | Logs must be maintained within India |
| KYC/Subscriber Data | Mandatory retention of KYC and subscriber data |

---
*Reference: CERT-In Directions 2022 | github.com/amitambekar510/soc-operations-handbook*
