# 🎓 Student Performance Predictor

This project predicts **students' academic performance** based on demographic, social, and study-related features using **Machine Learning**.

## 📋 Overview
Two prediction tasks were performed:
1. **Regression** – Predict final grade (**G3**) using Linear Regression.  
2. **Classification** – Predict **Pass/Fail** using Logistic Regression and Decision Tree.

## ⚙️ Features
- Data preprocessing with scaling, imputation, and one-hot encoding  
- Model evaluation using MSE, RMSE, R², Accuracy, Precision, Recall, F1  
- Feature importance visualization (Decision Tree)  
- Exported trained models using `joblib`

## 📊 Dataset
Dataset: [UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)  
Place `student-mat.csv` (or `student-por.csv`) in the same directory as the script.

## 🧠 Algorithms Used
- Linear Regression  
- Logistic Regression  
- Decision Tree Classifier  

## 🗂️ Files in Repository
| File | Description |
|------|--------------|
| `ML_OPEN_ENDED by 73` | Main Python script with preprocessing and model training |
| `report_summary.txt` | Short summary of models and metrics |
| `student-mat.csv` | Dataset (not required to upload) |
| `student_pass_logistic.pkl` / `student_pass_dt.pkl` / `student_g3_linear_reg.pkl` | Saved models |

## 🚀 How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
python ML_OPEN_ENDED by 73.ipynb
