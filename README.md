# 🧠 AI/ML Journey  

Welcome to my **AI/ML Learning Journey** repository!  
This repo documents my step-by-step progress in learning **Machine Learning & AI** with practical notebooks, theory, and interview tips.  

---

## 📂 Repository Structure  

---

## 📌 Topics Covered  

- **Day 1** → Multiple Linear Regression basics (equation, interpretation, coefficients)  
- **Day 2** → Model evaluation (R², Adjusted R², RMSE, MAE, Residual plots, Cross-validation, VIF)  
- **Day 3** → Overfitting and Regularization (Ridge & Lasso regression with interpretation)  

## Day 4 – Polynomial Regression

- Learned about **Polynomial Regression** as an extension of Linear Regression.  
- Key steps:
  - Used `PolynomialFeatures` to transform input features into polynomial terms.
  - Trained models using **LinearRegression()** on both raw and transformed features.
- Observations:
  - Polynomial regression improves performance on nonlinear data.
  - Compared results for degree = 2 and degree = 10:
    - Degree 2 showed a significant improvement over plain Linear Regression.
    - Degree 10 improved slightly further, but risk of overfitting increases.
- Files:
  - `DAY_4/Day4_Polynomial_Reg_1.ipynb`
  - `DAY_4/Day4_Polynomial_Reg_2.ipynb`

## Day 5 - Classification Metrics  

### 📘 Concepts Covered:
- **Regularization (Lasso & Ridge):**  
  Helps prevent overfitting by penalizing large coefficients.  

- **Confusion Matrix:**  
  Shows how many predictions were correct vs incorrect across classes (TP, TN, FP, FN).  

- **ROC (Receiver Operating Characteristic) Curve:**  
  Plots True Positive Rate vs False Positive Rate across thresholds.  

- **AUC (Area Under Curve):**  
  A single score summarizing the ROC curve → measures how well a model ranks positives vs negatives.  

### 🛠 Practical Use:
- Regularization improves **generalization** of models.  
- Confusion Matrix helps understand **type of errors** (false positives/negatives).  
- ROC-AUC is useful for **comparing models** and their ability to distinguish between classes.  

### 📂 Files Added:
- `Day5_Classification_Metrics.ipynb`  


##Day 6:Logistic Regression with Iris Dataset

- Used the classic **Iris dataset** (150 samples, 4 features).  
- Focused on **binary classification**: *Setosa vs. Non-Setosa*.  
- Worked with only the first 2 features (`Sepal length`, `Sepal width`) → `iris.data[:, :2]`  
  - `:` → selects all rows (all flowers).  
  - `:2` → selects only the first two columns (features).  
  - Result: (150, 2) array used for visualization.  

### Key Learnings:
- Logistic Regression can separate Setosa vs. Non-Setosa with high accuracy.  
- **Decision Boundary Visualization** in 2D helps understand how the model separates classes.  
- Reduced dimensionality (2 features out of 4) makes visualization easier.  

### Next Step:
- Extend to multi-class (Setosa, Versicolor, Virginica) logistic regression. 

---



