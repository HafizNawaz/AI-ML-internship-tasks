# 📑 AI/ML Internship - Task 1: Exploring and Visualizing a Simple Dataset

Welcome to my AI/ML internship repository! This repository contains the data exploration and visualization tasks completed during the internship program.

---

## Task Objective
The primary objective of this task is to perform **Exploratory Data Analysis (EDA)** and **Data Visualization** on a classic dataset. The goal is to understand data distribution, inspect its statistical properties, check for missing values, and uncover visual patterns or relationships between features across different classes.

## Dataset Used
* **Dataset Name:** Iris Dataset (loaded via Seaborn and saved as `iris.csv`).
* **Dataset Description:** It consists of 150 samples from three species of Iris flowers (*Iris setosa*, *Iris virginica*, and *Iris versicolor*). 
* **Features:** * `sepal_length` (Numerical)
  * `sepal_width` (Numerical)
  * `petal_length` (Numerical)
  * `petal_width` (Numerical)
  * `species` (Categorical - Target Variable)
* **Data Quality:** The dataset is clean and well-structured with **zero missing (null) values**.

## Workflow & Steps Applied

### 1. Environment Setup
The project utilizes the foundational Python libraries for Data Science and Machine Learning:
```bash
pip install pandas numpy seaborn matplotlib


2. Data Loading & Inspection
Loaded the dataset via Seaborn, exported it to a local CSV, and re-loaded it using Pandas (pd.read_csv).

Inspected rows and columns using df.shape (150 rows, 6 columns) and df.columns.

Checked first 5 rows (df.head()), data types (df.info()), and statistical summary (df.describe()).

3. Data Visualization
Applied three distinct statistical plots using Seaborn and Matplotlib:

Scatter Plot: Analyzed the correlation between sepal_length and sepal_width categorized by flower species.

Histogram (with KDE): Examined the distribution and density frequency of sepal_length.

Box Plot: Visualized the spread, median, and variance of sepal_length across the three distinct species to catch outliers and variance.

## Key Results and Findings:

Statistical Insights: The average sepal length across the entire dataset is approximately 5.84 cm, with values ranging from a minimum of 4.3 cm to a maximum of 7.9 cm.

Perfect Class Separation: The Scatter Plot and Box Plot clearly show that the Iris setosa species forms a completely distinct cluster, making it easily separable from versicolor and virginica based purely on sepal characteristics.

Feature Spread: Iris virginica displays the highest variance and maximum values for sepal length compared to the other two categories.
