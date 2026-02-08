
# 📊 Customer Churn Prediction & Risk Analysis Engine

This project presents an **end-to-end Machine Learning system** for predicting customer churn in the telecom industry.  
It focuses on **statistical rigor, model interpretability, and business-driven insights**, making it suitable for academic projects, interviews, and ML portfolios.

---

## 🚀 Project Overview

Customer churn is a major challenge for telecom companies. Losing customers directly impacts revenue and increases acquisition costs.

This system predicts **which customers are likely to churn** and highlights the **key risk drivers**, enabling proactive retention strategies.

The solution integrates:
- Statistical hypothesis testing
- Feature engineering
- Supervised machine learning
- Model evaluation and interpretability

---

## 🎯 Objectives

✔ Identify significant churn drivers using statistical tests  
✔ Handle noisy and imbalanced datasets  
✔ Build interpretable machine learning models  
✔ Compare multiple classification algorithms  
✔ Translate predictions into actionable business insights  

---

## 📂 Dataset

**IBM Telco Customer Churn Dataset**

- 7,043 customer records  
- 21 input features  
- Combination of categorical and numerical variables  
- Target variable: `Churn (Yes / No)`

### Feature Categories
- **Demographics:** gender, senior citizen, dependents  
- **Account Information:** tenure, contract type, payment method  
- **Services:** internet service, tech support, streaming services  
- **Financials:** monthly charges, total charges  

---

## ⚙️ Tech Stack

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **SciPy**
- **Matplotlib**
- **Imbalanced-learn (SMOTE)**
- **Jupyter Notebook**

---

## 🔬 Methodology

### 1️⃣ Data Preprocessing
- Missing value treatment
- Label encoding of categorical variables
- Feature scaling using `StandardScaler`
- Train-test split
- Class imbalance handling with **SMOTE**

---

### 2️⃣ Statistical Analysis
- **Chi-Square Test** for categorical features
- **Independent T-Test** for numerical features
- Identification of statistically significant churn drivers

---

### 3️⃣ Machine Learning Models
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**

Models are compared based on performance and interpretability.

---

### 4️⃣ Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Curve

---

### 5️⃣ Model Interpretability
- Logistic Regression coefficient analysis
- Identification of high-risk churn segments
- Business-oriented insights on customer behavior

---

## 📈 Results & Insights

**Logistic Regression** delivered the best overall performance:
- Strong ROC-AUC score
- Balanced precision and recall
- High interpretability for business use

### Key Churn Drivers Identified
- Contract type (month-to-month contracts)
- Short customer tenure
- High monthly charges
- Lack of tech support services

---

## 📂 Project Structure

```
.
├── churn_data.csv
├── Customer_Churn_Prediction.ipynb
├── README.md
```

---

## ▶️ How to Run

1. Clone or download the repository  
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn scipy matplotlib imbalanced-learn
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run `Customer_Churn_Prediction.ipynb` sequentially

---

## 🔮 Future Enhancements

- Tree-based models (Random Forest, XGBoost)
- SHAP / LIME for explainability
- Cost-sensitive learning
- Deployment using Flask / FastAPI
- Real-time churn risk dashboard

---

## 👤 Author

**Mohamed Sabeer**  
Machine Learning & Data Science Enthusiast  

---

## ⭐ Use Case

Ideal for:
- Academic mini & capstone projects
- Telecom analytics case studies
- Machine Learning portfolios
- Interview discussions on classification problems

---

**Feel free to fork, modify, and extend this project!**
