# HousingRegression - ML Ops Assignment

## GitHub Repository
👉 https://github.com/Mugil6/HousingRegression

## Project Description
This project implements a complete ML pipeline to predict Boston Housing Prices.

## Branches
- `main`: Final merged branch with README and workflow
- `reg`: Contains regression models (Linear, DecisionTree, RandomForest)
- `hyper`: Adds hyperparameter tuning using GridSearchCV

## ML Models Used
- Linear Regression
- Decision Tree
- Random Forest
- Ridge (with tuning)

## Metrics
- MSE (Mean Squared Error)
- R² (Coefficient of Determination)

## CI/CD
- GitHub Actions used to automate training and evaluation.
- Workflow file: `.github/workflows/ci.yml`

## How to Run
```bash
python regression.py  # for regression
python hyperparameter_tuning.py  # for tuning
