# dario-arcos-plugins

Dario Arcos' plugin catalog. Stable channel for [Viterbi](https://github.com/Dario-Arcos/Viterbi) — the agnostic meta-harness for agentic engineering.

## Install (Claude Code)

```
/plugin marketplace add Dario-Arcos/plugins-marketplace
/plugin install viterbi@dario-arcos-plugins
```

## Install (Codex)

```
codex plugin marketplace add Dario-Arcos/Viterbi --ref stable
codex plugin add viterbi@viterbi
```

## What the plugin is

The `viterbi` plugin is a thin onboarding pointer: one skill that detects whether your project already runs the Viterbi harness, guides `npx viterbi init` when it does not, and defers to your repo's own guidance when it does. The npm CLI owns installation, updates, and every operational skill — so the plugin can never drift from the harness in your repo.

## Channels

This catalog serves the `stable` ref of the Viterbi repository. Commits reach `stable` only through the promotion gate: harness validator, plugin sync check, and a live install smoke on both runtimes. For the dev channel, add the Viterbi repository directly and track `main`.

## Previous catalog

This repository previously served the `ai-framework` plugin (as `ai-framework-marketplace`). That plugin is deprecated and its repository archived; existing local installs keep working from cache. Viterbi supersedes it.
