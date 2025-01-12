# FYP
# Fraud Detection Using Machine Learning

This project demonstrates the implementation of various machine learning models to detect fraudulent transactions from an imbalanced dataset.

---

## Key Features:
1. **Data Preprocessing**:
   - Loaded and converted `.arff` file to a DataFrame.
   - Checked for missing values and descriptive statistics.
   - Selected important features (`V1` to `V28` and `Amount`).

2. **Visualization**:
   - Used Seaborn boxplots and stripplots to analyze feature distributions by class.

3. **Handling Imbalance**:
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)** to address class imbalance in the dataset.

4. **Models Implemented**:
   - **Random Forest**: Evaluated with regression and classification metrics.
   - **Support Vector Machine (SVM)**: Used standard scaling for improved performance.
   - **XGBoost**: Applied to binary classification with log loss as the evaluation metric.

5. **Evaluation Metrics**:
   - Classification Report (Precision, Recall, F1-score).
   - Confusion Matrix.
   - Regression metrics for Random Forest (MSE, MAE, R²).

---

## Libraries Used:
- `pandas`
- `scikit-learn`
- `scipy`
- `matplotlib`
- `seaborn`
- `xgboost`
- `imblearn`

---

## How to Use:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git

