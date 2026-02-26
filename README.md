# Capstone Project
This Project focuses on developing a predictive model by integrating two Datasets (Airplane Crashes and Air Traffic Passenger). The aim is to study the trends and patterns related to Air Travel Safety and passenger growth. The integration of multiple datasets helps enhance prediction accuracy and supports better analysis.
#Airplane Crash Analysis (1908–2009)
##Dataset
Historical records of airplane crashes from 1908 onwards, including crash location, airline operator, aircraft type, fatalities, and accident summaries.
##Objective
Analyze historical aviation accident trends and crash frequencies.
Identify factors affecting fatalities in crashes.
Explore how aviation safety improved over time.
Use statistical analysis and visualization to extract meaningful insights.
Understand survival probability in aviation accidents.
##Key Insights & Analysis
###1. Exploratory Data Analysis (EDA)
###Yearly Trends
Analyzed number of crashes per year.
Identified peak crash periods (notably early 1970s).
Examined fatality trends over decades.

###Geographic Distribution
Identified countries and continents with highest crash occurrences.
Compared fatality counts by region.

###Airline & Aircraft Impact
Determined operators with most recorded crashes.
Analyzed aircraft types involved in high-fatality incidents.

###Fatalities & Survival Analysis
Compared Aboard vs Fatalities.
Created Fatality Rate feature:
      Fatality_Rate = Fatalities / Aboard
Studied severity patterns across years.
###2. Statistical & Analytical Approaches
###Time-Based Analysis
Year-wise crash frequency trend visualization.
Studied long-term aviation safety improvements.

###Feature Correlation
Analyzed relationships between:
Aboard
Fatalities
Ground casualties

###Predictive Perspective
Explored possibility of predicting crash severity using:
Number of passengers
Aircraft type
Operator history
##Visualizations & Findings
Crash frequency peaked mid-20th century and declined in recent decades.
Fatality rate analysis showed many crashes had high severity.
Some operators and aircraft types were disproportionately represented.
Safety improvements over time significantly reduced fatality counts.
##Tools & Libraries Used
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from scipy.stats import zscore
import warnings
warnings.filterwarnings('ignore')

#Air Traffic Passenger Data Analysis
##Dataset
Air traffic passenger dataset containing historical passenger volume records across airports, regions, and travel categories (Domestic/International).
##Objective
Analyze passenger growth trends over time.
Identify seasonal travel patterns.
Compare domestic vs international traffic.
Prepare dataset for predictive modeling.
Apply linear regression for passenger forecasting.
##Key Insights & Analysis
###1. Exploratory Data Analysis (EDA)
###Yearly Passenger Trends
Studied long-term passenger growth.
Identified peak growth years.
###Monthly & Seasonal Patterns
Analyzed high-traffic months.
Identified recurring seasonal travel peaks.
###Regional & Airport Analysis
Compared passenger traffic across airports.
Identified busiest regions.
###Growth Rate Analysis
Computed year-over-year growth.
Measured expansion patterns in aviation demand.
###2. Statistical Analysis
Performed trend analysis using yearly aggregation.
Analyzed passenger growth patterns over time.
Compared seasonal variations.
Used correlation analysis to study feature relationships.
###Visualizations & Findings
Passenger traffic shows strong long-term growth.
Seasonal travel peaks observed in specific months.
Domestic vs international comparison revealed demand distribution differences.
Regression model captured strong time-based growth trend.
