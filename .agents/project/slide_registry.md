# Beamer Slide Registry

This registry tracks the organization of files inside `sections/`, their specific slide structure, and the completion status of the presentation narrative. Any AI agent or author editing slides should consult and update this registry.

---

## Presentation Outline & Narrative Flow

| File Path                                                                                            | Section / Slide Title     | Narrative Objective                                                               | Status     | Notes                                                  |
| :--------------------------------------------------------------------------------------------------- | :------------------------ | :-------------------------------------------------------------------------------- | :--------- | :----------------------------------------------------- |
| [main.tex](file:///c:/Users/Quirora/Documents/GitHub/slides/main.tex)                                | **Root Compiler Driver**  | Imports preambles, defines metadata, compiles slides in order                     | [Complete] | Driver only                                            |
| [01_introduction.tex](file:///c:/Users/Quirora/Documents/GitHub/slides/sections/01_introduction.tex) | **1. Structural Layouts** | Outline presentation roadmap, showcase local vs global column layouts             | [Complete] | Uses `columns` environment                             |
| [02_background.tex](file:///c:/Users/Quirora/Documents/GitHub/slides/sections/02_background.tex)     | **2. Data & Technicals**  | Formulate core mathematical models, show benchmarks/comparison tables             | [Complete] | Contains objective equations and `booktabs` comparison |
| [03_methodology.tex](file:///c:/Users/Quirora/Documents/GitHub/slides/sections/03_methodology.tex)   | **3. Implementation**     | Display code listings, requirements, and key framework classes                    | [Complete] | Requires `[fragile]` environment for `lstlisting`      |
| [04_evaluation.tex](file:///c:/Users/Quirora/Documents/GitHub/slides/sections/04_evaluation.tex)     | **4. Visualization**      | Present high-impact custom TikZ coordinate graphs (e.g. dimensions, architecture) | [Complete] | Imports coordinate visuals from `figures/tikz/`        |
| [05_conclusion.tex](file:///c:/Users/Quirora/Documents/GitHub/slides/sections/05_conclusion.tex)     | **5. Summary**            | Present summary of results, limitations, future work, and Q&A                     | [Draft]    | Simple placeholder frame                               |

---

## Progress Definitions

- **[Not Started]**: Empty file/placeholder.
- **[Draft]**: Contains general layout, bullet points, but needs polishing or final data.
- **[Complete]**: Highly polished, well-typeset, fits Beamer canvas bounds perfectly, and has clean TikZ/citations.
