# 🏡 House Price Prediction — Linear Regression (USA Housing)

---

## 🎯 Objective
Build a simple, interpretable linear regression pipeline to predict house prices using neighborhood-level features.  
The goal is both **predictive (accurate price estimates)** and **diagnostic (understand which factors drive value).**

---

## 📊 Data
- **Source:** `USA_Housing.csv`  
- **Rows:** 5,000  
- **Features (predictors):**  
  - `Avg. Area Income`  
  - `Avg. Area House Age`  
  - `Avg. Area Number of Rooms`  
  - `Avg. Area Number of Bedrooms`  
  - `Area Population`  
- **Target:** `Price` (continuous)

---

## 🧪 Approach

### Data Preparation
- Checked dtypes, summary statistics, and integrity  
- Engineered exploratory plots for outlier detection  
- No categorical encoding needed (all numeric)  

### Exploratory Analysis
- **Univariate:** Histograms, boxplots, and KDE plots  
- **Bivariate:** Scatterplots with regression lines  
- **Multivariate:** Correlation heatmap to check feature relationships  

### Modeling
- **Algorithm:** Ordinary Least Squares Linear Regression (`scikit-learn`)  
- **Evaluation:** Holdout train/test split  
- **Interpretation:** Model coefficients inspected to quantify feature impacts  

### Diagnostics
- R², RMSE, and MAE on train and test sets  
- Residual distribution and residuals vs. predicted plots to validate assumptions  
- Pairplots and error plots included in the notebook  

---

## 📈 Key Result
- **Test R² ≈ 0.927** → The model explains most of the variance in house prices using just area-level features.  

---

## 🔍 What Stood Out
- **Neighborhood-level signals are strong:** Area income and number of rooms heavily drive price.  
- **Interpretable model:** Coefficients offer clear business insights (e.g., “+1 room adds ≈ X to price”).  
- **Visual storytelling:** Clean diagnostic plots for both performance and assumptions.  

---

## 🖼 Visuals & Notebook Artifacts
- Pairplot of features vs. price  
- Correlation heatmap  
- Feature distributions (boxplots, histograms, KDE)  
- Residuals vs. predictions  
- Interactive prediction cell (enter features → get price estimate)  

---

## 🛠 Tech Stack
- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---


### 📌 Tags
`#Regression` `#HousePricePrediction` `#LinearRegression` `#EDA` `#ModelDiagnostics` `#DataScience` `#Python`
