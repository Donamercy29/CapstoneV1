#  Air Traffic & Aviation Analysis (Capstone Project)

##  Project Overview
This project analyzes aviation safety and passenger traffic trends using two datasets:
- Airplane Crashes Dataset
- Air Traffic Passenger Dataset

The project is divided into two phases:
- Phase 1: Exploratory Data Analysis (EDA)
- Phase 2: Machine Learning Model Development

---

##  Phase 1: Exploratory Data Analysis (EDA)

###  Airplane Crash Analysis (1908–2009)

#### Objective
- Analyze historical aviation accident trends
- Study fatality patterns and safety improvements
- Identify factors affecting crash severity

#### Key Insights
- Crash frequency peaked in the mid-20th century and declined over time  
- Fatality rates were higher in earlier decades  
- Significant improvements in aviation safety observed  
- Certain operators and aircraft types had higher crash frequency  

---

###  Air Traffic Passenger Analysis

#### Objective
- Analyze passenger growth trends
- Identify seasonal travel patterns
- Compare domestic vs international traffic

#### Key Insights
- Strong long-term growth in passenger traffic  
- Peak travel seasons identified (mid-year months)  
- International and domestic traffic show distinct patterns  
- Terminal and airline activity varies significantly  

---

##  Phase 2: Machine Learning (Prediction Model)

###  Objective
Build a predictive model to estimate passenger traffic using historical data.

---

###  Models Implemented
- Linear Regression (OLS)
- Ridge Regression
- Lasso Regression

---

###  Techniques Used
- Data Cleaning & Preprocessing  
- Feature Engineering (seasonality, interaction features)  
- Encoding (Frequency + One-Hot Encoding)  
- Feature Scaling (StandardScaler)  
- Cross Validation (5-Fold)  

---

###  Model Results

| Model | R² Score | RMSE |
|------|--------|------|
| Linear Regression (Baseline) | **0.58** | ~36,900 |
| Feature Engineered Model | 0.39 | ~44,200 |
| Ridge / Lasso | Evaluated for regularization |

---

###  Key Observations
- Baseline model performed better than feature engineered model  
- Additional features did not significantly improve prediction  
- Demonstrates importance of meaningful feature selection  
- Regularization techniques helped control model complexity  

---

##  Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

##  Project Structure
- Air-Traffic-Project
- Phase1_Airplane_Analysis.ipynb
- Phase1_Passenger_EDA.ipynb
- Phase2_ML_Model.ipynb  
- Air_Traffic_Passenger_Statistics.csv
- Airplane_Crashes_and_Fatalities.csv
- README.md

---

##  Conclusion

This project demonstrates an **end-to-end data science workflow**, including:
- Data cleaning and preprocessing  
- Exploratory data analysis  
- Feature engineering  
- Machine learning model development  
- Model evaluation and optimization  

---

##  Future Improvements
- Apply advanced models (Random Forest, XGBoost)  
- Improve feature engineering techniques  
- Incorporate external datasets for better prediction  
