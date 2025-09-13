🧑‍🤝‍🧑 Customer Personality Analysis – EDA & Clustering
📌 Project Overview

This project focuses on Customer Personality Analysis using the Customer Personality Analysis dataset.
The main goal is to understand customer behavior, spending patterns, and preferences to create customer segments using clustering techniques.

By segmenting customers, businesses can tailor marketing strategies, product recommendations, and campaigns to specific groups, improving ROI.

🗂 Dataset

Source: Customer Personality Analysis Dataset

Attributes:

Demographics: Age, Education, Marital Status, Income, etc.

Products: Spending on Wines, Fruits, Meat, Fish, Sweets, Gold.

Promotion Response: Campaign acceptance history.

Channels: Web, Catalog, Store purchases, Website visits.

Complaints & Recency.

🔧 Steps in the Project

Data Preprocessing

Removed irrelevant columns (Z_CostContact, Z_Revenue).

Handled missing values (Income).

Created new features (Age, Total Spending, Family Size, Customer For).

Removed outliers.

Exploratory Data Analysis (EDA)

Univariate & bivariate analysis of demographics, spending behavior, and purchase channels.

Visualizations with Seaborn, Matplotlib, and Plotly.

Clustering

Scaled numerical features.

Applied K-Means Clustering (optimal K chosen using Silhouette Score & Elbow Method).

Performed Hierarchical Clustering for comparison.

Cluster profiling to describe segment behavior.

📊 Key Insights

High-income customers spend more on wines and luxury items.

Families with children prefer catalog and store purchases.

Younger customers prefer the web channel.

Some customer groups are more campaign-responsive, guiding better marketing targeting.

📂 Project Structure
├── customer-analysis-eda-report-clustering.ipynb   # Main Jupyter Notebook
├── customer_analysis_report_updated.pdf            # Detailed PDF Report
├── README.md                                       # Project Documentation

🚀 Tech Stack

Python

Libraries: Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-learn

Clustering: K-Means, Hierarchical Clustering

📌 How to Run

Clone the repo:

git clone https://github.com/your-username/customer-personality-analysis.git
cd customer-personality-analysis


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook customer-analysis-eda-report-clustering.ipynb

✅ Summary in 3 Points

Data Cleaning & Feature Engineering – Handled missing values, created derived features, and removed outliers.

EDA – Analyzed demographics, spending behavior, and channel usage with visualizations.

Clustering & Segmentation – Applied K-Means (Silhouette Score for optimal K) & Hierarchical Clustering to build meaningful customer segments.

