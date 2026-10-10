# ⌘ Hierarchy

### Understand your codebase as a system, not just a collection of files.

**Hierarchy** is a concept for a local-first developer tool designed to make software architecture easier to explore, understand, and reason about.

By combining static analysis with interactive visualization, Hierarchy aims to reveal the relationships hidden within a codebase—from high-level architecture to individual dependencies—and help developers understand the potential consequences of change.

<p align="center">
  <em>See the structure. Trace the connections. Understand the system.</em>
</p>

---

> [!NOTE]
> **Early concept — not yet implemented.**
>
> Hierarchy is currently in the exploration stage. Its features, architecture, and implementation details are still being developed.

## ◈ Contents

- [Vision](#-vision)
- [Planned Capabilities](#-planned-capabilities)
- [Design Principles](#-design-principles)
- [Technical Direction](#-technical-direction)
- [Scope](#-scope)
- [Project Status](#-project-status)
- [License](#-license)

---

## ◈ Vision

Understanding an unfamiliar codebase often means jumping between files, following imports, tracing dependencies, and mentally reconstructing how its components fit together.

That understanding is valuable—but it shouldn't have to live entirely in a developer's head.

Hierarchy aims to transform a codebase into an **interactive structural model**, allowing developers to move between the big picture and the details, investigate relationships, and discover architectural problems that are difficult to recognize from individual files alone.

The goal isn't simply to visualize code. It's to make the structure and complexity of software easier to understand.

## ◈ Planned Capabilities

| Capability | Direction |
|:--|:--|
| **Architecture exploration** | Navigate a codebase through progressively deeper levels of detail. |
| **Dependency tracing** | Explore incoming and outgoing relationships between components. |
| **Change-impact analysis** | Investigate which components may be affected by a proposed change. |
| **Architectural diagnostics** | Surface potential circular dependencies, excessive coupling, and structural issues. |
| **Source-level context** | Connect architectural insights to the code and relationships that support them. |

*These capabilities represent the current vision, not implemented functionality. Priorities and scope may change as development progresses.*

## ◈ Design Principles

Hierarchy is intended to be shaped by a few core principles.

**01 — Clarity over clutter**

Complexity should be revealed progressively. An architectural overview should remain understandable without sacrificing access to deeper detail.

**02 — Evidence over guesswork**

Insights should be grounded in source code and traceable relationships, rather than presented as unexplained conclusions.

**03 — Honest analysis**

Observed facts, derived conclusions, heuristic warnings, and unknowns should be distinguished clearly. The tool should communicate the limits of static analysis.

**04 — Form and function**

Visualization is part of the product's reasoning process, not decoration. Navigation, spatial organization, interaction, and visual hierarchy should make analysis more intuitive.

**05 — Local-first by design**

The intended experience centers on analyzing codebases locally, without requiring a hosted service to perform core analysis.

## ◈ Technical Direction

The initial direction is to build around Python and gradually develop the analysis engine before expanding into the full application.

| Layer | Initial direction |
|:--|:--|
| **Source analysis** | Python's built-in `ast` module |
| **Structural model** | Explicit representations of code entities and relationships |
| **Analysis** | Dependency traversal, graph algorithms, and architectural checks |
| **Interface** | A modern, interactive frontend |
| **Distribution** | Potential desktop application |

These are exploratory choices, not finalized architectural commitments. Implementation details will be determined as the project develops.

## ◈ Scope

Hierarchy will initially focus on **Python codebases**.

Supporting multiple programming languages introduces additional parsing, name-resolution, and analysis challenges. Rather than pursuing broad language support immediately, the initial goal is to establish a reliable foundation for one language.

Additional languages may be considered as the analysis model and user experience mature.

## ◈ Project Status

<details>
<summary><strong>Current stage: Exploration and foundations</strong></summary>

The repository currently serves as the starting point for the project.

Planned early milestones:

- [ ] Establish the foundational Python skills and analysis concepts.
- [ ] Prototype repository scanning and source-code inspection.
- [ ] Extract structural information from Python projects.
- [ ] Build a dependency model and validate its accuracy.
- [ ] Explore interactive architecture visualization.
- [ ] Develop toward a usable local application.

These milestones are preliminary and may evolve as the project takes shape.

</details>

There is currently no release, installation process, or production-ready functionality.

## ◈ License

No license has been selected yet. Licensing will be determined as the project moves toward implementation.

---

<p align="center">
  <strong>Hierarchy</strong>
  <br />
  <sub>A clearer view of software architecture.</sub>
</p>
