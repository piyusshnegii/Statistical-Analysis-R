# Week 3 – Statistical Analysis and Predictive Modeling using R

## 📌 Project Overview

This project was completed as part of the Week 3 internship task on **Statistical Analysis and Predictive Modeling using R**.

The objective of this project was to perform statistical analysis, conduct hypothesis testing, and develop a predictive classification model using R. The Titanic Passenger Dataset was selected for the analysis and builds upon the cleaned dataset prepared during Week 1.

The project covers the complete workflow from exploratory statistical analysis and hypothesis formulation to logistic regression, model evaluation, and diagnostic analysis.

---

## 📊 Dataset

**Dataset:** Titanic Passenger Dataset

The dataset contains passenger information including:

- Passenger Class
- Sex
- Age
- Fare
- Survival Status
- Embarkation Port
- Family-related information

Two dataset files are included in this repository:

- `titanic_raw.csv` – Original Titanic dataset
- `titanic_cleaned.csv` – Cleaned and preprocessed dataset used for analysis

---

## 🎯 Objectives

The main objectives of this project were to:

- Perform exploratory statistical analysis.
- Formulate and test statistical hypotheses.
- Analyze relationships between variables.
- Develop a classification model for predicting passenger survival.
- Evaluate model performance using appropriate metrics.
- Perform model diagnostics and identify potential areas for improvement.

---

## 🧪 Statistical Analysis

Several statistical techniques were applied during the analysis.

### Normality Testing

The Shapiro-Wilk test was used to examine the distribution of numerical variables such as:

- Age
- Fare

### Hypothesis Testing

Independent two-sample t-tests were used to examine differences in Age and Fare between survival groups.

Chi-square tests were performed to evaluate associations between survival and categorical variables such as:

- Sex
- Passenger Class
- Embarkation Port

### Correlation Analysis

Pearson correlation analysis was used to examine the relationship between Age and Fare.

---

## 🤖 Predictive Modeling

A **Logistic Regression** model was developed to predict passenger survival.

The target variable was:

```text
Survived


