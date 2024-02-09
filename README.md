# customer_segmentation

## Getting Started

## Project Summary: Customer Segmentation Using RFM Analysis and Clustering

In this project, I implemented customer segmentation techniques to analyze and categorize customer behavior for targeted marketing strategies.

## Data Preprocessing:
Loaded and cleaned customer transaction data.
Engineered three essential features: Recency, Frequency, and Monetary (RFM) to quantify customer behavior.

## RFM Analysis:
Applied percentile-based clustering to categorize customers into segments based on RFM scores.
Utilized hard-coded percentile values for RFM clustering.

## KMeans Clustering:
Implemented KMeans clustering on RFM data to identify distinct customer segments.
Evaluated the optimal number of clusters using the elbow method and silhouette scores.

## Comparative Analysis:
Compared KMeans clustering results with the percentile-based clustering.
Explored the characteristics of each cluster, examining Recency, Frequency, and Monetary features.

## Log Transformation:
Applied log transformation to address left-skewness in RFM feature distributions.
Investigated the impact of log transformation on clustering results.

## Cluster Evaluation:
Evaluated clustering models using silhouette scores to measure the coherence of clusters.

## Cluster Assignment for New Data:
Developed a function for assigning new data points to clusters based on the trained KMeans model.

## Technical Skills:
Demonstrated proficiency in Python, utilizing libraries such as pandas, scikit-learn, and seaborn.
Implemented various clustering algorithms and performed exploratory data analysis.

# Prerequisites
Ensure you have the following dependencies installed:
Python (version x.x.x)
Pandas
NumPy
Scikit-Learn
Matplotlib
Seaborn

# Installation
Clone the repository and run the notebook!
