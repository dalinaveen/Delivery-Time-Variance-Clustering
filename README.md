# Delivery Time Variance Clustering

## Overview
This project analyzes delivery time patterns by clustering deliveries based on their average delivery time, variance, and weekday vs weekend behavior. The goal is to identify delivery performance patterns and potential delay issues using hierarchical clustering.

## Assumption
Since an actual dataset was not provided, a realistic sample delivery dataset was created and stored in a MySQL database to demonstrate the complete workflow.

## Tools & Technologies
- MySQL
- Python
- pandas
- scipy
- seaborn
- matplotlib

## Approach
1. Created a sample delivery dataset and stored it in MySQL.
2. Extracted delivery logs into Python using SQLAlchemy.
3. Engineered features such as average delivery time, variance, and weekend indicator.
4. Normalized the data and applied hierarchical clustering.
5. Visualized clusters using dendrograms and boxplots.
6. Exported final cluster assignments to a CSV file.

## Deliverables
- Jupyter Notebook with full analysis and clustering steps
- CSV file mapping each delivery to a cluster
- Visualizations and insights

## Outcome
The clustering reveals distinct delivery patterns, helping identify on-time, moderately delayed, and highly inconsistent deliveries.
