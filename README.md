# 📊 Student Performance Analysis using Linear Algebra & Statistics

This project explores how academic and lifestyle factors influence **student performance (CGPA)** using **Exploratory Data Analysis (EDA)**, **statistical tests**, and **linear algebra techniques** like **Principal Component Analysis (PCA)** and **Linear Regression**.

---

## 📌 Project Overview

The dataset contains student details such as:

* Age
* Study hours per week
* Sleep hours
* CGPA
* Stress level
* Attendance percentage
* Social media usage
* Part-time job & gender

The main objective is to understand **what factors impact CGPA** and how statistical & linear algebra methods can reveal patterns.

---

## 🎯 Objectives

* Preprocess the dataset (handle missing values, duplicates).
* Perform **EDA** to study distributions & relationships.
* Apply **T-test & ANOVA** to test hypotheses.
* Use **PCA** for dimensionality reduction and variance analysis.
* Apply **Linear Regression** to explore predictive relationships.

---

## 🛠️ Methodology

1. **Data Preprocessing:**

   * Handled missing values with median imputation.
   * Removed duplicates and cleaned dataset.

2. **Exploratory Data Analysis (EDA):**

   * Visualized CGPA distribution, attendance vs CGPA, stress levels, and study hours.
   * Identified correlations and patterns.

3. **Statistical Tests:**

   * T-test → Checked CGPA differences between students with/without part-time jobs.
   * ANOVA → Compared CGPA across different stress levels.

4. **Principal Component Analysis (PCA):**

   * Standardized features.
   * Reduced dataset dimensions while retaining ~81% of variance in top 5 components.

5. **Linear Regression:**

   * Explored relationship between study hours and CGPA.
   * Found negligible linear correlation, suggesting other factors matter more.

---

## 📈 Key Findings

* **Attendance** has some positive association with CGPA.
* **Stress levels** show weak but noticeable influence (low stress → slightly higher CGPA).
* **Study hours alone** are not a strong predictor of CGPA.
* **PCA** revealed that multiple factors together explain performance, not just one variable.

---

## 💡 Conclusion

Student performance is shaped by a **complex combination** of study habits, stress, sleep, attendance, and lifestyle factors. Linear Algebra methods like PCA help uncover these hidden relationships, while regression and statistical tests validate them.

---

## 🚀 Tech Stack

* Python 🐍
* Pandas, NumPy
* Matplotlib, Seaborn
* Scipy (stats)
* Scikit-learn (PCA, Linear Regression)

---

## 📂 Files in Repo

* `Project.ipynb` → Main notebook with code & analysis
* `Project Report.pdf` → Detailed explanation, methodology & results

---

## 🙏 Contributions

Suggestions and improvements are welcome! If you’ve worked on similar analyses, feel free to share your insights.
