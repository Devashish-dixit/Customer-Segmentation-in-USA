# Customer Segmentation in USA Prediction Notebook

## Proportion of Business Owners
- Calculated the proportion of respondents in the dataset that are business owners.
- Assigned the result to the variable `pct_biz_owners`.

## Income Category Distribution
- Created a DataFrame `df_inccat` to display the normalized frequency of income categories for business owners and non-business owners.
- Answered the question: Is the distribution of income different for business owners and non-business owners?

## Visualizing Income Distribution
- Created a side-by-side bar chart of `df_inccat` to visually compare the income distribution between business owners and non-business owners.

## Exploring Housing and Debt
- Created a scatter plot that shows the relationship between "HOUSES" and "DEBT."

## Analyzing Age of Business Owners
- Created a histogram from the "AGE" column in `df_small_biz` for business owners with incomes below $500,000.

## Clustering with K-Means
- Selected K-Means clustering as the appropriate model for segmentation.

## Hyperparameter Tuning
- Conducted hyperparameter tuning to identify the best number of clusters that yield an optimal silhouette score and low inertia error.
- Determined that the optimal number of clusters is 3.

## Cluster Analysis
- Visualized the mean values of features in `X` for each of the clusters using a side-by-side bar chart.

## Dimensionality Reduction with PCA
- Created a PCA transformer and used it to reduce the dimensionality of the data in `X` to 2 components.

## Visualizing Clustering Results
- Plotted a scatter plot of `X_pca` to demonstrate the clustering performed by our K-Means model.

These steps provide a comprehensive overview of the customer segmentation analysis conducted in this notebook.
