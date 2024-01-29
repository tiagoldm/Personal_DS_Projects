### Getting Started

##### 1: Download notebook 
##### 2: Download .csv file (and picture for cosmetic purposes) and place in the same folder as the notebook
##### 3: Open notebook with IDE such as Jupyter, Pycharm, etc

# Project Description

### Project where I analyzed a crops dataset including different crops and variables to find the feature that was the best predictor of the "crop" type.

##### Step 1: Checking datatypes and missing values to assess need for changes.
##### Step 2: Using Label Encoding to categorize the "crop" column to enable modelling.
##### Step 3: Creating X (features) and y (variable to predict), and implementing a train_test_split to get training and test data. 
##### Step 4: Running Logistic Regression inside a for loop to store the predicted values for each individual feature, and the results of an F1_score in lists.
##### Step 4: Building a correlation matrix of the features to find features with high correlation (>0.7), and dropping one of the columns to avoid colinearity. The decision was made by dropping the correlated column with the lowest f1_score.
##### Step 5: Running log_reg model again but this time using the 3 remaining features, at one. Obtained a final f_score above 0.5.
