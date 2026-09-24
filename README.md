# dotfiles

Public personal environment repo: terminal, editor, multiplexer configs.
No credentials, no tokens, no session state — ever.

Workflow: Etabli scaffold (see `workflow/spec.md`). Deployed files under
`workflow/`, `docs/agent-*`, `AGENTS.md`, `CLAUDE.md`, `PLAN*`, `scripts/plan-*`
are local-only via `.git/info/exclude` (managed by `deploy-workflow`),
never committed here.
