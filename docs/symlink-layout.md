# Symlink layout — dotfiles (env)

Managed links installed by `scripts/fix-links` (`--fix` repairs, no flag checks).
Etabli core links (Pi/Claude/agents workflow, skill catalog) stay in
etabli `docs/symlink-layout.md` and `scripts/check-fix-symlinks.sh`.

- `~/.config/nvim` -> `nvim/`
- `~/.tmux.conf` -> `tmux.conf`
- `~/.config/ghostty/config` -> `ghostty/config`
- `~/.config/herdr/config.toml` -> `herdr/config.toml`
- `~/.config/herdr/plugins/config/sessionizer/config.toml` -> `herdr/layouts/sessionizer.config.toml`
- `herdr/skills/herdr` linked into `~/.claude/skills/herdr`, `~/.codex/skills/herdr`, `~/.config/devin/skills/herdr`, `~/.agents/skills/herdr`, `~/.pi/agent/skills/herdr`
- macmini deploy: etabli `scripts/herdr-sync-mini` copies `herdr/` + vault resolver → `~/work/etabli-herdr/` (stays etabli-side until moved)
- do not commit `pi/extensions/herdr-agent-state.ts` (etabli-side rule, unchanged)
