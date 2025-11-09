# Customer Churn Prediction — Case Study

## 🎯 Objective
To develop, validate, and deploy a predictive model to identify customers likely to churn using real-world telecom data.

---

## 🧠 Overview
This repository contains all resources related to the Customer Churn Prediction Case Study.  
It follows the SRM University assignment rubric covering:
1. Data Preparation & EDA  
2. CHAID-like Model (Decision Tree using entropy)  
3. Logistic Regression Model  
4. Model Evaluation (Accuracy, ROC-AUC, Lift, Gains)  
5. Model Deployment (Pickle)  

---

## 🧩 Tools & Technologies
- Python 3.x  
- Libraries: pandas, numpy, scikit-learn, matplotlib  
- Jupyter Notebook / Google Colab  
- GitHub for version control

---

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Customer-Churn-Prediction.git
   ```
2. Place the dataset file (`Telco-Customer-Churn.csv`) in the `/data` folder.
3. Open the notebook:
   ```bash
   jupyter notebook notebooks/Churn_Case_Study.ipynb
   ```
4. Run all cells to train models and generate outputs.

---

## 📊 Evaluation Metrics
| Metric | Description |
|---------|--------------|
| Accuracy | Overall model correctness |
| ROC-AUC | Model's discriminative power |
| Precision/Recall | Churn identification performance |
| Lift/Gains | Marketing & retention performance indicator |

---

## 🚀 Deployment
Models are serialized with **Pickle** and can be integrated into applications or dashboards.  
Future model updates can be automated with a retraining pipeline using new customer data.

---

## 🧾 License
This project is for **academic use** as part of SRM University coursework.

---
