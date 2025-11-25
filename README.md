# DataAnalysisProject-SocialBehavior
Statistical analysis of a synthetic social behavior dataset, exploring drivers of happiness and stress with EDA, feature selection, and linear regression.

This project analyzes how lifestyle and demographic factors relate to **happiness** using a synthetic dataset of 2,000 people. It includes data exploration, statistical tests, and a linear regression model.

## What the Project Does
- Loads and inspects the dataset  
- Performs visual EDA (sleep vs stress, exercise vs happiness, etc.)  
- Runs correlation, ANOVA, and chi-square tests  
- Checks multicollinearity (VIF)  
- Builds a linear regression model to predict `happiness_score`  
- Evaluates model assumptions and residuals  

## Key Findings
- Exercise, diet quality, and sleep are the strongest numeric predictors of happiness.  
- Stress level is negatively associated with happiness.  
- Some categorical factors (like depression risk and high stress) show strong statistical relationships with happiness.  
- The linear regression model explains ~21% of the variance and passes diagnostic tests.
