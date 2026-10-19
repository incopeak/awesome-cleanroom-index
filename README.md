# Awesome Clean-Room Implementations

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](#contributing)

> A curated list of software independently reimplemented from observable behaviour, public specifications, or documented interfaces—with an emphasis on projects you can explore, build, and use.

Clean-room work is a **method**, not just a project label. This list prioritizes repositories whose own documentation explicitly describes clean-room development or reverse engineering. Related projects and workflow tools are kept in separate sections so the list does not overstate their provenance. Each project entry puts **`Reimplements:` first** so you can immediately see the familiar product or interface it aims to replace; language, licence, and status follow.

## Contents

- [Applications](#applications)
- [Developer tools and interfaces](#developer-tools-and-interfaces)
- [Clean-room workflow tools](#clean-room-workflow-tools)
- [Status and licensing notes](#status-and-licensing-notes)
- [Contributing](#contributing)

## Applications

### Creative tools

- **[PhotoCraft](https://github.com/storytold/photocraft)** — An image editor with layers, masks, adjustment layers, brushes, and PSD support.  
  `Reimplements: Adobe Photoshop-style editor` · `Language: Rust` · `License: MIT OR Apache-2.0` · `Status: Active development; check the roadmap for feature parity`  
  **Start here:** [README and setup](https://github.com/storytold/photocraft#readme)

- **[VectorCraft](https://github.com/storytold/vectorcraft)** — A native vector-illustration application for desktop platforms and WebAssembly.  
  `Reimplements: Adobe Illustrator-style workflow` · `Language: Rust` · `License: MIT OR Apache-2.0` · `Status: Active development`  
  **Start here:** [README and setup](https://github.com/storytold/vectorcraft#readme)

- **[LightCraft](https://github.com/storytold/lightcraft)** — A non-destructive photo editor built from scratch, with an engine-first architecture.  
  `Reimplements: Lightroom-style photo-editing workflow` · `Language: Rust` · `License: MIT OR Apache-2.0` · `Status: Active development`  
  **Start here:** [README and setup](https://github.com/storytold/lightcraft#readme)

- **[FilmCraft](https://github.com/storytold/filmcraft)** — A video editor with timeline editing, titles, captions, colour tools, codecs, and export features.  
  `Reimplements: Adobe Premiere Pro-style video-editing workflow` · `Language: Rust` · `License: MIT OR Apache-2.0` · `Status: Early, active development; consult the roadmap for current parity`  
  **Start here:** [README and setup](https://github.com/storytold/filmcraft#readme)

### Developer applications

- **[Open Claude Code](https://github.com/ruvnet/open-claude-code)** — An independently rebuilt CLI coding-agent workflow.  
  `Reimplements: Claude Code-style coding agent CLI` · `Language: TypeScript` · `License: MIT` · `Status: Active repository; inspect the current README before use`  
  **Start here:** [Install and usage](https://github.com/ruvnet/open-claude-code#readme) · Requires an appropriate model API key for provider-backed use.

## Developer tools and interfaces

- **[vst2sdk](https://github.com/Xaymar/vst2sdk)** — A header-only reimplementation of the VST 2.x plugin interface SDK for C/C++ interoperability.  
  `Reimplements: Steinberg VST 2.x SDK interface` · `Language: C / C++` · `License: BSD-3-Clause` · `Status: Public repository; README describes ongoing work and remaining gaps`  
  **Start here:** [README, documentation, and build guidance](https://github.com/Xaymar/vst2sdk#readme)

## Clean-room workflow tools

These projects help teams *perform* clean-room reimplementation. They are useful companions, but are not themselves replacement implementations of the target software.

- **[agentic-cleanroom](https://github.com/climashscape/agentic-cleanroom)** — A playbook and toolkit for specification-driven reimplementation, test oracles, parity tracking, and repeatable verification. Includes a small example project.  
  `Language: Python tooling` · `License: Apache-2.0` · `Status: Pre-publication / early-stage according to its README`  
  **Start here:** [Quick start](https://github.com/climashscape/agentic-cleanroom#quick-start)

- **[clean-room-coding](https://github.com/khhvmc5g6f-eng/clean-room-coding)** — A provenance- and licence-aware workflow with separated reference, handoff, and implementation zones, plus audit and similarity tooling.  
  `Language: Python` · `License: BUSL-1.1 (source-available; not OSI-approved)` · `Status: Pre-1.0`  
  **Start here:** [Installation and CLI quick start](https://github.com/khhvmc5g6f-eng/clean-room-coding#quick-start)

- **[dlfelps/cleanroom](https://github.com/dlfelps/cleanroom)** — A multi-agent pipeline designed to keep reference analysis separate from implementation and record the process.  
  `Language: Python` · `License: No repository-level LICENSE file found; terms unclear` · `Status: Public project; verify current maturity before relying on it`  
  **Start here:** [Repository and requirements](https://github.com/dlfelps/cleanroom)

## Status and licensing notes

- **Status is a snapshot, not a guarantee.** Projects evolve quickly; use each repository's releases, roadmap, issues, and recent commits for current information.
- **License means the repository's stated project license.** Bundled assets, dependencies, trademarks, and individual files may have separate terms. Check the linked license and notices before redistribution or commercial use.
- **Clean-room claims are not legal conclusions.** This list records what project documentation says; it does not certify the development process, legal compliance, compatibility, or freedom from third-party rights.
- **Not every reimplementation is clean-room.** A compatible replacement may reuse code, adapt existing code, or have unclear provenance. Such projects should not be presented as clean-room without evidence.
- **No endorsement or affiliation is implied.** Product names are used only to describe compatibility or intended workflows.

## Contributing

Contributions are welcome. Please open a pull request with:

1. **Project name and repository URL.**
2. **What it reimplements** and a short, factual description.
3. **Evidence of clean-room methodology** — ideally a project policy, development notes, or documentation explaining the use of public specifications or observable behaviour.
4. **Language, licence, and status**, each linked to the project's own documentation where possible.
5. **Getting-started link** — prefer the official README, quick-start, or installation page.

Please do not submit projects solely because they contain `clean-room` in a name or topic tag. If the methodology is unclear, suggest the project under a clearly labelled “related reimplementations” section instead.

---

**Have a suggestion?** Open an issue or pull request with the evidence above.
