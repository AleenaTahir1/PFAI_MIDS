# R Tasks: Data Manipulation, Visualization & Modeling

This repository contains a collection of basic yet essential R tasks for data analysis, visualization, statistical testing, and machine learning using built-in datasets.

## 📁 Contents

1. **Data Filtering & Sorting**  
   - Filter `mtcars` dataset for `mpg > 20`  
   - Sort by descending horsepower using `dplyr`

2. **Data Visualization**  
   - Scatter plot: Car weight vs. fuel efficiency  
   - Uses `ggplot2` with regression line

3. **Statistical Analysis**  
   - One-sample t-test using `t.test()` from the `stats` package  
   - Tests if sample mean differs from 10

4. **Machine Learning Model**  
   - Linear regression on `mtcars` to predict `mpg`  
   - Train-test split (80/20), preprocessing, and RMSE evaluation using `caret`

## 🛠️ Requirements

Make sure the following packages are installed:

```r
install.packages("dplyr")
install.packages("ggplot2")
install.packages("caret")
