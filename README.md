# Unsupervised Learning
# Project: Identify Customer Segments
# Source
Project 3 from Udacity's Intro to Machine Learning Nanodegree

# Description
Applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data that I used has been provided by Udacity's partners at Bertelsmann Arvato Analytics and represents a real-life data science task.

1. Assessed missing data and converted missing value codes to NaNs
2. Identified, and dropped features/samples that were outliers (features missing more than 20% of data)
3. Performed data wrangling and re-encoded categorical (via One-hot Encoding) and mixed features
4. Used an Imputer to replace all missing values
5. Applied feature scaling (via StandardScaler)
6. Applied PCA to find vectors of maximal variance and reduce dimensionality
7. Analyzed the ratio of explained variance accounted for by each principal component and decided to retain 20 principal components for clustering
8. Re-fitted a PCA instance on the determined transformation and reviewed the cumulative variance
9. Interpreted principal components to determine the most prominent features
10. Applied clustering (via KMeans) to the general population and used the Elbow Method to decide how many clusters to keep, then re-fit the K-means model with the selected         number of clusters
11. Mapped the customer data to the clusters for the general population (pre-processed, transformed features, applied clustering via PCA and KMeans from the general population,     and obtained cluster predictions for the customer demographic)
12. Compared customer demographic to the general population to see where the strongest customer base for the company is
13. Discovered ~200 features of people that are a suitable target audience for the company (also discovered 4 groups/clusters of people that aren't a suitable target audience       for the company)

# Install
This project requires Python 3.x and the following Python libraries installed:

NumPy
Pandas
Matplotlib
Seaborn
Scikit-Learn
You will also need to have software installed to run and execute an iPython Notebook

It's recommended to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.
