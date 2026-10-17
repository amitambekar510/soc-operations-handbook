---
title: MITRE ATT&CK Techniques for Financial Sector SOCs
version: 1.0
framework: MITRE ATT&CK Enterprise v14
---

# MITRE ATT&CK — Financial Sector Priority Techniques

> This reference lists the most frequently observed and highest-risk ATT&CK techniques in financial sector environments. Use this to prioritize detection rule development and threat hunting.

---

## High-Priority Techniques by Tactic

### Initial Access
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1566 | Phishing | Most common initial access in financial sector |
| T1078 | Valid Accounts | Credential theft targeting dealer/admin accounts |
| T1190 | Exploit Public-Facing Application | Trading portal, OMS web interface exploitation |
| T1133 | External Remote Services | VPN credential compromise for remote access |

### Execution
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1059.001 | PowerShell | Common post-exploitation tool in financial sector attacks |
| T1059.003 | Windows Command Shell | Living-off-the-land execution |
| T1204 | User Execution | Spear-phishing with financial document lures |

### Persistence
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1547.001 | Registry Run Keys | Common persistence in trading workstation attacks |
| T1053.005 | Scheduled Task | Persistence in server environments |
| T1136 | Create Account | Backdoor accounts in AD |
| T1505.003 | Web Shell | Persistence on internet-facing trading portals |

### Credential Access
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1003.001 | LSASS Memory | Credential dumping for lateral movement to privileged systems |
| T1110.003 | Password Spraying | Targeting trading portal and OMS user accounts |
| T1558.003 | Kerberoasting | Targeting service accounts in broker AD environments |
| T1555 | Credentials from Password Stores | Browser-saved credentials for trading portals |

### Lateral Movement
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1021.001 | Remote Desktop Protocol | Most common lateral movement in broker environments |
| T1021.002 | SMB/Windows Admin Shares | Spread within dealer workstation networks |
| T1550.002 | Pass the Hash | Using dumped NTLM hashes to access trading systems |

### Collection
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1005 | Data from Local System | Trading position data, client PII collection |
| T1039 | Data from Network Shared Drive | Broker shared drive access for client data |
| T1114 | Email Collection | Targeting trading desk email for non-public information |

### Exfiltration
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1041 | Exfiltration Over C2 Channel | Data exfiltration in broker APT incidents |
| T1048 | Exfiltration Over Alternative Protocol | DNS tunneling for covert data exfiltration |
| T1567 | Exfiltration to Cloud Storage | Upload of client data to personal cloud storage |

### Impact
| Technique ID | Technique | Financial Sector Relevance |
|---|---|---|
| T1486 | Data Encrypted for Impact | Ransomware targeting trading infrastructure |
| T1489 | Service Stop | Stopping trading services to cause disruption |
| T1485 | Data Destruction | Log tampering to cover financial fraud |

---

## Financial Fraud-Specific Techniques (Beyond Standard ATT&CK)

| Activity | Description | Detection Method |
|---|---|---|
| Mule Account Operation | Using legitimate accounts to layer fraudulent transfers | Behavioural analytics; rapid fund cycling detection |
| Market Manipulation | Wash trading, layering, spoofing to manipulate prices | OMS log analysis; order-to-trade ratio monitoring |
| Front-Running | Trading ahead of known client orders | OMS sequence analysis; dealer account correlation |
| Payout API Fraud | Exploiting payment APIs for unauthorised fund transfers | API anomaly detection; new beneficiary monitoring |
| Trade Log Tampering | Modifying trade records to conceal fraud | FIM on OMS logs; hash chain verification |

---
*Reference: MITRE ATT&CK Enterprise Framework | github.com/amitambekar510/soc-operations-handbook*
