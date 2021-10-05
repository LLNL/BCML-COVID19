# Budget Constrained Machine Learning for Early Prediction of Adverse Outcomes for COVID-19 Patients
- Paper: https://www.researchsquare.com/article/rs-593801/v1

## Structure:
- scripts/: scripts to run training routines
- main.py: main training script
- plot.py: plotting utilities
- preprocess.py: preprocessing utilities (data imputation, data normalization, etc.)
- train_all.py: train all models (XGBoost, Gaussian Process, and Logistic Classifier)
- train_budget.py: train budget models
- utils.py: handy utilities

## How to train models:
- Put your own data in the appropriate location
- Run the script: scripts/run_script.sh
