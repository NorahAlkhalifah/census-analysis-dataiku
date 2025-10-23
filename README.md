# U.S. Census Data Exploratory Analysis and Classification

This project explores and analyzes U.S. Census employment and demographic data using **Dataiku** and **Python**.  
It focuses on uncovering patterns in the workforce, assessing data quality, and preparing features for a classification task related to employment categories.

---

## 📘 Overview

The project aims to:
- Clean and standardize Census data for reliable analysis.  
- Assess feature usability and remove low-information columns.  
- Explore relationships between demographic and employment attributes.  
- Generate reproducible visuals and insights using Dataiku and Jupyter notebooks.  
- Build a foundation for a supervised **classification model** predicting employment class.

---

## 🧹 Data Preparation

- Column normalization and naming consistency.  
- Handling missing and imbalanced values.  
- Feature usability scoring to filter out non-informative columns.  
- Exporting cleaned data for downstream analysis.

---

## 📊 Exploratory Data Analysis

- **Univariate analysis:** histograms, bar plots, and distributions of key features.  
- **Bivariate analysis:** relationships between education, occupation, and income.  
- **Correlation insights:** heatmaps and trend detection.  
- Visuals exported directly from **Dataiku** and included in `outputs/charts/`.

---

## 🤖 Classification Focus

The analysis prepares data for a supervised classification problem.  
The target variable, *class of worker*, is explored to understand feature relationships, class balance, and potential model readiness.

---

## 🧠 Visualization and Reporting

- Interactive charts and dashboards created in **Dataiku**.  
- Static visual exports (PNG) stored under `outputs/charts/`.  
- Slide presentation summarizing methodology, insights, and future directions.

---

## 📂 Project Structure
census-analysis/
├─ README.md
├─ requirements.txt
├─ notebooks/
│ ├─ 00_data_overview.ipynb
│ ├─ 01_data_cleaning_feature_usability.ipynb
│ ├─ 02_exploratory_analysis.ipynb
├─ scripts/
│ └─ utils.py
├─ data/
│ ├─ raw/
│ └─ processed/
├─ outputs/
│ ├─ charts/
│ ├─ tables/
│ └─ report/
└─ presentation/
└─ slides.pptx

