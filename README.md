# Housing Prediction ML
This repository contains a machine learning project focused on predicting housing prices using python's sklearn library. The project involves data preprocessing, feature engineering, model training, and evaluation using various regression algorithms.  
  
## Notebooks  
1. [California Housing Price Prediction ML](California.ipynb)  
   [![Kaggle Dataset](https://img.shields.io/badge/Kaggle-Dataset-blue?logo=kaggle)](https://www.kaggle.com/code/vivirastucia/california-housing)
2. [Delhi Housing Price Prediction ML](Delhi.ipynb)

## Datasets
- [California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- [Delhi Housing Dataset]('to be added')
  
## Stack
- Python
    - Pandas, Numpy, Sklearn, Matplotlib, Urllib
- Jupyter Notebook

## Learning Model Explored  
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
    - Did not work well as the dataset is not large enough
- Gradient Boosting Regressor
    - Worked decently, as tabular data
- Histogram-based Gradient Boosting Regressor
    - Worked the best among all models tried
    - Mostly because it handles categorical features natively
  
- Finetunners
    - GridSearchCV
    - RandomizedSearchCV
