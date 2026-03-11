# jwcarman-marketplace

Claude Code plugins by [James Carman](https://github.com/jwcarman).

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add jwcarman/jwcarman-marketplace
```

## Available Plugins

### ralph-plugin

Autonomous spec-by-spec AI development loop. Scaffold a project, write specs, and let Claude implement them one at a time — tests are the judge.

```
/plugin install ralph-plugin@jwcarman-marketplace
```

| Command | What it does |
|---------|-------------|
| `/ralph-plugin:init` | Scaffold Ralph Loop + guided PRD setup |
| `/ralph-plugin:spec` | Write a new spec with guided brainstorming |
| `/ralph-plugin:run` | Execute one iteration (used by `ralph-loop.sh`) |
| `/ralph-plugin:status` | Show progress, remaining specs, recent commits |
| `/ralph-plugin:promote` | Promote `specs/backlog/` items to the active queue |

See [ralph-plugin](https://github.com/jwcarman/ralph-plugin) for full documentation.
