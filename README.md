# ai-skill-powersync

PowerSync TypeScript SDKs (web, React Native, Node) and sync rules for local-first apps. Use when adding PowerSync to a project, or writing or debugging code that uses @powersync/* packages or sync rules.

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-powersync
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-powersync

# Install plugin (plugin name is topic-only)
/plugin install powersync@guillempuche-ai-skill-powersync
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-powersync.git --path skills/powersync
```

### Manual

Copy `skills/powersync` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
