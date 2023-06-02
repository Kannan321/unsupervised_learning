# Automobile Data Analysis and Classification

This project aims to analyze automobile data using K-Means clustering and apply dimensionality reduction techniques for classification. It involves segmenting cars into various categories using K-Means clustering and classifying vehicle types using a set of features extracted from vehicle silhouettes.

## Part A: K-Means Clustering

### Steps and Tasks

1. Data Understanding & Exploration
   - Read 'Car name.csv' as a DataFrame and assign it to a variable.
   - Read 'Car-Attributes.json' as a DataFrame and assign it to a variable.
   - Merge both the DataFrames together to form a single DataFrame.
   - Print the 5-point summary of the numerical features and share insights.

2. Data Preparation & Analysis
   - Check and print feature-wise percentage of missing values present in the data and impute with the best suitable approach.
   - Check for duplicate values in the data and impute with the best suitable approach.
   - Plot a pairplot for all features.
   - Visualize a scatterplot for 'wt' and 'disp', with datapoints distinguished by 'cyl'. Share insights.
   - Visualize a scatterplot for 'wt' and 'mpg', with datapoints distinguished by 'cyl'. Share insights.
   - Check for unexpected values in all the features and datapoints with such values.

3. Clustering
   - Apply K-Means clustering for 2 to 10 clusters.
   - Plot a visual and find the elbow point.
   - On the above visual, highlight the possible Elbow points.
   - Train a K-means clustering model once again on the optimal number of clusters.
   - Add a new feature in the DataFrame which will have labels based upon cluster value.
   - Plot a visual and color the datapoints based on clusters.
   - Pass a new DataPoint and predict which cluster it belongs to.

## Part B: Dimensionality Reduction and Classification

### Steps and Tasks

1. Data Understanding & Cleaning
   - Read 'vehicle.csv' and save as a DataFrame.
   - Check the percentage of missing values and impute with the correct approach.
   - Visualize a pie chart and print the percentage of values for the variable 'class'.
   - Check for duplicate rows in the data and impute with the correct approach.

2. Data Preparation
   - Split the data into X and Y (Train and Test optional).
   - Standardize the Data.

3. Model Building
   - Train a base Classification model using SVM.
   - Print Classification metrics for the train data.
   - Apply PCA on the data with 10 components.
   - Visualize Cumulative Variance Explained with the Number of Components.
   - Draw a horizontal line on the above plot to highlight the threshold of 90%.
   - Apply PCA on the data, selecting minimum components with 90% or above variance explained.
   - Train an SVM model on components selected from the above step.
   - Print Classification metrics for the train data of the above model and share insights.

4. Performance Improvement
   - Train another SVM on the components out of PCA and tune the parameters to improve performance.
   - Share the best parameters observed from the above step.
   - Print Classification metrics for the train data of the above model and share the relative improvement in performance in all the models along with insights.

## Files and Directory Structure

- `Car name.csv`: CSV file containing car names data.
- `Car-Attributes.json`: JSON file containing car attributes data.
- `vehicle.csv`: CSV file containing vehicle silhouette features data.
- `unsupervised+learning.ipynb`: Jupyter Notebook containing the code and analysis for Part A and B.
- `README.md

