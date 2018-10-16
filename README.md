###### Run above in https://nbviewer.jupyter.org/github/danturti/Housing_Predictions_kaggle/tree/master/ - for rendering jupyter notebook(.ipynb) if it fails to render

# Ames Housing Data and Kaggle Challenge - Top 5%

This model will predict the price of a house at sale.

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

## The Modeling Process

1. The train dataset has all of the columns needed to generate and refine the models. The test dataset has all of those columns except for the target we are trying to predict in the Regression model.
2. Regression model generated using the training data. I am making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
3. Predict the values for your target column in the test dataset and finally submitted my predictions to Kaggle to see how your model does against unknown data.
  
