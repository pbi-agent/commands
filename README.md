# pbi-agent Commands Repository

This repository is the official commands catalog for [pbi-agent](https://github.com/pbi-agent/pbi-agent).

It is the canonical workspace for publishing reusable project command presets
that can be installed with `pbi-agent commands add`. Public commands live under
`commands/` as Markdown files; each filename becomes the installed slash alias.

## Current Command Catalog

- [`commands/execute.md`](commands/execute.md): execution-first collaboration mode
- [`commands/plan.md`](commands/plan.md): conversational planning mode
- [`commands/review.md`](commands/review.md): code review guidance
- [`commands/retrospective.md`](commands/retrospective.md): post-run workflow retrospective and customization diagnosis
- [`commands/orchestrate.md`](commands/orchestrate.md): sequential sub-agent execution with main-agent review and validation gates
- [`commands/plan-interactive.md`](commands/plan-interactive.md): interactive planning mode with adaptive clarification and environment grounding
