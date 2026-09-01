# Customer Segmentation Analysis

## Overview

This project uses Python and machine learning to segment customers based on demographics, purchasing behavior, and marketing campaign data. The goal is to identify groups of customers with similar characteristics to better understand spending patterns and campaign effectiveness.

## Objectives

* Clean and preprocess customer marketing data
* Perform feature engineering to create meaningful customer metrics
* Reduce dimensionality using Principal Component Analysis (PCA)
* Apply clustering algorithms to identify customer segments
* Visualize customer groups and analyze their characteristics

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Yellowbrick

## Data Preparation

The dataset was prepared by:

* Removing missing values
* Converting date fields
* Engineering new features such as customer age, total spending, family size, and customer tenure
* Encoding categorical variables
* Removing outliers
* Standardizing numerical features

## Machine Learning

The project applies several machine learning techniques, including:

* StandardScaler for feature scaling
* Principal Component Analysis (PCA) for dimensionality reduction
* K-Means (Elbow Method) to estimate the optimal number of clusters
* Agglomerative Clustering for customer segmentation

## Visualizations

The project includes visualizations such as:

* Pair plots
* 3D PCA projection
* Cluster distribution
* Income vs. spending analysis
* Spending by customer segment
* Promotion acceptance by cluster
* Customer demographic comparisons

## Results

The clustering model grouped customers into distinct segments based on purchasing behavior, income, demographics, and marketing engagement. These insights can help support targeted marketing strategies and customer relationship management.

## Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Dimensionality Reduction (PCA)
* Customer Segmentation
* Unsupervised Machine Learning
* Clustering Analysis
* Python Data Analysis
