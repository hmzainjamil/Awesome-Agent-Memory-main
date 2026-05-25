# Awesome-Agent-Memory-main

> **Awesome agent memory — curated memory systems for AI agents across sessions**

![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat)
![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-FF6B35?style=flat)
![Stars](https://img.shields.io/github/stars/hmzainjamil/Awesome-Agent-Memory-main?style=flat)
![Last Commit](https://img.shields.io/github/last-commit/hmzainjamil/Awesome-Agent-Memory-main?style=flat)

---

## CONCEPTS

| Concept | Description |
|---|---|
| **Session Memory** | Retain context within a conversation |
| **Persistent Memory** | Facts that survive session restarts |
| **Semantic Search** | Find relevant memories by meaning |
| **Memory Decay** | Age-based importance weighting |
| **Entity Tracking** | Remember people, tools, projects |
| **Decision Log** | Record why choices were made |
| **Feedback Loop** | Learn from corrections over time |
| **Export** | Portable memory format (JSON/MD) |

---

## 🔥 Hot Commands

```bash
# Activate skill
claude --skill Awesome-Agent-Memory-main 'your task'

# Quick workflow
claude 'memory automation task'

# Get capabilities
claude 'what can Awesome-Agent-Memory-main do?'
```

## ■ tip
> Mention **memory** or **agent** in your prompt to auto-activate this skill.

---

## ☠️ STARTUPS / BUSINESSES

- **Agencies**: automate memory workflows for clients at scale
- **Founders**: ship agent features 10x faster
- **Freelancers**: deliver persistence work with AI precision

---

## Features

- Memory automation
- Agent automation
- Persistence automation
- Context automation
- Recall automation
- Storage automation

---

## Installation

```bash
git clone https://github.com/hmzainjamil/Awesome-Agent-Memory-main.git
cd Awesome-Agent-Memory-main
```

---

## Usage

```bash
# Activate skill in Claude Code
claude --skill Awesome-Agent-Memory-main "your task here"

# Quick workflow
claude "memory automation task"

# Get help
claude "what can Awesome-Agent-Memory-main do?"
```

---

## Configuration

| Variable | Description | Default |
|---|---|---|
| `API_KEY` | Primary API key | Required |
| `MODEL` | AI model to use | claude-3-5-sonnet |
| `DEBUG` | Enable verbose debug | false |
| `MAX_TOKENS` | Max token budget | 8192 |
| `TIMEOUT` | Request timeout (sec) | 30 |
| `LOG_LEVEL` | Logging verbosity | info |

---

## Architecture

```
Awesome-Agent-Memory-main/
├── README.md           # Documentation
├── SKILL.md            # Claude Code skill definition
├── scripts/            # Automation scripts
├── templates/          # Output templates
├── examples/           # Usage examples
└── docs/               # Extended documentation
```

---

## Examples

### Basic

```bash
# Simple task
claude --skill Awesome-Agent-Memory-main "memory task"

# Verbose
claude --skill Awesome-Agent-Memory-main --verbose "detailed agent task"
```

### Advanced Pipeline

```bash
# Chain skills
claude --skill Awesome-Agent-Memory-main "step 1" | claude --skill summarize

# Batch run
for item in $(cat list.txt); do
  claude --skill Awesome-Agent-Memory-main "process $item"
done
```

---

## Troubleshooting

| Issue | Cause | Fix |
|---|---|---|
| Auth fails | Invalid API key | Re-export key in shell profile |
| Timeout | Network or large payload | Increase TIMEOUT value |
| Empty output | Prompt too vague | Add more context |
| Rate limit | Too many requests | Add delay between calls |
| Model error | Unsupported version | Update MODEL variable |
| Import error | Missing dependency | Run pip install -r requirements.txt |

---

## Comparison

| Feature | This Skill | Alt A | Alt B |
|---|---|---|---|
| Claude Code native | ✅ | ❌ | ✅ |
| Auto-activation | ✅ | ✅ | ❌ |
| Free to use | ✅ | ❌ | ✅ |
| Production ready | ✅ | ✅ | ❌ |
| Active maintenance | ✅ | ❌ | ❌ |

---

## Changelog

| Version | Changes |
|---|---|
| v2.0 | Claude 4 support, auto-activation |
| v1.5 | Added keyword triggers |
| v1.0 | Initial release |

---

## Contributing

1. Fork → feature branch → commit → PR
2. Follow conventional commits: `feat:`, `fix:`, `docs:`
3. Add tests for new features

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/Awesome-Agent-Memory-main&type=Date)](https://star-history.com/#hmzainjamil/Awesome-Agent-Memory-main&Date)

---

## 📜 License

MIT — free to use, modify, distribute.

---

Made with ❤️ by [@hmzainjamil](https://github.com/hmzainjamil)
