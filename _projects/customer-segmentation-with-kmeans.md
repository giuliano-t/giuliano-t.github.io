---
layout: default
title: "Customer Segmentation using Unsupervised Learning"
stack: "Python, K-Means, Clustering, Data Analysis"
priority: "minor"
date: 2024-12-15
github: https://github.com/giuliano-t/Customer-Segmentation-with-KMeans
---

## Unlocking Business Insights with Customer Segmentation

To move beyond a "one-size-fits-all" marketing strategy, this project segmented a customer base into distinct groups based on their purchasing behavior. The goal was to provide actionable insights for **targeted ad campaigns, personalized promotions, and customer retention strategies**.

Five new features were engineered: purchase **Frequency** and **Recency**, **CLV**, **Average Purchase Cost** and **Customer Age**.

The analysis used **unsupervised machine learning** with **K-Means clustering**. The **Elbow and Silhouette methods** guided the choice of the optimal number of segments. To handle high-dimensional data and enable clear visualization, I applied dimensionality reduction with **PCA and t-SNE**.

The final model identified **five distinct customer personas**:

- **Core loyal customers**, who bought cheaper items more frequently and recently
- **High-value spenders**, who bought more expensive items less frequently
- **Older and potential churn risk customers**, whose purchases were less recent and so might be leaving the customer base
- **Two overlapping clusters**, both consisting of customers who recently purchased lower-cost items, differentiated primarily by age.

![Customer Segments PCA Plot](/assets/images/customer_segments.png)

![Customer Segments t-SNE Plot](/assets/images/kmeans_other_image.png)

---

## Tech Stack

- **Algorithms**: K-Means Clustering, Elbow and Silhouette Methods
- **Dimensionality Reduction**: PCA, t-SNE  
- **Libraries**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn  

---

[🔗 View on GitHub](https://github.com/giuliano-t/Customer-Segmentation-with-KMeans)
