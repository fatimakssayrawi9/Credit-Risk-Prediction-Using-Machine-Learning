# Credit-Risk-Prediction-Using-Machine-Learning

---

This project builds a machine learning pipeline to predict whether a borrower is **high risk (1)** or **low risk (0)** for loan default. It leverages decision trees, random forests, and gradient boosting classifiers to improve the accuracy of credit risk classification.


---

## 📊 Dataset Descriptions

### 📌 `Training Data.csv`
- Contains **252,000** labeled entries used to train the models.
- Features include borrower’s demographic and financial attributes.
- Target column: `risk_flag` → `1` (high risk) or `0` (low risk).

### 📌 `Test Data.csv`
- Contains **unlabeled borrower entries** (same features).
- Used to test the trained model in real-world deployment scenarios.

---

## 🚀 How to Use This Notebook (Credit_Risk_Prediction_Using_Machine_Learning.ipynb)

1. Upload both datasets into the notebook environment (`Training Data.csv`, `Test Data.csv`).
2. Open and run all cells in the notebook `Credit_Risk_Prediction.ipynb`.
3. The pipeline includes:
   - Data cleaning & visualization
   - SMOTE class balancing
   - Feature scaling
   - Model training & comparison
   - Final prediction function + interactive user input
4. After execution, model and preprocessing artifacts are saved for deployment.

---


## 📦 How to Use This Notebook (Demo.ipynb)

## 📂 Project Setup Instructions

To run this notebook correctly, please make sure to **upload the following three files** before execution:

1. **random_forest_model.pkl**  
   → This file contains the trained Random Forest model.  
   🔗 Download it from your Google Drive: [Click Here]([YOUR_GOOGLE_DRIVE_LINK_HERE](https://drive.google.com/file/d/1RBZA9K3C8uHZ269RJe1aciK2PU8bs29c/view?usp=drive_link))

2. **scaler.pkl**  
   → This is the fitted `StandardScaler` used during training.  
   📁 This file is located in the project repository.

3. **model_columns.pkl**  
   → This contains the list of encoded feature column names used by the model.  
   📁 This file is also located in the project repository.

> ⚠️ Make sure to upload all three files before running the prediction or deployment cells.


---
## 📈 Model Comparison Summary

| Model             | Accuracy | Precision | F1-Score (High Risk) | Recall (High Risk) |
|------------------|----------|----------------------|---------------------|---------------|
| Decision Tree     | 0.89     | 0.92       | 0.93          |0.93           |
| **Random Forest** | **0.90** | **0.93**             | **0.96**         | **0.94**       |
| Gradient Boosting | 0.83     | 0.80                 | 0.89                |

> 🔥 **Random Forest** was selected as the final model due to its overall performance and generalization.

---

## 📄 Project Report

You can find the full analysis and methodology in the file:  
📍 `Final Report-Credit Risk Prediction-Fatima Kssayrawi.pdf`

This report presents the full development lifecycle of a credit risk prediction system using machine learning. It includes a detailed explanation of the problem, related work, dataset characteristics, data preprocessing steps, model training, performance evaluation, and model deployment. Through the use of Decision Tree, Random Forest, and Gradient Boosting algorithms, the study aims to identify high-risk borrowers accurately and interpretably. The report also discusses class imbalance handling with SMOTE, visualization of results through confusion matrices, and concludes with a practical deployment strategy for real-time predictions.

---

## 🧠 Author

**Fatima Kssayrawi**  
Graduate Student | Oakland University | April 2025

---

## ⭐️ Star this repo if you find it useful!

