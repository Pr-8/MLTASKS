# ML TASKS
## This repo contains two tasks made for the ML coding club
# Task 1
## Data Imputation and Feature Analysis Project

This project focuses on cleaning a dataset, imputing missing values, and identifying key features using exploratory data analysis (EDA) techniques. It leverages both simple statistical methods and machine learning tools such as KNN Imputer to handle missing data and assess feature relationships.

## Files
- `task1.ipynb`: The main Jupyter Notebook with the complete analysis.
- `datastud.csv`: Dataset used.
- `requirements_1.txt` : Requirement file

## Objectives
- Impute missing values in a dataset using multiple strategies.
- Analyze relationships between features to infer possible labels.
- Use encoding techniques compatible with distance-based algorithms like KNN.

## Methods Used
- Missing value imputation using:
  - Mode for categorical columns
  - Mean and KNN Imputer for numerical columns
- Encoding categorical variables using `pd.get_dummies`
- Exploratory Data Analysis (EDA):
  - Correlation heatmap
  - Pair plots
- Visualization tools: Matplotlib, Seaborn

## Observations
- Mean and KNN Imputer gave similar results due to a small proportion of missing data.
- One-hot encoding was avoided due to incompatibility with KNN distances.
- KNN turned out to be the best model for predictions. It gave an accuracy of around 72 percent.
## Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

## Author
- Pranav Prabhu Kumble

---

#Task 2

