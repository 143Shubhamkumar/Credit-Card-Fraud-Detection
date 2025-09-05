# Credit-Card-Fraud-Detection

This project applies Machine Learning techniques to detect fraudulent credit card transactions. It uses a highly imbalanced dataset and implements data preprocessing, model training, and evaluation to distinguish between fraudulent and non-fraudulent transactions.

📊 **Dataset**

The dataset contains anonymized credit card transaction data.

Features are numerical and result from PCA transformation to protect user privacy.

**Target variable:**

0 → Legitimate transaction

1 → Fraudulent transaction

⚠️ Since the dataset is highly imbalanced, techniques like resampling or anomaly detection are required.

**Run the cells step by step to:**

Load and preprocess the dataset

Handle imbalanced data

Train classification models

Evaluate performance

**📈 Workflow**

**1.Data Preprocessing**

 • Handle missing values

 • Normalize/scale data

 • Manage class imbalance with SMOTE / undersampling

**2.Exploratory Data Analysis (EDA)**

 • Visualize class distribution

 • Correlation heatmaps

 • Transaction amount analysis

**3.Model Training**

 • Logistic Regression

 • Random Forest

 • Other classifiers (e.g., Decision Tree, Gradient Boosting)

**4.Model Evaluation**

 • Accuracy, Precision, Recall, F1-score

 • ROC-AUC Curve

 • Confusion Matrix Visualization

**🙌 Acknowledgments**

 • Dataset: Kaggle - Credit Card Fraud Detection

 • Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Imbalanced-learn
