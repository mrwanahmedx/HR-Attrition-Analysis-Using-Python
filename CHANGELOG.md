# Changelog

## 2026-09-26 — repository hygiene

- Moved the superseded original notebook filename under `archive/` without rewriting its contents; `hr_attrition_analysis.ipynb` remains the single maintained analysis entry point.


## 2026-09-26

- Reorganized the notebook into a recruiter-readable analytical flow.
- Removed stored execution outputs from the committed notebook.
- Fixed incorrect `plt.title` assignments that could overwrite Matplotlib's title function.
- Replaced causal-sounding conclusions with association-focused language.
- Added local/Kaggle dataset-path handling.
- Added `requirements.txt` and dataset setup instructions.

The analytical scope remains exploratory; no production attrition model or causal claim is introduced.
