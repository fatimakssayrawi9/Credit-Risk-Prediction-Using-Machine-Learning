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


## 📦 How to Use This Notebook (Demo_Credit_Risk_Prediction.ipynb)

## 📂 Project Setup Instructions

To run this notebook correctly, please make sure to **upload the following files** before execution:

1. **Training Data.csv**  
   → This is the original training dataset used for building the model.  
   📌 It's required to **generate city/state mappings** and perform preprocessing steps such as feature analysis or re-encoding.  
   📁 This file is located in the project repository.

2. **random_forest_model.pkl**  
   → This file contains the trained Random Forest model.  
   🔗 Download it from Google Drive: [Click Here](https://drive.google.com/file/d/1RBZA9K3C8uHZ269RJe1aciK2PU8bs29c/view?usp=drive_link)

3. **scaler.pkl**  
   → This is the fitted `StandardScaler` used during training to standardize numeric features.  
   📁 This file is located in the project repository.

4. **model_columns.pkl**  
   → This contains the list of encoded feature columns used by the model for prediction.  
   📁 This file is also located in the project repository.

> ⚠️ Be sure to upload all four files **before running any prediction or deployment steps**.
> The training dataset is especially important for generating the **city and state mappings** used to interpret user input.



---
## 📈 Model Comparison Summary

| Model             | Accuracy | Precision | F1-Score (High Risk) | Recall (High Risk) |
|------------------|----------|----------------------|---------------------|---------------|
| Decision Tree     | 0.89     | 0.92       | 0.93          |0.93           |
| **Random Forest** | **0.90** | **0.93**             | **0.96**         | **0.94**       |
| Gradient Boosting | 0.83     | 0.89                 | 0.72                | 0.80 |

> 🔥 **Random Forest** was selected as the final model due to its overall performance and generalization.

---

## 📄 Project Report

You can find the full analysis and methodology in the file:  
📍 `Final Report-Credit Risk Prediction-Fatima Kssayrawi.pdf`

This report presents the full development lifecycle of a credit risk prediction system using machine learning. It includes a detailed explanation of the problem, related work, dataset characteristics, data preprocessing steps, model training, performance evaluation, and model deployment. Through the use of Decision Tree, Random Forest, and Gradient Boosting algorithms, the study aims to identify high-risk borrowers accurately and interpretably. The report also discusses class imbalance handling with SMOTE, visualization of results through confusion matrices, and concludes with a practical deployment strategy for real-time predictions.

---


## 📄 Project Presentation

You can find the full analysis and methodology in the file:  
📍 `Artificial_Intelligence_Project__Fatima_Kssayrawi_Final_Version.pdf`

This presentation showcases a complete machine learning pipeline for predicting credit risk based on borrower data. It includes:
1. An overview of the credit risk problem and its importance in finance
2. Technical challenges and traditional methods
3. A detailed breakdown of our machine learning approach including preprocessing, feature engineering, model selection, and evaluation
4. A visual comparison of classifiers (Random Forest, Decision Tree, Gradient Boosting)
5. Deployment strategy using a Streamlit web application for real-time predictions

---

## 🧠 Author

**Fatima Kssayrawi**  
Graduate Student | Oakland University | April 2025

---

## ⭐️ Star this repo if you find it useful!

