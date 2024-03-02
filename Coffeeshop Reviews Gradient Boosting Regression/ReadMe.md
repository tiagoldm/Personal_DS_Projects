### Getting Started

##### 1: Download notebook 
##### 2: Download .csv files and place in the same folder as the notebook
##### 3: Open notebook with IDE such as Jupyter, Pycharm, etc

# Project Description

### Project where I analyzed the a coffeeshop dataset to predict the number of reviews for each location, based on several features.

##### Step 1: Filling missing values using different methods, and encoding categorical columns, using an ordinal and non-ordinal encoder for different columns
##### Step 2: Grouping number of reviews by rating, to find mean, min, and max for each, in order to evaluate a relationship between both these columns
##### Step 3: Building a baseline model, using a logitic regression to estimate the target variable number of reviews, for each location. 
##### Step 4: Running k-fold validation to extract the average mean_standard error of training data, since I didn't have access to the test data number of reviews.
##### Step 5: Building a Gradient boosting regressor model to estimate the number of reviews, using a function to iterate through hyperparameters such as max_depth, n_estimators, and learning_rate. Extracting mse for each combination, to find the optimal combination of parameters which returned the lowest MSE.
##### Step 6: Creating a DataFrame with the predicted number of reviews for each location.
