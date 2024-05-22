# Titanic-Survival


## Introduction
This project aims to analyze the factors that influenced the survival of passengers on the RMS Titanic. Using the Titanic dataset from Kaggle, we perform data cleaning, exploratory data analysis, and apply machine learning models to predict survival rates.

## Analysis
- **Data Preparation:** Handle missing values, perform feature engineering, and normalize data.
  From the data, we observe that the Cabin column has a significant amount of missing 
  information. 
  We will need to handle these missing values appropriately when we use this column.
  Most other columns are complete, although there are some missing Age entries that need to be 
  addressed.

- **Exploratory Data Analysis:** Analyze feature distributions, visualize correlations, and 
  identify 
  key factors influencing survival.
  From our analysis, it is clear that the number of people who did not survive (demise) is 
  greater 
  than those who did survive.
  We also see that males had a significantly lower survival rate compared to females.

- **Feature Scaling:** We use RobustScaler.
  
- **Model Training:** Train various machine learning models such as Logistic Regression.
  
- **Model Evaluation:** Evaluate model performance using metrics like accuracy, precision, 
  recall, and F1-score.
  
## Key Findings
**1.Missing Data:** The Cabin column has a significant amount of missing values, which requires careful handling. The Age column also has some missing entries that need to be imputed.

**2.Survival Rates:** The number of passengers who did not survive is greater than those who survived.

**3.Gender Disparity:** Female passengers had a much higher survival rate compared to male passengers.

## Get in Touch
If you have any questions, suggestions, or feedback, don't hesitate to reach out.

Email : sanketmadane99@gmail.com
