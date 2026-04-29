# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Environment

Python 3.14 virtual environment at `.venv/`. Activate before running anything:

```bash
source .venv/bin/activate
```

## Running Notebooks

```bash
jupyter lab         # launch JupyterLab
jupyter notebook    # classic notebook UI
```

## Project Layout

- `data/` — input datasets
- `models/` — saved model artifacts
- `sample.ipynb` — starter notebook template

## Stack

Data science and LLM experimentation playground. Key installed packages: JupyterLab, NumPy, Pandas, Matplotlib, Requests, BeautifulSoup, Arrow.

No build system, test runner, or linter is configured yet.