# README for TabPFN basics repo

Repo for upcoming Manning book on machine learning for tabular data that shows a basic TabPFN model. This repo:

- Contains code to train a simple model on the [Airbnb NYC listing dataset](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data )
- Uses details from the  [TabPFNDemo Colab](https://colab.research.google.com/drive/194mCs6SEPEW6C0rcP7xWzcEtt1RBc8jJ?usp=sharing) and associated [blog](https://t.co/WtEZ06Q8JF)
- Adapts the [code for training an XGBoost model](https://github.com/ryanmark1867/xgboost_basics/blob/master/notebooks/model_training.ipynb) on the same dataset (itself adapted from code for training a [Keras model](https://github.com/ryanmark1867/deep_learning_basics/blob/master/notebooks/model_training.ipynb))

The only files changed from the XGBoost / Keras versions of the code are: 
- the [training notebook](https://github.com/ryanmark1867/tabpfn_basics/blob/master/notebooks/model_training.ipynb), where the statements for training and exercising the XGBoost model are replaced with code to train and exercise the TabPFN model
- the [model training config file](https://github.com/ryanmark1867/tabpfn_basics/blob/master/notebooks/model_training_config.yml), where the train and test proportions are cranked down so that they are around 1k each to fit the limits for TabPFN





