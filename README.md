# Python Projects Workspace

This repository contains a collection of Python exercises, assessments, Jupyter notebooks, and small scripts organized for learning, practice, and lightweight data analysis.

## Repository Overview

- `Assessments/` — Graded exercises and assessment notebooks. Includes supporting scripts such as `student_data_organizer.py` and a `sales-assessment/` subfolder with related data files.
- `Days/` — Daily learning notebooks and short scripts covering Python fundamentals, file I/O, data structures, and small examples.
- `Lab_work/` — Hands-on lab notebooks used for in-class practice.

## Key Files

- `Assessments/sales-assessment/assessmentpro.ipynb`: Sales data analysis exercises (reading CSVs, computing revenue, exporting filtered data).
- `Assessments/student_data_organizer.py`: Example script for organizing student data.

## Prerequisites

- Python 3.8 or newer
- Jupyter (for running notebooks)
- Recommended: use a virtual environment (venv, conda)

## Quick Setup

1. Create a virtual environment and activate it (PowerShell):

```powershell
python -m venv .venv
& .venv\Scripts\Activate.ps1
```

2. (Optional) Install project-wide dependencies if provided:

```powershell
pip install -r requirements.txt
```

Note: This workspace may not include a global `requirements.txt`. Install packages as needed per notebook (common packages: `pandas`, `numpy`, `matplotlib`).

## Running Notebooks

- Open the workspace in VS Code and use the Jupyter extension, or run:

```powershell
jupyter notebook
```

- Then open any notebook under `Assessments/`, `Days/`, or `Lab_work/` and run cells interactively.

## Running Scripts

- From the workspace root (after activating the venv):

```powershell
python Days/day1.py
python Assessments/student_data_organizer.py
```

Adjust paths if running from a different working directory.

## Data Files and Paths

- Example data CSVs are located under `Assessments/sales-assessment/` (e.g., `sales_data.csv`, `electronics_order.csv`). Notebooks expect relative paths; ensure your working directory is the notebook's folder or adjust file paths accordingly.

## Recommended Improvements

- Add a `requirements.txt` listing used packages and versions for reproducibility.
- Add short README snippets inside `Assessments/` and `Days/` describing each notebook's purpose.
- Add a `LICENSE` if you plan to share the repository publicly.

## Contributing

This workspace is educational. To contribute:

1. Create a branch or copy the repository.
2. Add or update notebooks and scripts in the appropriate folder.
3. Update or add `requirements.txt` when introducing new dependencies.

## Contact

If you'd like me to:
- generate a `requirements.txt` from imports,
- add short descriptions for each notebook, or
- add simple run scripts (`run.ps1` / `run.sh`),

tell me which you'd prefer and I'll implement it.
