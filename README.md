#### Name - Yashraj Ramdas Chavan  
#### Roll No. - DA25M031  
#### Assignment 8 - Data Analytics Lab (DA5401) JUL–NOV 2025  

# 🚴‍♂️ DA5401 — Assignment 8: Ensemble Learning on Bike Sharing Data

---

## 🧠 Objective
To apply and compare different ensemble strategies for predicting hourly bike rentals (`cnt`) and demonstrate how each technique improves model performance through **bias reduction**, **variance reduction**, or **model diversity**.

---

## 🧩 Methodology

| Part | Topic | Key Focus |
|------|--------|------------|
| **A** | Baseline Models | Data preprocessing, Linear Regression & Decision Tree baseline |
| **B** | Bagging & Boosting | Variance reduction (Bagging) and Bias reduction (Gradient Boosting) |
| **C** | Stacking | Combining diverse models (KNN, Bagging, GBR) using Ridge meta-learner |
| **D** | Final Analysis | RMSE comparison, bias–variance explanation, and best model discussion |

---

## 🧾 Results Summary

| Model | RMSE |
|:--|--:|
| Linear Regression *(Baseline)* | **133.84** |
| Decision Tree (max_depth=6) | 158.69 |
| Bagging (100 DTs) | 155.27 |
| Gradient Boosting | 123.13 |
| **Stacking (KNN + Bagging + GBR → Ridge)** | **116.48** |

✅ **Best Model:** *Stacking Regressor* — achieved the lowest RMSE, showing optimal bias–variance balance.

---

## 🎯 Key Takeaways
- **Bagging** ↓ variance through averaging multiple Decision Trees.  
- **Boosting** ↓ bias via sequential residual learning.  
- **Stacking** combined **diverse learners** and a **Ridge meta-learner** to optimally blend predictions, achieving the best generalization.


---

