# Credit Card Customer Segmentation with K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.8+-green)
![Jupyter Notebook](https://img.shields.io/badge/Tools-Jupyter%20Notebook-orange)
![Scikit-learn](https://img.shields.io/badge/Library-Scikit--learn-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-lightblue)

## Project Overview
This project focuses on segmenting credit card customers using K-Means Clustering, a popular unsupervised machine learning algorithm. By analyzing customer data, we aim to group customers with similar purchasing behaviors into distinct clusters. This segmentation helps businesses understand their customer base better and allows for more personalized marketing strategies.



## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Features](#features)
- [Dataset Description](#dataset-description)
- [K Means Clustering](#k-means-clustering)
- [Model Evaluation](#model-evaluation)
- [Reasult](#reasult)
- [Contact](#contact)


## Introduction
Credit card companies deal with diverse customer behaviors, and understanding these behaviors is essential for providing better services. Customer Segmentation is a process of dividing customers into distinct groups with similar characteristics. Using K-Means Clustering, this project segments customers based on various features like their spending habits, frequency of purchases, and other behaviors.

This segmentation helps in:
Identifying high-value customers
Personalizing marketing campaigns
Optimizing product recommendations
Managing customer retention strategies

## Objective
The primary objectives of this project are:

-To apply K-Means Clustering to segment credit card customers based on their behavior.

-To interpret the clusters and provide actionable insights for better decision-making.

-To visualize the clusters and evaluate their validity using metrics like the elbow method and silhouette score.


# Features
- Unsupervised Learning: Uses the K-Means Clustering algorithm for customer segmentation.
  
- Data Preprocessing: Handles missing values, data scaling, and feature selection.
  
- Visualization: Provides insights into the clusters formed using various plots.
  
- Evaluation: Uses metrics like the elbow method and silhouette score to evaluate the clustering performance.
  
## Dataset Description
This dataset contains credit card transaction data for a set of customers. Each record provides details on various aspects of the customers' credit card usage, including balance, purchases, cash advances, and payment history. The dataset has the following columns:

-  CUST_ID:      A unique identifier for each customer (e.g., C10001, C10002, etc.).

-  BALANCE:     The current balance on the customer's credit card account.

-  PURCHASES:    The total amount of purchases made by the customer during the billing period.

-  INSTALLMENTS_PURCHASES:    The amount of purchases made by the customer that are paid in installments.

-  CASH_ADVANCE:    The total amount of cash advances taken by the customer during the billing period.

-  CREDIT_LIMIT:    The credit limit assigned to the customer's credit card.

-  PAYMENTS:    The total amount of payments made by the customer towards the credit card balance.

-  MINIMUM_PAYMENTS:     The minimum amount the customer is required to pay during the billing period.

-  TENURE:     The number of months the customer has had the credit card account (e.g., 12 months).


## K-Means Clustering

K-Means Clustering is a partition-based clustering algorithm that divides a dataset into K distinct, non-overlapping clusters. The goal of the algorithm is to minimize the within-cluster variance by grouping similar data points together.

Steps in the K-Means algorithm:

- Initialization: Select K random points as the initial centroids.
- 
- Assignment: Each data point is assigned to the nearest centroid based on the Euclidean distance.
- 
- Centroid Update: The centroids are recalculated as the mean of all points in the cluster.
- 
- Repeat: Steps 2 and 3 are repeated until the centroids no longer change or the maximum number of iterations is reached.
  
The result is a set of K clusters, where each data point belongs to the cluster whose centroid is nearest to it.


## Model Evaluation 

- #### The Elbow Method
  
 The Elbow method is a method of interpretation and validation of consistency within cluster analysis designed to help find the appropriate number of clusters in a dataset
  
![elbove method](https://github.com/user-attachments/assets/fa16b8f9-89e7-4155-8354-6f64875add93)

#### Silhouette Score

The Silhouette Coefficient is calculated using the mean intra-cluster distance (a) and the mean nearest-cluster distance (b) for each sample. The Silhouette Coefficient for a sample is (b - a) / max(a, b). To clarify, b is the distance between a sample and the nearest cluster that the sample is not a part of. Note that Silhouette Coefficient is only defined if number of labels is 2 <= n_labels <= n_samples - 1.

![sillicore](https://github.com/user-attachments/assets/7367b2b1-53a7-4955-9714-79e336091a66)

## Reasult
The results of the K-Means Clustering model depend on how well the data points are grouped into distinct clusters based on their similarity. Below is an example of how to present the results and insights from applying K-means clustering to a dataset.

![radar chat](https://github.com/user-attachments/assets/7f7b20ef-8c69-4a37-bce7-6cbf9eeac519)

#### Summary of the Clusters:

- Cluster 0 (Red): Likely represents high-spending customers who prefer installment purchases and are more financially stable, with lower balances and higher installment-based purchases.
  
- Cluster 1 (Green): Represents low-activity customers who use their credit cards less frequently and have lower balances and credit limits.
  
- Cluster 2 (Blue): Likely represents high-balance customers who tend to carry a large outstanding balance, make minimum payments, and have been using the card for a long period


## Contact

- **Author**: Muhammad Yasir Saleem
- **Email**: myasirsaleem94@gmail.com
- **LinkedIn**:https://www.linkedin.com/in/muhammad-yasir-saleem/

Feel free to reach out if you have any questions or need further information.












