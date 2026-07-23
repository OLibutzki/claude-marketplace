# libutzki-marketplace

A personal Claude Code plugin marketplace.

## Adding this marketplace

```
/plugin marketplace add OLibutzki/claude-marketplace
```

## Installing a plugin

```
/plugin install devcontainer-claude@libutzki-marketplace
```

## Plugins

- **devcontainer-claude** — a skill that wires the Claude Code CLI into dev containers
  using the [`ghcr.io/olibutzki/devcontainer-feature-claude-code/claude-code`](https://github.com/olibutzki/devcontainer-feature-claude-code)
  feature. Triggers automatically when someone wants to set up a devcontainer with
  Claude Code available in it. The feature installs Claude Code via the native installer,
  enforces a non-root `remoteUser`, always runs a default-deny egress firewall
  (extendable via `allowedDomains`), and auto-persists auth/config across rebuilds — no
  manual `mounts`/`capAdd` needed. The `version` option accepts `"latest"` (default;
  newest release) or `"stable"` (~1 week behind, skips releases with major regressions)
  alongside an exact version pin.
