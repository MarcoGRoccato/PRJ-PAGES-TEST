# Project Title

**Lead:** Your Name

## What lives here
- Code + notebooks (R/Python/Quarto)
- Drafts (manuscript, slides)
- Rendered outputs (results/*)

## What does NOT live here
- Raw / large / sensitive data → keep in `D:/RESEARCH_HUB/04_DATA/...` (or encrypted vault)
  and link into `data/` if needed.

## Run order
1. analysis/notebooks/01-import.qmd → import from 04_DATA/…
2. 02-clean.qmd → cleaning
3. 03-eda.qmd → exploration
4. 04-modeling.qmd → models
5. 05-figures.qmd → export to results/

## Quarto
- HTML pages under `docs/` (or `results/site/`)
- DOCX/PDF under `results/` or `D:/RESEARCH_HUB/06_DELIVERABLES/`
