### Getting Started

##### 1: Download notebook 
##### 2: Download .csv file and place in the same folder as the notebook
##### 3: Open notebook with IDE such as Jupyter, Pycharm, etc

# Project Description

### Project where I cleaned, pre-processed and modeled the penguins.csv file to find clusters of species based on different features

##### Step 1: Dropping missing values from dataset, and applying thresholds on numeric columns to remove outliers
##### Step 2: Using Label Encoding to categorize the "sex" column, into 0 and 1.
##### Step 3: Using standard scaling to normalize numeric features, and then applying PCA on the same features, setting n_components to those with an explained variance ratio above 0.1.
##### Step 4: Using KMeans to perform elbow analysis in order to find the optimal number of clusters, and then fitting it to the preprocessed dataset.
##### Step 5: Displaying a scatter plot to visualize the clusters found by the model, and then creating a new column in the penguins_clean dataset and grouping by the cluster_labels to organize data by species.
