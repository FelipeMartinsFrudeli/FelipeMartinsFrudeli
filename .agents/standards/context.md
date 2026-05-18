### Purpose

Factual baseline the README must stay consistent with. When facts change, update this file in the same commit as the README change.

### Identity

- Name: Felipe Frudeli (full: Felipe Martins Frudeli)
- Location: São Paulo, Brazil
- GitHub: https://github.com/FelipeMartinsFrudeli
- LinkedIn: https://linkedin.com/in/felipe-martins-frudeli
- Public contact email: `contato@felipefrudeli.com`
- Personal domain: felipefrudeli.com

### Career target (current, 2026-05-18)

- **Primary 24-month bet:** ASML Application Software, Veldhoven (NL). Path = "Option C — C++ pivot + Application Software role" per `Plans/asml_career_path/asml_path_decision.md`.
- **Standing ambition:** top 0.1% software engineer band, C++17/20 specialization. Honest base rate ~5–15% on a 48-month plan; kill-switches at month 18 and month 30.
- **Working language:** English-first.
- **EU mobility:** Brazilian citizen, jus sanguinis dossier in progress. ASML sponsors the Dutch Highly Skilled Migrant permit for qualifying SWE roles.

### Current professional structure (2026)

- Felipe is a **PJ (third-party contractor) developer**, not a W2/CLT employee.
- He holds simultaneous PJ contracts with **Petri Tecnologia** and **Plantoo**. Petri is his current employer of record; Petri also contracts work for Plantoo, so part of the work delivered for Plantoo flows through the Petri relationship.
- The README should describe this as "third-party developer at Petri Tecnologia and Plantoo (PJ)" rather than implying conventional employment with either.

### Current work (public-relevant)

- **AGROOPS - PLANTOO** (2025–) — current client work, partly routed through Petri. Stack in 2026: **Spring Boot (Java 21) backend, React + Vite web, Expo / React Native mobile**. Live surfaces: `https://plantoo-v3.felipefrudeli.com`, API at `https://plantoo-v3-api.felipefrudeli.com/agroops/health`. Felipe owns the structural refactor of the API and active delivery across backend and mobile slices.
- **Petri Tecnologia** (2024–) — current employer of record. Delivery across customer products including AWS-based facial-recognition workflows and offline-first farm-management mobile features.
- **Comodoro** (active context) — Petri-owned delivery app created from zero, with production API + web operational flows.
- **Inovent** (active context) — Petri-owned complete ERP + NF-e system created from zero for production business operations.
- **IA Flow** (active context) — Petri-owned support and tickets app rebuilt from legacy code to restore operational continuity.
- Prior Plantoo stack (Express backend, Vue web) is historical and should not be the current stack description.

### Documented outcomes (AGROOPS - PLANTOO, sourced from vault — do not invent)

Source-of-truth: `/var/www/AGENTS/notes_agent/.agents/.claude/memory/plantoo-v3-felipe-v2-refactor.md` (state as of 2026-04-29 on branch `refactor/felipe-v2`).
Public README copy rule: prefer percentage/business-impact phrasing; avoid absolute defect-count deltas on public profile text.

- Sonar reliability issues: **70 → 0** ✅
- Sonar security issues: **3 → 0** ✅
- Sonar maintainability issues: **419 → 230** (−45%) ✅
- Anemic-entity violations (POL-3): **32 → 0** ✅
- `application/workflows/` files: **14 → 0** (directory eliminated) ✅
- Workflow layer migration: **100% removal** of legacy `application/workflows/` (14 files → 0) in favor of modular use-case structure.
- Authentication and token flows moved to explicit use cases + service ports (`AuthLoginGuard`, `RefreshTokenIssuer`, `RefreshTokenReader`).
- Work-order remuneration boundaries moved to explicit application service port + infrastructure implementation.
- Architectural invariants enforced mechanically via `.agents/check-structure.sh` `--pol1` / `--pol3` flags.
- Refactor tooling Felipe authored (Python): `prune_imports.py`, `prune_wildcards.py`, `collapse_imports.py`, `extract_consts.py` — used to compress **1,605 imports across 478 files**.

### Skill grouping (current, honest)

- **Production now (Petri + AGROOPS - PLANTOO):**
  - Backend: Java 21, Spring Boot, Maven (AGROOPS - PLANTOO). TypeScript / Node.js (NestJS, Express) on legacy and parallel work at Petri.
  - Frontend: React + Vite.
  - Mobile: React Native (Expo).
  - Data: PostgreSQL.
  - Cloud / infra: AWS (S3, Rekognition), Docker, GitHub Actions.
- **In active pivot (2026):** C++17/20 toward ASML Application Software bar. 16-week curriculum in `Plans/asml_career_path/c_pivot_16_week_curriculum.md`. **Currently below interview-pass level** — the README must not overclaim.
- **Open-source stack (not a job):** active contributor to `paperclipai/paperclip` (agent orchestration platform). This is part of the toolchain Felipe uses to operate, plus public proof of working at the edge of agent tooling. **Must not be presented as employment or selected work.**
- **Architecture posture:** DDD, Clean Architecture, hexagonal-style boundaries, SOLID, enterprise integration patterns — used when they pay off, never as identity markers. The AGROOPS - PLANTOO refactor specifically pushed for stricter hexagonal boundaries and contract-first backend design.

### Prior experience (de-emphasized on this surface)

- **Benverse Protector** (Roblox, 2022–2024) — Lua game, 16.3M+ visits at peak. Real production scale, but **not aligned with the current backend / fullstack engineering profile** Felipe wants this README to project. Treat as optional one-line "prior work" mention at most, or omit.

### Open-source signal

- Active 2026 contributor to `paperclipai/paperclip` via fork at `FelipeMartinsFrudeli/paperclip`. Dominant GitHub activity through 2026.
- Profile: 12 public repos, 121 followers, account opened 2019-05-24.

### Education

- **ETEC Sales Gomes** — Technical Degree in Systems Analysis and Development, Tatuí/SP. **Completed 2025.**

### Audience this README is written for

- ASML recruiters and engineering hiring panels (Veldhoven, NL).
- Senior IC interviewers at global tier-1 software companies scanning a profile in 60 seconds.
- Open-source collaborators landing from `paperclipai/paperclip` activity.

### Out of scope (do not put in this README)

- Frudeli Softwares, Frudeli Blox Studio.
- FRD Technologies, FRD Flow State (not a business yet).
- Internal Frudeli infrastructure (SERVER_01, NOTES_AGENT, vault tooling, MAIN_AGENT, sub-agents).
- Personal financial information, family details, address.
- "Operator-architect" or founder framing.
- Software-architect aspirations without active architect-track work.
- OSINT / investigative tech as a stated interest.

### Related

- [[.agents/standards/agents|agents]]
- [[.agents/standards/style|style]]
