# Changelog

## 1.0.1 - 2026-11-05

- README: list what each hook reads and changes, for the plugin directory review.
- Screenshots re-encoded smaller, without metadata.

## 1.0.0 - 2026-11-05

First public release. The plugin is now named `agent-crabs` (it was `agents` in development builds).
If you ran a development build named `agents`, move `pluginConfigs.agents` in your settings to `pluginConfigs.agent-crabs`.

- Docked Agents pane with live status, newest first, last 100 agents.
- A crab costume per agent type.
- Model, effort, context bar, output tokens, requests, tool calls and elapsed time per agent.
- Latest tool call while an agent runs.
- Transcript viewer: open any subagent's transcript from the pane or with `/agents-pane view`, and return with `/agents-pane back`.
- Fallback rows above the prompt when the pane is closed or the terminal is too narrow, set with the `rows` option.
- Needs Claude Code 2.1.300 or later.
