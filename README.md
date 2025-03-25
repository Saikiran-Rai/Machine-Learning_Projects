# Village Infrastructure Prediction

This repository contains Jupyter notebooks and datasets for predicting village infrastructure using machine learning models.

## Project Overview
The goal of this project is to analyze village infrastructure data and build predictive models using logistic regression and random forest classifiers.

## Repository Structure

- `dataset_creation.ipynb` - Processes raw data and performs feature engineering.
- `lr_trained_model.ipynb` - Implements and evaluates a Logistic Regression model.
- `rf_trained_model.ipynb` - Implements and evaluates a Random Forest model.
- `main.ipynb` - Integrates dataset creation and model execution.
- `Village_infras.csv` - Contains village infrastructure data with 13 columns and 20000 rows.

## Requirements
To run the notebooks, install the following dependencies:

```sh
pip install pandas scikit-learn numpy matplotlib seaborn
```

## Usage
1. Run `dataset_creation.ipynb` to preprocess the data.
2. Execute `lr_trained_model.ipynb` or `rf_trained_model.ipynb` to train and evaluate models.
3. Use `main.ipynb` to integrate the entire workflow.

## Results
- The logistic regression model provides a baseline performance.
- The random forest classifier improves predictive accuracy.
