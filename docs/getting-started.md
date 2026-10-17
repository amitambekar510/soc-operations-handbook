---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started

## Choose Your Approach

### Option A — AI Builder (Fastest)

Generate a complete, customized handbook in one session using any AI tool.

1. Open [`ai-builder/organization-profile-form.md`](https://github.com/amitambekar510/soc-operations-handbook/blob/main/ai-builder/organization-profile-form.md)
2. Fill in your organization details (~10 minutes)
3. Open [`ai-builder/master-prompt.md`](https://github.com/amitambekar510/soc-operations-handbook/blob/main/ai-builder/master-prompt.md)
4. Paste both into Claude / ChatGPT / Copilot / Gemini
5. Your handbook is generated

### Option B — Manual Customization

1. Clone the repository:
   ```bash
   git clone https://github.com/amitambekar510/soc-operations-handbook.git
   ```
2. Navigate to `handbook-sections/`
3. Open each section `.md` file
4. Replace `[PLACEHOLDER]` values with your organization details
5. Add your SIEM-specific examples

### Option C — Pick and Choose

Browse the repository and download only the sections, templates, or checklists you need.

---

## Repository Structure

```
soc-operations-handbook/
├── handbook-sections/     ← 21 complete sections
├── ai-builder/            ← AI generation prompts
├── templates/             ← Document templates
├── checklists/            ← Operational checklists
├── compliance/            ← Indian regulatory reference
└── mitre-attack/          ← ATT&CK coverage guides
```

---

## Attribution Requirement

When using this framework, include this attribution in your document:

> *"This document was developed using the SOC Operations Handbook framework by Amit Ambekar, available at https://github.com/amitambekar510/soc-operations-handbook"*

See [LICENSE.md](https://github.com/amitambekar510/soc-operations-handbook/blob/main/LICENSE.md) for full terms.
