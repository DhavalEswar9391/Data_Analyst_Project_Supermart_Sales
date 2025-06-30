# Data_Analyst_Project_Supermart_Sales
# 🛒 Supermart Grocery Sales Prediction - Retail Analytics Project

This project analyzes a fictional retail dataset from a grocery delivery app and builds a machine learning model to predict sales using linear regression.

## 📌 Project Overview

The objective of this project is to:
- Understand sales patterns across categories, cities, and time
- Perform data preprocessing and feature engineering
- Visualize sales trends
- Build and evaluate a linear regression model to predict future sales

---

## 📁 Dataset

- **Name**: Supermart Grocery Sales - Retail Analytics Dataset
- **Source**: Provided via project description (Fictional Dataset)
- **Content**: Order ID, Customer Name, Category, Sub Category, City, Region, State, Order Date, Sales, Discount, Profit, Month, Year

---

## 📊 Technologies & Tools

- **Language**: Python
- **Libraries**: 
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for ML modeling

---

## 🚀 Steps Performed

1. **Data Cleaning**
   - Removed duplicates and missing values
   - Converted order dates to datetime format
   - Extracted month, year, day

2. **EDA (Exploratory Data Analysis)**
   - Sales by category, time, and region
   - Correlation analysis via heatmap

3. **Feature Engineering**
   - Encoded categorical columns
   - Extracted time-based features

4. **Model Building**
   - Linear Regression using `scikit-learn`
   - Feature scaling with `StandardScaler`
   - Evaluation using Mean Squared Error and R² Score

5. **Visualization**
   - Actual vs Predicted sales

---

## 📈 Results

- ✅ Model trained using Linear Regression
- ✅ Evaluation Metrics:
  - **R² Score**: _0.82_ _(example)_
  - **MSE**: _1758.26_ _(example)_

---

## 📌 Future Work

- Try advanced models like Random Forest, XGBoost
- Build a Streamlit app or Power BI dashboard
- Add hyperparameter tuning and cross-validation

---

## 🙋‍♂️ Author

**Ankit Roy**  
*Aspiring Data Analyst | Python & ML Enthusiast*  
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

---

## 📎 License

This project is for educational purposes only. Dataset is fictional.
