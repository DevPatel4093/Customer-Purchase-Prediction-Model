## Customer Purchase Prediction using Decision Tree 🌳 Classifier

Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.

---

## 📌 Project Overview
This project implements a **Decision Tree Classifier** to predict whether a customer will subscribe to a **term deposit** based on their **demographic and behavioral data**.  
The model is built using the **Bank Marketing Dataset** from the UCI Machine Learning Repository.


---

## 📂 Dataset Information
- **Dataset Name:** Bank Marketing Dataset (bank-additional.csv)
- **Source:** UCI Machine Learning Repository  
- **Link:** https://archive.ics.uci.edu/dataset/222/bank+marketing
- **Target Variable:** `deposit`  
  - `yes` → Customer subscribed  
  - `no` → Customer did not subscribe  

---

## 🛠 Technologies Used
- **Python**
- **Libraries:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

---

## ⚙️ Project Workflow
1. Data loading and inspection  
2. Data cleaning and duplicate removal  
3. Exploratory Data Analysis (EDA)  
4. Outlier handling using IQR method  
5. Correlation analysis and feature elimination  
6. Label encoding of categorical features  
7. Train-test split  
8. Decision Tree model training  
9. Model evaluation using accuracy, confusion matrix, and classification report  
10. Decision Tree visualization  

---

## 🌲 Machine Learning Models Used
Two Decision Tree classifiers were implemented:
- **Gini Index based Decision Tree**

Model performance was evaluated using:
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## 📁 Project Structure
```
Customer Purchase Prediction-main/
│── decision-tree-classifier.ipynb
│── bank-additional.csv
└── README.md
```
---

## 👨‍💻 Author
**Dev Patel**
