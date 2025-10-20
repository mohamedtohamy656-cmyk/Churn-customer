# Churn-customer
# 📊 Customer Churn Analysis Dashboard

This project analyzes customer churn data to identify key reasons behind customer loss, based on demographics, contract types, and payment methods.

---

## 🔍 Overview

| Metric | Value |
|:-------|:------|
| Total Customers | 6.69K |
| Churned Customers | 1.796K |
| Churn Rate | 26.9% |
| Average Invoice | $31 |
| Total Charges | $7.247M |
| ARPU | $1.084K |

---

## 🧠 Key Insights

### 1. Churn Reasons
- **46%** left due to **competitors**  
- **16%** due to **attitude or dissatisfaction**  
- **11%** due to **price concerns**  

### 2. Age & Churn
- Higher churn rates among younger customers (<30)  
- Senior group churn is around **45%**

### 3. Contract Type
- **Month-to-Month:** 46.3% churn rate  
- **Yearly:** 6.6% churn rate  

### 4. Payment Method
- **Direct Debit:** 38%  
- **Credit Card:** 20%  
- **Paper Check:** 35%  

---

## 📈 Visualization Examples

Below are key charts generated from the analysis:

### 🧩 Churn Distribution
![Churn Distribution](churn_distribution.png)

### 📊 Churn by Contract Type and Gender
![Churn by Contract](churn_by_contract.png)

### 💳 Churn by Payment Method
![Churn by Payment](churn_by_payment.png)

### 👥 Churn Rate by Age Group
![Churn by Age](churn_by_age.png)

---## 📊 Dashboard Overview
Dashboard1.PNG
The following dashboard shows the main churn metrics and demographic breakdown.
![Dashboard Overview](images/dashboard.png)

![Dashboard Overview](https://github.com/mohamedtohamy656-cmyk/Churn-customer/commit/0adcf8c372c76a342b86cbba6c5bb7b9e154df09)


## ⚙️ Technologies Used
- **Python 3.9+**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## 💾 How to Run

```bash
git clone https://github.com/mohamedtohamy656-cmyk/Customer-Churn-Analysis
cd Customer-Churn-Analysis
pip install -r requirements.txt
python churn_analysis.py
