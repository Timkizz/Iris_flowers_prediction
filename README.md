# Iris Flower Classification - Data Preprocessing and Exploratory Data Analysis (EDA)

## Project Overview
This project is my week 2 assignment in AnalystLabAfrica as a Machine Learning Intern. The main goal is to prepare the iris dataset for modeling by cleaning, transforming, and understanding the underlying patterns.

## Project Objective
To prepare the dataset for machine learning by:
* Cleaning and transforming raw data.
* Understanding feature distributions.
* Identifying relationships between variables.

## Dataset Information
* **Number of Entries:** 150 Entries (rows)
* **Data columns:** Total of 6 columns
* **Missing Values:** 0 Missing values
* **Data types:** `float64`(4), `int64`(1), `str`(1)
* **Memory usage:** 7.4 KB

## Steps Taken
* [x] Load Dataset
* [x] Data Assessment
* [x] Exploratory Data Analysis (EDA)
  * [x] Understood Features Distribution
  * [x] Identified Underlying patterns and relationships between variables
* Data Preprocessing
  * [x] Dropped Unnecessary Column (Id)
  * [x] Checked for missing values, duplicated values and outliers
  * [x] Encoded Target Variable (Species)

## Visualizations


## Key Insights
* **Sepals vs. Petals:** Sepals are much bigger than petals. The petal lengths are widely spread, which usually means flowers fall into different species. On the other hand, the sepal widths are almost the same, hovering right around 3cm.
* **Species Separation:** *Iris-setosa* forms a completely isolated cluster across all scatter plots. This makes it the easiest species to classify accurately.
* **Strong Linear Correlation:** An upward diagonal pattern exists between PetalLength and PetalWidth. As PetalLength increases, PetalWidth increases for all species.
* **Petals over Sepals:** *Iris-versicolor* and *Iris-virginica* flowers mix together a lot on the sepal charts, while they split into two distinct groups on the petal charts. This makes petals much better for telling them apart.
* **Clear Hills:** The smooth curves running diagonally down the chart show that while sepal sizes overlap heavily among all three flowers, petal sizes have a huge, clear gap between species.

## Tools Used
* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
