# Remote Sensing
## Overview

This project was conducted as part of my MSc Data Science, which focuses on detecting and monitoring landscape changes—such as urbanization, deforestation, and agricultural expansion—using hyperspectral imagery from the Sentinel-2A satellite. Monitoring these changes is essential for managing environmental challenges and mitigating climate-related hazards. Satellite data, particularly from Sentinel-2A, provides a valuable resource for mapping Land Cover Land Use (LCLU) classes due to its high spatial resolution and multi-spectral capabilities.

## Objectives

The project aims to explore three unsupervised learning techniques to identify natural sub-groups or clusters of pixels corresponding to different LCLU classes:

1. Principal Component Analysis (PCA)
2. K-means Clustering
3. Clustering Large Applications (CLARA) Clustering

The project will compare the performance of these clustering techniques using different feature groups derived from the Sentinel-2A data, including:

* All spectral bands
* Selected spectral bands
* Vegetation indices
* Principal components (from PCA

## Methodology

1. **Data Source**: Sentinel-2A satellite imagery with a 10m spatial resolution, which enhances the accuracy of LCLU mapping.
2. **Feature Groups**: Several feature groups were chosen based on literature reviews, including spectral bands and vegetation indices like green leaf area index (LAI) and chlorophyll content (Ch), which are key indicators for monitoring vegetation cover.
3. **Clustering Performance**: The K-means and CLARA clustering algorithms will be used to segment pixels into LCLU classes. Clustering results are validated using the Silhouette Index (SI) to determine the optimal number of clusters and assess clustering accuracy.
4. **Comparison**: The project will assess the impact of dimensionality reduction (PCA) and feature selection on clustering performance. Results between K-means and CLARA will be evaluated using clustering validation methods.

## Goals

1. **Pixel-based Clustering**: Implement clustering of hyperspectral Sentinel-2A imagery using K-means and CLARA algorithms.
2. **Feature Analysis: Explore** the impact of feature selection and dimensionality reduction (PCA) on clustering outcomes.
3. **Performance Comparison**: Evaluate the performance of K-means and CLARA clustering using cluster validation techniques.
