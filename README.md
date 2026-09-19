# Titanic Data Science Project

An exploratory data analysis and preprocessing project using the classic Titanic dataset. This notebook walks through cleaning, transforming, and analyzing passenger data to understand survival patterns.

## Contents

- `intro_project.ipynb` — Main analysis notebook
- `train.csv` — Titanic passenger dataset

## What's covered

- Data Inspection: Checking shape, data types, and missing values
- Missing Value Handling: Filling missing `Age` values by grouping on `Pclass` and `Sex`; filling `Embarked` and `Fare` with mode/median
- Encoding: Converting categorical columns (`Sex`, `Embarked`) into numeric values
- Feature Engineering: Extracting passenger titles from names, creating `FamilySize` and `IsAlone` features
- Correlation Analysis: Heatmap of feature relationships with `Survived`
- Linear Regression: Modeling `Fare` based on `Pclass`
- Outlier Detection: Comparing IQR and Z-score methods on `Fare`, with log transformation to reduce skew

## Tools used

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn, scipy)

## How to run

1. Clone this repo
2. Open `intro_project.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab
3. Make sure `train.csv` is in the same directory (or upload it if using Colab)
4. Run all cells
