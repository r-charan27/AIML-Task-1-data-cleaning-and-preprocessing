# AIML-Task-1-data-cleaning-and-preprocessing
# 🧹 Task 1: Data Cleaning & Preprocessing - Titanic Dataset

## 📌 Internship Task Overview
This task is part of the **AI & ML Internship** focused on understanding the fundamentals of data preprocessing for machine learning.

## 🎯 Objective
To clean and prepare the Titanic dataset for ML modeling by handling missing values, encoding categorical variables, scaling numerical features, and detecting/removing outliers.

---

## 📂 Dataset
- **Name:** Titanic Dataset  
- **Source:** [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧪 Steps Followed

### 1. Data Loading & Exploration
- Loaded CSV using `pandas`
- Explored dataset using `.head()`, `.info()`, `.describe()`
- Checked for null values

### 2. Handling Missing Values
- Imputed missing `Age` values using **median**
- Filled missing `Embarked` values using **mode**
- Dropped the `Cabin` column due to excessive missing data

### 3. Encoding Categorical Variables
- Applied **one-hot encoding** to `Sex` and `Embarked` columns

### 4. Feature Scaling
- Standardized `Age` and `Fare` using **StandardScaler** from `sklearn`

### 5. Outlier Detection & Removal
- Visualized outliers using **boxplots**
- Removed extreme `Fare` values using **IQR method**

---

## 📊 Visualizations Included
- Null value heatmap
- Boxplots for outlier detection

---

## 📖 What I Learned
- Importance of data preprocessing in ML
- Techniques for handling nulls, encoding, and scaling
- How preprocessing affects model performance
- Common pitfalls and how to clean real-world data

---

## 📁 Repository Contents
- `Titanic_Preprocessing.ipynb`: Main Jupyter notebook
- `Titanic-Dataset.csv`: Dataset file (or link to Kaggle)
- `README.md`: This file
- 'Cleaned Titanic-Dataset.csv'
---
## 💬 Final Thoughts
Preprocessing is a vital step in the ML pipeline. A clean and well-prepared dataset can drastically improve model accuracy and robustness.
---
AUTHOR--MUMMADI RAMCHARAN
