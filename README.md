# 🌳 Decision Tree Loan Prediction

This project uses a **Decision Tree Classifier** to predict whether a loan will be **approved** or **defaulted** based on applicant information. It's a classification-based machine learning model trained on bank loan data and helps financial institutions make data-driven lending decisions.

---

## 🎯 Objective

- Predict loan outcome: **Good Loan** vs **Bad Loan**
- Identify key features affecting loan decisions
- Help banks reduce risk by targeting reliable customers
- Visualize decision logic using a Decision Tree

---

## 🧾 Dataset Overview

- **Source**: Kaggle / UCI Repository / Synthetic data
- **File**: `loan_data.csv`
- **Rows**: ~10,000 loan records
- **Columns**:  
  - `age`, `income`, `credit_score`, `loan_amount`  
  - `employment_status`, `education_level`, `loan_purpose`  
  - `loan_status` → Target (`0`: Bad, `1`: Good)

📥 Example dataset:  
[https://www.kaggle.com/datasets/itsmesunil/bank-loan-modelling](https://www.kaggle.com/datasets/itsmesunil/bank-loan-modelling)

---

## ⚙️ Tools & Technologies

- Python 3.x
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook or VS Code

---

## 🔁 Workflow

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features
   - Normalize numeric columns (optional)

2. **Model Training**
   - Split data into train/test sets
   - Train a `DecisionTreeClassifier`
   - Visualize the decision tree structure

3. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC Curve

4. **Prediction**
   - Predict loan approval for new applicants
   - Export model using `joblib` or `pickle` (optional)

---

## ✅ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/loan-decision-tree.git
cd loan-decision-tree
