### Purpose

User-facing edit commands for this repository. Agents acting on this repo should accept these as authoritative shorthand.

### Commands

- **refactor readme** — Apply current `.agents/AGENTS.md` + `.agents/STYLE.md` to `README.md`. Update `.agents/CONTEXT.md` in the same change if facts shifted.
- **update skills** — Edit the skills grouping in `README.md` and the `Skill grouping` block in `.agents/CONTEXT.md`. Both in one commit.
- **update roles** — Edit the employment / role section in `README.md` and the `Employment / contract history` block in `.agents/CONTEXT.md`. Both in one commit.
- **refresh stack icons** — Regenerate the skillicons.dev line in `README.md` based on `.agents/CONTEXT.md`. Do not introduce icons not represented in CONTEXT.
- **add project highlight** — Add a single concrete project line under the relevant section. Must be tied to a consequence (scale, role, outcome), never a bare repo name.
- **shrink readme** — Pass: cut adjectives, remove decorative formatting, collapse redundant sentences. No factual loss.
- **enforce style** — Re-read `.agents/STYLE.md` and rewrite weak proof, hype vocabulary, or stack-flexing sentences.
- **verify agents** — Read `.agents/AGENTS.md`, `.agents/SECURITY.md`, `.agents/STYLE.md`, `.agents/CONTEXT.md`, `.agents/COMMANDS.md` and confirm `README.md` does not violate any rule. Report drift without auto-fixing unless asked.

### Command discipline

- Each command produces a single focused commit unless the user asks otherwise.
- README content changes never include unrelated repo restructuring.
- Governance changes (anything in `.agents/`) get their own commit with rationale.

### Related

- [[.agents/AGENTS|Governance]]
- [[.agents/STYLE|Style]]
- [[.agents/CONTEXT|Context]]
