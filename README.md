# pbi-agent Commands Repository

This repository is the official commands catalog for [pbi-agent](https://github.com/pbi-agent/pbi-agent).

It is the canonical workspace for publishing reusable project command presets
that can be installed with `pbi-agent commands add`. Public commands live under
`commands/` as Markdown files. Each command declares its slash alias and metadata
in frontmatter.

## Current Command Catalog

- [`commands/execute.md`](commands/execute.md): execution-first collaboration mode
- [`commands/plan.md`](commands/plan.md): conversational planning mode
- [`commands/review.md`](commands/review.md): code review guidance
- [`commands/retrospective.md`](commands/retrospective.md): post-run workflow retrospective and customization diagnosis
- [`commands/orchestrate.md`](commands/orchestrate.md): sequential sub-agent execution with main-agent review and validation gates
- [`commands/plan-interactive.md`](commands/plan-interactive.md): interactive planning mode with adaptive clarification and environment grounding
- [`commands/refine-task.md`](commands/refine-task.md): task prompt refinement mode for clarifying and scoping user requests into clear task prompts for later planning or implementation
- [`commands/fix-review.md`](commands/fix-review.md): fix review findings from the previous `/review` turn in this session
- [`commands/commit.md`](commands/commit.md): commit staged changes with validation and focused staging workflow
- [`commands/code-quality-review.md`](commands/code-quality-review.md): code quality review guidance focused on maintainability and structural improvements