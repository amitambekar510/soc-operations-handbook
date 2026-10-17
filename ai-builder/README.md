# 🤖 AI Builder — Generate Your SOC Handbook Automatically

The AI Builder is the most powerful feature of this project. It allows you to generate a **complete, fully customized SOC Operations Handbook** for your organization using any AI tool — in a single session.

---

## ⚡ Quick Start (5 Steps)

```
1. Open organization-profile-form.md
2. Fill in your organization details (takes ~10 minutes)
3. Open master-prompt.md and copy its full content
4. Open your preferred AI tool (Claude, ChatGPT, Copilot, Gemini)
5. Paste: [master-prompt content] + [your filled profile form]
   → Your complete SOC handbook is generated
```

---

## 📁 Files in This Folder

| File | Purpose |
|---|---|
| [`organization-profile-form.md`](./organization-profile-form.md) | **Fill this first** — your org details drive the entire handbook |
| [`master-prompt.md`](./master-prompt.md) | Single prompt that generates all 21 sections |
| [`section-prompts/`](./section-prompts/) | Individual prompts if you want to generate one section at a time |
| [`output-templates/`](./output-templates/) | Structured output formats for different use cases |

---

## 🧠 How the AI Builder Works

### The Logic
Every section prompt is structured as:
```
"Given this organization profile [YOUR PROFILE], generate Section N of
a SOC Operations Handbook covering [TOPIC]. Use these parameters:
[SECTION-SPECIFIC PARAMETERS]. Format as [STRUCTURE]."
```

The AI reads your profile and automatically:
- Uses your organization name and type throughout
- Adjusts regulatory requirements to your applicable frameworks
- Scales procedures to your team size
- Adapts monitoring scope to your contracted log sources
- Customizes SLA targets to your service tier
- Tailors financial fraud monitoring to your sector

### What Gets Customized
| Profile Field | What It Customizes |
|---|---|
| Organization type | Governance structure, roles, client communication tone |
| Industry sector | Financial fraud section, regulatory obligations, threat focus |
| SIEM tool | Detection examples, query syntax guidance, dashboard structure |
| Team size | Shift model, escalation matrix, capacity planning |
| Regulatory scope | Compliance sections, audit calendar, reporting workflows |
| SOC type (internal/MSSP) | Dual perspective content, SLA framework, client templates |

---

## 💡 Tips for Best Results

1. **Be specific in your profile** — the more detail you provide, the more customized your output
2. **Use Claude for best results** — handles long-context generation well across all 21 sections
3. **Generate in sections if needed** — if your AI tool has context limits, use the individual section prompts
4. **Review and validate** — AI output is a strong starting draft; review for accuracy before finalizing
5. **Iterate** — generate a section, review it, then ask the AI to refine specific parts

---

## 🔄 Section-by-Section Generation

If your AI tool cannot handle the full 21-section generation in one session, use the individual section prompts:

```
1. Fill organization-profile-form.md
2. For each section you need:
   - Open section-prompts/prompt-NN-[section-name].md
   - Paste: [section prompt] + [your org profile]
   - Save the generated section
3. Compile all sections into your final handbook
```

---

## ✅ Quality Checklist After Generation

After your handbook is generated, verify:

- [ ] Organization name appears correctly throughout
- [ ] SIEM tool name is consistent (if you chose to include it)
- [ ] Regulatory sections match your applicable frameworks
- [ ] SLA targets match your contracted service levels
- [ ] Escalation contacts are updated with real names/numbers
- [ ] All `[PLACEHOLDER]` values have been replaced
- [ ] Section cross-references are accurate
- [ ] Reviewed by a senior SOC analyst or manager before operational use

---

## 🛠️ Supported AI Tools

This AI Builder has been designed and tested for use with:

| AI Tool | Notes |
|---|---|
| **Claude (Anthropic)** | Best for long-context, full 21-section generation |
| **ChatGPT (OpenAI)** | Use GPT-4 or later; may need section-by-section for full handbook |
| **Microsoft Copilot** | Works well for individual sections |
| **Google Gemini** | Use Gemini 1.5 Pro for best results |
| **Any LLM** | The prompts are model-agnostic |

---

*The AI Builder is continuously improved. If you find a prompt that produces poor results for your organization type, please open an issue or submit a Pull Request.*
