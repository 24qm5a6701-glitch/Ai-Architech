
# 🚀 ClaimGuard AI  
## Intelligent Insurance Fraud Risk Scoring System

ClaimGuard AI is a Machine Learning-powered web application that predicts the probability of fraud in insurance claims and assigns a risk category (Low / Medium / High).

This system helps insurance companies detect potentially fraudulent claims in real-time and prioritize high-risk cases for investigation.

---

## 📌 Problem Statement

Insurance companies face major financial losses due to fraudulent claims. Manual verification is:

- Time-consuming  
- Expensive  
- Not scalable  

ClaimGuard AI solves this problem using Machine Learning to automatically assess fraud risk.

---

## 🧠 Features

- Fraud probability prediction (0–100%)
- Risk categorization (Low / Medium / High)
- SMOTE-based imbalance handling
- Random Forest classification
- Real-time prediction using Flask
- Clean and professional web interface

---

## 🏗️ Project Architecture

1. Data Generation & Preprocessing  
2. Train-Test Split  
3. SMOTE for Imbalanced Data  
4. Feature Scaling (StandardScaler)  
5. Random Forest Model Training  
6. Model Serialization (Pickle)  
7. Flask Web Deployment  

---

## 🛠️ Technology Stack

### Programming Language
- Python

### Data Processing
- Pandas
- NumPy

### Machine Learning
- Scikit-learn
- Random Forest Classifier
- SMOTE
- StandardScaler

### Deployment
- Flask
- HTML
- CSS

---

## 📂 Project Structure

ClaimGuard_AI_WebApp/
│
├── app.py
├── claimguard_ai_model.pkl
├── claimguard_ai_scaler.pkl
│
├── templates/
│     └── index.html
│
└── static/
      └── style.css

---

## 🚀 How To Run The Project

### 1️⃣ Install Dependencies

pip install flask pandas numpy scikit-learn imbalanced-learn

### 2️⃣ Run Application

python app.py

### 3️⃣ Open Browser

http://127.0.0.1:5000

---

## 🧪 Example Test Case (High Risk)

Age: 22  
Months as Customer: 2  
Annual Premium: 4000  
Total Claim Amount: 95000  
Incident Severity: 3  
Vehicles: 3  
Bodily Injuries: 2  
Witnesses: 0  

Expected Output:
- High Fraud Probability  
- HIGH RISK  

---

## 📊 Business Impact

- Reduces fraudulent claim payouts  
- Improves claim processing speed  
- Enhances operational efficiency  
- Supports data-driven decision making  

---

## 🌍 Social Impact

- Protects genuine customers  
- Prevents misuse of insurance systems  
- Builds trust in digital insurance platforms  

---

## 👨‍💻 Developed By

Prashanth  
Koushik
Narender
B.Tech – Computer Science (Data Science)

---

⭐ If you found this project useful, consider giving it a star!
