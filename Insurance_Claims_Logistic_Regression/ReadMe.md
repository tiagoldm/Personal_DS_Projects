*Project Description

Project where I analyzed the car_insurance dataset to find the feature that was the best predictor of the claim "outcome". 
I started by cleaning missing values using mean imputation (both columns with missing values followed a normal distribution) and then used Label Encoding to categorize columns with object type values, preparing for model application.
Afterwards, I ran a Logistical Regression inside a for loop to store the predicted values for each individual feature and then built a confusion matrix, to calculate the accuracy of each predictor and find the feature which was the best predictor of the "outcome" of the claim. 
