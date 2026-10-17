---
layout: default
title: AI Builder Guide
nav_order: 3
---

# AI Builder Guide

The AI Builder lets you generate a complete SOC Operations Handbook customized for your organization using any AI tool.

## How It Works

```
Fill Organization Profile → Paste into AI Tool → Complete Handbook Generated
```

## Step-by-Step

### Step 1: Fill Your Organization Profile

Open [`organization-profile-form.md`](https://github.com/amitambekar510/soc-operations-handbook/blob/main/ai-builder/organization-profile-form.md) and answer every field:

- Organization type and industry sector
- Applicable Indian regulations (CERT-In, SEBI, RBI, DPDP)
- SIEM tool and technology stack
- SOC type (internal / MSSP / hybrid)
- Team size and shift model
- Log sources monitored
- SLA tier

This takes approximately 10 minutes.

### Step 2: Open the Master Prompt

Open [`master-prompt.md`](https://github.com/amitambekar510/soc-operations-handbook/blob/main/ai-builder/master-prompt.md) and copy its full content.

### Step 3: Combine and Submit to AI

In your AI tool, paste:
1. The full content of `master-prompt.md`
2. Your completed `organization-profile-form.md`

Submit in a single message.

### Step 4: Review and Finalize

Your AI tool will generate all 21 sections. After generation:

- [ ] Review each section for organizational accuracy
- [ ] Replace any remaining `[PLACEHOLDER]` values
- [ ] Add organization logo and branding
- [ ] Have senior SOC analyst review technical procedures
- [ ] Obtain CISO / SOC Manager sign-off before operational use

## Supported AI Tools

| Tool | Notes |
|---|---|
| **Claude (Anthropic)** | Best for full 21-section generation in one session |
| **ChatGPT (OpenAI GPT-4+)** | Works well; may need section-by-section for full handbook |
| **Microsoft Copilot** | Good for individual sections |
| **Google Gemini 1.5 Pro** | Handles long context well |

## Individual Section Generation

If your AI tool cannot handle all 21 sections at once, use the individual section prompts in [`ai-builder/section-prompts/`](https://github.com/amitambekar510/soc-operations-handbook/tree/main/ai-builder/section-prompts).

Each `prompt-NN-section-name.md` file generates one section when combined with your organization profile.
