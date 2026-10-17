## Josh Mabry

AI and product engineer. Agent workflows. Developer tools. Interfaces. AI systems R&D at [protoLabs.studio](https://protolabs.studio).

### Agent systems

- **[protoAgent](https://github.com/protoLabsAI/protoAgent)**: open-source
  multi-agent framework on LangGraph. The model runs the tool loop, delegates to
  subagents, other agents and coding agents, keeps memory across sessions, and
  reaches models through a LiteLLM gateway. Extended by git-URL plugins. MIT.
- **How it's built**: by directing AI coding agents behind test and review gates.
  Agents do the volume; the gates check each change; every fixed bug gets a
  regression test.
- **The operator console**: the React surface the fleet is run from. Live agent
  state, task progress, tool calls, output.
- **[protoLab](https://github.com/protoLabsAI/protoLab)**: self-hosted inference and
  evaluation lab (vLLM, LiteLLM, Langfuse) benchmarking local models against
  frontier models on agent tasks.
- **[ORBIS](https://orbis.protolabs.studio)**: voice-first companion (Rust, Tauri).
  Speech and a small model on-device; heavier reasoning goes to the fleet over A2A.

### Interfaces

- **[protoLabs design system](https://storybook.protolabs.studio)**: TypeScript
  React with Storybook interaction tests, including components for agent UIs: tool
  cards, command palette, AI surfaces.
- **[GlyphKit](https://glyphkit.design)**: 38 primitives, design tokens,
  motion and theme foundations, with a published Storybook.
- **FEWS NET data visualization** (Phase2, 2022): accessible chart and map Web
  Components for the famine early warning network, rendered to screen and to
  printed reports. [Public visualization spec](https://help.fews.net/brand/visualizations).

[joshmabry.dev](https://joshmabry.dev) · [LinkedIn](https://linkedin.com/in/mabry1985)
