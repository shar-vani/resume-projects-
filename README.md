# resume-projects-
# Stock Price Analysis & Prediction

## Project Overview

This project focuses on analyzing historical stock market data and building a predictive model to forecast stock prices. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, and regression modeling.

The goal is to understand stock behavior, identify trends, and predict future prices using machine learning techniques.

---

##  Objectives

* Analyze stock price trends over time
* Identify volatility and risk patterns
* Perform feature engineering using date-based attributes
* Build a regression model for price prediction
* Evaluate model performance using appropriate metrics

---

##  Dataset

* Source: Yahoo Finance / Kaggle
* Features:

  * Open, High, Low, Close
  * Adjusted Close
  * Volume
  * Date

---

##  Data Preprocessing

* Converted `Date` column to datetime format
* Extracted:

  * Year
  * Month
  * Day
* Verified no missing values using `df.info()`
* Checked statistical distribution using `df.describe()`

---

##  Exploratory Data Analysis (EDA)

* Visualized stock price trends over time
* Analyzed distribution using skewness
* Identified:

  * Right-skewed data
  * Presence of outliers
  * High volatility

---

##  Feature Engineering

* Created new features:

  * `year`, `month`, `day`
  * `is_quarter_end` (to capture financial cycles)

---

##  Model Building

* Model Used: Linear Regression
* Features used:

  * Open, High, Low, Volume
* Target:

  * Close price

---

##  Model Evaluation

* RMSE (Root Mean Squared Error)
* R² Score

These metrics were used since this is a regression problem.

---

##  Visualization

* Year-wise stock trend analysis
* Subplots for Open, High, Low, Close comparison
* Actual vs Predicted values (model performance)

---

##  Key Insights

* The dataset shows strong positive skewness, indicating extreme high values
* Stock exhibits high volatility over time
* Significant growth observed in later years
* Quarter-end periods may influence price movement

---

##  Technologies Used

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn

---

##  Future Improvements

* Use advanced models (Random Forest, LSTM)
* Add real-time data using APIs
* Build interactive dashboard (Streamlit / Power BI)

---

##  Conclusion

This project demonstrates the application of data analysis and machine learning techniques to understand stock behavior and predict future prices. It highlights the importance of data preprocessing, feature engineering, and proper evaluation in building reliable models.
