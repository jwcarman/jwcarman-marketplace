# jwcarman-marketplace

This repo **is** the Claude Code marketplace — it defines and publishes plugins authored by James Carman.

## Structure

- `.claude-plugin/marketplace.json` — the marketplace manifest; lists all plugins with their source repo and pinned version
- `README.md` — public-facing docs shown on GitHub

## How to update a plugin version

Edit the `version` field for the relevant plugin in `.claude-plugin/marketplace.json`. That's it.

## Current plugins

| Plugin | Source | Description |
|--------|--------|-------------|
| `ralph-plugin` | https://github.com/jwcarman/ralph-plugin.git | Autonomous spec-by-spec AI development loop |
