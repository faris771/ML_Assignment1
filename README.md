# Assignment #1: Exploratory Data Analysis and Regression Modeling

This repository contains the Python code and analysis for Assignment #1 in the "Machine Learning and Data Science" course (ENCS5341) at the Electrical and Computer Engineering Department.

## Overview

The goal of this assignment is to perform an in-depth analysis of a dataset containing information about cars and fuel consumption. We will use Python for the solution, leveraging libraries such as Pandas for data manipulation and analysis, and NumPy for numerical operations.

## Dataset

The dataset, `cars.csv`, is provided and contains information about various cars, including fuel consumption. The main tasks include:

1. **Data Exploration:**
   - Read the dataset and examine the number of features and examples.
   - Identify features with missing values and determine the number of missing values in each.

2. **Data Imputation:**
   - Fill missing values in each feature using appropriate imputation methods, such as mean, median, or mode.

3. **Country-wise Fuel Economy:**
   - Use a box plot to visualize fuel economy (mpg) for cars produced by different countries.

4. **Distribution Analysis:**
   - Determine which feature ('acceleration', 'horsepower', or 'mpg') has a distribution most similar to a Gaussian.
   - Support the answer with histograms of each feature.

5. **Quantitative Measure:**
   - Provide a quantitative measure supporting the distribution analysis.

6. **Correlation Analysis:**
   - Plot a scatter plot showing the correlation between 'horsepower' and 'mpg'.
   - Analyze whether the correlation is positive or negative.

7. **Linear Regression:**
   - Implement the closed-form solution of linear regression.
   - Learn a linear model to predict 'mpg' from 'horsepower' and visualize the learned line on the scatter plot.

8. **Quadratic Regression:**
   - Learn a quadratic function and visualize it.

9. **Gradient Descent:**
   - Implement the gradient descent algorithm for simple linear regression.
