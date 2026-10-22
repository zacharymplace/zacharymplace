# Z$ — Systems Builder

I build governed AI systems, operational infrastructure, and evidence-driven products.

My work focuses on a practical question: **how do we make software capable without making its actions opaque, unbounded, or difficult to recover from?** I turn that question into state machines, authorization boundaries, evidence contracts, operator surfaces, tests, and working systems.

[Explore my portfolio](https://z-systems-builder.zacharyplace.chatgpt.site) · [View my flagship case study](https://sentra-hermes-case-study.zacharyplace.chatgpt.site)

## Flagship case study: Sentra–Hermes

Integrity-gated lifecycle infrastructure for governed AI agents.

The Hermes name refers to [Nous Research’s Hermes Agent](https://github.com/NousResearch/hermes-agent). My contribution is the surrounding operating infrastructure: Sentra’s decision layer, authorization boundaries, readiness checks, verification, and preserved evidence for workflows involving Hermes agents. The case study does not claim authorship of Hermes Agent or establish that Hermes Agent executed the historical checkpoint tasks.

Sentra–Hermes turns agent execution into a bounded, inspectable sequence:

**Readiness → Authorization → Execution → Verification → Advancement → Completion**

The documented successor-lifecycle checkpoint recorded:

- 13/13 repository-integrity checks passed
- 3/3 governed tasks completed
- Four single-transition authorizations consumed
- Zero recovery issues found in a read-only replay of the historical checkpoint snapshot
- Predecessor and successor evidence preserved

These are results from a bounded lifecycle checkpoint, not a claim of general production readiness. The case study documents the implementation and its evidence; Hermes Observability below provides related public tooling.

[Read the flagship case study](https://sentra-hermes-case-study.zacharyplace.chatgpt.site)

## Selected public repositories

These five pinned repositories show how I turn operating ideas into inspectable software. Each README includes first-run steps, an example output or development screenshot, and the limits of the current version.

| Project | What you can inspect or try | Current scope |
| --- | --- | --- |
| [**Pick Up Here**](https://github.com/zacharymplace/pick-up-here) | Resume work in a Git repository using saved evidence, change comparisons, and optional local Gemma guidance. | **Prototype release candidate.** Facts and comparison work without AI; collected evidence does not establish runtime correctness. |
| [**Commonfeed**](https://github.com/zacharymplace/commonfeed) | Read RSS and Atom feeds in finite sessions with explained selections and private feedback. | **Published local reader; focused product probe.** Includes a fictional sample session. Long-term reliability and improved reading outcomes are not established here. |
| [**Backsolve**](https://github.com/zacharymplace/backsolve) | Record decisions, evidence, tests, and outcomes behind AI-assisted work in Whyfiles and portable archives. | **Local v0.1 CLI prototype.** Records are assembled deterministically from explicit captures; the confidence score is a heuristic, not independent verification. |
| [**LineForge**](https://github.com/zacharymplace/lineforge) | Turn chess games into annotations, mistake cards, review sessions, and portable study artifacts. | **Local v0.1 application prototype.** Coach lenses are deterministic; optional Stockfish analysis is separate. Learning gains and broader usability remain unproven. |
| [**Hermes Observability**](https://github.com/zacharymplace/hermes-observability) | Inspect observability standards, structured trace contracts, and local readiness reports. | **v0.1 standards and validation tooling.** A fixture PASS does not establish live ingestion, another repository's compliance, or production readiness. |

Start with the repository READMEs for runnable examples and current boundaries. A passing check supports the behavior it exercises; it does not by itself establish user value or readiness for production.

## How I work

- Make authority explicit.
- Preserve evidence instead of rewriting inconvenient history.
- Design stopping points and recovery paths before scaling execution.
- Connect technical implementation to operating logic.
- Treat human judgment as part of the system architecture.

## Background

My background spans operational finance, product architecture, automation, governance, and technical prototyping. That combination shapes how I build: controls should serve the work, evidence should survive scrutiny, and interfaces should help people make better decisions.

I am most interested in systems where software acts, humans judge, and the boundary between those responsibilities must remain clear.
