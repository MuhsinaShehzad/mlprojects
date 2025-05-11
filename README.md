#  Medical Insurance Price Prediction

This project uses Machine Learning to predict individual medical insurance charges based on demographic and health-related features.

---

##  Project Overview

Medical insurance premiums vary greatly depending on factors like age, BMI, and smoking status. This project aims to analyze these features and build a predictive model to estimate insurance charges using various regression algorithms.

---

##  Tools & Libraries

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (Linear Regression, Random Forest, Gradient Boosting, XGBoost)
- Jupyter Notebook

---

##  Key Insights

- **Smoking** is the most influential factor affecting insurance costs.
- Higher **BMI** and **age** are strongly associated with higher charges.
- **Sex** and **region** have minimal influence on the prediction.
- Among all models, **XGBoost** gave the highest prediction accuracy.
  
---

##  Files in This Repository

| File Name                      | Description                            |
|-------------------------------|----------------------------------------|
| `insurance.csv`               | The dataset used for model training    |
| `ML_Project.ipynb`            | The full notebook with analysis & models |
| `Visualization`              | The graphs and plots
| `README.md`                   | Project summary and insights           |


---

## Conclusion

The XGBoost Regressor outperforms other models in accuracy, making it a reliable choice for predicting medical insurance charges based on personal and health factors.
