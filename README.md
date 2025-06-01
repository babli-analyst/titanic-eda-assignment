# Titanic EDA Assignment

This repository contains the Exploratory Data Analysis (EDA) performed on the Titanic dataset as part of the Week 2 assignment.

## Objective

Perform a full EDA workflow on the Titanic dataset to explore survival patterns based on passenger features like class, gender, age, etc.

---

## Files Included

- `titanic_eda_assignment.ipynb` or `titanic_eda_assignment.py` – EDA code
- `Titanic.csv` – Dataset file
- `README.md` – Project overview

---

## Tasks Performed

- Loaded and cleaned the dataset using Pandas
- Handled missing values in `age`, `embarked`, `embark_town`
- Dropped unnecessary columns like `deck`
- Performed grouping and aggregation:
  - Survival rate by gender
  - Survival rate by class
  - Survival rate by both class and gender
- Created visualizations using Matplotlib, Seaborn, and Pandas:
  - Age distribution histogram
  - Barplots for survival rate
  - Correlation heatmap

---

## Visualizations

- Age distribution (histogram)
- Survival by class and gender (barplot)
- Correlation heatmap (Seaborn)

---

## Key Insights

- Women had the highest survival rate among all genders.
- First-class passengers had a significantly higher survival rate.
- Age distribution showed a large number of passengers in the 20–40 age group.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## How to Run

1. Clone this repository or download the files.
2. Open the `.ipynb` or `.py` file in Jupyter Notebook or any Python IDE.
3. Run all the cells to see analysis and visualizations.

---
