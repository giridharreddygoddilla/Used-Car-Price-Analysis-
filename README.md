# 🚗 Used Car Price Analysis

### Data-Driven Insights into Used Car Prices, Vehicle Age, Mileage, and Clustering

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikitlearn)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)

## 📌 Project Overview

This project explores a used-car dataset using Python to investigate the relationships between vehicle age, kilometres driven, asking price, fuel type, and brand. It combines exploratory data analysis, statistical measures, data visualisation, K-Means clustering, and linear regression to examine used-car market patterns.

## 🎯 Key Objectives

- 🧹 Clean and preprocess mileage and asking-price data.
- 🚘 Identify the top 10 car brands by listing count.
- 📊 Explore the relationship between vehicle age and asking price.
- ⛽ Compare asking-price distributions across fuel types.
- 🔍 Use the Elbow Method to investigate suitable K-Means cluster counts based on vehicle age and mileage.
- 📈 Fit a linear regression model to examine the relationship between vehicle age and asking price.
- 📉 Calculate the skewness and kurtosis of asking prices.

## 🛠️ Technologies Used

- **Python** — Data analysis and modelling
- **Pandas & NumPy** — Data manipulation
- **Matplotlib & Seaborn** — Visualisation
- **Scikit-learn** — K-Means clustering and linear regression
- **SciPy** — Statistical analysis
- **Jupyter Notebook** — Interactive development

## 📊 Key Analyses

The notebook includes brand-count bar charts, age-versus-price scatter plots, fuel-type boxplots, mileage-category violin plots, a K-Means Elbow plot, and a linear regression fitted line.

## 🚀 Getting Started

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
```

Place `used_car_dataset.csv` in your project directory, update the file path in the notebook, and run `Clustering and Fitting _ Assignment - 2.ipynb` in Jupyter Notebook.

## 💡 Project Outcome

This project demonstrates how data analysis and machine learning techniques can be applied to used-car listings to explore pricing patterns, vehicle characteristics, and potential customer or vehicle segments.

**Note:** The notebook fits a linear regression model and explores clustering, but does not evaluate predictive accuracy on a separate test set or establish an optimal cluster count automatically. The clustering features are also not scaled before fitting K-Means.
