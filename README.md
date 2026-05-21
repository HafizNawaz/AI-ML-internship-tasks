# AI/ML Internship - Task 1: Dataset Exploration & Visualization

Welcome to my AI/ML internship repository! This project covers the foundational Exploratory Data Analysis (EDA) and visualization tasks.

---

## Task Objective
Perform **Exploratory Data Analysis (EDA)** and **Data Visualization** on the classic Iris dataset to analyze feature distributions, check statistical properties, and uncover patterns between flower species.

##  Dataset Overview
* **Name:** Iris Dataset (Loaded via Seaborn)
* **Size:** 150 rows, 5 columns (**Zero missing values**)
* **Features:** `sepal_length`, `sepal_width`, `petal_length`, `petal_width`
* **Target:** `species` (*Setosa*, *Virginica*, *Versicolor*)

---

## Workflow & Steps

### 1. Setup & Inspection
* **Libraries:** `pandas`, `numpy`, `seaborn`, `matplotlib`
* **Exploration:** Used `df.head()`, `df.info()`, and `df.describe()` for structural and statistical summaries.

### 2. Data Visualization
Applied three distinct statistical plots using Seaborn & Matplotlib:
* **Scatter Plot:** Analyzed the relationship between sepal length and width across different species.
* **Histogram (with KDE):** Examined the distribution and density frequency of `sepal_length`.
* **Box Plot:** Visualized the spread, median, and outliers of `sepal_length` across the three species.

---

## Key Findings
* **Statistical Insights:** The average sepal length is **5.84 cm** (ranging from 4.3 cm to 7.9 cm).
* **Clear Class Separation:** *Iris setosa* forms a completely distinct cluster, making it easily separable from the other two species based on sepal characteristics.
* **Feature Spread:** *Iris virginica* displays the highest variance and the maximum values for sepal length.
