# FLAML_AutoML 
<p>
  Code samples for AutoML training using the FLAML library.     
</p>

<p>
  Code supports:  
  <ol>
    <li>AutoML ensemling with Multiple model types (XGBoost, LightGBM, sklearn, etc.)  </li>
    <li>Multi-fold ensemles.  </li>
    <li>Optimal ensemble prediction blending with `Optuna`.  </li>
    <li>Experiment tracking and hyper-parameter sweep with `Weights and Biases (wandb)`  </li>
  </ol>
</p>

### Files Description
  `automl_regression_1.ipynb`:   
      &emsp; Code is for the Kaggle competition -
    [Playground Series - S03E14](https://www.kaggle.com/competitions/playground-series-s3e14)  
      &emsp; Jupyter notebook built for `google-colab` environment.  
      &emsp; The code is to train the regression models over tabular data.   
      &emsp; Currently supported models: XGBoost, LightGBM, CatBoost, Sklearn-knn-regressor, sklear-extra-trees-regressor.  
  `./data/`:   
      &emsp; `train.csv`: Train data.  
      &emsp; `test.csv`: Test data  
      &emsp; `orig_data.csv`: Original Data from which competition train data was generated.  
      &emsp; `sample_submission.csv`: Sample submission format for the competition.  
      
# How to use:   
<ol>
  <li> Train AutoML model(s):  </br>
    &emsp; Set the `choice` option in the `config` dictionary to 1. (Bottom cell of the jupyter botebook.)  </br> 
    &emsp; Set the configuration you want for auto-ml in the same dictionary. Run the cell.  
  </li>
  <li> Test the model:   </br>
    &emsp; Set the `choice` option in the `config` dictionary to 2.  
  </li>
  <li> Hyper-parameter sweep:   </br>
    &emsp; An explicit hyper-parameter sweep without/in addition to automl search can be done with `choice`=3.  </br> 
    &emsp; See/update hyper-parameter sweep ranges in the cell.  
  </li>
</ol>

# Update in Progress.  
