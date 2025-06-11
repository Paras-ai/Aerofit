# 🏋️‍♀️ Aerofit Data Exploration Case Study

This repository contains my complete solution for Aerofit's customer profiling and business recommendation case study.

---

## 🎯 Objective

Aerofit is a leading fitness equipment brand offering various treadmill models.  
The objective of this case study is to analyze Aerofit's customer data and develop:

- Customer profiling for each product model (KP281, KP481, KP781)
- Outlier detection and data cleaning
- Relationship analysis between customer features and product choice
- Business recommendations based on data analysis

---

## 📂 Repository Contents

- **data/**
  - `aerofit_data.csv` — raw dataset

- **reports/**
  - `Aerofit_CaseStudy_Questions.pdf` — problem statement for the case study
  - `Aerofit_CaseStudy_Solution.pdf` — solution PDF containing full analysis and recommendations

---

## 🔎 Solution Approach

### 1️⃣ Data Preparation & Cleaning
- Imported dataset and performed missing value check.
- Detected outliers using boxplots and removed them using 5th-95th percentile clipping.

### 2️⃣ Exploratory Data Analysis
- Analyzed impact of gender, marital status, and age on product choice.
- Used scatter plots and count plots to visualize relationships.
- Built customer profiles for KP281, KP481, and KP781 products.

### 3️⃣ Probability Analysis
- Calculated marginal, conditional, and joint probabilities using pandas crosstab.
- Derived business insights from customer behavior.

### 4️⃣ Correlation Analysis
- Used correlation heatmap to detect relationships between continuous features.

### 5️⃣ Business Recommendations
- Built clear customer profiles for each product.
- Recommended marketing and sales strategies based on customer segments.

---

## 🧰 Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 💡 Key Learnings

- End-to-end Exploratory Data Analysis (EDA)
- Customer profiling from real-world business data
- Outlier detection & data cleaning
- Business insight generation for product recommendations

---

✅ Author: **Paras Khurana**
