# Employee-Salary-Prediction

A data-driven approach to forecast whether an individual's annual income surpasses \$50,000 based on demographic and occupational factors. This project leverages the UCI Adult Census dataset to build a robust classification model that aids HR professionals and analysts in informed salary decision-making.

---

## 📌 Objective

To develop and deploy a predictive model that classifies income categories using historical census data. The system uses machine learning to uncover patterns that distinguish higher-income individuals.

---

## 📊 Dataset Overview

- **Dataset Name:** Adult Income Dataset
- **Records:** ~32,000
- **Target Variable:** `income` (`>50K` or `<=50K`)
- **Features Include:**  
  Age, Education, Occupation, Workclass, Marital Status, Hours-per-week, and more.

---

## 🧰 Tools & Technologies

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Streamlit  
- **IDE:** Jupyter Notebook  
- **Deployment:** Streamlit Web App

---

## 🧭 Project Pipeline

1. **Data Acquisition**  
   Load and examine raw census data.

2. **Preprocessing & Cleaning**  
   - Replace invalid entries (`?`) with meaningful labels  
   - Encode categorical features  
   - Detect and eliminate outliers

3. **Exploratory Data Analysis (EDA)**  
   Visualize trends, distributions, and correlations for data insights.

4. **Model Training**  
   Implement and evaluate multiple classification models:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - AdaBoost  
   - Gradient Boosting

5. **Model Selection**  
   Identify the top-performing algorithm based on evaluation metrics.

6. **Deployment**  
   Deploy the final model as an interactive web application using Streamlit.

---

## 🏁 Key Results

| Model               | Accuracy   |
|--------------------|------------|
| Logistic Regression| 77%      |
| Random Forest      | 80%      |
| KNN           | 79%      |
| SVM           | 78%      |
| **Gradient Boosting** | **85.7% ✅** |

> Gradient Boosting was selected as the final model due to its superior performance.

---

## 🌐 Web Application

You can launch the app locally using Streamlit:

```bash
streamlit run app.py
