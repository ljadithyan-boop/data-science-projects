# 📊 Data Science Projects

> A collection of beginner-to-intermediate Data Science & Machine Learning projects built using Python and Jupyter Notebook.

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 🗂️ Projects Overview

| # | Project | Type | Tools | Accuracy |
|---|---------|------|-------|----------|
| 1 | [Customer Churn Prediction](#1-customer-churn-prediction) | ML Classification | Scikit-learn, Pandas | 81.76% |
| 2 | [COVID-19 Global Analysis](#2-covid-19-global-analysis) | EDA + Time Series | Pandas, Seaborn | — |
| 3 | [Netflix Content Analysis](#3-netflix-content-analysis) | EDA + Pattern Detection | Pandas, Matplotlib | — |

---

## 1. 📉 Customer Churn Prediction

**Folder:** `01_Customer_Churn_Prediction/`

### Overview
A machine learning project to predict whether a telecom customer will churn (leave) or stay, using the IBM Telco Customer Churn dataset with 7,043 records and 21 features.

### 🔧 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (LogisticRegression, DecisionTreeClassifier)

### 📊 Key Steps
- Data cleaning & type conversion (TotalCharges fix)
- Exploratory Data Analysis — churn rate, contract type analysis
- One-hot encoding of categorical features
- Model training & evaluation

### 📈 Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | **81.76%** |
| Decision Tree | 80.62% |

### 🔍 Key Insights
- Month-to-month contract customers churn the most
- ~26% overall churn rate in the dataset
- Logistic Regression outperformed Decision Tree on this dataset

### 📁 Dataset
[IBM Telco Customer Churn Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

---

## 2. 🦠 COVID-19 Global Analysis

**Folder:** `_COVID19_Global_Analysis/`

### Overview
Exploratory Data Analysis of global COVID-19 trends using the Our World in Data (OWID) dataset — 429,435 rows across 67 columns covering cases, deaths, and vaccinations from 2020–2024.

### 🔧 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Datetime

### 📊 Key Analyses
- Global new cases & deaths over time (wave visualization)
- Cumulative case growth trend
- Top 10 countries by total cases
- Simple growth rate forecasting insight

### 🌍 Top 10 Countries by Total Cases
| Country | Total Cases |
|---------|------------|
| United States | 103.4 Million |
| China | 99.4 Million |
| India | 45.0 Million |
| France | 39.0 Million |
| Germany | 38.4 Million |

### 🔍 Key Insights
- Distinct COVID waves clearly visible — Omicron peak in early 2023 was the largest
- Average daily new cases in last 30 days of data: **5,175**
- Growth rate vs total cases: **0.001% per day**

### 📁 Dataset
[Our World in Data — COVID-19](https://github.com/owid/covid-19-data)

---

## 3. 🎬 Netflix Content Analysis

**Folder:** `Netflix_Content_Analysis/`

### Overview
Exploratory Data Analysis of Netflix's content library using a dataset of 6,234 titles. Uncovers trends in genres, ratings, countries, directors, and release patterns over time.

### 🔧 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn

### 📊 Key Analyses
- Movies vs TV Shows distribution
- Top 10 genres on Netflix
- Top 10 content-producing countries
- Top 10 directors by number of titles
- Content release trend (last 20 years)
- Release Year vs Movie Duration correlation

### 🔍 Key Insights
- **Movies dominate** over TV Shows on Netflix
- **Top genres:** International Movies, Dramas, Comedies
- **Most common rating:** TV-MA
- **Content exploded after 2015**, peaked around 2018–2019
- **USA leads** with 2,032 titles; India is #2
- **Newer movies are slightly shorter** (correlation: −0.221)

### 📁 Dataset
[Netflix Titles Dataset](https://raw.githubusercontent.com/prasertcbs/basic-dataset/master/netflix_titles.csv)

---

## 🛠️ Tech Stack

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter)

---

## 🚀 How to Run Any Project

```bash
# 1. Clone the repo
git clone https://github.com/ljadithyan-boop/data-science-projects.git

# 2. Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Launch Jupyter Notebook
jupyter notebook
```

Then open any `.ipynb` file from the project folders.

---

## 👤 Author

**Adithyan**
- GitHub: [@ljadithyan-boop](https://github.com/ljadithyan-boop)

---

⭐ If you found this helpful, consider giving the repo a star!
