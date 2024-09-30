# Retail Customer Segmentation with Machine Learning

## Project Overview
This project focuses on segmenting customers based on their purchasing behavior using **KMeans clustering**. The dataset consists of retail transactions from 2010-2011, and the goal is to identify customer groups that can be targeted for personalized marketing and retention strategies.

## Features
- **Data Cleaning**: Handling missing values, correcting anomalies (negative prices/quantities), and ensuring proper formatting of invoice data.
- **Feature Engineering**: Deriving new features like Total Purchase Value, Purchase Frequency, and Average Order Value to better understand customer behavior.
- **Clustering**: Using KMeans to cluster customers into meaningful segments, with the optimal number of clusters determined by the **silhouette score**.

## Key Results
The analysis produced three customer segments:
1. **High-Value Customers**: Frequent buyers who make large purchases.
2. **Occasional Buyers**: Customers who shop infrequently but may have significant value.
3. **Low-Value Shoppers**: Less frequent buyers with smaller purchase volumes.

## Installation & Usage
pip install -r requirements.txt

## Dependencies
- pandas
- matplotlib
- seaborn
- scikit-learn
  
## Conclusion
This project showcases how machine learning can help businesses better understand and target their customers. By analyzing purchasing behavior, companies can create strategies tailored to different customer groups, leading to more effective marketing and higher retention.

