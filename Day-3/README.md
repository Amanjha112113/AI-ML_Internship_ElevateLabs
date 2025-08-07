📈 Day 3: Housing Price Prediction - Linear Regression
This is my Day 3 task for the AI/ML Internship program.In this task, I implemented simple and multiple linear regression models on the Housing Price Prediction dataset and created advanced visualizations using Python libraries.

📌 What I Did

Loaded the Housing dataset using Pandas.
Converted categorical variables (e.g., mainroad, furnishingstatus) to numeric using LabelEncoder.


Performed Linear Regression:
Built a simple linear regression model using area as the sole feature.
Built a multiple linear regression model using all available features.


Evaluated models:
Calculated Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.
Exported metrics and coefficients to model_results.txt.


Created visualizations:
Plotted a correlation heatmap to show feature relationships.
Plotted a scatter plot with regression line for simple linear regression (Area vs. Price).
Plotted a bar chart of feature importance for multiple linear regression.
Plotted actual vs. predicted prices for model evaluation.
Combined all plots into a single image, saved as housing_price_analysis.png.


Created interactive visualizations:
Generated an interactive 2D scatter plot using Plotly (Area vs. Price).
Generated an interactive 3D scatter plot using Plotly (Area, Bedrooms vs. Price).
Exported as scatter_plot.html and 3d_scatter_plot.html.




📊 Tools Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Plotly


📂 Files in this Folder

main.py → Fully functional Python script with data preprocessing, model training, evaluation, and visualization generation.
model_results.txt → Model performance metrics (MAE, MSE, R²) and coefficients.
housing_price_analysis.png → Combined Matplotlib/Seaborn visualizations.
scatter_plot.html → Interactive Plotly 2D scatter plot.
3d_scatter_plot.html → Interactive Plotly 3D scatter plot.
Housing.csv → Dataset file (you can download it from the link below).
README.md → This file.


📥 Dataset Source
You can get the Housing Price Prediction dataset from:

Kaggle: Housing Price Prediction Dataset


✅ What I Learned

How to implement simple and multiple linear regression models
How to preprocess categorical data for machine learning
How to evaluate regression models using MAE, MSE, and R²
How to create static visualizations with Matplotlib and Seaborn
How to create interactive visualizations with Plotly
How to interpret regression coefficients and feature importance


🎯 This project provides a solid foundation for understanding linear regression and data visualization, essential for advanced machine learning tasks.
