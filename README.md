# Replication Code: Jump Characteristics of Energy and Non-Energy ETFs

This repository contains the replication code for the study titled:

**"A New Kind of Shock: Examining Jump Characteristics of Energy and Non-Energy ETFs"**

The code includes all steps necessary to preprocess the data, perform jump statistical analysis, and run regression models.
---

## 📁 Files Included

### 1. `Jump statistical analysis.ipynb`
- **Language**: Python (Jupyter Notebook)
- **Description**: Performs the statistical analysis of jumps in ETF returns.
- **Includes**:
  - Data transformation from `.sas7bdat` to `.csv`
  - Data cleaning and filtering
  - Jump statistic calculation
  - T-tests for group comparisons

### 2. `Regression code.Rmd`
- **Language**: R (R Markdown)
- **Description**: Conducts regression analysis on jump metrics.
- **Includes**:
  - Baseline and interaction regression models
  - Coefficient extraction and summary
  - Uses packages like `tidyverse`, `dplyr`, and `data.table`

---

## 📦 Data Access

This study uses proprietary data from the Trade and Quote (TAQ) database, accessed via the Wharton Research Data Services (WRDS) platform. Due to licensing restrictions, the dataset is **not included** in this repository.

Interested researchers can request access to the TAQ database via their institutional WRDS account:  
👉 [https://wrds-www.wharton.upenn.edu/](https://wrds-www.wharton.upenn.edu/)

---

## ▶️ How to Use

1. Obtain the necessary TAQ data through WRDS.
2. Convert and preprocess the data using `Jump statistical analysis.ipynb`.
3. Run jump statistics and t-tests.
4. Perform regression analysis using `Regression code.Rmd`.

---

## 📜 License

This code is licensed under the **MIT License**. See the `LICENSE` file for details.
