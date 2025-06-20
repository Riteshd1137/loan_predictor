# loan_predictor
Predicts loan eligibility using DecisionTreeClassifier on a real Kaggle dataset. Features include income, education, and credit history. Built with scikit-learn, pandas, and matplotlib. Includes model accuracy and decision tree visualization.


# 💳 Loan Eligibility Predictor using Decision Tree (Scikit-learn)

This project predicts whether a person is eligible for a loan using a Decision Tree model trained on real Kaggle data.

---

## 📂 Dataset
Kaggle Dataset: [Loan Prediction Problem Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

---

## 🔍 Features Used
- ApplicantIncome
- Education (0 = Not Graduate, 1 = Graduate)
- Credit_History (0 = Bad, 1 = Good)

**Target Variable:**  
- Loan_Status (Eligible / Not Eligible)

---

## 🧠 What I Learned
- Loading and cleaning real-world data
- Converting categorical data into numeric
- Using `DecisionTreeClassifier` from scikit-learn
- Evaluating accuracy with `train_test_split`
- Visualizing tree structure using `plot_tree`

---

## 📈 Model Accuracy
0.8470588235294118

## 💻 Tech Stack
- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## 📁 Files Included
- `loan_predictor.ipynb` – Main notebook
- `train_u6lujuX_CVtuZ9i.csv` – Training dataset
- `README.md` – Project overview
