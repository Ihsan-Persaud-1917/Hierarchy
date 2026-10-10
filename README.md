# <span style="color:#8B7CFF">◈</span> Hierarchy

<p align="center">
  <img src="https://placehold.co/1200x320/101020/8B7CFF?text=H+I+E+R+A+R+C+H+Y&font=montserrat" alt="Hierarchy — Understand the structure behind the code" width="100%" />
</p>

<p align="center">
  <strong>Understand your codebase as a system, not just a collection of files.</strong>
  <br />
  <br />
  <img src="https://img.shields.io/badge/STATUS-CONCEPT%20STAGE-8B7CFF?style=for-the-badge" alt="Concept stage" />
  <img src="https://img.shields.io/badge/APPROACH-LOCAL--FIRST-22D3EE?style=for-the-badge" alt="Local first approach" />
  <img src="https://img.shields.io/badge/INITIAL%20LANGUAGE-PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python first" />
</p>

<p align="center">
  <em>See the structure. Trace the connections. Understand the system.</em>
</p>

---

> [!IMPORTANT]
> **Hierarchy is an early-stage concept.** No implementation or production-ready functionality exists yet. The features and technical direction described here are planned ideas, not current capabilities.

## <span style="color:#8B7CFF">✳</span> The Vision

Software is more than the sum of its files.

Behind every codebase lies a network of components, dependencies, abstractions, and relationships. Understanding that structure often means jumping between files and mentally reconstructing how everything fits together.

**Hierarchy aims to make that invisible structure explorable.**

By combining static analysis with interactive visualization, the goal is to help developers move from the big picture to individual implementation details, trace dependencies, and investigate how changes may affect an entire system.

Not another file browser.

**A different way to understand code.**

## <span style="color:#22D3EE">⌘</span> What Hierarchy Could Become

<table>
  <tr>
    <td width="50%">
      <h3>◈ Architecture Explorer</h3>
      Navigate a codebase through layers of abstraction, from high-level modules to individual classes and functions.
    </td>
    <td width="50%">
      <h3>⤳ Dependency Tracing</h3>
      Follow incoming and outgoing dependencies to understand how components connect and where relationships lead.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>⌁ Change Impact</h3>
      Investigate which components may be affected by a proposed change, with traceable evidence behind the results.
    </td>
    <td width="50%">
      <h3>✳ Architectural Insights</h3>
      Surface potential circular dependencies, excessive coupling, and other structural problems.
    </td>
  </tr>
</table>

<sub>All capabilities above are aspirational and subject to change.</sub>

## <span style="color:#A78BFA">◉</span> Design Philosophy

Hierarchy should be as considered in its presentation as it is in its analysis.

| Principle | What it means |
|:--|:--|
| <span style="color:#8B7CFF">**Clarity**</span> | Reveal complexity progressively without overwhelming the developer. |
| <span style="color:#22D3EE">**Evidence**</span> | Ground insights in source code and explainable relationships. |
| <span style="color:#34D399">**Honesty**</span> | Distinguish observed facts from derived conclusions and heuristic warnings. |
| <span style="color:#FBBF24">**Intentional design**</span> | Make visualization and interaction useful to the developer's reasoning process. |
| <span style="color:#F472B6">**Local-first**</span> | Center the experience on local code analysis, without requiring a hosted service for core functionality. |

## <span style="color:#FBBF24">⌘</span> Technical Direction

The initial plan is to begin with Python and establish a reliable analysis engine before building the full application.

```text
          SOURCE CODE
               │
               ▼
       ┌────────────────┐
       │  Python Parser │
       └────────┬───────┘
                ▼
       ┌────────────────┐
       │ Structural Model│
       └────────┬───────┘
                ▼
       ┌────────────────┐
       │ Graph Analysis │
       └────────┬───────┘
                ▼
       ┌────────────────┐
       │ Interactive UI │
       └────────────────┘
```

<sub>Conceptual flow only — implementation details remain undecided.</sub>

Potential foundations include Python's built-in `ast` module, graph algorithms, and a modern interactive frontend. A desktop application may follow once the analysis engine and interface have matured.

## <span style="color:#34D399">◎</span> The Road Ahead

<details>
<summary><strong>Phase 01 — Foundations</strong></summary>

- [ ] Develop the initial Python analysis prototype.
- [ ] Scan repositories and extract structural information.
- [ ] Model modules and dependency relationships.
- [ ] Validate results against test projects.

</details>

<details>
<summary><strong>Phase 02 — Exploration</strong></summary>

- [ ] Build an interactive architecture view.
- [ ] Support dependency tracing and contextual inspection.
- [ ] Explore useful navigation and visualization patterns.

</details>

<details>
<summary><strong>Phase 03 — Intelligence</strong></summary>

- [ ] Investigate change-impact analysis.
- [ ] Explore architectural diagnostics.
- [ ] Improve analysis accuracy, performance, and explainability.

</details>

<details>
<summary><strong>Phase 04 — Product</strong></summary>

- [ ] Develop a cohesive local application.
- [ ] Evaluate desktop packaging and distribution.
- [ ] Assess future language support.

</details>

<sub>These are exploratory milestones, not delivery commitments.</sub>

## <span style="color:#F472B6">◇</span> Scope & Licensing

**Starting language:** Python

**Intended approach:** Local-first

**License:** Undecided

The initial focus will be one language rather than attempting to support every ecosystem from the beginning. Additional languages and the eventual licensing model will be considered as the project takes shape.

---

<p align="center">
  <br />
  <strong><span style="color:#8B7CFF">HIERARCHY</span></strong>
  <br />
  <em>Structure, revealed.</em>
  <br />
  <br />
  <sub>A project at the beginning of its journey.</sub>
</p>
