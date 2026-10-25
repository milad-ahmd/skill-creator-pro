<div align="center">

# 🛠️ skill-creator-pro

**Turn any workflow into a well-written SKILL.md, with a linter to validate it. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/skill-creator-pro)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/skill-creator-pro?style=social)](https://github.com/milad-ahmd/skill-creator-pro)
![Category](https://img.shields.io/badge/category-Agent%20Productivity-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/skill-creator-pro/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- skill-creator-pro
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/skill-creator-pro /tmp/skill-creator-pro
mkdir -p ~/.claude/skills && cp -r /tmp/skill-creator-pro/skills/skill-creator-pro ~/.claude/skills/
```

**Per project:** copy `skills/skill-creator-pro` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/skill-creator-pro/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Create a skill for our release process
Turn this checklist into an agent skill
```

The full workflow, rules and output format are in [`SKILL.md`](skills/skill-creator-pro/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
