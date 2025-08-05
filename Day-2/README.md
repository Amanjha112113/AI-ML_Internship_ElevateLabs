# 📊 Day 2: Titanic Dataset - Exploratory Data Analysis (EDA)

This is my **Day 2 task** for the AI/ML Internship program.  
In this task, I performed Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries.

---

## 📌 What I Did

1. **Loaded the Titanic dataset** using Pandas.
2. **Generated summary statistics**:
   - Used `describe()` to compute mean, median, std, min, max, etc.
   - Exported to `summary_statistics.csv`.
3. **Visualized distributions**:
   - Plotted histograms and KDEs for all numerical features.
   - Plotted boxplots to identify outliers and data spread.
4. **Created a correlation matrix heatmap**:
   - Identified relationships between numerical features.
5. **Plotted pairplot** for key features:
   - Explored feature interactions colored by survival.
6. **Combined all plots into a single image** using Pillow.
   - Exported as `eda_summary.png`.

---

## 📊 Tools Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Pillow (for combining images)

---

## 📂 Files in this Folder

- `main.py` → Fully functional Python script with all EDA steps and image generation.
- `summary_statistics.csv` → Descriptive statistics of the dataset.
- `eda_summary.png` → Combined visual of all plots & other images
- `Titanic-Dataset.csv` → Dataset file (you can download it from links below).
- `README.md` → This file.

---

## 📥 Dataset Source

You can get the Titanic dataset from:

- Kaggle: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
- GitHub (direct CSV): [Download CSV](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## ✅ What I Learned

- How to summarize data using descriptive statistics
- How to visualize distributions and outliers
- How to detect correlations and feature interactions
- How to use Seaborn and Matplotlib for insightful EDA
- How to programmatically combine multiple plots into one image

---

🎯 **This EDA helps build a strong foundation for feature engineering and model building in future tasks.**
