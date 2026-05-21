# AI-ML-internship-tasks:

# Task 1: Exploring and Visualizing a Simple Dataset
1. Data Loading & Inspection:

 Loaded the dataset via Seaborn, exported it to a local CSV, and re-loaded it using Pandas (pd.read_csv).

Inspected rows and columns using df.shape (150 rows, 6 columns) and df.columns.

Checked first 5 rows (df.head()), data types (df.info()), and statistical summary (df.describe()).

2. Data Visualization:

Applied three distinct statistical plots using Seaborn and Matplotlib:

Scatter Plot: Analyzed the correlation between sepal_length and sepal_width categorized by flower species.

Histogram (with KDE): Examined the distribution and density frequency of sepal_length.

Box Plot: Visualized the spread, median, and variance of sepal_length across the three distinct species to catch outliers and variance.

# Key Results and Findings:

Statistical Insights: The average sepal length across the entire dataset is approximately 5.84 cm, with values ranging from a minimum of 4.3 cm to a maximum of 7.9 cm.

Perfect Class Separation: The Scatter Plot and Box Plot clearly show that the Iris setosa species forms a completely distinct cluster, making it easily separable from versicolor and virginica based purely on sepal characteristics.

Feature Spread: Iris virginica displays the highest variance and maximum values for sepal length compared to the other two categories.
