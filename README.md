<p align="center">
  <img src="project_logo.png" alt="Project Logo" width="250">
</p>

<p align="center">

  <!-- Python Version -->
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python Version">

  <!-- Scikit-Learn -->
  <img src="https://img.shields.io/badge/ML-Scikit--Learn%200.24%2B-orange?logo=scikitlearn&logoColor=white" alt="Scikit-Learn">

  <!-- Pandas -->
  <img src="https://img.shields.io/badge/Pandas-Used%20in%20EDA%20%26%20Cleaning-150458?logo=pandas&logoColor=white" alt="Pandas">

  <!-- NumPy -->
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white" alt="NumPy">

  <!-- Visualization Libraries -->
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-brightgreen" alt="Visualization">

  <!-- Flask API -->
  <img src="https://img.shields.io/badge/Deployment-Flask%20API-000000?logo=flask&logoColor=white" alt="Flask">

  <!-- Dataset Size -->
  <img src="https://img.shields.io/badge/Dataset-1186%20rows%20×%207%20columns-yellow" alt="Dataset Size">

  <!-- Jupyter Notebook -->
  <img src="https://img.shields.io/badge/Notebook-Jupyter-F37726?logo=jupyter&logoColor=white" alt="Jupyter">

  <!-- Project Status -->
  <img src="https://img.shields.io/badge/Status-Active-success" alt="Project Status">

</p>


# 📊 Project Valuation Analysis — Machine Learning & Data Analytics


A comprehensive machine learning and data analytics project focused on analyzing and predicting the valuations of Unicorn companies (privately held startups valued at over $1B). This project covers the entire ML lifecycle, from data processing and exploratory analysis to model training, optimization, and API deployment.

## ⭐ Features

* **End-to-end ML Workflow:** Complete pipeline from raw data to a production-ready model.
* **Global Dataset:** Analysis of Unicorn companies worldwide from **2012–2022**.
* **In-depth EDA:** Extensive exploratory data analysis with charts and insights.
* **Predictive Models:** Implementation of **Linear Regression** (baseline) and optimized **Random Forest**.
* **Hyperparameter Tuning:** Optimization using `GridSearchCV`.
* **Sector & Investor Analysis:** Insights into dominant sectors and high-frequency investors.
* **Deployment-Ready API:** A lightweight **Flask API** for serving valuation predictions.

---

## 📁 Project Structure
├── Project_Valuation_Analysis.ipynb                     
├── Project Valuation Analysis_ ML _ DA projects.pdf     
├── unicorns till sep 2022.csv                            
└── README.md                                            


## 📄 Dataset Overview

The dataset includes **1186 unicorn companies** with attributes such as `Company`, `Valuation ($B)`, `Join date`, `Country & City`, `Industry`, and `Investors`.

### Data Cleaning and Transformation

Extensive pre-processing was performed to ensure data quality:

* ✔ Removal of missing values.
* ✔ Conversion of valuation strings to numeric types.
* ✔ Parsing dates into year/month features.
* ✔ Splitting and transforming investor lists.
* ✔ Handling inconsistent sector labels.



## 🔍 Exploratory Data Analysis (EDA)

The `Project_Valuation_Analysis.ipynb` notebook provides detailed visualizations, including pie charts, bar charts, line graphs, and correlation heatmaps.


---

### 📌 Key Insights

* The **US** accounts for approximately **54%** of all global Unicorn companies.
* **Fintech** is identified as the most dominant sector by unicorn count.
* **Rapid unicorn growth** was observed in the years between **2018–2021**.

### 📸 Visualization Highlights

Here are a few key visualizations from our exploratory data analysis:

#### 🟦 Distribution of Unicorn Valuations

This histogram illustrates the distribution of valuations among Unicorn companies. It clearly shows that a vast majority of unicorns are valued at or near the $1 Billion threshold, with a long tail indicating a few highly valued outliers.

<p align="center">
  <img src="valuation_distribution.png" alt="Distribution of Unicorn Valuations" width="700"/>
</p>

#### 🌍 Top 10 Countries Producing Unicorns

This pie chart highlights the top countries that have produced Unicorn companies. The United States dominates by a significant margin, followed by China and India, showcasing regional concentrations of high-growth startups.

<p align="center">
  <img src="top_countries_unicorns.png" alt="Top 10 Countries by Unicorn Count" width="700"/>
</p>


## 🤖 Machine Learning Workflow

### 1. Data Preparation

* Feature Scaling
* One-hot Encoding for categorical features
* Null value imputation (if necessary)
* Train-test split for model validation

### 2. Models Trained

| Model | Purpose | Notes |
| :--- | :--- | :--- |
| **Linear Regression** | Baseline model | Used as a simple benchmark. |
| **Random Forest** | Main predictive model | Non-linear, robust, and handles high-dimensional data well. |

### 3. Evaluation and Optimization

| Metric | Optimization | Optimized Hyperparameters |
| :--- | :--- | :--- |
| **Mean Squared Error (MSE)** | `GridSearchCV` | `n_estimators` |
| **R² Score** | Feature Importance | `max_depth` |
| **Feature Importance** | | `min_samples_split` |


---

## 👨‍💻 Author

**Aditya Sharma**  
Data Scientist | Business Intelligence Developer 

---

## 📄 License

This project is intended for educational and portfolio purposes.  
Please attribute the author if you reuse or reference this work.

---
