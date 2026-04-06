# Week 11: Difference-in-Differences Demo

Standalone teaching repository for **QM 2023 — Statistics II / Data Analytics**. Walks through DiD intuition, parallel trends, OLS estimation, and placebo checks using a monthly REIT panel around the 2008 crisis.

## Prerequisites

- Python 3.10+
- pip

## Install Dependencies

From this folder (`Week-11-Demo`):

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

## Run the Notebook

Open `difference_in_differences_demo.ipynb` in VS Code or Jupyter. Set the workspace folder to **Week-11-Demo** (so paths resolve correctly), then run all cells from top to bottom.

Optional PNG exports are written under `output/` when you run cells that save figures.

## Data

`data/reit_firm_panel.csv` is the same firm-month panel used in Assignment 11 (bundled here so this repo is self-contained).

## Main Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- statsmodels

## Publishing as a GitHub Template

Initialize or clone as its own repository, then push to GitHub. Students can clone or use "Use this template" without the full course monorepo.
