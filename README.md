# PromptForge

<!-- Badges here (license, build) -->

# PromptForge ⚒️ — Craft Reusable AI Prompts & Rules Across Any IDE

**One rule set, every coding assistant.** PromptForge lets you design, version and sync prompts + rules for Cursor, CLINE, RooCode and Windsurf—backed by a built-in “Memory Bank” so your AI partner always knows your project’s architecture, decisions and task backlog.

## 🚀 Why PromptForge?

| Benefit | How it helps you |
|---------|-----------------|
| **Cross-IDE portability** | Drop‐in support for Cursor, CLINE, RooCode, Windsurf—no rewrites. |
| **Consistent AI behaviour** | Plan • Implement • Debug workflows baked into rule files. |
| **Persistent context** | Markdown docs & tasks folder act as long-term memory. |
| **Minimal token usage** | Modular rule structure loads only what each platform needs. |
| **Instant onboarding** | `manage_rules.py install <path>` spins up rules in 60 sec. |

## 📦 Quick Start

```bash
# 1. Clone PromptForge
git clone https://github.com/youracct/promptforge && cd promptforge

# 2. Install rules into an existing project
python src/manage_rules.py install ~/git/my_project
```

## Directory Overview

cursor/rules/      # Cursor-specific .mdc files
clinerules/        # CLINE rules
docs/              # PRD, architecture, tech specs
tasks/             # RFCs, active context, backlog
src/               # rule management scripts

## Roadmap
- RooCode native structure
- VS Code extension scaffold
- Automated rule-lint CI

> **Heads-up!**  
> This repository is a **name-testing mirror** with no code inside.  
> Click below to explore the full project, docs and install script:

[Go to the working repo](https://github.com/botingw/rulebook-ai?src=github_abtest-PromptForge)



