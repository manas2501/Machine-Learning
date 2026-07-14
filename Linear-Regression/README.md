# Linear Regression: Vehicle CO₂ Emissions

## Overview

This project uses simple linear regression to predict vehicle CO₂ emissions from two individual features:

- Engine size
- Combined fuel consumption

## Dataset

The notebook downloads the Fuel Consumption CO₂ dataset from IBM Skills Network when it runs. The data includes vehicle engine specifications, fuel-consumption measurements, and CO₂ emissions.

## Workflow

1. Load and explore the dataset.
2. Visualize relationships between vehicle features and emissions.
3. Split the data into training and test sets.
4. Train separate `LinearRegression` models.
5. Evaluate predictions using MAE, MSE, RMSE, and R².

## Tools

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Run locally

```powershell
py -m pip install -r requirements.txt
py -m jupyter notebook
```

Open `LR_Project.ipynb`, choose the Python kernel, and select **Run All**. An internet connection is needed on first run because the dataset is downloaded from its source.
