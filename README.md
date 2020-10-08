# Nepal_New_Cases_Predictor_Project Overview
* Created a model that can estimate the new COVID-19 cases of Nepal.
* Cleaned and filtered the data where I selected Nepal as a country but if we want we can select any country and proceed its case study.
* Used RandomForest Regressor model to train and built the model, also compared the accuaracy of RandomForest Regressor, KNN and Linear Regression.
* Reached around 87% of accuracy for our predition.
* Model is brought into production using Streamlit framework.https://www.streamlit.io/

# Code and Resources Used
Python version : 3.8.3
Packages: pandas, numpy, matplotlib, seaborn, scikitlearn, pickle, streamlit
For Web Framework Requirements : pip install sreamlit
# Problem Definition
The problem we are working on is regression problem where main objective is to predicting the accuracy level for new cases. In short, we can write as:

> Given a dataset of COVID-19, how well our model will predict the new cases?
# Tools
  * Numpy - for numerical operations
  * Pandas - for data analysis
  * Matplotlib - for data visualization
  * Seaborn - same use as Matplotlib with additional features
  * Scikit-Learn(Sklearn) - for machine learning modelling
  
# EDA
> Nepal First Five days case which we can see there was no any cases till first five days
<img src="first_5_days_case.png"/>

> Nepal latest five days bar-chart
<img src="last_5_days_bar_comparision.png"/>

> Nepal corona case yearwise comparision (2019 and 2020)
<img src="latest_case_growth_with_days.png"/>

> Nepal latest case line graph
<img src="latest_case_linegraph.png"/>

> Newcases vs total cases line graph 
<img src="newcases_vs_totalcases_linearGraph.png"/>

