# Linear Regression 2.0 🧮📈

A hands-on Python project demonstrating **linear regression** with real-world datasets. This project helps you understand how input features influence output predictions and how machine learning models can make data-driven forecasts.  

---

## 🔍 Overview

Linear Regression 2.0 explores the relationship between independent variables (features) and dependent variables (targets) using Python.  
This version focuses on multiple datasets to practice regression with **single and multiple features**, including an **electricity billing dataset**.

**Key concepts covered:**
- Simple Linear Regression
- Multiple Linear Regression
- Data preprocessing
- Model evaluation (R², RMSE, MAE)
- Visualization of regression results

---


---


---

## 🗃️ Datasets

### 1. Electricity Billing Dataset (`electricity_bill.csv`)  
Analyze and predict electricity bills. Columns include:

| Column Name            | Description |
|------------------------|-------------|
| `Month`                | Month of the record |
| `Units_Consumed`       | Total electricity units consumed |
| `Fixed_Charge`         | Constant charge applied to customer |
| `Rate_per_Unit`        | Cost per unit of electricity |
| `Peak_Hours_Units`     | Units consumed during peak hours |
| `OffPeak_Hours_Units`  | Units consumed during off-peak hours |
| `Customer_Type`        | Type of customer (Residential/Commercial) |
| `Region`               | Geographical region of customer |
| `Year`                 | Year of record |
| `Bill_Amount`          | Total electricity bill for the month |

This dataset is ideal for predicting `Bill_Amount` using consumption patterns and customer information.

---

## 📈 Sample Visualization

The project includes visualizations to understand patterns and model predictions.  

**Example:** Scatter plot with regression line for electricity billing dataset:

<img width="580" height="432" alt="image" src="https://github.com/user-attachments/assets/7117a7e8-1b85-4305-9950-c1b6f5a6dba8" />


- **X-axis:** Units Consumed  
- **Y-axis:** Bill Amount  
- **Red line:** Predicted Bill Amount from linear regression model

This helps to visually confirm the accuracy of the model and identify trends.
