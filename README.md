# Big_data_project
# Big Data & Machine Learning Project

## 📌 Project Overview

This project is part of a Big Data coursework assignment. It involves setting up a development environment using Docker and applying machine learning techniques on customer data from `store_customers.csv`. The key goal is to predict whether a customer has a high or low salary based on their demographic attributes.

---

## 📁 Dataset

- **File**: `store_customers.csv`
- **Size**: 7,000 entries
- **Features**:
  - `CustomerID`
  - `Age`
  - `Salary`
  - `Gender`
  - `Country`

---

## 🧠 Machine Learning Task

- **Problem Type**: Binary classification (High Salary vs. Low Salary)
- **Algorithm Used**: Random Forest Classifier (Scikit-learn)
- **Target Variable**: `HighSalary` (based on median salary threshold)
- **Features Used**: `Age`, `Gender`, `Country`
- **Performance Metrics**:
  - Accuracy: ~52%
  - Precision: ~55%
  - Recall: ~66%
  - ROC AUC: ~51.8%

---

## 📊 Visualizations

- Confusion Matrix
- ROC Curve
- Feature Importance Bar Chart

---

## 🔧 Environment & Tools

- **Language**: Python
- **Libraries**: Pandas, Scikit-learn, Matplotlib, Seaborn
- **Environment**: Docker (Hadoop/Spark-ready container), Jupyter Notebook

---

## 🔄 Reflection

Challenges faced included:
- Setting up a multi-service Docker environment
- Encoding and processing categorical variables for ML models
- Achieving meaningful accuracy with limited features

---

## ✅ Recommendations

- Include richer features like profession, spending patterns, and education
- Try cloud-native environments like AWS EMR or Databricks for scalability
- Automate container setup using `docker-compose`

---

## ☁️ Environment Comparison

| Environment     | Pros                           | Cons                              |
|----------------|--------------------------------|-----------------------------------|
| Local IDE       | Easy to use, fast for testing  | Not scalable                      |
| Docker          | Portable, reproducible         | Complex to set up initially       |
| Cloud (AWS/GCP) | Scalable, production-ready     | Cost, requires cloud expertise    |

---

## 📬 Contact

For questions or collaboration, feel free to reach out via GitHub or email.
