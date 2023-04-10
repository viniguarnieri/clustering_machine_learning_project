# Clustering Project

# 1. Business Problem
### Introduction
  The challenge is to separate a dataset consisting of three numeric features (A, B, and C) into clusters. For that it is necessary to identify the number of discrete clusters present in the data, and create a clustering model that separates the data into that number of clusters. After that it has to be possible to visualize the clusters to evaluate the level of separation achieved by the model.

# 2. Solution Strategy
  My strategy to solve this challenge was:
  
  **Step 01.** *Data Description:* My goal is to use methods to predict the correct number of clusters and then show the separated data in clusters. 
  
  **Step 02.** *Data Filtering:* Check if the data does not have empty rows.
  
  **Step 03.** *Data Preparation:* Prepare the data, normalizing and making them bidimensional so that the Machine Learning models can run correctly.
  
  **Step 04.** *Number of clusters:* Use the Elbow Method along with Silhouette score to identify the correct number of clusters.
  
  **Step 05.** *Machine Learning:* Use a Machine Learning algorithm to divide the data in the number of clusters found.
  
  **Step 06.** *Plot the results:* Plot the clusters.

# 4. Machine Learning Model Applied
- K-Means clustering algorithm
  
# 5. Machine Learning Model Performance 
### Metrics
- Elbow Method
<div align="center">
<img src="https://user-images.githubusercontent.com/126209562/230824596-dc496d0c-8a6f-4efd-8cd3-7d3a7aa07a38.png" width="600px" />
</div>

#

- Silhouette score

| Number of clusters | Silhouette score |
| ------------- | ------------- |
| 3 | 0.3840 |
| 4 | 0.3258 |
| 5 | 0.2908 |

- Number of clusters: 4

# 6. Results 
- Clusters plotted
  <div align="center">
<img src="https://user-images.githubusercontent.com/126209562/230824836-d42cea9a-ff8c-4f3c-af72-f02c76c02575.png" width="600px" />
</div>
