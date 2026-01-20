# Delivery Time Variance Clustering

## Project Description
This project focuses on analyzing delivery time patterns by clustering deliveries based on their behavior. Using delivery pickup and drop-off timestamps, the project identifies groups of deliveries with similar average delivery time, variance, and weekday vs weekend patterns. The goal is to understand delivery performance and highlight potential delay issues using data-driven techniques.

## Assumption
Since an actual dataset was not provided, a realistic sample delivery dataset was generated and stored in a MySQL database. This approach was used to demonstrate the complete end-to-end workflow expected for real-world data.

## Technologies Used
- MySQL  
- Python  
- pandas  
- scipy  
- seaborn  

## Workflow
1. Generated a realistic delivery dataset and stored it in MySQL.
2. Extracted delivery logs from MySQL into Python using SQLAlchemy.
3. Cleaned and processed timestamp data using pandas.
4. Engineered key features such as:
   - Average delivery time  
   - Delivery time variance  
   - Weekday vs weekend indicator
5. Normalized the data and applied hierarchical clustering using scipy.
6. Visualized delivery patterns using dendrograms and boxplots with seaborn.
7. Exported final cluster assignments into a CSV file.

## Deliverables
- Jupyter Notebook containing the full analysis and clustering process  
- CSV file mapping each delivery ID to a cluster  
- Visualizations explaining delivery time behavior  

## Key Insights
- Identified clusters representing on-time, moderately delayed, and highly inconsistent deliveries.
- Highlighted how delivery variance differs between weekday and weekend deliveries.
- Demonstrated how clustering can help detect operational inefficiencies.

## Conclusion
This project demonstrates an end-to-end data analysis and clustering workflow using SQL and Python. The same approach can be directly applied to real production delivery datasets to support data-driven decision-making.

## To run this Set Your MySQL setup here to run this.
