# NYC Traffic Volume Classification & Regression

This project analyzes NYC hourly traffic count data and applies machine learning models for both classification (traffic level) and regression (volume prediction). It demonstrates end-to-end EDA, model building, evaluation, and tuning with real-world transportation data.

---

## 📊 EDA & Feature Engineering

- Analyzed traffic counts by street, borough, and time.
- Handled missing values and applied median imputation for stability.
- Engineered features: `Total_Traffic`, `Morning_Traffic`, `Evening_Traffic`.
- Detected class imbalance in traffic level labels.
- Used heatmaps and correlation matrices for feature selection.

---

## 🧠 Multiclass Classification

- Labeled traffic levels into **Low, Medium, High** based on volume thresholds.
- Trained Decision Tree and Random Forest classifiers.
- Evaluated performance using **Precision, Recall, F1-Score**, and support.
- Random Forest generalized better than Decision Tree, avoiding overfitting.

---

## 📈 Regression Modeling

- Predicted traffic volume using:
  - Linear Regression
  - Decision Tree
  - KNN
  - SGD Regressor
  - SVR
- Used `StandardScaler` to normalize features.
- Tuned hyperparameters with `GridSearchCV` (5-fold).
- Evaluated with **MSE, MAE, RMSE, R² Score**.

---

## ✅ Key Insights

- **Linear Regression** and **SGD Regressor** performed best (R² ≈ 1.00).
- **KNN** performed strongly after tuning.
- **SVR** was less effective due to high error and low fit.
- Highlighted the value of ML for **automated traffic planning** and **congestion forecasting**.

---

## 🛠️ Skills Used

**Tools & Libraries**: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib  
**Techniques**: EDA, Multiclass Classification, Regression, Standardization, GridSearchCV, Performance Metrics  
**Models**: Decision Tree, Random Forest, Linear Regression, KNN, SGD Regressor, SVR

---

## 📁 Files

- `MLFINAL.ipynb` – Notebook with full analysis and models  
- `MLFINALS.pptx` – Project Presentation  
- `README.md` – Project documentation
