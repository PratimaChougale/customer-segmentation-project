Customer Segmentation Using Machine Learning (K-Means Clustering)

A complete end-to-end Data Science project to segment customers based on purchasing behavior using K-Means clustering. This project helps businesses understand customer groups to improve marketing strategy, personalize offers, and increase revenue.

📌 Project Overview

Customer segmentation is one of the most important applications of machine learning in marketing.
In this project, we analyzed the features of mall customers and grouped them into distinct clusters using unsupervised learning.

This project includes:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Finding optimal number of clusters (Elbow Method)
- Training K-Means clustering model
- Visualizing cluster groups
- Business insights for each customer group

Dataset Information:
Dataset Name: Mall Customers Dataset
Columns:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)
This dataset is commonly used for unsupervised clustering projects.

Exploratory Data Analysis (EDA)
Performed to understand:
- Age distribution
- Income distribution
- Gender proportions
- Spending behavior
- Correlations between income & spending

Important visualizations:
- Histograms
- Pairplots
- Scatter plots
- Boxplots

Modeling (K-Means Clustering)
1. Feature Selection
We used:
- Age
- Annual Income (k$)
- Spending Score (1–100)

2. Finding Optimal K
Used Elbow Method to choose the best number of clusters.

3. Model Training
Trained a K-Means model with optimal K (usually 5 clusters).

4. Visualization
Created:
- 2D cluster plot
- 3D cluster visualization
- Centroid visualization

Cluster Insights (Business Ready)
✔ Cluster 0 — High Income, High Spending
Premium customers → target for luxury products.

✔ Cluster 1 — Low Income, Low Spending
Budget-focused → offer discounts or loyalty programs.

✔ Cluster 2 — High Income, Low Spending
Price-sensitive affluent customers → targeted promotions may help.

✔ Cluster 3 — Young, High Spending
Trendy, high-engagement audience → ideal for fashion & lifestyle products.

✔ Cluster 4 — Average Income, Average Spending
Middle-tier customers → can be pushed into premium category with offers.

Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

How to Run This Project
Clone this repository:
git clone https://github.com/yourusername/customer-segmentation-project.git

Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook

Results:
The model successfully classified customers into 5 meaningful segments that help businesses:

Improve targeted marketing:
Increase ROI

Personalize communication:
Understand customer behavior


Author:

Pratima Jitendra Chougale

Freelance Data Analyst

📧 Email: chougalepratima@gmail.com
