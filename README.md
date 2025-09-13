Customer Personality Analysis – EDA & Clustering

This project focuses on Customer Personality Analysis using the Customer Personality Analysis dataset from Kaggle. The goal is to understand customer behavior, spending patterns, and preferences, and then segment customers into meaningful groups using clustering techniques. By identifying these customer segments, businesses can design personalized marketing strategies, improve product targeting, and maximize return on investment.

The dataset contains customer demographic details such as age, education, marital status, and income, along with product-level spending on categories like wines, fruits, meat, fish, sweets, and gold. It also includes customer responses to marketing campaigns, purchase channels (web, catalog, and store), complaints, and recency of purchase.

The workflow of the project begins with data preprocessing, where irrelevant columns such as Z_CostContact and Z_Revenue were removed, missing values in the Income column were handled, new features like Age, Total Spending, Family Size, and Customer For were created, and outliers were treated. This was followed by exploratory data analysis (EDA), which explored the distribution of demographics, income, and spending behavior, as well as purchase channel preferences and campaign responses. Visualizations were created using Seaborn, Matplotlib, and Plotly to make the findings more interpretable.

For segmentation, the dataset was standardized and clustering was applied. K-Means clustering was performed, with the optimal number of clusters chosen using the Silhouette Score and Elbow Method. Hierarchical clustering was also carried out for comparison. The resulting clusters were profiled to reveal distinct customer groups, such as high-income luxury spenders, families with children preferring catalog and store purchases, younger customers who use the web channel more, and campaign-responsive segments.

In summary, this project demonstrates the complete pipeline of customer analysis starting from cleaning and feature engineering, to exploratory analysis, and finally customer segmentation using clustering. The three main contributions are: (1) Data cleaning and feature engineering to prepare a high-quality dataset, (2) Exploratory analysis to uncover customer demographics, spending behavior, and preferences, and (3) Clustering and segmentation using K-Means with Silhouette Score and Hierarchical clustering to identify actionable customer groups for targeted marketing strategies.


