### Purpose

Voice, vocabulary, and visual rules the README must follow.

### Voice

- Archetype: serious backend / fullstack engineer pivoting upward toward ASML Application Software and top-tier global C++ SWE. Public surface is engineering identity, not founder/CEO.
- Register: **short engineering RFC, persuasive copywriting layer on top.** Formal section headers, HR-readable language inside, technical credibility implicit in the numbers cited.
- Sentence style: short, declarative, verb-led. The bullet that opens "Reduced reliability defects from 70 to 0" beats any sentence that opens with a technology name.
- Tone: precise, sober, persuasive through evidence. No hype, no exclamations, no "passionate", no "results-driven", no marketing voice.
- Honesty bar: never overclaim a skill that is in active pivot. "Building C++17/20 depth" is fine. "C++ engineer" is not, until production C++ work exists.

### Amplify

- direct
- results-first
- structured
- technically mature
- low-ego

### Suppress

- consultancy / agency tone
- founder-CEO framing
- generic "passionate developer" / "innovator" language
- stack-flexing without consequence
- complex words used to substitute for results
- emoji walls and decorative formatting

### Vocabulary

- Lead with what was shipped and what changed. Architecture vocabulary (DDD, Clean Architecture, hexagonal, EIP, SOLID) appears only when paired with a concrete consequence.
- Prefer plain results phrasing over pattern names:
  - "fewer regressions" over "high code quality"
  - "stable contracts between services" over "well-designed APIs"
  - "less manual rework for support" over "robust integrations"
- The C++ pivot is described as **active** or **in progress**, never as a current production skill.

### Reader takeaway after the README

- this person ships, and the ships run in production
- this person can grow into deeper systems work — C++ pivot is real and underway
- this person will not hide gaps behind jargon

### Visual

- Cold, premium, structured surfaces.
- More white space than decoration.
- One skillicons row is acceptable as a secondary visual; prose must work without it.
- Strong typography hierarchy. `##` for top-level sections, `###` for subsections, bold for emphasis inside paragraphs.
- No animated gifs, no visitor counters, no third-party trophy widgets.

### Proof discipline

- Strong proof: shipped refactors with measurable before/after; named features delivered into production; active open-source contributions to a public project; in-progress study with a defined target.
- Weak proof: pattern-name lists, generic "X years of experience" claims, follower counts, title inflation, "experience with" sentences without an outcome.
- Production Roblox work (`Benverse Protector`) is real but is **not aligned with the current backend / fullstack profile**. Omit on this surface; kept on file in `context.md` only.

### RFC bullet rule

Every Outcomes-section bullet must answer: **What did Felipe personally do, and what is the measurable result?**

- ✅ "Reduced Sonar reliability issues from 70 to 0 on the production API."
- ✅ "Broke a 1,472-line workflow class into 16 cohesive use cases without changing observable behavior."
- ✅ "Shipped a facial-recognition feature into a live customer product."
- ❌ "Experience with Spring Boot and DDD."
- ❌ "Worked on backend features."

### Localization

- README is English-first.

### Related

- [[.agents/standards/agents|agents]]
- [[.agents/standards/context|context]]
