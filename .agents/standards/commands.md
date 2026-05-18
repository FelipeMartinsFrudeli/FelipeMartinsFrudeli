### Purpose

User-facing edit commands for this repository.

### Commands

- **refactor readme** — Apply current `.agents/standards/agents.md` + `style.md` to `README.md`. Update `context.md` in the same change when facts shifted.
- **update stack** — Edit the stack section in `README.md` and the `Skill grouping` block in `context.md`. Both in one commit.
- **update work** — Edit the current-work section in `README.md` and `Current work` in `context.md`. Both in one commit.
- **refresh stack icons** — Regenerate the skillicons.dev row in `README.md` based on `context.md`. Only icons represented in `context.md`.
- **shrink readme** — Pass: cut adjectives, remove decorative formatting, collapse redundant sentences. No factual loss.
- **enforce style** — Re-read `style.md` and rewrite weak proof, hype vocabulary, or stack-flexing sentences. Tighten honesty bar on the C++ pivot.
- **verify agents** — Read every file in `.agents/standards/` and confirm `README.md` does not violate any rule. Report drift without auto-fixing unless asked.
- **publish** — Run `git push origin main` after explicit operator approval. Never push without an active accepted confirmation on the controlling Paperclip issue.

### Command discipline

- Each command produces a single focused commit unless the operator asks otherwise.
- README content changes never include unrelated repo restructuring.
- Governance changes get their own commit with rationale.

### Related

- [[.agents/standards/agents|agents]]
- [[.agents/standards/style|style]]
- [[.agents/standards/context|context]]
