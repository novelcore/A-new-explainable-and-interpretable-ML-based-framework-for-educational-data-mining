# A-new-explainable-and-interpretable-ML-based-framework-for-educational-data-mining

This repository contains the feature description as well as the descriptive statistics and a complete exploratory data analysis of the datasets utilized in the research manuscript "*A new explainable and interpretable ML-based framework for educational data mining*"


## Hyperparameters for Data

The hyperparameters of all algorithms were optimized in order to achieve the best possible performance.

### $\text{DATASET}_1$

- LGBM 
  - n_estimators: 100
  - learning_rate: 0.100
  - max_depth: 5
  - subsample_for_bin: 20
- XGBoost
  - n_estimators: 200
  - learning_rate: 0.100
  - max_depth: 3
  - reg_alpha: 10
- Random-Forest
  - n_estimators: 200
  - max_depth: 3
  - min_samples_split: 3
- NGBoost
  - natural_gradient: True
  - n_estimators: 200
  - learning_rate: 0.010
  
  
  ### $\text{DATASET}_2$

- LGBM 
  - n_estimators: 100
  - learning_rate: 0.100
  - max_depth: 3
  - subsample_for_bin: 50
- XGBoost
  - n_estimators: 100
  - learning_rate: 0.100
  - max_depth: 3
  - reg_alpha: 10
- Random-Forest
  - n_estimators: 100
  - max_depth: 9
  - min_samples_split: 5
- NGBoost
  - natural_gradient: True
  - n_estimators: 200
  - learning_rate: 0.010



