# Codex Plugins

Private Codex plugin marketplace for reusable workflows.

## Marketplace

Codex should consume this repository with a sparse marketplace path:

```bash
codex plugin marketplace add <owner>/codex-plugins --sparse .agents/plugins
```

Plugins live under `.agents/plugins/plugins/<plugin-name>` and are listed in `.agents/plugins/marketplace.json`.
