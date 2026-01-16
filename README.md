# Customer Churn Analysis using Machine Learning 📊🤖

## 📌 Project Overview
This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave a service so that businesses can take proactive retention actions. Logistic Regression is used as the primary classification model.

---

## 📂 Dataset
- Customer churn dataset containing demographic, usage, and billing-related information.
- Key features include:
  - Age
  - Tenure
  - Usage Frequency
  - Support Calls
  - Payment Delay
  - Total Spend
  - Subscription and Contract details
- Target variable:
  - **Churn** (0 = No churn, 1 = Churn)

---

## 🛠️ Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  
- Git & GitHub  
- Miniconda  

---

## 🔍 Steps Performed
1. Loaded and explored the customer churn dataset.
2. Performed data cleaning and checked for missing values.
3. Encoded categorical variables using one-hot encoding.
4. Split data into training and testing sets.
5. Trained a Logistic Regression model.
6. Evaluated the model using:
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-score
7. Interpreted results from a business perspective.

---

## 📈 Model Performance
- **Accuracy:** ~83%
- **Recall for Churn Customers:** ~84%
- The model effectively identifies customers at risk of churn, which is crucial for retention strategies.

---

## 💡 Key Insights
- Customers with frequent support calls and payment delays are more likely to churn.
- High recall ensures fewer churn customers are missed.
- Logistic Regression provides a good balance between performance and interpretability.

---

## ▶️ How to Run This Project

1. Open Anaconda Prompt (Miniconda)
2. Clone the repository:
