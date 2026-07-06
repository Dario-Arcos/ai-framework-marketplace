# dario-arcos-plugins

Dario Arcos' plugin catalog. Stable channel for [Viterbi](https://github.com/Dario-Arcos/Viterbi) — the agnostic meta-harness for agentic engineering.

## Install (Claude Code)

```
/plugin marketplace add Dario-Arcos/plugins
/plugin install viterbi@dario-arcos-plugins
/plugin install viterbi-sonar@dario-arcos-plugins
```

## Install (Codex)

```
codex plugin marketplace add Dario-Arcos/Viterbi
codex plugin add viterbi@viterbi
codex plugin add viterbi-sonar@viterbi
```

## Plugins

| Plugin | What it does |
| --- | --- |
| `viterbi` | Core harness workflows: missions, proportional loops, adversarial review, memory GC, skillpack governance, and the `npx viterbi init` onboarding path. |
| `viterbi-sonar` | Sonar and frontier-radar workflows: public-first signal harvest, refute pass, and proposal diffs with a supervised gate. |

## Channels

This catalog serves the `stable` ref of the Viterbi repository — commits land there only after the full promotion gate (harness validator, plugin sync check, and a live install smoke on both runtimes). For the dev channel, add the Viterbi repository directly and track `main`.

## Previous catalog

This repository previously served the `ai-framework` plugin (as `ai-framework-marketplace`). That plugin is deprecated and its repository archived; existing local installs keep working from cache. Viterbi supersedes it.
