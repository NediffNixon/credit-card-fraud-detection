# 💳 Credit Card Fraud Detection with Imbalanced Classification

This project focuses on detecting fraudulent credit card transactions using supervised learning. It demonstrates a complete machine learning pipeline for **imbalanced classification problems**, showcasing practical techniques to improve model performance in real-world fraud detection scenarios.

---

## 🧠 Project Highlights

- Addressed **high class imbalance** with a combination of **upsampling** (for minority class) and **downsampling** (for majority class).
- Trained and compared:
  - **Random Forest**
  - **XGBoost Classifier**
- Used **Optuna** for hyperparameter tuning to optimize model performance.
- Prioritized **false negative minimization**, as missing a fraud case is more costly than flagging a legitimate one.

---

## ⚙️ Pipeline Overview

1. **Data Preprocessing**
   - Feature scaling and train-test split
   - Resampling to handle class imbalance
2. **Model Training**
   - Random Forest and XGBoost classifiers
   - Evaluation using Precision, Recall, F1 Score
3. **Hyperparameter Optimization**
   - Performed using Optuna
4. **Evaluation**
   - Focused on **recall and F1 score** for fraud class
   - Discussed **business cost of false negatives vs. false positives**

---

## 🛠️ Technologies Used
Python

scikit-learn

imbalanced-learn (SMOTE)

## 📄 License
This project is licensed under the MIT License.
