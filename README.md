# Automobile Data Analysis

This project aims to analyze automobile data using K-Means clustering to segment cars into various categories. It also involves data understanding, exploration, preparation, analysis, and visualization.

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

## Files and Directory Structure

- `Car name.csv`: CSV file containing car names data.
- `Car-Attributes.json`: JSON file containing car attributes data.
- `README.md`: This file explaining the project and its steps.
- `unsupervised+learning.ipynb`: Jupyter Notebook containing the code and analysis for Part A.

## Prerequisites

To run the code and perform the analysis, you need to have the following dependencies installed:

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/automobile-data-analysis.git
