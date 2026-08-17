<div align="center">

# 🐼 Data Analysis & Wrangling with Pandas

### Practical Data Manipulation, Cleaning & Transformation in Google Colab

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)
![NAVTTC](https://img.shields.io/badge/NAVTTC-AI--ML--DL-blue?style=for-the-badge)

**A hands-on practice notebook focused on core Data Analysis tasks using Pandas: handling missing values, value replacement, row deletion, unique value extraction, and applying lambda transformations.**

</div>

---

## 📖 Overview

This notebook is part of the **NAVTTC Artificial Intelligence, Machine Learning & Deep Learning** program[cite: 1, 2]. It focuses on practical Data Wrangling techniques using the **Pandas** library, which is essential for pre-processing datasets before building Machine Learning models[cite: 1, 2, 4].

---

## 🎯 Key Concepts & Operations Covered

- 📊 **Categorical Data Inspection:**
  - `value_counts()`: Frequency counting for categorical values[cite: 4].
  - `unique()`: Extracting distinct categorical values from a column[cite: 4].
- ⚙️ **Column Transformation:**
  - `apply()` with `lambda`: Applying element-wise operations across DataFrames (e.g., adding years to age)[cite: 4].
- 🔍 **Missing Data Detection:**
  - `isnull()`: Checking for `NaN` / `None` values[cite: 4].
  - `isnull().sum()`: Summing total missing entries per column[cite: 4].
- 🔄 **Data Replacement & Cleaning:**
  - `replace()`: Updating specific cell values (e.g., updating names and numerical marks)[cite: 4].
- 🗑️ **Data Dropping:**
  - `drop()`: Removing rows by index[cite: 4].
  - Using `inplace=True` for direct modification[cite: 4].

---

## 💻 Code Summary

1. **Unique Values & Frequencies:** Counting city occurrences and retrieving unique city names (`lahore`, `karachi`, `islamabad`)[cite: 4].
2. **Lambda Transformations:** Dynamically creating modified columns using functions on target series[cite: 4].
3. **Missing Value Handling:** Identifying null values within dataset columns[cite: 4].
4. **DataFrame Operations:** Modifying row/column data through value replacement and targeted index dropping[cite: 4].

---

## 🛠️ Tools & Environment

| Tool / Tech | Purpose |
|------------|---------|
| 🐍 **Python 3** | Core Programming Language[cite: 4] |
| 🐼 **Pandas** | Data Manipulation & Analysis Library[cite: 4] |
| ☁️ **Google Colab** | Cloud Notebook Environment[cite: 4] |
| 🌐 **GitHub** | Version Control & Code Hosting[cite: 4] |

---

## 🚀 How to Run

1. Open **Google Colab**[cite: 4].
2. Import or upload this notebook (`.ipynb`)[cite: 4].
3. Execute all cells sequentially (`Shift + Enter`) to view the output streams[cite: 4].

---

## 👨‍🎓 Course & Student Information

- **Course:** NAVTTC AI, Machine Learning & Deep Learning[cite: 1, 2]
- **Module:** Data Science Fundamentals & Pandas Wrangling[cite: 1, 2, 4]
- **Student Name:** Sobia Sharif

---

<div align="center">

### ⭐ *Clean data leads to better AI models!*

</div>
