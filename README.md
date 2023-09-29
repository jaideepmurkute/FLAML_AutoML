# FLAML_AutoML 
Code samples for AutoML training using the FLAML library.   

Code is for the Kaggle competition - Playground Series - S03E14 - https://www.kaggle.com/competitions/playground-series-s3e14.  
The code is to train the regression models over tabular data.   
Currently supported models: XGBoost, LightGBM, CatBoost, Sklearn-knn-regressor, sklear-extra-trees-regressor.  
  
How to use:   
1] Train AutoML model(s):   
  &emsp; Set the `choice` option in the `config` dictionary to 1. (Bottom cell of the jupyter botebook.)  
  &emsp; Set the configuration you want for auto-ml in the same dictionary. Run the cell.  
2] Test the model:   
  &emsp; Set the `choice` option in the `config` dictionary to 2.  
3] Hyper-parameter sweep:   
  &emsp; An explicit hyper-parameter sweep without/in addition to automl search can be done with `choice`=3.  
  &emsp; See/update hyper-parameter sweep ranges in the cell.  

Update in Progress.  
