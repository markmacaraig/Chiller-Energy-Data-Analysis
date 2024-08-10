Project Overview:
This project will enable prediction of chilled water flowrate based on operating conditions as well as external environmental factors.  

Installation and Setup:  

Codes and Resources Used:  

·      Editor: Jupyter Notebook   
·      Python Version: 3.9.13

Python Packages Used:  

·      Data Manipulation: pandas, numpy   
   
·      Data Visualization: matplotlib, seaborn  

· 	     Machine Learning: sklearn, xgboost

Data:  
The dataset used for this project was taken from was taken from Kaggle. The data, HVAC Energy data, is a csv file containing a time-series data from a commercial building in Asia.  

Results and Evaluation:
There were two models generated for this project namely the Random Forest Regressor model and the XGB Regressor models. These models are considered ensemble models.  
The approach used by ensemble models is combining multiple other models to produce a set of final predictions.  
Both models performed essentially the same based on the evaluation metrics used. Both models have relatively low RMSE and MAE scores which indicates that the models performed well in predicting the target values.  

Future Work:  
The most important recommendation is to acquire additional datasets to strengthen or challenge the results of this analysis. In addition, if this project is going to be continued and implemented,  
the next step would be to explore if optimization of any operating parameters that can be manipulated can be achieved to determine the appropriate setpoints to minimize energy consumption.  

References:  
1. Data Driven Chiller Plant Energy Optimization with Domain Knowledge. (2018). https://arxiv.org/pdf/1812.00679
2. RandomForestRegressor. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
3. XGBoost for Regression.2021. https://machinelearningmastery.com/xgboost-for-regression/
   


