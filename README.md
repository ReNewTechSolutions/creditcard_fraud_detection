📌 Credit Card Fraud Detection using Machine Learning
Project Overview
Developed by ReNewTech Solutions, this project applies Decision Tree and Support Vector Machine (SVM) models to detect fraudulent credit card transactions.

Highly imbalanced dataset (fraud ≈ 0.17% of transactions)

Models evaluated:

Using all 30 original features

Using top 6 features most correlated with fraud

Metrics:

Accuracy

ROC-AUC Score

Confusion Matrix

Precision, Recall, F1-Score

Project Structure
README.md — Project overview and documentation

train_decision_tree.py — Train and evaluate Decision Tree model

train_svm_model.py — Train and evaluate SVM model

top6_feature_training.py — Train models with top 6 selected features

visualize_roc_curves.py — Plot ROC curves for evaluation

requirements.txt — Project dependencies

plots/ — Folder for saved visualization images

Dataset
Source: Credit Card Fraud Detection (Kaggle)

Real-world European card transactions

Strong class imbalance (fraud is rare)

Machine Learning Models
Decision Tree Classifier

Support Vector Machine (SVM) — LinearSVC

Both models evaluated:

On all features

On the top 6 features identified via Pearson correlation

Enhancements Beyond IBM Course
While inspired by the IBM Developer Skills Network (Machine Learning with Python specialization), this project by ReNewTech Solutions adds:

Feature selection using correlation analysis

Reduced-feature model training and evaluation

Clean separation of training scripts for modularity

ROC curve visualizations

Structured project organization for real-world deployment

How to Run
# 1. Clone the repository
git clone https://github.com/ReNewTechSolutions/creditcard_fraud_detection.git
cd creditcard_fraud_detection

# 2. Install dependencies
pip install -r requirements.txt

# 3. Train Decision Tree
python train_decision_tree.py

# 4. Train SVM Model
python train_svm_model.py

# 5. Train models on Top 6 features
python top6_feature_training.py

# 6. Visualize ROC Curves
python visualize_roc_curves.py

Future Improvements
Introduce XGBoost, Random Forest, Gradient Boosting

Apply SMOTE or undersampling for imbalance handling

Implement hyperparameter tuning (GridSearchCV, RandomizedSearchCV)

Explore real-time fraud prediction API deployment

Author
Felicia Goad
ReNewTech Solutions

License
This project is licensed under the MIT License.

Official Tagline
Advanced Fraud Detection for a Safer Digital Future — ReNewTech Solutions 2025

Project Badges



