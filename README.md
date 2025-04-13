# Credit Card Fraud Detection using Machine Learning  
Developed by **ReNewTech Solutions**, this project applies Decision Tree and Support Vector Machine (SVM) models to detect fraudulent credit card transactions.

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![Last Updated](https://img.shields.io/badge/Last%20Updated-April%202025-blueviolet)
[![Download Release](https://img.shields.io/github/v/release/ReNewTechSolutions/creditcard_fraud_detection?label=Download%20Release)](https://github.com/ReNewTechSolutions/creditcard_fraud_detection/releases/latest)
[![GitHub Project](https://img.shields.io/badge/View%20Project-on%20GitHub-blue?logo=github)](https://github.com/ReNewTechSolutions/creditcard_fraud_detection)

---

## 📌 Project Overview
This project tackles the challenge of detecting credit card fraud using machine learning models on a highly imbalanced dataset (fraud ≈ **0.17%** of transactions).

**Models Evaluated:**
- Using **all 30 original features**
- Using **top 6 features most correlated** with fraud

**Metrics Evaluated:**
- Accuracy
- ROC-AUC Score
- Confusion Matrix
- Precision, Recall, F1-Score

---

## 🛠 Project Structure

```plaintext
creditcard_fraud_detection/
│── README.md                  # Project overview and documentation
│── requirements.txt            # Required Python libraries
│── train_decision_tree.py       # Train and evaluate Decision Tree model
│── train_svm_model.py           # Train and evaluate SVM model
│── top6_feature_training.py     # Train models using top 6 features
│── visualize_roc_curves.py      # Plot and compare ROC curves
│── plots/                      # ROC curve images and visualizations
📊 Dataset
Source: Credit Card Fraud Detection dataset from Kaggle

Details: Real-world European card transactions

Challenge: Highly imbalanced (only ~0.17% are fraudulent)

📈 Models Used
Decision Tree Classifier

Support Vector Machine (LinearSVC)

Both models were evaluated for:

Full feature set

Top 6 selected features

✨ Enhancements Beyond IBM Course
This project was inspired by coursework from the IBM Developer Skills Network (Machine Learning with Python specialization).

Enhancements made by ReNewTech Solutions:

Added feature selection based on correlation analysis

Trained and compared models on reduced feature sets

Visualized ROC curves for performance insights

Reorganized project structure and documentation

All code restructuring and upgrades were independently developed to deepen practical understanding.

🚀 How to Run This Project
1️⃣ Clone the Repository

bash
Copy
Edit
git clone https://github.com/ReNewTechSolutions/creditcard_fraud_detection.git
cd creditcard_fraud_detection
2️⃣ Install Required Libraries

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Train Decision Tree Model

bash
Copy
Edit
python train_decision_tree.py
4️⃣ Train SVM Model

bash
Copy
Edit
python train_svm_model.py
5️⃣ Train and Evaluate on Top 6 Features

bash
Copy
Edit
python top6_feature_training.py
6️⃣ Visualize ROC Curves

bash
Copy
Edit
python visualize_roc_curves.py
🛠 Future Improvements
Experiment with XGBoost, Random Forest, and Gradient Boosting

Address class imbalance with SMOTE or undersampling

Apply hyperparameter tuning (GridSearchCV, RandomizedSearchCV)

📌 Author
Felicia Goad, ReNewTech Solutions

📜 License
MIT License

🔥 Official Tagline:
Advanced Fraud Detection for a Safer Digital Future — ReNewTech Solutions 2025.
