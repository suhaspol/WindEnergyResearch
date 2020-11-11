# WindEnergyResearch
Wind Energy Research
Author: Suhas Pol
Date: 11/11/2020
This research project applies Data Science Method (DSM) to develop Machine Learning (ML) models for wind turbine power curve calibration. Here, the EOLOS dataset timeseries was used to create and test models. Feature engineering involved adding features related to spatial (gradient) and temporal (standard deviation) variations. Further features representing categorical information regarding seasons and wind speed were added (Notebook Step 3 EDA). Model testing was performed on the processed dataset and also on log of the processed data set. OLS and Random Forest Regressor models were tested. The Random Forest Regressor hyperparameters were determined using a Bayesian Optimiser.  The Random Forest Regressor model that was created using the log of data had the best performance for datatframes having all features as well as for the one with limited features (Notebook Step 5 Modelling). For the data used R2>0.98 for the Random Forest  Regressor model compared to R2=0.93 for the physics-based model expression. 

