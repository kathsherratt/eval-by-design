# eval-by-design

Forecast evaluation as study design.

Evaluating forecasts means choosing a design, whether or not the evaluator states it.
Who chose which models forecast which targets (the evaluator, or the forecasters) decides whether an evaluation is experimental or observational.
The aim (describe, compare, explain) decides how much of that design has to be made explicit.
This repository collects notes, sketches and outputs that develop this idea.

Companion to [eval-by-method](https://github.com/epiforecasts/eval-by-method), which applies part of the framework to the European COVID-19 Forecast Hub.

## Layout

| Directory | Contents |
|---|---|
| `sources/` | Original notes and sketches, copied unedited. Read-only reference |
| `concepts/` | One note per idea: key question, claims and evidence, tools, sources |
| `map.qmd` | Concept by output matrix |
| `sim/` | Shared simulator of forecasts, targets and target choice |
| `outputs/` | One directory per planned output |

## Outputs

| Output | Status | Venue |
|---|---|---|
| Theory paper: designs for comparative evaluation | Sketch (`sources/evaluation-design-sketch.qmd`) | TBC: IJF, epidemiology methods journal |
| Workflow paper: rules for forecast evaluation | Notes (`sources/workflows_10-simple-rules.md`) | TBC: possibly PLOS Comput Biol Quick Tips |
| scoringutils vignette: evaluation workflow | Plan (`sources/workflows_evaluation-vignette-plan.md`) | scoringutils pkgdown site |
| Course on forecast evaluation | Idea | TBC |

## Sources

| File | Origin |
|---|---|
| `evaluation-design-sketch.qmd` | eval-by-method `attic/`, issue [#174](https://github.com/epiforecasts/eval-by-method/issues/174) |
| `workflows_10-simple-rules.md` | Google Doc "10 Simple rules for forecast evaluation" (co-authored), exported to eval-by-method `attic/` |
| `workflows_evaluation-vignette-plan.md` | Claude session, 2026-09-30, then eval-by-method `attic/` |
| `ranking-literature-scoping.qmd`, `ranking-literature.bib` | eval-by-method `attic/` |
| `model-building.qmd` | eval-by-method `attic/`, early cohort framing |
| `dag-reasoning-sketch.qmd` | eval-by-method branch `paper/dag-reasoning`, `report/quarto/supplement/` |

Linked but not copied: eval-by-method `attic/regime-standardised-scores.qmd` (depends on that repository's data) and `attic/future-work.qmd` (Hub-specific extensions).

## Licence

Text: CC BY 4.0. Code: MIT. See `LICENSE.md`.
