# TelecomChurnAnalysis

# 📊 Customer Churn Prediction using Machine Learning

This project predicts **which customers are likely to stop using a service (churn)** using machine learning techniques.  
The dataset used is the **Telco Customer Churn dataset**, which contains customer demographics, account information, and service usage patterns.

---

## 🎯 Project Objective
To build a machine learning model that can **predict customer churn**, helping businesses:

- Identify high-risk customers  
- Improve retention strategies  
- Reduce customer acquisition costs  

---

## 📊 Dataset Used
**Telco Customer Churn CSV**  
Public dataset containing:  
- Customer demographics  
- Tenure  
- Internet/phone service details  
- Contract, billing, payment methods  
- Churn (target variable)

Dataset Source:  
`Telco-Customer-Churn.csv`

---

## 🚀 Steps Performed in the Notebook

### **1. Data Loading & Cleaning**
- Handling missing values  
- Converting TotalCharges to numeric  
- Removing customerID column  

### **2. Exploratory Data Analysis (EDA)**
- Churn distribution  
- Tenure vs Churn  
- Contract Type vs Churn  
- Heatmap correlation  

### **3. Data Preprocessing**
- Label encoding categorical variables  
- Train-test split (80/20)  

### **4. Machine Learning Models**
Models implemented:  
- Logistic Regression  
- Random Forest  
- XGBoost (optional)

### **5. Model Evaluation**
Metrics used:  
- Accuracy  
- Precision, Recall, F1-score  
- ROC-AUC  
- Confusion Matrix  

---

## 🖥️ How to Run This Notebook

### **1. Clone this repository**
```bash
git clone https://(https://github.com/preetidhyani92/TelecomChurnAnalysis.git)
cd TelecomChurnAnalysis

---

📌 Conclusions

Customers with month-to-month contracts churn more.

Higher monthly charges correlate with higher churn.

Longer tenure customers rarely churn.

Random Forest gives better performance than Logistic Regression.

---

🤝 Contributions

Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.

---

📜 License

This project is licensed under the MIT License.


