# kaggle  - Predicting Permeability 

This project involves a kaggle competition among our class to build a supervised learning model to predict permeability, given geometric properties of a medium.  The performance indicator used for the competition was the Root Mean Squared Log Error (RMSLE).  

Various models were used, including Random Forest, Extra Trees, XG Boost, Neural Networks - all of which notebooks are included.  

However, the best performing model ended up using a Principle Component Analysis (PCA) with Regression (notebook: "PCA_Regression").  A Column Transformer and Transformed Target Regressor were then applied.  

I made many attempts to use Partial Least Squares (PLS) Regression, either on its own or following the same process as the PCA model.  The premise was that the model would perform even better given that PLS is for supervised learning. However, the results were never as strong as the PCA model.  
