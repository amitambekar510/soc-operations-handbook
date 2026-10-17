---
title: ATT&CK Detection Coverage Guide
version: 1.0
---

# MITRE ATT&CK Detection Coverage Guide

> How to measure and progressively improve your SOC's ATT&CK detection coverage.

---

## What is ATT&CK Coverage?

ATT&CK coverage measures the percentage of MITRE ATT&CK techniques (Enterprise matrix) for which your SOC has active detection — either through SIEM rules, EDR policies, or documented hunt procedures.

**Coverage Formula**:
```
Coverage % = (Techniques with active detection / Total applicable techniques) × 100
```

---

## Coverage Maturity Levels

| Level | Coverage % | Description |
|---|---|---|
| Initial | < 20% | Basic signature rules; limited behavioral detection |
| Developing | 20–40% | Behavioral rules added; key techniques covered |
| Defined | 40–60% | Systematic coverage by tactic; documented gaps |
| Managed | 60–80% | Purple team validated; continuous improvement |
| Optimizing | > 80% | Near-complete coverage; ML/behavioral analytics |

**Financial sector SOC target**: > 60% within 12 months; > 75% within 24 months.

---

## How to Measure Your Coverage

### Step 1: Export Your Detection Rules
Export your SIEM detection rules with their MITRE ATT&CK technique tags.

### Step 2: Map to ATT&CK Navigator
1. Go to https://mitre-attack.github.io/attack-navigator/
2. Create a new layer
3. Mark each technique where you have active detection
4. Export as JSON for version control

### Step 3: Identify Gaps
ATT&CK Navigator shows uncovered techniques in white. Prioritize coverage gaps based on:
- Techniques relevant to your sector (see financial-sector-techniques.md)
- Techniques in recent threat intelligence from your SIEM TI feeds
- Techniques used in recent incidents you or the industry experienced

---

## Coverage Improvement Process

### Monthly: New Rule Deployment
- Deploy minimum 2 new ATT&CK-mapped detection rules per month
- Sourced from: Purple team sessions, threat hunting findings, new TI, PIR action items

### Quarterly: Purple Team Session
- Target 5–10 new ATT&CK techniques per session
- Validate existing detections against real execution (Atomic Red Team)
- Update ATT&CK Navigator layer after each session

### Annually: Full Coverage Review
- Export complete SIEM rule list with ATT&CK mappings
- Update ATT&CK Navigator layer
- Present coverage trend to CISO (current % vs prior year)
- Set coverage targets for next year

---

## ATT&CK Resources

| Resource | URL | Use |
|---|---|---|
| ATT&CK Navigator | https://mitre-attack.github.io/attack-navigator/ | Visualize coverage |
| Atomic Red Team | https://github.com/redcanaryco/atomic-red-team | Test detection rules |
| MITRE ATT&CK | https://attack.mitre.org | Technique reference |
| SIGMA Rules | https://github.com/SigmaHQ/sigma | SIEM-agnostic detection rules |
| MITRE CTID | https://ctid.mitre-engenuity.org | Threat-informed defense |

---
*Reference: MITRE ATT&CK Framework | github.com/amitambekar510/soc-operations-handbook*
