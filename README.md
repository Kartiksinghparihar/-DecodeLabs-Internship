# E-Commerce Data Analytics Project

## Overview
This project performs exploratory data analysis (EDA), data cleaning, statistical analysis, visualization, and machine learning on an E-Commerce dataset.

The objective is to extract business insights from customer orders, analyze purchasing behavior, detect outliers, visualize trends, and build predictive models for sales and order success.

---

## Project Tasks

### Task 1: Data Understanding
- Load dataset using Pandas
- Explore dataset structure
- Check data types
- View dataset dimensions
- Generate descriptive statistics

### Task 2: Data Cleaning
- Identify missing values
- Handle missing values in `CouponCode`
  - Remove some missing records
  - Replace missing values with "None"
  - Apply forward-fill technique
- Standardize text formatting

### Task 3: Statistical Analysis
Calculate:
- Mean
- Median
- Mode
- Standard Deviation

For:
- Quantity
- TotalPrice
- UnitPrice

Additional Analysis:
- Correlation Matrix
- Rolling Averages (7-Day and 14-Day)
- Outlier Detection using:
  - IQR Method
  - Z-Score Method

### Task 4: Data Visualization
Visualizations created:
- Histogram of UnitPrice
- Histogram of ItemsInCart
- Histogram of TotalPrice
- Payment Method Distribution
- Order Status Distribution
- Referral Source Distribution
- Violin Plot
- Scatter Plot
- Correlation Heatmap
- Box Plot

### Task 5: Machine Learning

#### Regression Model
Predict:
- TotalPrice

Features:
- Quantity
- ItemsInCart
- UnitPrice

Algorithm:
- Linear Regression

Evaluation Metrics:
- R² Score
- Mean Absolute Error (MAE)

#### Classification Model
Predict:
- Order Success (Delivered / Not Delivered)

Algorithm:
- Logistic Regression

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn

---

## Project Structure
