# Codex Plugins

Private Codex plugin marketplace for reusable workflows.

## Install

Add the marketplace from GitHub:

```bash
codex plugin marketplace add <owner>/codex-plugins
```

The repository also keeps a `.agents/plugins` mirror for tools that expect repo-scoped marketplace files, but the root `marketplace.json` is the canonical manifest for `codex plugin marketplace add`.

## Layout

- `marketplace.json`: marketplace manifest consumed by Codex.
- `plugins/<plugin-name>`: plugin packages referenced by the root marketplace.
- `.agents/plugins`: mirrored marketplace layout for repo-scoped workflows.
