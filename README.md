

## Installing with Skilz (Universal Installer)

The recommended way to install this skill across different AI coding agents is using the **skilz** universal installer.

### Install Skilz

```bash
pip install skilz
```

This skill supports [Agent Skill Standard](https://agentskills.io/) which means it supports 14 plus coding agents including Claude Code, OpenAI Codex, Cursor and Gemini.


### Git URL Options

You can use either `-g` or `--git` with HTTPS or SSH URLs:

```bash
# HTTPS URL
skilz install -g https://github.com/wshobson/agents

# SSH URL
skilz install --git git@github.com:wshobson/agents.git
```

### Claude Code

Install to user home (available in all projects):
```bash
skilz install -g https://github.com/wshobson/agents
```

Install to current project only:
```bash
skilz install -g https://github.com/wshobson/agents --project
```

### OpenCode

Install for [OpenCode](https://opencode.ai):
```bash
skilz install -g https://github.com/wshobson/agents --agent opencode
```

Project-level install:
```bash
skilz install -g https://github.com/wshobson/agents --project --agent opencode
```

### Gemini

Project-level install for Gemini:
```bash
skilz install -g https://github.com/wshobson/agents --agent gemini
```

### OpenAI Codex

Install for OpenAI Codex:
```bash
skilz install -g https://github.com/wshobson/agents --agent codex
```

Project-level install:
```bash
skilz install -g https://github.com/wshobson/agents --project --agent codex
```


### Install from Skillzwave Marketplace
```
# Claude to user home dir ~/.claude/skills
skilz install wshobson_agents/plugins__developer-essentials__skills__debugging-strategies

# Claude skill in project folder ./claude/skills
skilz install wshobson_agents/plugins__developer-essentials__skills__debugging-strategies --project

# OpenCode install to user home dir ~/.config/opencode/skills
skilz install wshobson_agents/plugins__developer-essentials__skills__debugging-strategies --agent opencode

# OpenCode project level
skilz install wshobson_agents/plugins__developer-essentials__skills__debugging-strategies --agent opencode --project

# OpenAI Codex install to user home dir ~/.codex/skills
skilz install wshobson_agents/plugins__developer-essentials__skills__debugging-strategies

# OpenAI Codex project level ./.codex/skills
skilz install wshobson_agents/plugins__developer-essentials__skills__debugging-strategies --agent opencode --project


# Gemini CLI (project level) -- only works with project level
skilz install wshobson_agents/plugins__developer-essentials__skills__debugging-strategies --agent gemini

```

See this site [skill Listing](https://skillzwave.ai/skill/wshobson__agents__plugins__developer-essentials__skills__debugging-strategies__SKILL/) to see how to install this exact skill to 14+ different coding agents.


### Other Supported Agents

Skilz supports 14+ coding agents including Claude Code, OpenAI Codex, OpenCode, Cursor, Gemini CLI, GitHub Copilot CLI, Windsurf, Qwen Code, Aidr, and more.

For the full list of supported platforms, visit [SkillzWave.ai/platforms](https://skillzwave.ai/platforms/) or see the [skilz-cli GitHub repository](https://github.com/SpillwaveSolutions/skilz-cli)


<a href="https://skillzwave.ai/">Largest Agentic Marketplace for AI Agent Skills</a> and
<a href="https://spillwave.com/">SpillWave: Leaders in AI Agent Development.</a>

