# AML Practice

This repository contains a collection of machine learning and data analysis notebooks and one Python script for practicing common supervised learning, recommender system, and time-series forecasting techniques.

## What’s in this repository

### Classification and regression
- `ada_class.ipynb` — AdaBoost classifier using the breast cancer dataset.
- `ada_reg.ipynb` — AdaBoost regressor using the diabetes dataset.
- `rf_class.ipynb` — Random Forest classifier using the breast cancer dataset.
- `rf_reg.ipynb` — Random Forest regressor using the California housing dataset.

### Recommender systems
- `Content_based_recomm.ipynb` — Content-based recommendation using TF-IDF and cosine similarity.
- `item_based.ipynb` — Item-based collaborative filtering example.
- `model_based_recomm.ipynb` — Model-based recommendation using Truncated SVD.
- `user_recomm_system.ipynb` — A scratch notebook with user recommender-system experiments.

### Time-series forecasting
- `Arima.ipynb` — ARIMA model for forecasting airline passenger data.

## Technologies used

The notebooks and scripts mainly use:
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- statsmodels
- Jupyter Notebook

## Setup

This project uses a virtual environment.

### Create and activate the virtual environment

On Windows PowerShell:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

### Install dependencies

If you are using the repository virtual environment, install the packages directly into it:

```powershell
.\venv\Scripts\python.exe -m pip install --upgrade pip
.\venv\Scripts\python.exe -m pip install jupyter pandas numpy scikit-learn matplotlib seaborn statsmodels
```

### Run the notebooks

```powershell
jupyter notebook
```

Then open the desired `.ipynb` file from the repository root.

## Notes

- Some notebooks are practice notebooks and may contain exploratory code rather than polished production-ready implementations.
- The repository is best used as a learning workspace for machine learning experiments.
