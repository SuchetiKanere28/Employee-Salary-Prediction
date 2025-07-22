# Employee-Salary-Prediction
# Employee Salary Prediction 🧠💼

This project aims to predict whether an individual earns more than \$50K per year based on demographic and occupational attributes from the UCI Adult Census dataset. The model helps in understanding income patterns and supports HR decisions in salary assessment and workforce planning.

## 🔍 Problem Statement

Develop a machine learning model to classify whether an individual's income exceeds \$50,000 annually. The dataset includes features such as age, gender, education, workclass, occupation, and hours worked per week.

---

## 📁 Dataset

- **Source:** UCI Machine Learning Repository  
- **File Used:** `adult.csv`  
- **Target Variable:** `income` (binary: `<=50K` or `>50K`)

---

## ⚙️ Technologies Used

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit  
- **IDE:** Jupyter Notebook

---

## 🔄 Workflow

1. **Data Loading**  
   Load and inspect the dataset for structure and completeness.

2. **Data Preprocessing**  
   - Handle missing values (replace `?` with 'Other')  
   - Label encode categorical variables  
   - Detect and remove outliers

3. **Exploratory Data Analysis (EDA)**  
   Visualize distributions and relationships between variables.

4. **Model Building**  
   Train and evaluate multiple classification algorithms:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - AdaBoost  
   - Gradient Boosting

5. **Model Evaluation**  
   Use accuracy, precision, recall, and F1-score for evaluation.

6. **Model Deployment**  
   Deploy the best-performing model (Gradient Boosting with 85.7% accuracy) using Streamlit.

---

## 📊 Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 81.6%    |
| Decision Tree       | 84.0%    |
| Random Forest       | 84.3%    |
| AdaBoost            | 85.1%    |
| **Gradient Boosting** | **85.7%** ✅ |

---

## 🚀 Deployment

Run the Streamlit web app locally:

```bash
streamlit run app.py
