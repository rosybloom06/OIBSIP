# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project was completed as part of the **OASIS INFOBYTE Data Analytics Internship (Level 2 - Task 1)**.

The objective of this project is to build a **Linear Regression** model capable of predicting house prices based on various property features. The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and interpretation.

---

## 🎯 Objective

Develop a machine learning model to predict house prices using housing features such as:

- Lot Area
- Neighborhood
- Overall Quality
- Year Built
- Garage Features
- Basement Area
- Number of Rooms
- Roof Material
- and many more.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Ames Housing Dataset

The dataset contains **1460 residential properties** with **80 explanatory features** describing different aspects of each house.

Target Variable:

- **SalePrice**

---

## 📊 Project Workflow

### 1. Data Loading
- Loaded the Ames Housing dataset
- Inspected dataset structure
- Checked data types

### 2. Exploratory Data Analysis (EDA)
- Checked missing values
- Generated descriptive statistics
- Visualized the distribution of house prices

### 3. Data Preprocessing
- Filled missing numerical values using Median
- Filled missing categorical values using Mode
- Applied One-Hot Encoding to categorical features

### 4. Feature Selection
Selected all relevant housing features while excluding the target variable.

### 5. Correlation Analysis
- Generated a correlation heatmap
- Identified features strongly correlated with SalePrice

### 6. Model Building
- Train/Test Split (80/20)
- Linear Regression Model

### 7. Model Evaluation
Evaluated the model using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 8. Visualization
- Actual vs Predicted Prices Scatter Plot
- Residual Plot

### 9. Model Interpretation
- Analysed Linear Regression coefficients
- Identified features with the highest positive and negative influence on house prices

---

## 📈 Model Performance

| Metric | Value |
|---------|---------|
| Mean Squared Error (MSE) | 2,628,175,164.32 |
| Root Mean Squared Error (RMSE) | 51,265.73 |
| R² Score | 0.6574 |

The model explains approximately **65.7%** of the variation in house prices.

---

## 📷 Visualizations Included

- Distribution of House Prices
- Correlation Heatmap
- Actual vs Predicted Prices
- Residual Plot

---

## 📁 Project Structure

```
HousePricePrediction/
│
├── task-1.ipynb
├── README.md
└── TrainData.csv
```

---

## 📚 Key Learnings

Through this project, I learned:

- Exploratory Data Analysis (EDA)
- Handling missing values
- Feature Engineering
- One-Hot Encoding
- Linear Regression
- Train-Test Split
- Model Evaluation Metrics
- Residual Analysis
- Feature Importance using Model Coefficients

---

## 🚀 Future Improvements

- Ridge Regression
- Lasso Regression
- Hyperparameter Tuning
- Feature Selection
- Cross Validation
- Ensemble Models (Random Forest, XGBoost)

---

## 👨‍💻 Author

**Rosybloom06**

Project completed as part of the **OASIS INFOBYTE Data Analytics Internship (Level 2 - Task 1).**
