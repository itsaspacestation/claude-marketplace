# claude-marketplace

Claude Code plugin marketplace by itsaspacestation. Each plugin lives in its own repository. This repository only holds the catalogue in `.claude-plugin/marketplace.json`.

## Install
```
/plugin marketplace add itsaspacestation/claude-marketplace
/plugin install <plugin>@itsaspacestation
```

## Plugins
| Plugin | Repository | Description |
|---|---|---|
| `ni` | [itsaspacestation/natural-intelligence](https://github.com/itsaspacestation/natural-intelligence) | Terse replies, TDD, DDD, git conventions, reviews, .NET and Rust builds, planning, evidence-based analysis |

## Add a plugin
Add an entry to `plugins[]` with a `github` source, then run `claude plugin validate . --strict`.
