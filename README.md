# claude-skills

Curated [Claude Code](https://claude.com/claude-code) skills. Loaded into
`~/.claude/skills/` via Home Manager on my NixOS config.

## Skills

| Name | Source | Description |
| --- | --- | --- |
| `grill-with-docs` | vendored from [mattpocock/skills](https://github.com/mattpocock/skills) | Interview-style design exploration that updates `CONTEXT.md` and ADRs inline. |
| `grill-me` | vendored from [mattpocock/skills](https://github.com/mattpocock/skills) | Stripped-down grilling session — interview the user until shared understanding is reached. |
| `handoff` | vendored from [mattpocock/skills](https://github.com/mattpocock/skills) | Compact the current conversation into a handoff doc for a fresh agent to pick up. |

## Vendoring

Third-party skills are copied into this repo verbatim. Each vendored skill
folder includes the upstream `UPSTREAM-LICENSE` file. Credits and links live
in the table above.

To refresh a vendored skill against upstream, replace the contents of its
folder with the new upstream version and update `UPSTREAM-LICENSE` if the
upstream license changed.

## License

This repo is MIT licensed (see `LICENSE`). Vendored skills retain their
original licenses (`UPSTREAM-LICENSE` files inside their folders).
