# Felipe Frudeli — Engineering Profile

> **Status:** Active · **Track:** Backend / Fullstack engineer · **Next bet:** ASML Application Software, Veldhoven (NL) · **Long arc:** Top-tier global C++ software engineering

## Summary

I move production codebases from "fragile, hard to change" to "stable, safe to ship". Recent example: I led the structural refactor of a Spring Boot 21 platform now serving customers in production — cutting reliability defects from **70 to 0**, security defects from **3 to 0**, maintainability debt by **−45%**, and eliminating an entire 14-file legacy "workflows" layer in the process.

The kind of engineer hiring managers describe as: *"will leave the system measurably better than they found it."*

## Background

- **Country / time zone:** São Paulo, Brazil — open to relocation, EU eligibility track in progress.
- **Current contract structure:** PJ third-party developer with **Petri Tecnologia** (employer of record) and **Plantoo** (client). Part of the Plantoo delivery flows through the Petri relationship.
- **Active product contexts:** **Comodoro** (delivery + operations platform), **Inovent** (frontend architecture workstream), and **IA Flow** (AI-enabled workflow and automation context).
- **Education:** Technical degree in Systems Analysis and Development, ETEC Sales Gomes (Tatuí/SP) — completed 2025.
- **Working language:** English (technical reading and writing), Portuguese (native).

## Outcomes shipped

### Plantoo V3 — platform refactor and live-go

> Owned the structural refactor of the V3 generation of a multi-tenant agribusiness platform, taking it from a fragile state to a controlled production go-live.

- **Reduced Sonar reliability issues from 70 to 0** and **security issues from 3 to 0** on the production API.
- **Reduced maintainability debt by 45%** (419 → 230 issues), measured by an independent SonarQube scan post-refactor.
- **Eliminated a 14-file legacy "workflows" layer**, the codebase's largest source of hidden coupling. Notable conversions:
  - A single 1,472-line workflow class broken down into 16 cohesive use cases with a shared helper and an audit value record — preserving behavior verbatim.
  - An 840-line authentication workflow rewritten as 9 use cases plus 3 service ports for login guarding and refresh-token handling.
  - A 1,333-line remuneration workflow extracted to an explicit service port — clarifying boundaries between billing logic and the rest of the API.
- **Locked architectural invariants in CI** so the gains hold under future change: every use case has a single typed entry point, every service has a clean interface/implementation split, and domain entities now carry their own behavior instead of being passive data bags.
- **Built mechanical refactor tooling** (Python scripts) to compress over **1,600 imports across 478 files** safely and to extract repeated literals into named constants — converting a multi-week manual cleanup into a deterministic, reviewable pass.

### Petri Tecnologia — features delivered into production

- **Shipped a facial-recognition feature** into a live customer product, using AWS Rekognition + S3 for the pipeline. Designed the integration so the recognition path could fail gracefully without blocking the rest of the user flow.
- **Built offline-first farm-management mobile features** in Android (Kotlin) and React Native, with Crashlytics feedback loops to surface regressions within hours instead of weeks.
- **Hardened backend services in production** — including the Plantoo work above, where Petri is the contracting party.

## Open-source

Active contributor to **[paperclipai/paperclip](https://github.com/paperclipai/paperclip)** — an open-source agent orchestration platform. Push fixes and patterns upstream as part of using it day-to-day. Not employment; part of how I work.

## Direction

The 24-month bet is **ASML Application Software in Veldhoven**. The path is a focused C++17/20 ramp tied to ASML's interview bar, running in parallel with continued backend production work and open-source contributions. The longer arc is top-tier global software engineering at C++ depth — measured by external validation, not by self-assessment.

I write English-first for international reach. EU work eligibility (jus sanguinis) is in progress as a parallel track.

## Contact

- **Email:** [contato@felipefrudeli.com](mailto:contato@felipefrudeli.com)
- **LinkedIn:** [felipe-martins-frudeli](https://linkedin.com/in/felipe-martins-frudeli)
- **GitHub:** you are here.
