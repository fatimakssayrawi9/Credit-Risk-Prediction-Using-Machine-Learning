# Credit-Risk-Prediction-Using-Machine-Learning


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

## 🚀 How to Use This Notebook

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

## 📈 Model Comparison Summary

| Model             | Accuracy | F1-Score (High Risk) | Recall (High Risk) |
|------------------|----------|----------------------|---------------------|
| Decision Tree     | 0.89     | 0.56                 | **0.58**            |
| **Random Forest** | **0.90** | **0.53**             | 0.47                |
| Gradient Boosting | 0.83     | 0.19                 | 0.17                |

> 🔥 **Random Forest** was selected as the final model due to its overall performance and generalization.

---

## 📄 Project Report

You can find the full analysis and methodology in the file:  
📍 `Report.pdf`

It includes:
- Data insights  
- Visualization analysis  
- Justification for using SMOTE  
- Model evaluation with confusion matrices  
- Final recommendation

---

## 🧠 Author

**Fatima Kssayrawi**  
Graduate Student | Oakland University | April 2025

---

## ⭐️ Star this repo if you find it useful!

