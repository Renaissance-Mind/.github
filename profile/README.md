<p align="center">
  <img width="1672" height="941" alt="Renaissance Mind vision" src="https://github.com/user-attachments/assets/399db0d9-18b7-406b-b444-7ccfd5c7660c" />
</p>

<h1 align="center">Renaissance Mind</h1>

<p align="center">
  <strong>Human intelligence infrastructure for the agent era.</strong>
</p>

<p align="center">
  Execution observability · Personal context · Cognitive augmentation
</p>

<p align="center">
  <a href="https://github.com/Renaissance-Mind/TokenFlow">TokenFlow</a> ·
  <a href="https://github.com/Renaissance-Mind/Runlight">Runlight</a> ·
  <a href="https://github.com/Renaissance-Mind/agent-in-chat-feishu">Agent-in-Chat Feishu</a>
</p>

Renaissance Mind builds tools for the human side of the Human-Agent Loop: making agent execution observable, personal context controllable, and knowledge representation easier for people to understand, judge, and create with.

AI agents are getting better at writing code, calling tools, searching information, automating workflows, and completing tasks. Faster execution, however, does not automatically make people better at learning, reasoning, or making decisions. We care about the layer that turns agent work into human understanding.

## What We Build

| Layer | Core question | Current work |
| --- | --- | --- |
| **Execution** | What are my agents doing, and what happened after they ran? | Token accounting, run observability, chat-native agent workflows |
| **Context** | How can AI understand a person's history, preferences, projects, and boundaries over time? | Personal context models, chat context, project context, privacy-aware memory |
| **Cognitive Augmentation** | How can complex information become easier to learn, inspect, judge, and reuse? | Knowledge presentation, editable visual reconstruction, thinking surfaces |

Renaissance Mind does not put people and agents in opposition. We assume agents will keep getting more capable; the missing infrastructure is the layer that lets people observe, guide, learn from, and build on that work.

## Public Projects

| Project | What it does | Try it |
| --- | --- | --- |
| [TokenFlow](https://github.com/Renaissance-Mind/TokenFlow) | Private, local-first token accounting for the AI agents you actually use. It uploads usage metadata without prompts, responses, source paths, or session IDs. | `npm install -g @renaissancemind/tokenflow`<br>`tokenflow status` |
| [Runlight](https://github.com/Renaissance-Mind/Runlight) | A live status light for AI-agent runs across projects and machines. It records lifecycle events such as starts, heartbeats, tool activity, permission waits, completions, failures, and aborts without taking control of the agent. | `npm install -g runlight`<br>`runlight setup` |
| [Agent-in-Chat Feishu](https://github.com/Renaissance-Mind/agent-in-chat-feishu) | A Feishu/Lark agent loop that lets local coding agents participate in normal chat workflows, read recent chat context, and execute lightweight tasks when mentioned. | `npm install -g agent-in-chat-feishu@latest`<br>`agentchat setup feishu` |

## Research Tracks

- **Personal Context** — context layers that help AI understand what a person knows, how they prefer to learn, which projects they are working on, and which data must stay local or be forgotten.
- **Knowledge Presentation** — systems for transforming information into representations that are easier for people to inspect, edit, remember, and reuse.
- **DrawAI** — an image-to-editable-SVG/PPTX reconstruction pipeline for knowledge visuals and presentation artifacts.
- **MindCanvas** — a thinking surface for brainstorming, notes, chat, and AI-assisted reasoning.

## Design Principles

- **Human-agent loops over replacement narratives** — agents should make people more capable, not less involved.
- **Observability before automation** — before asking agents to do more, people need to see what happened.
- **Context under user control** — personal context should be understandable, inspectable, and privacy-aware.
- **Knowledge as editable representation** — AI output should become something people can check, modify, and build on.
- **Local-first where it matters** — prompts, responses, source paths, and sensitive context should stay local unless the user explicitly chooses otherwise.

## Quick Start

Token accounting for local AI agents:

```bash
npm install -g @renaissancemind/tokenflow
tokenflow status
```

Live status for agent runs:

```bash
npm install -g runlight
runlight setup
```

Feishu/Lark agent-in-chat workflow:

```bash
npm install -g agent-in-chat-feishu@latest
agentchat setup feishu
```

## Links

- TokenFlow: [GitHub](https://github.com/Renaissance-Mind/TokenFlow) · [Website](https://tokenflow.renaissancemind.ai/)
- Runlight: [GitHub](https://github.com/Renaissance-Mind/Runlight) · [Website](https://runlight.renaissancemind.ai/)
- Agent-in-Chat Feishu: [GitHub](https://github.com/Renaissance-Mind/agent-in-chat-feishu) · [Website](https://agent-in-chat.renaissancemind.ai/)

## Contributing

Renaissance Mind is early and project-specific. Please open issues, discussions, and pull requests in the relevant repository. When reporting a bug, include the tool name, operating system, install method, command output, and any relevant local logs with sensitive content removed.

## Licensing

Licensing is project-specific. Public repositories without a `LICENSE` file should not be assumed to be open source; please check each repository before reusing code.
