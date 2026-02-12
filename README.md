# izantech Claude Plugins

Developer productivity plugins and multi-agent workflows for Claude Code.

## Setup

First, register this marketplace with Claude Code:

```bash
claude plugin marketplace add izantech/claude-plugins
```

This only needs to be done once. The marketplace will be available in all future sessions.

## Installation

Install plugins from this marketplace using:

```bash
/plugin install <plugin-name>@izantech
```

## Available Plugins

### lineup

Structured multi-agent workflow for complex development tasks.

**Install:**
```bash
/plugin install lineup@izantech
```

**Features:**
- Multi-stage pipeline: Clarify → Research → Plan → Implement → Verify
- Specialized subagents with role-specific tools and models
- Persistent memory across sessions
- Slash commands for workflow automation

[View full documentation →](https://github.com/izantech/lineup)

## Contributing

Have a plugin idea or improvement? Open an issue or PR!

## License

MIT
