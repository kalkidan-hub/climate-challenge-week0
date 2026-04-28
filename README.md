Climate Challenge Week 0

This repository contains the Week 0 climate analysis starter work for five countries: Ethiopia, Kenya, Nigeria, Sudan, and Tanzania. The raw and cleaned CSV files live in `data/`, and the exploratory notebooks for each country live in `notebooks/`.

What is in the repo

- `data/`: country climate datasets and the data legend
- `notebooks/`: EDA notebooks for Ethiopia, Kenya, Nigeria, Sudan, and Tanzania
- `src/`: Python package scaffold for reusable code
- `scripts/`: helper scripts for running tasks
- `tests/`: automated test scaffold

Data source

The datasets come from NASA POWER MERRA-2 reanalysis data. The included country files cover daily observations from 2015-01-01 through 2026-03-31 using representative capital-city coordinates.

Environment setup

1. Create a virtual environment.

```bash
python -m venv .venv
```

2. Activate it.

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Windows Command Prompt:

```bat
.venv\Scripts\activate.bat
```

macOS/Linux:

```bash
source .venv/bin/activate
```

If PowerShell blocks activation, run this once and then reactivate:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

Install dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

Working with the notebooks

Open the notebooks in Jupyter or VS Code and run them country by country:

- `notebooks/ethiopia_eda.ipynb`
- `notebooks/kenya_eda.ipynb`
- `notebooks/nigeria_eda.ipynb`
- `notebooks/sudan_eda.ipynb`
- `notebooks/tanzania_eda.ipynb`

Python packages used in this repo include `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scipy`, `statsmodels`, `scikit-learn`, `jupyter`, `ipykernel`, `openpyxl`, and `xlrd`.

Running tests

```bash
python -m pytest
```

Notes

- The repository is organized for exploratory analysis first, with `src/` and `scripts/` available for any reusable code or automation you add later.
- The data legend in `data/Data Legend.txt` describes the source, variables, and missing-value convention used in the CSV files.
