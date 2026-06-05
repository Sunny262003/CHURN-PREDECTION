# CHURN-PREDECTION
# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a service based on historical customer data. Customer retention is a critical challenge for businesses, and identifying customers at risk of leaving helps organizations take proactive measures to improve customer satisfaction and reduce revenue loss.

This project uses classification algorithms to analyze customer behavior, identify churn patterns, and predict future customer attrition.

---

# 🎯 Objectives

* Predict whether a customer will churn or remain with the company.
* Analyze customer behavior and service usage patterns.
* Identify the key factors influencing customer churn.
* Build and evaluate classification models.
* Support business decision-making through predictive analytics.

---

# 📂 Dataset

### Dataset Name

Telco Customer Churn Dataset

### Description

The dataset contains customer demographic information, account details, subscribed services, billing information, and churn status.

### Features Include

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Online Security
* Tech Support
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges

### Target Variable

| Variable | Description                               |
| -------- | ----------------------------------------- |
| Churn    | Yes = Customer Left, No = Customer Stayed |

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Machine Learning
* Data Visualization

---

# 🔄 Project Workflow

## 1. Data Collection

* Load customer churn dataset.
* Understand dataset structure and features.

## 2. Data Preprocessing

* Handle missing values.
* Remove irrelevant columns.
* Convert categorical variables into numerical format.
* Prepare data for machine learning.

## 3. Exploratory Data Analysis (EDA)

Analyze:

* Customer demographics
* Service subscriptions
* Billing patterns
* Churn distribution

Visualizations help identify important churn trends.

## 4. Feature Engineering

* Encode categorical features.
* Create machine-learning-ready datasets.

## 5. Train-Test Split

Split data into:

* Training Set (80%)
* Testing Set (20%)

## 6. Model Training

Train classification models such as:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

## 7. Model Evaluation

Evaluate model performance using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## 8. Feature Importance Analysis

Identify the most influential factors contributing to customer churn.

---

# 🤖 Machine Learning Algorithms

## Logistic Regression

Advantages:

* Simple and interpretable
* Fast training
* Good baseline model

## Decision Tree

Advantages:

* Easy to visualize
* Captures non-linear relationships

## Random Forest

Advantages:

* High accuracy
* Handles complex datasets
* Reduces overfitting

## Support Vector Machine (SVM)

Advantages:

* Effective for classification tasks
* Strong generalization capability

---

# 📊 Evaluation Metrics

| Metric           | Description                           |
| ---------------- | ------------------------------------- |
| Accuracy         | Overall prediction correctness        |
| Precision        | Accuracy of churn predictions         |
| Recall           | Ability to identify churned customers |
| F1 Score         | Balance between Precision and Recall  |
| Confusion Matrix | Visualization of predictions          |

---

# 📈 Results

Typical model performance on the Telco Customer Churn Dataset:

| Model               | Accuracy  |
| ------------------- | --------- |
| Logistic Regression | 80% - 83% |
| Decision Tree       | 75% - 80% |
| Random Forest       | 82% - 86% |
| SVM                 | 83% - 87% |

Random Forest and SVM generally provide the best performance.

---

# 🔍 Key Factors Influencing Churn

Feature importance analysis often reveals the following major churn drivers:

* Contract Type
* Tenure
* Monthly Charges
* Total Charges
* Internet Service
* Online Security
* Tech Support
* Payment Method

These insights help businesses design customer retention strategies.

---

# 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
│
├── models/
│   └── churn_model.pkl
│
├── images/
│   ├── churn_distribution.png
│   ├── feature_importance.png
│   └── confusion_matrix.png
│
├── README.md
│
└── requirements.txt
```

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Move into the project directory:

```bash
cd Customer-Churn-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🚀 Running the Project

```bash
python churn_prediction.py
```

---

# 📉 Business Impact

This project enables organizations to:

* Improve customer retention.
* Reduce customer acquisition costs.
* Identify high-risk customers.
* Develop personalized retention campaigns.
* Increase long-term revenue.

---

# 🔮 Future Enhancements

* Hyperparameter tuning
* XGBoost and LightGBM models
* Deep Learning approaches
* Real-time churn prediction dashboard
* Deployment using Flask or Streamlit
* Automated customer retention recommendations

---

# 💡 Key Learnings

* Data preprocessing techniques
* Exploratory Data Analysis (EDA)
* Feature engineering
* Classification algorithms
* Model evaluation
* Business analytics using machine learning

---

# 📜 Conclusion

The Customer Churn Prediction project demonstrates how Machine Learning can be used to identify customers who are likely to leave a service. By analyzing customer behavior and service usage patterns, the model helps businesses make data-driven decisions, improve customer retention, and increase profitability. The project highlights the practical application of classification techniques in solving real-world business problems.

---

# 👨‍💻 Author

KOTTURU SANMITHA CHOWDARY



GitHub: https://github.com/your-username
