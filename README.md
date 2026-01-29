# 🚢 Titanic Survival – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand data quality, feature distributions, relationships between variables, and factors influencing passenger survival.

The analysis focuses on identifying key patterns using statistical summaries and visualizations to support data-driven insights.

---

## 📊 Dataset Information
- **Dataset:** Titanic Dataset
- **Rows:** 418
- **Columns:** 12
- **Target Variable:** `Survived`
- **Key Features:**
  - Numerical: `Age`, `Fare`, `SibSp`, `Parch`
  - Categorical: `Sex`, `Pclass`, `Embarked`, `Cabin`

---

## 🎯 Objectives
- Understand the structure and quality of the dataset
- Identify and analyze missing values
- Classify numerical and categorical variables
- Detect and interpret outliers
- Analyze relationships between features and survival outcome
- Draw meaningful insights from the data

---

## 🔍 EDA Steps Performed

### 1️⃣ Data Understanding
- Examined dataset shape, column types, and summary statistics
- Classified columns into numerical and categorical features

---

### 2️⃣ Missing Value Analysis
- Identified missing values using `isna().sum()`
- Found that the `Cabin` column contains a high proportion of missing values
- Visualized missing vs non-missing data

---

### 3️⃣ Univariate & Bivariate Analysis
- Analyzed distributions of numerical features
- Explored relationships between:
  - Gender and survival
  - Passenger class and survival
  - Fare and survival
- Used bar plots, box plots, and count plots for visualization

---

### 4️⃣ Outlier Detection
- Detected outliers in numerical features using the **IQR method**
- Identified that sales-related skewness is expected and informative
- Outliers were retained as they represent genuine observations

---

### 5️⃣ Multigroup Comparison
- Compared survival outcomes across multiple categorical groups
- Identified key factors influencing survival probability

---

## 📈 Key Insights
- Gender is a strong indicator of survival probability
- Higher passenger class is associated with better survival chances
- Fare distribution is right-skewed with significant outliers
- Missing data patterns require careful handling, especially for `Cabin`

---

## ⚠️ Data Limitations
- The dataset contains missing values that may impact certain analyses
- Findings are limited to the available features and sample size

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Dataset Source
The dataset used in this project was obtained from Kaggle:

🔗[Titanic Dataset - Kaggle](https://www.kaggle.com/datasets/brendan45774/test-file)

---

## 👤 Author
**Shiva Prasad**  
Aspiring Data Analyst / Data Scientist  

---

⭐ If you find this project useful, feel free to star the repository!

