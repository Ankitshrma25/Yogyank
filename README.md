Yogyank EDA Notebook
=====================

Project Overview
----------------
This repository contains an exploratory data analysis (EDA) notebook for the Yogyank farmer scoring dataset. The notebook inspects, cleans, and visualizes the data to support modeling and evaluation.

Included Files
--------------
- Notebook/EDA.ipynb — main EDA notebook
- Data/farmer_scoring_sample_yogyank_round1.csv — sample dataset used in the notebook
- broken_yogyank_training.py — legacy/training script (keep for reference)
- requirements.txt — Python dependencies

How to run
----------
1. Create and activate a Python environment (recommended).

```bash
python -m venv venv
venv\Scripts\activate    # Windows
pip install -r requirements.txt
```

2. Open and run the notebook `Notebook/EDA.ipynb` in Jupyter or VS Code.

What this notebook does
----------------------
- Loads the sample farmer scoring dataset.
- Performs exploratory analysis and basic data quality checks.
- Builds a simple preprocessing pipeline to prepare features for modeling.
- Exports cleaned data or transformed features for downstream training.

AI Helper
---------
I help AI to first undertand what assement fast and creating preprocessing pineline preprocessor

Notes & Next Steps
------------------
- Review the notebook cells for assumptions about missing values and feature types.
- If you plan to train models, use the preprocessing pipeline outputs as input to training scripts.

Contact
-------
If you need help or changes to the notebook, update the notebook or open an issue.
