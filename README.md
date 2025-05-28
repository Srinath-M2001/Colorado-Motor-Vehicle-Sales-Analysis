# 🚗 Colorado Motor Vehicle Sales Analysis

This project explores and analyzes motor vehicle sales data across counties in Colorado from 2008 to 2015. The analysis aims to uncover seasonal patterns, compare county-level performances, and build a predictive model for future sales.

---

## 📊 Project Overview

* **Dataset**: `colorado_motor_vehicle_sales.csv`
* **Period Covered**: 2008 to 2015
* **Features**: Year, Quarter, County, Sales
* **Objective**: Perform EDA, visualize trends, and build a predictive model using machine learning.

---

## 🔍 Key Insights

* **Seasonal Trends**: Sales tend to peak during specific quarters, with Q4 showing higher medians in some years.
* **Top Counties**: Counties like Arapahoe and Denver consistently show higher sales across multiple quarters.
* **Sales Over Time**: Time series plots reveal a gradual increase in vehicle sales from 2008 to 2015.
* **Distribution Analysis**: Sales show right-skewed distribution, indicating a few counties have significantly higher numbers.

---

## 🛠️ Tools & Technologies

* **Languages**: Python
* **Libraries**: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `ipywidgets`
* **Model Used**: `RandomForestRegressor`
* **Hyperparameter Tuning**: `GridSearchCV`
* **Evaluation Metric**: Root Mean Squared Error (RMSE)

---

## 📈 Model Performance

* **Initial RMSE**: \~20.4M
* **After Tuning (GridSearchCV)**: **\~19.98M**
* **Best Parameters**:

  * `n_estimators`: 200
  * `max_depth`: None
  * `min_samples_split`: 2

---

## 📌 Features Implemented

* Exploratory Data Analysis (EDA) with visualization
* Interactive bar chart for filtering by year and quarter using `ipywidgets`
* Time series line plots and box plots by quarter
* Sales prediction using Random Forest Regressor
* Model tuning using GridSearchCV for optimal performance

---

## 📎 How to Run

1. Clone the repository.
2. Ensure all required libraries are installed.
3. Run the notebook or Python file.
4. Use widgets to interactively explore quarterly sales by county.
5. Review model metrics and visualizations for insights.
