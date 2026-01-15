# Andrew's Renovate Configs

A collection of Renovate presets designed to streamline dependency management with sensible defaults and grouping strategies.

## 📜 Available Presets

### 1. Default (Base)

**Filename:** `default.json`

The standard configuration. Includes `best-practices`, `:automergeAll`, and OSV vulnerability alerts.

**Usage:**

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>maccuaa/renovate-config"]
}
```

### 2. Grouped

**Filename:** `grouped.json`

Inherits from the Default preset but bundles all **minor** and **patch** updates into a single PR to reduce noise.

**Usage:**

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>maccuaa/renovate-config:grouped"]
}
```

## ⚖️ License

[MIT](LICENSE)
