# Customer Segmentation Analysis

This repository contains the code and analysis for a customer segmentation project using data related to customer demographics and financial attributes. The goal of the project was to identify distinct customer segments based on various attributes, which could be valuable for targeted marketing strategies.

## Project Overview

The project involved:
- **Data Cleaning and Preprocessing**: Standardizing and preparing the dataset for analysis.
- **Dimensionality Reduction**: Using Principal Component Analysis (PCA) to reduce the dimensionality of the data while retaining key patterns.
- **Clustering**: Identifying customer segments using unsupervised learning techniques (e.g., k-means clustering).
- **Segmentation Analysis**: Grouping customers into four distinct clusters based on demographic and financial factors.

## Data Used

The dataset includes the following key columns:
- `Age`
- `Education`
- `Years Employed`
- `Income`
- `Card Debt`
- `Other Debt`
- `Debt-to-Income Ratio`
- `Behavioral Data`

## Key Findings

After analyzing the data, four distinct customer clusters were identified:
1. **Cluster 1**: Younger customers with moderate income and lower debt-to-income ratios.
2. **Cluster 2**: Highly educated, higher-income customers with significant debts.
3. **Cluster 3**: Middle-aged customers with stable employment and low debt.
4. **Cluster 4**: Older customers with substantial debt but high income levels.

Each segment's key attributes, such as average age, income, education level, and debt profile, were analyzed in detail.

## Technologies Used

- **Python**: For data analysis, preprocessing, and clustering (`Pandas`, `Scikit-learn`, etc.).
- **Jupyter Notebook**: For running the code and presenting the analysis.

## Future Improvements
Some additional refinements and adjustments may be made to the analysis, such as:
- Optimizing the number of clusters.
- Incorporating new features into the segmentation process.

## Conclusion
This project provides a comprehensive view of how customer data can be used to create meaningful segments, which can aid businesses in crafting more effective marketing strategies.
