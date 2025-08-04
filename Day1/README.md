# 🚢 Day 1: Titanic Dataset - Data Cleaning & Preprocessing

This is my **Day 1 task** for the AI/ML Internship program.  
In this task, I worked with the Titanic dataset to clean and prepare the data for machine learning.

---

## 📌 What I Did

1. **Loaded the dataset** using Pandas.
2. **Checked for missing values** and data types.
3. **Filled missing values**:
   - Replaced missing `Age` values with the **median age**.
   - Replaced missing `Embarked` values with the **most common port**.
4. **Converted categorical data**:
   - Changed `Sex` column to 0 (male) and 1 (female).
   - Used **one-hot encoding** for the `Embarked` column.
5. **Standardized numerical features**:
   - Applied **StandardScaler** to `Age` and `Fare` so they have mean 0 and std 1.
6. **Visualized and removed outliers** using a boxplot and IQR method.
7. **Created multiple plots** (bar chart, boxplot, histogram, pie chart, heatmap) to understand the data better.

---

## 📊 Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📂 Files in this folder

- `main.py` → Python script with full preprocessing and visualizations.
- `Figure_1.png` →  Image showing all combined plots.
- `Titanic-Dataset` → Titanic dataset
- `README.md` → This file.

---

## 📥 Dataset Source

Titanic dataset used from:  
[Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
or  
[GitHub CSV Link](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## ✅ What I Learned

- How to clean missing values
- How to encode categorical data
- How to normalize/standardize features
- How to find and remove outliers
- How to visualize data for better understanding

---

