### Getting Started

##### 1: Download notebook 
##### 2: Download .csv files and place in the same folder as the notebook
##### 3: Open notebook with IDE such as Jupyter, Pycharm, etc

# Project Description

### Project where I analyzed a dataset with housing information to predict the number of reviews for each location, based on several features.

##### Step 1: Filling missing/miscoded values using different methods, correcting column datatypes, and encoding categorical columns using an ordinal and non-ordinal encoder for different columns.
##### Step 2: Grouping apartment prices by number of bedrooms, to find the mean price, and variance per number of bedrooms, in order to evaluate the impact of the number of bedrooms on price
##### Step 3: Building a baseline model, using a logistic regression to estimate the target variable sale price, for each apartment in a new dataset containing only features. 
##### Step 4: Running k-fold validation to extract the average mean_standard error of training data, since I didn't have access to the test data number of reviews.
##### Step 5: Building a Gradient boosting regressor model to estimate the sale price, using a function to iterate through hyperparameters such as max_depth, n_estimators, and learning_rate. Extracted mse for each combination to find the optimal combination of parameters which returned the lowest MSE. Achieved a decrease of around 25% in the MSE for the final model.
##### Step 6: Created a DataFrame with the predicted price for each apartment in the new dataset.

