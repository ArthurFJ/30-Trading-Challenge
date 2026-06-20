# 30-Trading-Challenge

Overview
--------

This repository contains a 30-day hands-on challenge focused on trading systems, strategy research, and applied market analysis. Each day is a small project that demonstrates a concept, builds intuition, and provides reproducible code and data.

Objectives
---------

- Build practical trading skills through daily projects.
- Learn data handling, feature engineering, backtesting, and model evaluation.
- Create a reusable set of templates, scripts, and notebooks for future research.

Audience
-------

This repo is aimed at students and practitioners with basic Python and finance knowledge who want a structured 30-day progression.

Structure & Flow
---------------

Top-level layout:

```
30-Trading-Challenge/
| README.md
| .gitignore
| requirements.txt
| Templates/
|  |- Notebooks/
|  |- References/
| Days/
|  |- DAY-01/
|  |-- README.md
|  |-- Notebook.ipynb
|  |-- Docs/References.json
|  |-- Data/raw/
|  |-- Data/processed/
|  |-- Script/
|  |-- Output/
|  |-- Miscellaneous/
```

How to use
---------

1. Create and activate a Python virtual environment.
2. Install dependencies: `pip install -r requirements.txt`.
3. Open the notebook for a day and run step-by-step.

Rules & Conventions
------------------

- Keep raw data in `Days/DAY-NN/Data/raw/` and processed artifacts in `Data/processed/`.
- Notebooks should be runnable from top to bottom.
- Add references and licenses in `Docs/`.

Contributions
------------

Open pull requests with proposed Day folders, data provenance, and clear licensing for shared datasets.
