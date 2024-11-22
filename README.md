# 🛡️ **Credit Card Fraud Detection with GBM & XGBoost**

![Python](https://img.shields.io/badge/Python-3.8-blue?logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green?logo=pandas&logoColor=white)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikit-learn&logoColor=white)  
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-red?logo=xgboost&logoColor=white)  
![SHAP](https://img.shields.io/badge/SHAP-Interpretability-lightgrey?logo=shap&logoColor=white)  

---

## 📢 **Welcome to My Project**  
A robust **Credit Card Fraud Detection** system leveraging **Gradient Boosting Machines (GBM)** and **XGBoost**! This project showcases the power of predictive analytics and interpretability tools in combating financial fraud.

---

## 🔍 **Project Overview**  
Fraud detection is a critical need for financial institutions. This project uses a transactional dataset to identify fraudulent activities and builds **high-performance machine learning models** to predict fraud efficiently. Key highlights include:  
- **Data Preparation**: Cleaning and preprocessing transactional data.  
- **Model Development**: Optimizing and comparing GBM and XGBoost models.  
- **Interpretability**: Leveraging **SHAP** to understand model decisions.

---

## 🛠️ **Technologies & Libraries Used**  
- ![Python](https://img.shields.io/badge/Python-3.8-blue?logo=python&logoColor=white)  
- **Pandas**, **NumPy**: For data manipulation and processing.  
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?logo=matplotlib&logoColor=white)  
- **Scikit-Learn**: For machine learning pipelines.  
- ![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-red?logo=xgboost&logoColor=white)  
- **SHAP**: Interpretability for complex models.

---

## 🚀 **How It Works**  
### **1. Data Preparation**  
- Handle missing values and duplicates (e.g., reversed/multi-swipe transactions).  
- Generate features for better fraud prediction.  

### **2. Model Training & Optimization**  
- Implement GBM and XGBoost.  
- Perform hyperparameter tuning to achieve the best performance.  

### **3. Evaluation Metrics**  
- **Precision, Recall, F1-Score**: Assess the ability to detect fraud accurately.  
- **AUC-ROC Curve**: Evaluate the tradeoff between sensitivity and specificity.  

### **4. Interpretability with SHAP**  
- **Beeswarm Plot**: Visualize feature importance.  
- **Waterfall Plot**: Explain individual predictions.  
- **Partial Dependence**: Analyze variable impact.

---

## 📈 **Project Results**  
### **Model Performance**  
| **Model**         | **Precision** | **Recall** | **F1-Score** | **AUC** |  
|--------------------|---------------|------------|--------------|---------|  
| Gradient Boosting  | 0.92          | 0.89       | 0.90         | 0.94    |  
| XGBoost            | 0.94          | 0.91       | 0.92         | 0.96    |  

### **Best Model**: XGBoost, due to superior performance metrics.

---

## 📂 **Directory Structure**  
```bash
Credit_Card_Fraud_Detection/  
├── data/               # Dataset files  
├── notebooks/          # Jupyter notebooks for EDA and modeling  
├── models/             # Trained models (GBM, XGBoost)  
├── visuals/            # SHAP and ROC curve plots  
├── requirements.txt    # Dependencies  
└── README.md           # Project documentation (this file)  
