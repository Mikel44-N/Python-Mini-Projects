# Housing EDA and Machine Learning

## Overview
This project explores a housing dataset and trains a baseline linear regression model to predict `MEDV`.

## Exploratory Data Analysis
- Inspect data types, missing values, and descriptive statistics.
- Explore the distribution and potential outliers of housing values.
- Examine correlations between numeric variables.
- Visualize relationships between housing value and selected features, including `RM` and `LSTAT`.
- Compare average housing values across `CHAS` groups.

## Machine Learning
- Define `MEDV` as the target and use the remaining columns as features.
- Split the data into training and test sets (80/20, with `random_state=42`).
- Train a scikit-learn `LinearRegression` model.
- Evaluate predictions using MAE, MSE, RMSE, and R².
- Plot actual versus predicted housing values.

## Tools
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- Jupyter Notebook

## Requirements
Install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Place `Housing.csv` in the same directory as the notebook.
2. Open `Housing_EDA_and_Machine_Learning.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells from top to bottom.

The dataset must contain the target column `MEDV`, along with the numeric feature columns referenced in the notebook (`RM`, `LSTAT`, and `CHAS`).

## Notes
This project demonstrates exploratory analysis and a baseline regression workflow. Model metrics depend on the supplied dataset and split; correlation should not be interpreted as causation.
