# 📊 Customer Churn Prediction in BFSI using Machine Learning

## 🚀 Project Overview

This project focuses on predicting **customer churn** in the Banking, Financial Services, and Insurance (BFSI) sector using machine learning techniques. The goal is to identify customers who are likely to leave the bank based on their financial and behavioral patterns.

Customer retention is a critical challenge in banking, as retaining an existing customer is significantly more cost-effective than acquiring a new one. This project demonstrates how data-driven insights can help banks take proactive actions to reduce churn.

---

## 🎯 Problem Statement

Banks lose a portion of their customers every year due to various reasons such as dissatisfaction, inactivity, or better offers from competitors.

The objective of this project is to build a **complete data science pipeline** to:

* Analyze customer data
* Identify patterns leading to churn
* Predict high-risk customers
* Provide actionable business insights

---

## 📁 Dataset Information

* **Source:** Kaggle – Bank Customer Churn Dataset
* **Records:** 10,000 customers
* **Features:** 11 (after preprocessing)
* **Target Variable:**

  * `Exited = 1` → Customer churned
  * `Exited = 0` → Customer retained

### Key Features:

* Credit Score
* Age
* Balance
* Geography
* Gender
* Number of Products
* IsActiveMember
* Estimated Salary

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Google Colab

---

## 🔄 Project Workflow

1. **Data Loading & Understanding**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing**

   * Encoding categorical variables
   * Feature scaling
   * Handling class imbalance (SMOTE)
4. **Feature Engineering**

   * Balance-to-Salary Ratio
   * Products per Tenure
   * Age Group segmentation
5. **Model Building**

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * Gradient Boosting
6. **Model Evaluation**

   * Accuracy
   * Precision, Recall, F1-score
   * ROC-AUC Curve
7. **Business Insights**

---

## 📈 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~78%     |
| Decision Tree       | ~82%     |
| Random Forest       | ~87%     |
| Gradient Boosting   | ~85%     |

✅ **Best Model:** Random Forest

* Accuracy: ~87%
* ROC-AUC: ~0.91

---

## 📊 Key Insights

* Customers aged **45–60** have the highest churn rate
* **Inactive users** are 2.7× more likely to churn
* Customers with **high balance but low activity** are at high risk
* **Geography** plays a significant role in churn behavior
* Holding more products does not always mean loyalty

---

## 🏦 Real-World Application

Banks can use this model to:

* Identify high-risk customers
* Take proactive retention actions
* Offer personalized services
* Reduce revenue loss

This approach is similar to strategies used by major financial institutions to improve customer retention and engagement.

---

## ⚖️ Ethical Considerations

* Risk of bias based on geography or demographics
* Transparency in AI-based decision-making
* Avoiding unfair treatment of customers

---

## 🧪 Sample Prediction

The model can take a new customer’s data and predict:

* Whether they will churn
* Probability of churn

---

## 📌 Conclusion

This project successfully demonstrates a complete machine learning pipeline applied to a real-world BFSI problem. The model helps transform raw data into meaningful insights that can support business decision-making.

---

## 📚 References

* Kaggle Dataset
* Scikit-learn Documentation
* Imbalanced-learn Documentation
* BFSI Industry Reports

---

## 👨‍💻 Author

Ritesh Dudhbhate
B.Tech IT – BFSI Lab Project
