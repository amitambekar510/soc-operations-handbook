---
template: Chain of Custody Form
version: 1.0
use_case: Digital forensics evidence tracking
---

# Chain of Custody Form

> 📋 Print or use digitally for every piece of digital evidence collected during an incident.

---

## Incident Details

| Field | Value |
|---|---|
| Incident Reference Number | INC-YYYY-NNNN |
| Incident Type | [Ransomware / Data Breach / Insider Threat / Other] |
| Evidence Item ID | INC-YYYY-NNNN-E001 |
| Date of Collection | DD-MM-YYYY |
| Time of Collection (IST) | HH:MM IST |

---

## Evidence Description

| Field | Value |
|---|---|
| Evidence Type | [Disk Image / Memory Dump / Log Archive / Physical Device / Other] |
| Source System Hostname | |
| Source System IP Address | |
| Operating System / Version | |
| Evidence File Name | |
| Evidence File Size | |

---

## Integrity Verification

| Hash Type | Hash Value |
|---|---|
| MD5 | |
| SHA256 | |
| Verification Timestamp | |
| Verified By | |

---

## Collection Details

| Field | Value |
|---|---|
| Collection Method | [FTK Imager / dd / Velociraptor / WinPmem / LiME / Other] |
| Tool Version | |
| Write Blocker Used | [Yes / No / N/A] |
| Collection Environment | [Live System / Offline / Remote] |

---

## Authorization

| Field | Value |
|---|---|
| Collected By (Full Name) | |
| Collected By (Role) | |
| Collected By (Signature) | |
| Witnessed By (Full Name) | |
| Witnessed By (Role) | |
| Client CISO Authorization | |
| Authorization Reference | |

---

## Storage Details

| Field | Value |
|---|---|
| Storage Location | |
| Encryption Applied | [Yes / No] |
| Encryption Method | [AES-256 / BitLocker / LUKS / Other] |
| Access Restricted To | |
| Legal Hold Applied | [Yes / No] |

---

## Chain of Access Log

| Date | Accessed By | Purpose | Hash Re-Verified | Returned to Storage |
|---|---|---|---|---|
| | | | Yes / No | Yes / No |
| | | | Yes / No | Yes / No |

---

*Form Version 1.0 | SOC Operations Handbook | github.com/amitambekar510/soc-operations-handbook*
