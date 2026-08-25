# Claude Code Plugins Plus

> The open-source marketplace of **Claude Code** plugins, skills, and agents — 400+ plugins, 2,700+ skills, 200+ agents, every one spec-validated before it ships. Install with the `ccpi` CLI.

**Created and maintained by [Jeremy Longshore](https://github.com/jeremylongshore) / [Intent Solutions](https://intentsolutions.io).**

**Live work → [jeremylongshore/claude-code-plugins-plus-skills](https://github.com/jeremylongshore/claude-code-plugins-plus-skills)**
**Marketplace → [tonsofskills.com](https://tonsofskills.com)**

[![GitHub stars](https://img.shields.io/github/stars/jeremylongshore/claude-code-plugins-plus-skills?style=social)](https://github.com/jeremylongshore/claude-code-plugins-plus-skills)
[![GitHub forks](https://img.shields.io/github/forks/jeremylongshore/claude-code-plugins-plus-skills?style=social)](https://github.com/jeremylongshore/claude-code-plugins-plus-skills/network/members)
[![CLI: ccpi](https://img.shields.io/badge/CLI-ccpi-blueviolet?logo=npm)](https://www.npmjs.com/package/@intentsolutionsio/ccpi)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](https://github.com/jeremylongshore/claude-code-plugins-plus-skills/blob/main/LICENSE)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U5S225PTME)

---

## What this is

This repository is the **Intent Solutions organization landing page** for **Claude Code Plugins Plus** — one of the largest open-source marketplaces of plugins, skills, and agents for [Claude Code](https://code.claude.com/docs/en/), Anthropic's official CLI.

If you landed here from the Intent Solutions org: **Claude Code Plugins Plus is built and maintained by Jeremy Longshore under Intent Solutions.** The catalog ships and develops in the canonical repository:

### → [github.com/jeremylongshore/claude-code-plugins-plus-skills](https://github.com/jeremylongshore/claude-code-plugins-plus-skills)

## Why it stands out

- **One canonical catalog** — the marketplace manifest *is* the `marketplace.json` the Claude Code CLI reads. No registries to reconcile, no manual sync step.
- **Spec-correct or it doesn't ship** — every contribution runs the Intent Solutions validator against the [AgentSkills.io](https://agentskills.io/specification) open standard plus Claude Code's [skill](https://code.claude.com/docs/en/skills) and [plugin](https://code.claude.com/docs/en/plugins) references. The 8-field marketplace frontmatter (`name / description / allowed-tools / version / author / license / compatibility / tags`) is enforced, not aspirational.
- **Forge-generated and hand-authored, both first-class** — generate production-grade plugins from any REST API with an audit trail, or hand-author against the same templates and validators.
- **Production-tested patterns** — playbooks and a public wiki cover the failure modes that show up at scale: rate limits, MCP reliability, multi-agent cost caps, incident debugging.

## Install

```bash
# Recommended — the ccpi package manager
pnpm add -g @intentsolutionsio/ccpi
ccpi search devops
ccpi install devops-automation-pack
ccpi list --installed

# Or use Claude Code's built-in command
/plugin marketplace add jeremylongshore/claude-code-plugins
```

**Browse the full catalog at [tonsofskills.com](https://tonsofskills.com).**

## Documentation

The complete README, quickstart, contribution guide, validator, playbooks, and wiki all live in the canonical repository:

**[→ Open jeremylongshore/claude-code-plugins-plus-skills](https://github.com/jeremylongshore/claude-code-plugins-plus-skills)**

---

Built and maintained by **Jeremy Longshore** · **Intent Solutions** — [intentsolutions.io](https://intentsolutions.io)
