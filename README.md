## Using Seaborn and Matplotlib for making EDA (Exploratory Data Analysis) and visualization ,Then using Skikitlearn for making Random Forest model for predicting effect of actions on specific features

## **Notebook Contents**

### <span style="color:#3498db;">Part 1: Exploratory Data Analysis (EDA)</span>
1. **Uploading the dataset**: Loading the initial dataset for analysis.
2. **Visualizing Cells by Location**: Using graphs to explore the x, y, and z coordinates of different cells.
3. **Exploring feature relationships**: Utilizing `sns.pairgrid` to visualize the relationships between columns.
4. **Dropping features 8 and 14**: These features are removed after analysis shows irrelevance or redundancy.
5. **Correlation Matrix**: Creating a correlation matrix to assess relationships between features.
6. **Removing highly correlated features**: Dropping features 9 and 18 due to high multicollinearity.
7. **Adding a day column**: Introducing a "day" column to track data over time.
8. **Combining all datasets**: Merging 15 datasets into a unified dataset.
9. **Plotting Feature Means over Time**: Visualizing the mean of each feature over 15 days to identify trends.
10. **Excluding Feature 1**: Feature 1 is excluded from the model as it remains constant across time.
11. **Clustering based on x, y, z locations**: Clustering location data into 7 clusters and adding a new column `location_cluster`.
12. **Data Preparation**: Preparing data (X, y_11, y_12) for model input.
13. **Random Forest Classifier**: Building a Random Forest model to predict features 11 and 12.
14. **Model Evaluation**: Assessing performance metrics for both features.
15. **Results**: Achieving <span style="color:#2ecc71;">99.6%</span> accuracy for feature 11 and <span style="color:#2ecc71;">99.4%</span> accuracy for feature 12.


