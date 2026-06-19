# fedmaq-presentations

Modular LaTeX Beamer repository (Moloch theme) for FedMAQ thesis and progress updates.

## Structure

```text
.cursor/              # rules, project metadata, slide_registry
preamble/             # packages, macros
sections/             # defense deck modules
figures/tikz/         # standalone TikZ
updates/              # milestone progress decks
main.tex
```

## Compile

```bash
latexmk -pdf main.tex
```

VS Code: LaTeX Workshop with TeX Live.

## Agent onboarding

1. Read [../fedmaq-experiments/HANDOFF.md](../fedmaq-experiments/HANDOFF.md).
2. Read [AGENTS.md](AGENTS.md). Domain rules: `../fedmaq-experiments/.cursor/rules/`.

Legacy `.agents/` migrated to `.cursor/`.
