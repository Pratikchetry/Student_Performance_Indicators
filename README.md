# 📊 Student Performance Indicator

A complete machine learning pipeline to predict student performance based on factors such as study habits, attendance, parental involvement, and more. The aim is to help educators and policymakers make data-driven decisions to improve student outcomes.

---

## 📂 Project Structure

1. **Understanding the Problem Statement**
2. **Data Collection**
3. **Data Checks to Perform**
4. **Exploratory Data Analysis (EDA)**
5. **Data Pre-Processing**
6. **Model Training**
7. **Choosing the Best Model**

---

## 📝 Problem Statement

The objective of this project is to analyze and predict student exam performance based on various factors, including:

- Hours studied
- Classes attended
- Parental involvement
- Educational resources availability
- Participation in extracurricular activities
- Sleep habits
- Past exam scores
- Motivation level
- Internet access
- Tutoring sessions
- Family income level (Low, Medium, High)
- Teacher quality (Low, Medium, High)
- School type (Public, Private)
- Peer influence (Positive, Neutral, Negative)
- Physical activity (hours per week)
- Presence of learning disabilities
- Parental education level
- Distance to school (Near, Moderate, Far)
- Gender
- Exam score

---

## 📊 Data Collection

The data is sourced from various educational institutes, comprising both structured and unstructured formats, capturing relevant factors affecting student performance.

---

## ✅ Data Checks

The following data checks are performed to ensure data integrity:

- **Missing Data**: Identify and handle missing values.
- **Outliers Detection**: Address outliers to reduce skewness.
- **Data Consistency**: Validate data formats and encoding.
- **Data Distribution**: Examine variable distribution for skewness.

---

## 🔍 Exploratory Data Analysis (EDA)

EDA is performed to understand key relationships and patterns:

- **Correlation Heatmaps**: To show how variables relate to each other.
- **Boxplots/Histograms**: Visualize distributions across categories such as parental involvement, school type, and income level.
- **Scatter Plots**: Explore relationships like study hours vs exam scores, physical activity vs performance, etc.

---

## 🔧 Data Pre-Processing

Preprocessing steps include:

- **Handling Missing Data**: Using statistical methods or domain expertise.
- **Encoding Categorical Variables**: Converting categorical values into numerical formats (e.g., one-hot encoding).
- **Normalization/Standardization**: Scaling numeric features for consistency.
- **Feature Selection**: Identify the most impactful variables using techniques like correlation analysis or model feature importance.

---

## 🤖 Model Training

Several machine learning models are employed:

- **Linear Regression**
- **Decision Trees**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **XGBoost**

Performance metrics used for evaluation:

- Mean Squared Error (MSE)
- R-squared (R²)
- Mean Absolute Error (MAE)

---

## 🏆 Choosing the Best Model

After comparing model performance, the best model is selected based on predictive accuracy and generalizability. Hyperparameter tuning is conducted to optimize the final model.

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries**
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - xgboost
---
