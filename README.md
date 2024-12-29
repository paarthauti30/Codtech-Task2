# Codtech-Task2
Overview of the Project
Project: Customer Segmentation using K-Means Clustering

Objective
The objective of this project is to perform customer segmentation on retail data using K-Means clustering. The aim is to identify distinct customer groups based on their annual income and spending scores, enabling targeted marketing strategies and improved customer relationship management.

Key Activities

Data Cleaning:
Removed unnecessary columns (CustomerID, Gender).
Handled missing values by filling them with the mean of respective columns.
Data Scaling:
Standardized the data using StandardScaler to ensure all features contribute equally to the distance calculations in clustering.
K-Means Clustering:
Implemented the elbow method to determine the optimal number of clusters.
Applied K-Means clustering to segment customers into distinct groups.
Visualization:
Created scatter plots to visualize customer segments based on annual income and spending scores.
Segment Analysis:
Analyzed each cluster to derive insights on average income, spending scores, and the number of customers in each segment.
![number of cluster](https://github.com/user-attachments/assets/b8ab54a2-d2ad-4b74-9aff-30c5bbee3874)
![customer segmentation](https://github.com/user-attachments/assets/63c06eca-f5b7-47c4-89a6-a4f467fcb95e)

Technologies Used

Python: The primary programming language for data analysis.
pandas: Used for data manipulation and analysis.
matplotlib: Employed for data visualization.
scikit-learn: Utilized for implementing K-Means clustering and data scaling.
Key Insights

Customer Group Identification: The clustering process revealed distinct customer segments, allowing for tailored marketing strategies.
Income and Spending Patterns: Analysis of clusters provided insights into the relationship between annual income and spending behavior.
Data-Driven Decision Making: The segmentation results can guide business decisions, enhancing customer engagement and retention strategies.
This project provides a comprehensive understanding of customer segmentation techniques, paving the way for more advanced analyses and targeted marketing initiatives in the retail sector.
