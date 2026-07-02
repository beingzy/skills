# Personal Skills

Reusable Codex skills maintained by beingzy.

## Catalog

| Skill | Purpose | Use When | Agent Notes | Pairs Well With |
|---|---|---|---|---|
| [`flat-minimal`](./flat-minimal/) | Quiet, flat, minimal UI polish with outline-less enclaves, calm spacing, selective width breakouts, and factual brand fidelity. | Polishing websites, landing pages, brand kits, docs pages, public product pages, or product-adjacent UI toward a chill, structured, external-facing style. | [Claude Code](./flat-minimal/agents/claude-code.md), [OpenCode](./flat-minimal/agents/opencode.md), [OpenAI](./flat-minimal/agents/openai.yaml) | `design-taste-frontend`, `impeccable` |

## Structure

Each skill lives in its own folder and contains:

- `SKILL.md`: trigger metadata and core instructions
- `agents/`: runtime-specific UI metadata or agent notes
- `references/`: optional deeper guidance loaded only when needed

## Invocation

Use a skill by name in a prompt:

```text
Use $flat-minimal with impeccable to polish this brand page.
```

The skill is intended as a preference overlay. It should guide taste and review criteria while still relying on project context, brand guidelines, and broader frontend design skills.
