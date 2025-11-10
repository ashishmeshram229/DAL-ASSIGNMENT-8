# 🚀 Ensemble Learning: Bias–Variance Trade-Off  

**Name:** Ashish Rajhans Meshram  
**Roll No:** DA25M016  
**Course:** DA5401 – Machine Learning | IIT Madras  

This project analyzes how ensemble regression models — **Bagging**, **Boosting**, and **Stacking** — manage the **bias–variance trade-off** using the **Bike Sharing Dataset (hour.csv)**.

---

## 🧠 Objective
- Load and preprocess data with One-Hot & Cyclical encoding.  
- Train baseline regressors (Decision Tree, Linear).  
- Implement ensemble techniques (**Bagging**, **Boosting**, **Stacking**).  
- Evaluate models using **RMSE** and visualize their bias–variance behavior.

---

## ⚙️ Model Results

| Model | RMSE | Improvement |
|:--|:--:|:--|
| Decision Tree | 103.70 | Baseline |
| Bagging | 98.77 | ↓ Variance |
| Boosting | 81.49 | ↓ Bias |
| Stacking | 95.02 | ↓ Both |

**Best Performer:** Gradient Boosting Regressor  
**Most Balanced:** Stacking Regressor  

---

## 📊 Visual Insights
- **RMSE Comparison Chart** — performance ranking  
- **Residual Distribution** — bias and variance check  
- **Bias–Variance Plot** — conceptual trade-off curve  
- **Learning Curve** — model generalization pattern  
- **Feature Importance (Boosting)** — dominant predictors  
- **Predicted vs Actual Scatter** — model alignment  

---

## 🏁 Conclusion
> Ensemble methods progressively reduce prediction error:
> - **Bagging** lowers variance  
> - **Boosting** lowers bias  
> - **Stacking** balances both  
>
> The **Gradient Boosting Regressor** achieved the lowest RMSE, validating the **bias–variance trade-off principle** in ensemble learning.

