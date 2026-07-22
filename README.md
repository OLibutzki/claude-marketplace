# libutzki-marketplace

A personal Claude Code plugin marketplace.

## Adding this marketplace

Local path:

```
/plugin marketplace add C:\Entwicklung\claude\claude-plugin-marketplace
```

Once pushed to GitHub, it can instead be added as `owner/repo`.

## Installing a plugin

```
/plugin install devcontainer-claude@libutzki-marketplace
```

## Plugins

- **devcontainer-claude** — a skill that wires the Claude Code CLI into dev containers
  using the [`ghcr.io/OLibutzki/devcontainer-features/claude-code`](https://github.com/OLibutzki/devcontainers-claude-feature)
  feature. Triggers automatically when someone wants to set up a devcontainer with
  Claude Code available in it.
