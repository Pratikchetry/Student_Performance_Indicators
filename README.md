
# 📊 Student Performance Indicator

**Life cycle of Machine Learning Project**

This project aims to build a model that predicts student performance (exam scores) based on various factors such as study habits, attendance, parental involvement, and more. By understanding how these factors contribute to academic success, educators and policymakers can take actionable steps to improve student outcomes.

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

The goal of this project is to analyze how various factors influence student performance in exams. The model aims to predict exam scores based on the following variables:

- **Hours studied**
- **Classes attended**
- **Parental involvement**
- **Availability of educational resources**
- **Participation in extracurricular activities**
- **Average hours of sleep per night**
- **Scores from previous exams**
- **Level of motivation**
- **Internet access**
- **Tutoring sessions attended per month**
- **Family income level** (Low, Medium, High)
- **Quality of teachers** (Low, Medium, High)
- **School type** (Public, Private)
- **Influence of peers on academic performance** (Positive, Neutral, Negative)
- **Physical activity per week** (in hours)
- **Presence of learning disabilities**
- **Parental education level**
- **Distance from home to school** (Near, Moderate, Far)
- **Gender**
- **Exam score**

---

## 📊 Data Collection

Data is collected from various educational institutes that track students’ performance along with the mentioned factors. This includes both structured and unstructured data sources.

---

## ✅ Data Checks to Perform

Before moving to model training, the following checks are performed on the dataset:

- **Missing Data:** Identify and handle missing values.
- **Outliers Detection:** Remove or transform outliers to avoid model skewness.
- **Data Consistency:** Ensure all values are in an appropriate format (e.g., categorical values encoded correctly).
- **Data Distribution:** Check the distribution of each variable to detect any skewness.

---

## 🔍 Exploratory Data Analysis (EDA)

EDA is conducted to understand the relationships and distributions between various factors and exam scores. Key visualizations and insights include:

- Correlation heatmaps to understand how variables relate.
- Boxplots and histograms to analyze the distribution of scores based on categories like school type, parental involvement, and income levels.
- Scatter plots to explore relationships like study hours vs. exam scores, or physical activity vs. performance.

---

## 🔧 Data Pre-Processing

The following preprocessing steps are performed before feeding the data into the model:

1. **Handling Missing Data**: Imputing missing values based on statistical methods or domain knowledge.
2. **Encoding Categorical Variables**: Converting categories like "Family Income Level" and "School Type" into numerical formats using techniques like one-hot encoding.
3. **Normalization/Standardization**: Scaling numeric features to ensure consistent ranges.
4. **Feature Selection**: Selecting important features that impact the target variable using techniques like correlation analysis or feature importance from models.

---

## 🤖 Model Training

Several machine learning algorithms are explored to predict student performance, including but not limited to:

- **Linear Regression**
- **Decision Trees**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **XGBoost**

Each model is evaluated using appropriate performance metrics such as:

- **Mean Squared Error (MSE)**
- **R-squared (R²)**
- **Mean Absolute Error (MAE)**

---

## 🏆 Choosing the Best Model

After training, the models are compared based on their predictive performance. The model with the highest accuracy and generalizability is chosen as the final model. Additionally, hyperparameter tuning is performed to further optimize the best-performing model.

---

## 🚀 Getting Started

To get started with this project, follow these steps:

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`

### Installation

Clone this repository:

```bash
git clone https://github.com/your-username/Student-Performance-Indicator.git
cd Student-Performance-Indicator
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

### Usage

Run the notebooks to follow along with the model-building process:

```bash
jupyter notebook
```

---

## 📈 Results and Analysis

The final model shows that factors such as hours studied, classes attended, and parental involvement have a significant impact on student performance, while factors like physical activity and peer influence show a weaker correlation.

---

## 💡 Future Work

- Incorporating more sophisticated models like neural networks.
- Collecting real-time data to track student performance over time.
- Implementing a web-based dashboard to visualize student performance trends for educators.

---
