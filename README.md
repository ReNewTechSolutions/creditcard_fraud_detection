![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![Last Updated](https://img.shields.io/badge/Last%20Updated-April%202025-blueviolet)

[![Download Release](https://img.shields.io/github/v/release/ReNewTechSolutions/creditcard_fraud_detection?label=Download%20Release)](https://github.com/ReNewTechSolutions/creditcard_fraud_detection/releases/latest)
[![GitHub Project](https://img.shields.io/badge/View%20Project-on%20GitHub-blue?logo=github)](https://github.com/ReNewTechSolutions/creditcard_fraud_detection)

Credit Card Fraud Detection using Machine Learning

📌 Project Overview
This project applies Decision Tree and Support Vector Machine (SVM) models to detect fraudulent credit card transactions.
The dataset is highly imbalanced, reflecting real-world fraud detection challenges.

We evaluate model performance:

Using all 30 original features

After applying feature selection to choose the top 6 correlated features

Model metrics include Accuracy, ROC-AUC Score, Confusion Matrix, and Classification Report.

🛠 Project Structure
graphql
Copy
Edit
📁 creditcard_fraud_detection
│── README.md                  # Project documentation
│── train_decision_tree.py      # Decision Tree training and evaluation
│── train_svm_model.py          # SVM model training and evaluation
│── top6_feature_training.py    # Training on top 6 selected features
│── visualize_roc_curves.py     # Visual ROC curve plots
│── requirements.txt            # Required dependencies
│── plots/                      # ROC Curve images and model visualizations
📊 Dataset
Source: Credit Card Fraud Detection dataset on Kaggle

Real-world European card transactions

Imbalanced dataset (fraudulent transactions ≈ 0.17%)

📈 Models Used
Decision Tree Classifier

Support Vector Machine (LinearSVC)

Both evaluated for:

All features

Top 6 correlated features (based on Pearson correlation with the target)

✨ Enhancements from IBM Original Lab
This project was inspired by coursework from the IBM Developer Skills Network (Machine Learning with Python specialization).
However, it was extended and customized by:

Adding feature selection based on correlation analysis.

Evaluating models on the reduced feature set for performance comparison.

Visualizing ROC curves for Decision Tree and SVM models.

All enhancements and restructuring were independently developed to extend learning beyond the course material.

🚀 How to Run This Project
1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/ReNewTechSolutions/creditcard_fraud_detection.git
cd creditcard_fraud_detection
2️⃣ Install dependencies

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
5️⃣ Train and Evaluate Top 6 Features Only

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
Experiment with XGBoost, Random Forest, and Gradient Boosting models.

Handle imbalance with SMOTE or undersampling techniques.

Hyperparameter tuning with GridSearchCV or RandomizedSearchCV.

📌 Author
Felicia Goad, ReNewTech Solutions
MIT License

🔗 Official Tagline:

"Advanced Fraud Detection for a Safer Digital Future — ReNewTech Solutions 2025."

