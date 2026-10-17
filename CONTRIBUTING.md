# Contributing to SOC Operations Handbook

Thank you for your interest in contributing! This project exists to help the security community build better SOC documentation — every contribution makes it more valuable for everyone.

---

## 🤝 Ways to Contribute

| Contribution Type | How |
|---|---|
| Fix a factual error or outdated information | Open an Issue or Pull Request |
| Add a new template or checklist | Pull Request to `templates/` or `checklists/` |
| Improve an existing handbook section | Pull Request to `handbook-sections/` |
| Add SIEM-specific examples | Pull Request with SIEM-specific subsection |
| Add regulatory content for other frameworks | Pull Request to `compliance/` |
| Improve AI prompts | Pull Request to `ai-builder/section-prompts/` |
| Report a broken link or formatting issue | Open an Issue |
| Suggest a new section | Open an Issue with the `new-section` label |

---

## 📋 Contribution Guidelines

### Before You Start
1. Check [open issues](https://github.com/amitambekar510/soc-operations-handbook/issues) to avoid duplicate work
2. For major changes, open an issue first to discuss
3. Read the [LICENSE.md](./LICENSE.md) — by contributing you agree to its terms

### Pull Request Process
1. Fork the repository
2. Create a feature branch: `git checkout -b improvement/section-name`
3. Make your changes following the formatting standards below
4. Test that your Markdown renders correctly on GitHub
5. Commit with a clear message: `git commit -m "Improve Section 9: add ransomware playbook detail"`
6. Push and open a Pull Request with a clear description

### Content Standards
- Write in clear, professional English
- Keep content SIEM-agnostic — reference generic SIEM concepts, not specific vendor syntax
- Align with existing section structure and formatting
- Include regulatory references where applicable (CERT-In, SEBI, RBI, DPDP)
- Do not include proprietary or confidential information

---

## 📝 Formatting Standards

Each handbook section follows this structure:

```markdown
---
section: NN
title: Section Title
version: 1.x
last_updated: YYYY-MM
---

# Section NN: Title

## NN.1 Subsection Title
Content...

### Key Points
- Point 1
- Point 2

### Regulatory Alignment
| Regulation | Relevant Clause |
|---|---|
| CERT-In | ... |
```

---

## 🏷️ Issue Labels

| Label | Use |
|---|---|
| `bug` | Factual error or broken content |
| `enhancement` | Improvement to existing content |
| `new-section` | Proposal for a new section |
| `new-template` | Proposal for a new template |
| `regulatory` | Regulatory content update |
| `ai-builder` | AI Builder improvement |
| `documentation` | README or project documentation |

---

## 👤 Credit

Significant contributors will be credited in [CHANGELOG.md](./CHANGELOG.md). Thank you for helping make this project better!
