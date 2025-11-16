# Iris Data Analysis 🌸
**Exploring flower data with visualizations and a simple machine learning model**

## Project Overview

This project explores the Iris dataset, a classic dataset in machine learning. It includes:

- **Data Exploration**: Histograms, boxplots and pairplots to understand feature distributions.
- **Feature Relationships**: Scatterplots and heatmaps.
- **Machine Learning**: A simple **Logistic Regression** model to classify iris species.

## Files

- `iris_analysis.ipynb` – Jupyter notebook containing all code, visualizations, and model training.

## How to Run

1. Clone or download the repository.
2. Open the notebook in **Jupyter Notebook** or **VS Code**.
3. Run each cell sequentially to reproduce the analysis and plots.

## Insights from Visualizations

### 1. Histogram – Distribution of Numerical Features
- Most features (sepal length, sepal width, petal length, petal width) show roughly **normal or slightly skewed distributions**.
- `Petal length` and `petal width` vary more across species, suggesting they are **more useful for distinguishing species**.
- Histograms help identify **ranges, common values, and potential outliers** in the data.

### 2. Boxplot – Sepal Length by Species
- **Setosa** has a **smaller sepal length** than Versicolor and Virginica.
- There is **little overlap** between Setosa and the other two species, making it easier to separate.
- **Outliers** are visible, helping to understand unusual measurements.
- Boxplots summarize **median, quartiles, and spread** for each species.

### 3. Pairplot – Scatterplots + Histograms for All Features
- Petal length and petal width show **clear separation between species**, especially Setosa vs others.
- Sepal measurements overlap more, so they are **less discriminative**.
- Pairplots make it easy to see **relationships between two features** and detect clusters or correlations.

### 4. Heatmap – Correlation Between Features
- Petal length and petal width are **highly positively correlated**.
- Sepal length and sepal width have **low correlation**, indicating they vary independently.
- Correlation analysis helps **understand which features might be redundant** or highly related for model training.

### 5. Scatter Plot – Petal Length vs Petal Width
- There is **distinct clustering by species**, especially Setosa, which is well-separated from the other two species.
- Petal length and width are **strong predictors for classification**.
- Scatter plots clearly show **linear or non-linear separation patterns** between species.

### Overall Observation
- **Petal measurements** (length and width) are the most important features for distinguishing iris species.
- **Sepal measurements** provide some information but overlap significantly.
- Visualizations confirm that the dataset is **well-suited for classification models**.
