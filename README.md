# Amazon Sales Data Prediction – Project

## Overview

This repository contains a **Project** for R programming. 
The project focuses on analyzing **Amazon sales data** to understand patterns, relationships, and key drivers influencing outcomes, followed by building and evaluating multiple predictive models using R.

The analysis follows a complete data science workflow, including data exploration, preprocessing, regression, classification, clustering, regularization techniques, model evaluation, and interpretation of results.

---

## Table of Contents

1. Project Objective  
2. Project Structure  
3. Tools and Technologies  
4. Data Exploration  
5. Data Preprocessing  
6. Regression Models  
7. Regularization Techniques (Ridge & Lasso)  
8. Classification Models  
9. Clustering Analysis  
10. Model Evaluation and Diagnostics  
11. Key Insights  
12. Learning Outcomes  

---

## Project Objective

The primary objectives of this project are to:
- Explore and understand Amazon sales data
- Identify important features influencing outcomes
- Apply regression, classification, and clustering techniques
- Use regularization methods to prevent overfitting
- Evaluate and interpret model performance

---

## Project Structure

- `Amazon_Sales_Data_Prediction.Rmd` – R Markdown file containing the complete analysis, code, visualizations, and interpretations.

The R Markdown format ensures **reproducibility**, combining code, outputs, and explanations in a single document.

---

## Tools and Technologies

- R  
- RStudio  
- R Markdown  

Key R packages used include:
```r
tidyverse
caret
MASS
glmnet
car
ggplot2
```

---

## Data Exploration

Exploratory Data Analysis (EDA) includes:
- Summary statistics
- Distribution and relationship visualizations
- Detection of missing values and outliers

EDA guided preprocessing and model selection decisions.

---

## Data Preprocessing

Preprocessing steps include:
- Handling missing values
- Feature scaling and normalization
- Encoding categorical variables
- Preparing datasets for different modeling techniques

---

## Regression Models

Regression techniques are used to model continuous outcomes and understand relationships between predictors and the target variable.

Methods include:
- Multiple Linear Regression
- Model interpretation using coefficients
- Performance evaluation using residuals and goodness-of-fit metrics

---

## Regularization Techniques (Ridge & Lasso)

To address multicollinearity and overfitting, **regularization techniques** are applied:

- **Ridge Regression**: Penalizes large coefficients using L2 regularization
- **Lasso Regression**: Performs feature selection using L1 regularization

These methods improve model stability and generalization by controlling model complexity.

---

## Classification Models

Classification techniques are used to predict categorical outcomes.

Methods include:
- k-Nearest Neighbors (kNN) for classification
- Model evaluation using confusion matrix and classification metrics such as accuracy, precision, recall, and F1-score

kNN is used to understand distance-based learning and the impact of choosing optimal k values.

---

## Clustering Analysis

Unsupervised learning techniques are applied to discover hidden patterns in the data.

- **k-Means Clustering** is used to group observations
- The **Elbow Method** is applied to determine the optimal number of clusters
- Cluster results are visualized and interpreted

Clustering helps identify natural groupings within the dataset without using labeled outcomes.

---

## Model Evaluation and Diagnostics

Models are evaluated using:
- Residual analysis
- Diagnostic plots
- Confusion matrices for classification
- Comparison of model performance across techniques

This ensures reliability and interpretability of results.

---

## Key Insights

The project highlights:
- Key predictors influencing Amazon sales outcomes
- Benefits of regularization in improving model performance
- Trade-offs between regression, classification, and clustering approaches
- How unsupervised learning reveals hidden data structure

---

## Learning Outcomes

Through this final project, the following skills were strengthened:
- End-to-end data analysis in R
- Regression, Ridge, and Lasso modeling
- Classification using kNN
- Clustering with k-means and elbow method
- Model evaluation and interpretation
- Communicating results through reproducible reports

---

## Author

**Manasa Vijayendra Gokak**  
Graduate Student – Data Science  
DePaul University
