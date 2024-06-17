# E-Customer Segmentation
A brief description of what this project does and who it's for

# Abstract

This repository explores methods of customer segmentation in ecommerce to enhance marketing strategies and optimize business decisions. It covers dataset details, applied methodologies (including clustering algorithms and statistical techniques), and key insights for improving ecommerce performance and customer satisfaction.
## Problem Statement

Given the e-commerce data, use k-means clustering algorithm to cluster customers with similar interest.
## Dataset Information

| Column   |            Description                   |
|----------|------------------------------------------|
| Cust_ID  | Unique Numbering of Customers            |
| Gender   | Gender of Customer                       |
| Orders   | No. of Past orders placed by the customer|


Remaining 35 features (brands) contains the number of times customers have searched them.
## Workflow

* First Import the necessary libraries needed for the project. Below are the libraries that I have used
    - import pandas as pd
    - import numpy as np
    - import matplotlib.pyplot as plt
    - import seaborn as sns
    - from sklearn.preprocessing import MinMaxScaler
    - from sklearn.metrics import silhouette_score
    - from sklearn.cluster import KMeans
    - from yellowbrick.cluster import KElbowVisualizer

* Load the dataset using pandas.
* Understand the data with basic statistics, info, total records, features and their data types also number of null values.
* Perform the data cleaning techniques like treating the missing values.
* Visualize the data with the help of Matplotlib or Seaborn to get better understanding of the features.
    - In my project I have used Seaborn's
    - Boxplot(To visualize the Outliers present in the data)
    - Barplot (To get to 10 customer ID based on Total searches)
    - Countplot (To get gender count and Prior orders count)
    - Heatmap (To find the Correlation)
    - Histogram (To get know how the data is distributed)

