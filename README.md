# clave-skills

Marketplace for the [clave](../claw) assistant hub. Each plugin lives in its own repo and is
listed in `.claude-plugin/marketplace.json`; this repo is only the catalog.

Install in Claude Code:

```
/plugin marketplace add trianglegrrl/clave-skills
/plugin install mms-assistant@clave
```

Add a domain by publishing a plugin repo (`.claude-plugin/plugin.json` + `skills/<name>/SKILL.md`,
see mms-assistant for the shape) and appending it to `plugins` here. Planned: `home-assistant`.
