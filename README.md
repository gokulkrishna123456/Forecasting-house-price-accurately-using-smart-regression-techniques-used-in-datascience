# 🏠 Forecasting House Prices Using Smart Regression Techniques

This project applies data science and machine learning techniques to accurately forecast house prices based on historical data and various influential features. It leverages smart regression models and exploratory data analysis to support informed decision-making in the real estate industry.

---

## 📌 Problem Statement

The goal is to develop a robust and interpretable regression model to predict house prices, considering factors such as location, property characteristics, and market trends.

> **Problem Type**: Regression  
> **Target Variable**: House Price (continuous variable)

---

## 🎯 Objectives

- Build a predictive model that can accurately forecast house prices.
- Identify the most influential features affecting prices.
- Provide actionable insights for stakeholders like homebuyers, sellers, and investors.
- Ensure the model is practical and interpretable.

---

## 🧠 Workflow Overview

1. Data Collection & Description
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Building & Evaluation
6. Visualization of Results
7. Deployment (future enhancement)

---

## 🧾 Dataset Details

- **Source**: Kaggle (e.g., "House Prices: Advanced Regression Techniques")
- **Features**: 80–97 structured features (numerical & categorical)
- **Sample Features**:
  - Living area size
  - Construction year
  - Number of bedrooms/bathrooms
  - Location
  - Garage space
- **Target**: House Price

---

## 🧹 Data Preprocessing

- Handling missing values via imputation
- Encoding categorical variables using LabelEncoder and OneHotEncoder
- Outlier treatment via IQR/Z-score methods
- Feature scaling using StandardScaler/MinMaxScaler
- Removing duplicates and ensuring type consistency

---

## 📊 Exploratory Data Analysis (EDA)

- **Univariate Analysis**: Histograms, boxplots, countplots
- **Bivariate/Multivariate**: Heatmaps, pairplots, scatterplots
- **Insights**:
  - Larger living area = higher price
  - Location and property type strongly affect price

---

## 🛠️ Feature Engineering

- Created new features: price per sq. ft., property age, average room size
- Used binning, polynomial features, and ratios
- Feature selection was guided by domain knowledge and model performance

---

## 🤖 Model Building

### Algorithms Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- TensorFlow Decision Forests (TF-DF)

### Model Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

> **Train/Test Split**: 80/20 using `train_test_split`

---

## 📈 Results & Insights

- Models were evaluated using residual plots and prediction accuracy
- **Feature Importance** revealed:
  - Living area size
  - Number of bedrooms
  - Location
- Random Forest and XGBoost gave the most accurate predictions

---

## 🧰 Tools and Technologies

- **Language**: Python  
- **Notebook**: Google Colab / Jupyter  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`

---

## 👥 Team Members & Contributions

| Name               | Contribution                             |
|--------------------|------------------------------------------|
| **P. Indhira**     | Flowchart, documentation & reporting     |
| **E. Gokul Krishnan** | Data preprocessing, EDA               |
| **M. Mani Maran**  | Feature engineering, model building      |

**college name** : Sri Ramanujar Engineering College

---

## 🔗 Repository Link

[GitHub Repository](https://github.com/gokulkrishna123456/Forecasting-house-price-accurately-using-smart-regression-techniques-used-in-datascience)

---

## 🙏 Acknowledgements

Special thanks to **Sri Ramanujar Engineering College** and the **B.Tech (AI & DS) Department** for their support in completing this project.
