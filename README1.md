# CodeAlpha Data Science Internship

## Task 4:  Sales Prediction using Python

## Project Overview

This project was completed as part of the **CodeAlpha Data Science Internship**. The objective is to predict sales based on advertising expenditures and marketing factors using machine learning techniques. By analyzing the relationship between advertising channels and sales performance, the model helps businesses make data-driven marketing decisions.

---

## Objectives

* Analyze advertising and sales data.
* Perform data cleaning and preprocessing.
* Explore relationships between advertising channels and sales.
* Build a machine learning model for sales prediction.
* Evaluate model performance using regression metrics.
* Generate actionable business insights.

---

## Dataset Information

The dataset contains advertising-related features and corresponding sales values.

### Features

* TV Advertising Budget
* Radio Advertising Budget
* Newspaper Advertising Budget
* Other marketing-related features (if available)

### Target Variable

* Sales

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

* Loaded the dataset using Pandas.
* Examined dataset structure and feature information.

### 2. Data Cleaning

* Checked for missing values.
* Removed duplicate records.
* Ensured data consistency.

### 3. Exploratory Data Analysis (EDA)

* Analyzed sales distribution.
* Studied relationships between advertising spend and sales.
* Identified important trends and patterns.

### 4. Feature Selection

* Selected relevant advertising features.
* Prepared independent and target variables.

### 5. Model Building

* Split the dataset into training and testing sets.
* Trained a Linear Regression model.

### 6. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 7. Visualization

Generated visualizations including:

* Advertising Spend vs Sales
* Feature Impact Analysis
* Actual vs Predicted Sales Comparison

---

## Results

The regression model successfully predicted sales based on advertising expenditure.

### Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

A higher R² score indicates better prediction accuracy.

---

## Key Insights

* Advertising expenditure has a direct impact on sales performance.
* TV advertising generally contributes the most to sales growth.
* Radio advertising positively influences customer engagement.
* Data-driven advertising strategies can improve return on investment (ROI).
* Machine learning can assist businesses in forecasting future sales.

---

## Business Applications

This project can help organizations:

* Forecast future sales.
* Optimize advertising budgets.
* Improve marketing effectiveness.
* Support strategic business planning.

---

## How to Run the Project

### Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Run the Project

1. Open Google Colab or Jupyter Notebook.
2. Upload the dataset.
3. Execute all notebook cells.
4. Review predictions and visualizations.

---

## Project Structure

```text
Sales-Prediction/
│
├── Sales_Prediction.ipynb
├── sales_data.csv
├── README.md
├── requirements.txt
└── screenshots/
    ├── dataset_preview.png
    ├── sales_analysis.png
    ├── actual_vs_predicted.png
    ├── feature_importance.png
    └── model_results.png
```

---

## Future Improvements

* Implement advanced regression models such as Random Forest Regressor and XGBoost.
* Perform hyperparameter tuning.
* Deploy the model as a web application.
* Build an interactive sales forecasting dashboard.

---

## Conclusion

This project demonstrates how machine learning can be used to predict sales based on advertising expenditures. The insights obtained from the analysis can help businesses optimize marketing strategies, allocate budgets efficiently, and improve overall revenue performance.

---

**Internship:** CodeAlpha Data Science Internship

**Task:** Task 4 – Sales Prediction using Python

**Tools Used:** Python, Pandas, NumPy, Matplotlib, Scikit-learn

**Author:** Srinivas Konakalla
