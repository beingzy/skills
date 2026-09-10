# Personal Skills

Reusable Codex skills maintained by beingzy.

## Catalog

| Skill | Purpose | Use When | Agent Notes | Pairs Well With |
|---|---|---|---|---|
| [`flat-minimal`](./flat-minimal/) | Quiet, flat, minimal UI polish with outline-less enclaves, calm spacing, selective width breakouts, and factual brand fidelity. | Polishing websites, landing pages, brand kits, docs pages, public product pages, or product-adjacent UI toward a chill, structured, external-facing style. | [Claude Code](./flat-minimal/agents/claude-code.md), [OpenCode](./flat-minimal/agents/opencode.md), [OpenAI](./flat-minimal/agents/openai.yaml) | `design-taste-frontend`, `impeccable` |
| [`reader-centered-writing`](./reader-centered-writing/) | Reader-centered structure and close rhetorical analysis from passages through article series. | Planning, drafting, revising, or analyzing explanations, arguments, product announcements, tutorials, and connected essays. | [OpenAI](./reader-centered-writing/agents/openai.yaml) | `copywriting`, `craft-engineering-blog`, `launch` |

## Structure

Each skill lives in its own folder and contains:

- `SKILL.md`: trigger metadata and core instructions
- `agents/`: runtime-specific UI metadata or agent notes
- `references/`: optional deeper guidance loaded only when needed

## Invocation

Use a skill by name in a prompt:

```text
Use $flat-minimal with impeccable to polish this brand page.
Use $reader-centered-writing to plan an article series around a complex idea.
```

Skills provide focused methods and preferences while still relying on project context and any broader domain-specific guidance.
