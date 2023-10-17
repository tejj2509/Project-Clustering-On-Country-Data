# Country Data Clustering and Dendrogram

## Overview

This dataset contains information about 167 countries, including various socio-economic and health indicators. In this project, we applied K-Means clustering to classify countries into three groups: those needing the most help, those needing less or moderate help, and countries needing the least or no help. Additionally, in this project, created a dendrogram to visualize the hierarchical clustering structure of the data.

## Content

The dataset includes the following columns:

- `Country`: The name of the country.
- `Child_Mortality_Rate`: The child mortality rate in the country.
- `Exports`: Exports as a percentage of GDP.
- `Health`: Total health expenditure as a percentage of GDP.
- `Imports`: Imports as a percentage of GDP.
- `Income`: Per capita income.
- `Inflation`: Inflation rate.
- `Life_Expectancy`: Life expectancy at birth.
- `Fertility_Rate`: Fertility rate.
- `GDP`: Gross Domestic Product (GDP).

## Clustering Results

We performed K-Means clustering with `k=3` to classify countries into three clusters based on the socio-economic and health indicators. The clusters represent:

- Cluster 1: Countries needing the most help.
- Cluster 2: Countries needing less or moderate help.
- Cluster 3: Countries needing the least or no help.

The results of the clustering analysis can be found in the `clustering_results.csv` file, which includes the cluster labels assigned to each country.

## Dendrogram

To gain insights into the hierarchical structure of the data, we generated a dendrogram. The dendrogram visualizes the relationships between countries at different levels of similarity. This can help in understanding the hierarchy of countries and identifying the optimal number of clusters. The dendrogram can be found in the `dendrogram.png` image file.

## Usage

This dataset and the clustering results can be used for various purposes, including:

- Analyzing and visualizing the socio-economic development of different countries.
- Understanding the hierarchical relationships between countries.
- Identifying countries that may require various levels of assistance.
- 

## Acknowledgments

- The original dataset was obtained from (https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data).
- Special thanks to contributors to the data source and the scikit-learn library for clustering algorithms.
