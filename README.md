# 💼 Salary Prediction using Linear Regression

This project demonstrates how to build a **machine learning model** that predicts an employee’s salary based on their years of experience using **Linear Regression**.  
It’s a beginner-friendly project that covers data analysis, visualization, and model evaluation — all in one Jupyter Notebook.

---

## 📘 Project Overview

The goal of this project is to understand how salaries increase with experience and to create a simple **predictive model** using **Supervised Machine Learning**.  
We use the **Linear Regression algorithm** from `scikit-learn` to learn the relationship between **Years of Experience** and **Salary**.

---

## 📂 Dataset

**File:** `Salary_dataset.csv`  
The dataset contains the following columns:
- `YearsExperience` — Number of years an employee has worked.  
- `Salary` — Corresponding salary in USD.

This is a clean dataset with no missing values.

---

## 🧠 Key Concepts Covered

- Data loading and cleaning using **Pandas**
- Data visualization using **Matplotlib** and **Seaborn**
- Building a **Linear Regression model** using `scikit-learn`
- Evaluating model performance using:
  - Mean Squared Error (MSE)
  - R² Score
- Visualizing the **Regression Line** and **Predictions**

---

## ⚙️ Technologies Used

| Category | Tools |
|-----------|-------|
| Language | Python |
| Libraries | NumPy, Pandas, Matplotlib, Seaborn, scikit-learn |
| Environment | Jupyter Notebook |

---

## 📊 Model Workflow

1. **Import Libraries**
2. **Load and Explore Dataset**
3. **Data Visualization**
4. **Split Data into Train & Test Sets**
5. **Train the Linear Regression Model**
6. **Make Predictions**
7. **Evaluate the Model**
8. **Visualize the Regression Line**

---

## 🚀 Results

- The model learns a **strong positive correlation** between experience and salary.
- It can **accurately predict salaries** for new data points.
- Example: Input: 5 years of experience
- Predicted Salary: ≈ ₹75,000
