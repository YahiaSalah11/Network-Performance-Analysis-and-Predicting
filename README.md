Notebook Contents
Part 1: Exploratory Data Analysis (EDA)
Uploading the dataset: Loading the initial dataset for analysis.
Visualizing Cells by Location: Using graphs to explore the x, y, and z coordinates of different cells.
Exploring feature relationships: Utilizing sns.pairgrid to visualize the relationships between columns.
Dropping features 8 and 14: These features are removed after analysis shows irrelevance or redundancy.
Correlation Matrix: Creating a correlation matrix to assess relationships between features.
Removing highly correlated features: Dropping features 9 and 18 due to high multicollinearity.
Adding a day column: Introducing a "day" column to track data over time.
Combining all datasets: Merging 15 datasets into a unified dataset.
Plotting Feature Means over Time: Visualizing the mean of each feature over 15 days to identify trends.
Excluding Feature 1: Feature 1 is excluded from the model as it remains constant across time.
Clustering based on x, y, z locations: Clustering location data into 7 clusters and adding a new column location_cluster.
Data Preparation: Preparing data (X, y_11, y_12) for model input.
Random Forest Classifier: Building a Random Forest model to predict features 11 and 12.
Model Evaluation: Assessing performance metrics for both features.
Results: Achieving 99.6% accuracy for feature 11 and 99.4% accuracy for feature 12.

