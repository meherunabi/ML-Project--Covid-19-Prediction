# ML-Project--Covid-19-Prediction
## Project Overview:
In such, outbreaking situation Machine Learning algorithms can assist to foresee the issue in different aspects and generate prediction for different countries in terms of number of cases, deaths and recoveries. To align with the objective, the project has been executed to focus and experiment  on predicting covid-19 confirmed cases and deaths for next 30 days. In this experiment, polynomial regression and SVM(Support Vector Machine) models are being used to see prediction on confirmed and death cases.

## Covid-19 Data Source:
For this project, the latest dataset operated by the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) has been used. This is the most cleaned and updated public data source which contains data since 22 January,2020. Data source URL-https://github.com/CSSEGISandData/COVID-19

## Method & System Flow:
In order to achieve the objectives and get the prediction, standard ML process flow has been followed. The following is the flow diagram shows the step by step process to predict results and evaluate the models.
At the beginning of the experiment, various EDA(Exploratory Data Analysis) has been done to get to know the data sets and see different scenarios for different countries. After EDA, the entire datasets are splitted to training by  75 % and test by  25%. With training data are being fitted to the polynomial and SVM models. After fitting the training data to the models, we  are built with test data to get the predicted results. 

Method Evaluation and Performance
Model evaluation for ‘Confirmed Cases’:
In this experiment, two models - Polynomial regression and SVM are being used to calculate next 30 days predicted confirmed cases. Through evaluating these models for confirmed cases, following evaluation scores are found for two models - 

Model
MAE Score
MSE Score
MAPE
R^2 matric score
Polynomial Regression
5965791.891618436


53441280372402.6
8%
0.78
SVM
51734104.92227845
3554471293232899.0
93%
-14.015
Table 1 : Polynomial regression Vs SVM evaluation on Confirmed Cases
 
From the above table, considering MAE , MSE, MAPE and R^2 matric score to evaluate two models, it can be said that Polynomial regression model performed well compared to SVM models in terms of confirmed cases. Polynomial regression model holds less error in all off the error matric than SVM. 
Therefore, the Polynomial regression model works better to predict covid-19 confirmed cases for next 30 days.
Model evaluation for Death cases:
In this experiment, two models - Polynomial regression and SVM are being used to calculate next 30 days predicted confirmed cases. Through evaluating these models for confirmed cases, following evaluation scores are found for two models - 

Model
MAE Score
MSE Score
MAPE
R^2 matric score
Polynomial Regression
271090.6697476223



114255509000.87125
16%
0.67
SVM
4268945.636868819



22227981242771.63
298%
-325.7

Table 2 : Polynomial regression Vs SVM evaluation on Death Cases
From the above table, considering MAE , MSE, MAPE and R^2 matric score to evaluate two models, it can be said that the Polynomial regression model performed well compared to SVM models in terms of confirmed cases. Polynomial regression model holds less error in all off the error matrices than SVM. 
Therefore, the Polynomial regression model works better to predict covid-19 confirmed cases for next 30 days.

