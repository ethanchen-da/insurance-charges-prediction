# Medical Insurance Cost Analysis

## Objective
Analyze key factors affecting medical insurance charges and build predictive models to estimate costs.

## Dataset
The dataset contains demographic and lifestyle information, including:
- Age
- BMI
- Number of children
- Smoking status
- Region
- Medical insurance charges

## Methodology
- Data cleaning and outlier removal (IQR method)
- Exploratory Data Analysis (EDA)
- Feature encoding and scaling
- Linear Regression (baseline & reduced)
- OLS regression for statistical interpretation
- Interaction feature engineering

## Key Insights
- Smoking is the strongest driver of insurance charges
- Age and BMI significantly increase costs, especially for smokers
- Interaction terms improve model performance
- Linear models perform well for moderate costs but underpredict extreme cases

## Model Performance
| Model              | R²   | RMSE |
|-------------------|------|------|
| Linear Regression | ~0.63| ~4200|

## Tools
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels
