# Installation

This package follows the official Codex plugin layout.

## Required plugin structure

```text
frontend-architect-os/
├── .codex-plugin/
│   └── plugin.json
└── skills/
    └── <skill-name>/
        └── SKILL.md
```

## Personal local marketplace installation

1. Copy the plugin folder:

```bash
mkdir -p ~/.codex/plugins
cp -R frontend-architect-os ~/.codex/plugins/frontend-architect-os
```

2. Create or update `~/.agents/plugins/marketplace.json`:

```json
{
  "name": "local-personal",
  "interface": {
    "displayName": "Local Personal Plugins"
  },
  "plugins": [
    {
      "name": "frontend-architect-os",
      "source": {
        "source": "local",
        "path": "./.codex/plugins/frontend-architect-os"
      },
      "policy": {
        "installation": "AVAILABLE",
        "authentication": "ON_INSTALL"
      },
      "category": "Developer Tools"
    }
  ]
}
```

3. Restart Codex Desktop.

4. Open Plugins and install or enable **Frontend Architect OS**.

## Important

Copying a folder to `~/.codex/plugins` alone may not be enough. Codex loads plugins through a marketplace entry.
