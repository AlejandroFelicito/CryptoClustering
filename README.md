
# CryptoClustering
Module 19 Challenge


## Description 
**CryptoClustering** solution, due 2/15/2024


## Before you begin 
1. Create a new repository for this project called **CryptoClustering**. Do not add this homework to an existing repository.
2. Clone the new repository to your computer.
3. Push your changes to GitHub. 


## Instructions 
1. Rename the _Crypto_Clustering_starter_code.ipynb_ file as _Crypto_Clustering.ipynb_
2. Load the _crypto_market_data.csv_ into a DataFrame
3. Get the summary statistics and plot the data to see what the data looks like before proceeding.


## Requirements 
### Find the Best Value for k by Using the Original Data (15 points)
To receive all points, you must:
- [X] Code the elbow method algorithm to find the best value for k. Use a range from 1 to 11. (5 points)
- [X] To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k. (5 points)
- [X] Answer the following question: What’s the best value for k? (5 points)


### Cluster the Cryptocurrencies with K-Means by Using the Original Data (10 points)
To receive all points, you must:
- [X] Initialize the K-means model with four clusters by using the best value for k. (1 point)
- [X] Fit the K-means model by using the original data. (1 point)
- [X] Predict the clusters for grouping the cryptocurrencies by using the original data. Review the resulting array of cluster values. (3 points)
- [X] Create a copy of the original data, and then add a new column of the predicted clusters. (1 point)
- [X] Using hvPlot, create a scatter plot by setting _x="price_change_percentage_24h"_ and _y="price_change_percentage_7d"_. Color the graph points with the labels that you found by using K-means. Then add the crypto name to the _hover_cols_ parameter to identify the cryptocurrency that each data point represents. (4 points)


### Optimize the Clusters with Principal Component Analysis (10 points)
To receive all points, you must:
- [X] Create a PCA model instance, and set _n_components=3_. (1 point)
- [X] Use the PCA model to reduce the features to three principal components. Then review the first five rows of the DataFrame. (2 points)
- [X] Get the explained variance to determine how much information can be attributed to each principal component. (2 points)
- [X] Answer the following question: What’s the total explained variance of the three principal components? (3 points)
- [X] Create a new DataFrame with the PCA data. Be sure to set the _coin_id_ index from the original DataFrame as the index for the new DataFrame. Review the resulting DataFrame. (2 points)


### Find the Best Value for k by Using the PCA Data (10 points)
To receive all points, you must:
- [X] Code the elbow method algorithm, and use the PCA data to find the best value for k. Use a range from 1 to 11. (2 points)
- [X] To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k. (5 points)
- [X] Answer the following questions: What’s the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data? (3 points)


### Cluster the Cryptocurrencies with K-means by Using the PCA Data (10 points)
To receive all points, you must:
- [X] Initialize the K-means model with four clusters by using the best value for k. (1 point)
- [X] Fit the K-means model by using the PCA data. (1 point)
- [X] Predict the clusters for grouping the cryptocurrencies by using the PCA data. Review the resulting array of cluster values. (3 points)
- [X] Create a copy of the DataFrame with the PCA data, and then add a new column to store the predicted clusters. (1 point)
- [X] Using hvPlot, create a scatter plot by setting _x="PC1"_ and _y="PC2"_. Color the graph points with the labels that you found by using K-means. Then add the crypto name to the _hover_cols_ parameter to identify the cryptocurrency that each data point represents. (4 points)


### Visualize and Compare the Results (15 points)
To receive all points, you must:
- [] Create a composite plot by using hvPlot and the plus sign (+) operator to compare the elbow curve that you created from the original data with the one that you created from the PCA data. (5 points)
- [] Create a composite plot by using hvPlot and the plus (+) operator to compare the cryptocurrency clusters that resulted from using the original data with those that resulted from the PCA data. (5 points)
- [] Answer the following question: Based on visually analyzing the cluster analysis results, what’s the impact of using fewer features to cluster the data by using K-means? (5 points)


### Coding Conventions and Formatting (10 points)
To receive all points, you must:
- [X] Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. (3 points)
- [X] Name functions and variables with lowercase characters, with words separated by underscores. (2 points)
- [] Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. (3 points)
- [X] Use concise logic and creative engineering where possible. (2 points)


### Deployment and Submission (10 points)
To receive all points, you must:
- [] Submit a link to a GitHub repository that’s cloned to your local machine and that contains your files. (4 points)
- [X] Use the command line to add your files to the repository. (3 points)
- [X] Include appropriate commit messages in your files. (3 points)


### Code Comments (10 points)
To receive all points, you must:
- [X] Be well commented with concise, relevant notes that other developers can understand. (10 points)


## Submission 
To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.


## Credits 
* Received comments and guidance from Instructor, Teaching Assistant 
* Used StackOverflow, module documentation, class activities for specific details
