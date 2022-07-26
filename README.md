<!-- markdownlint-disable -->
<h1 align="center">
  # DAB402: Air Quality Prediction
    <br>
</h1>
<p align="center">
<strong>🏆&nbsp; My goal was to perform to check the quality of air using ‘Air Quality Chemical Multisensor Device’ by finding the R^2 score and coefficient of regression using different regression models and the best model is selected to evaluate the Air Quality..</strong>
</p>

## Objective of Project:
This is the classic marketing bank dataset uploaded originally in the UCI Machine Learning Repository. The dataset gives you information about a marketing campaign of a financial institution.
Analyze data in order to find ways to look for future strategies in order to improve future marketing campaigns for the bank.

## Research Objectives:
The following are the business objective of this application,

- **Find the Target Variable.**

- **Find the variable highly correlated with the target variable. Decide independent parameter to predict the dependent parameter for modelling.**

- **Find the best Model for Evaluating the Quality of Air with highest Accuracy Score**

---

<p align="center">
     🧙‍♂️&nbsp; Click <a href="https://github.com/haritikajolly/Air-Quality-Prediction/blob/ba52441feed1e9ee548efaa51b46aa2cac8ef0b9/Air%20Quality%20Prediction.ipynb"> to access the Project Notebook</a> <br>
</p>

---

## Table of Contents:

[Jupyter Notebook Link](https://github.com/haritikajolly/Air-Quality-Prediction/blob/ba52441feed1e9ee548efaa51b46aa2cac8ef0b9/Air%20Quality%20Prediction.ipynb)
>**Data Sourcing**

>**Data Importing**

>**Data review, Descriptive Statistics, Null checks, Cleaning and handling outliers**

>**Descriptive Statistics (after missing values imputation)**

> **Outlier Detection & Handling**

> **Histograms**

> **Co-relation between variables**

> **Modelling**

> **a) 1. Linear Regression Model**

> **b) 2. Lasso Regression Model**

> **c) 3. Decision Tree Model**

> **Conclusion**
   
  
>**Conclusion from Modelling & Research answers.**

## Technologies:
This project is created with:
* Jupyter Notebook
* Python
* Python Libraries: Pandas, NumPy, matplotlib, SciPy, Seaborn, Scikit Learn


## Classification & Modelling - Results:

**For designing the model for predicting Quality of Air, I have applied Linear Regression, Decision Tree, Lasso Regression.**

**When tested on test data below are MSE, RMSE and R^2 scores obtained from different algorithms:**

**Conclusion**

MSE	RMSE	R^2
Linear Regression	1.1097	1.0534	97.2476
Lasso Regression	1.0903	1.0442	97.2955
Decision Tree Regression	0.0042	0.0649	99.9895

**Result: By seeing the table we conclude that Decision Tree Regression model is giving More accuracy out of all these model so it will be considered as the best model for evaluating the Quality of Air.**

## Modelling & Research answers :

> Q: Find the classification model that can be used in the future as a predictive model, that will result in higher accuracy?

In comparison with all 3 classification algorithms Decision Tree Regression outperformed Linear Regression and Lasso Regression classification by achieving the highest accuracy among all of the three classification algorithms.
So Decision Tree Regression model will be considered as the best predictive model for evaluating the Quality of Air.

> Q: Find the variable highly correlated with the target variable. Decide independent parameter to predict the dependent parameter for modelling ?

By seeing the correlation we conclude that Target variable : C6H6_GT is highly correlated to PTO8.S2_NMHC, so we take PTO8.S2_NMHC as independent parameter to predict the dependent parameter i.e., C6H6_GT


## Content:

-  Air Quality Prediction.pdf # PDF Report / summary of the final assignment.

-  Air Quality Prediction.docx # Report in Doc Format.

-  Air Quality Prediction.ipynb # Jupyter notebook with coding.

- Copy of AirQualityUCI.csv #  Dataset CSV File.

- README.md # this readme file
