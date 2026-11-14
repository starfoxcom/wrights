# wrights

The Claude Code marketplace for the Wright family of plugins. It lists each plugin by its own GitHub release, pinned by SHA-256, so the plugin you install is exactly the file its project released.

| Plugin | What it does | Project |
|---|---|---|
| `bindwright` | Sets up a repo for agentic coding from a few questions: rules, session skills, guard hooks and review workflows, fitted to the repo. | [starfoxcom/bindwright](https://github.com/starfoxcom/bindwright) |
| `findwright` | A code index that adapts to each project: plain-English questions, names and regex searches over every file the project tracks. | [starfoxcom/findwright](https://github.com/starfoxcom/findwright) |

## Install

Add the marketplace once, then install a plugin from it:

```
claude plugin marketplace add starfoxcom/wrights
claude plugin install bindwright@wrights
claude plugin install findwright@wrights
```

Each plugin's own README covers its setup after the install.

## Updates

Each project's release opens a pull request here that moves its entry to the new release. Run `claude plugin marketplace update wrights`, then `claude plugin update <plugin>@wrights`.
