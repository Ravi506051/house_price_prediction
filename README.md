# House Price Prediction

A machine-learning project exploring how property attributes can be used to estimate house prices. The repository provides a practical workflow for preparing structured data, training regression models and reviewing prediction errors.

## Workflow
- Inspect property features, target values and missing data.
- Prepare numerical and categorical variables.
- Establish a simple baseline.
- Train and compare suitable regression models.
- Evaluate predictions on held-out data.
- Review residuals and feature contributions.

## Technology
Python · Pandas · NumPy · Scikit-learn · Data Visualization

## Getting started
```bash
git clone https://github.com/Ravi506051/house_price_prediction.git
cd house_price_prediction
python -m venv .venv
# Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
```
Open the notebook or run the project entry point available in the repository. If there is no requirements file, install the libraries imported by the project.

## Model validation
Document the dataset date, location coverage, currency and feature units. Compare models with a median-price baseline and report actual MAE, RMSE and R-squared results. Fit imputation, encoding and scaling using training data only.

## Limitations
Predictions are estimates, not formal property valuations. Market conditions, location coverage and data quality can materially affect results.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

## Reproduce the notebooks

This repository contains two notebooks: `house_price_prediction.ipynb` and `house_price_prediction (1).ipynb`. Create a Python environment, install the libraries imported by the notebook, then open it with Jupyter:

```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install jupyter
jupyter notebook
```

Run cells from top to bottom and check any dataset path referenced in the notebook before training. The repository does not include a `requirements.txt`, so the notebook's imports are the source of truth for additional packages.
