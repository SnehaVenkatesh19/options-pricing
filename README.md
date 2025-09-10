# Option Pricing Prediction Using Machine Learning

## 📖 Project Overview
This project explores how machine learning can enhance traditional option pricing models.  
We compared regression and classification models against the Black-Scholes benchmark to predict option values.

## 🎯 Objectives
- Integrate machine learning into option pricing beyond Black-Scholes.
- Predict current option values using regression models.
- Classify over/under estimates of option values using classification models.

## 📊 Dataset
- **Value**: Current option value  
- **S**: Current asset value  
- **K**: Strike price of option  
- **Tau**: Time to maturity (years)  
- **r**: Annual interest rate  
- **BS**: Black-Scholes estimate (Over/Under classification)

## 🛠️ Methodology
- **Data Preparation**: Normalization, dummy variables, K-Fold cross-validation.  
- **Regression Models**: OLS Regression, Decision Tree, Random Forest, XGBoost.  
- **Classification Models**: Logistic Regression, Decision Tree, Random Forest.  
- **Evaluation Metrics**: R² for regression, Accuracy & F1 for classification.  

## 📈 Results
- **Regression**: XGBoost achieved the best performance with Out-of-Sample R² = **0.997**, lowest MSE & MAE.  
- **Classification**: Random Forest achieved the highest accuracy (**0.933**) and F1-score (**0.85**).

## 📈 Results

| Task            | Model               | Metric(s)                | Performance |
|-----------------|--------------------|--------------------------|-------------|
| Regression      | OLS Regression     | R²                       | 0.89        |
| Regression      | Random Forest      | R²                       | 0.992       |
| Regression      | XGBoost            | **R² = 0.997**           | Best Model  |
| Classification  | Logistic Regression| Accuracy, F1             | 0.88 / 0.81 |
| Classification  | Random Forest      | **Accuracy = 0.933, F1 = 0.85** | Best Model |
  

## 🔍 Business Insight
- ML models outperform traditional models in capturing non-linear patterns.  
- Accuracy is critical in contexts like high-frequency trading, where pricing decisions have significant consequences.  
- ML offers adaptability to changing market conditions, improving practical utility beyond Black-Scholes.  


