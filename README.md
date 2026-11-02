🛒 E-Commerce Customer Segmentation Using RFM

A Machine Learning case study that segments e-commerce customers using **RFM Analysis, K-Means, and DBSCAN clustering**. The project uses **PCA and t-SNE** for dimensionality reduction and visualization, and derives actionable marketing personas to help businesses improve customer engagement and retention.

📌 Project Overview

Understanding customer purchasing behavior is essential for successful marketing strategies. This project analyzes customer data to identify different customer segments based on their purchasing patterns.

By applying clustering algorithms, customers are grouped into meaningful segments, allowing businesses to design personalized marketing campaigns, improve customer retention, and maximize revenue.

🎯 Objectives

- Perform data cleaning and preprocessing.
- Calculate Recency, Frequency, and Monetary (RFM) features.
- Apply feature scaling to prepare data for clustering.
- Implement K-Means and DBSCAN clustering algorithms.
- Determine optimal clusters using the Elbow Method and Silhouette Score.
- Apply PCA for dimensionality reduction.
- Visualize customer segments using t-SNE.
- Develop customer personas and actionable marketing strategies.

📊 Dataset

The project uses the Customer Personality Analysis dataset (marketing_campaign.csv).

The dataset contains customer information, purchase recency, spending across product categories, and purchasing activity across different channels.

RFM Features

| Feature | Description |
|---|---|
| Recency | Number of days since the last purchase |
| Frequency | Estimated purchase frequency using channel purchase counts |
| Monetary | Total spending across product categories |

Note: Frequency is calculated using available purchase-channel count columns because the dataset does not contain individual transaction-level records.

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

🤖 Machine Learning Techniques

1. K-Means Clustering
Groups customers into clusters based on similarities in their RFM characteristics.

2. DBSCAN Clustering
Identifies dense customer groups and detects unusual observations as noise points.

3. PCA (Principal Component Analysis)
Reduces the dimensionality of scaled RFM features into two principal components for visualization.

4. t-SNE
Creates a two-dimensional representation to visualize customer segment patterns.

📈 Methodology

1. Dataset loading and exploration.
2. Data cleaning and preprocessing.
3. RFM feature engineering.
4. Feature scaling using StandardScaler.
5. Optimal cluster selection using the Elbow Method and Silhouette Score.
6. Customer segmentation using K-Means.
7. Density-based clustering using DBSCAN.
8. Dimensionality reduction using PCA.
9. Cluster visualization using t-SNE.
10. Customer profiling and marketing persona generation.

 💡 Marketing Personas

The project derives customer personas from the actual RFM cluster profiles.

Possible marketing strategies include:

- High-Value Customers:** VIP rewards, loyalty benefits, and exclusive offers.
- Loyal Customers:** Personalized recommendations and retention campaigns.
- At-Risk Customers:** Win-back campaigns and targeted discounts.
- Low-Engagement Customers:** Customer onboarding and second-purchase incentives.
- Potential-Growth Customers:** Product recommendations and promotional bundles.

📂 Project Structure


E-Commerce-Customer-Segmentation/
│
├── Customer_Segmentation_Lab_Corrected.ipynb
├── marketing_campaign.csv
└── README.md


📊 Expected Outcomes

- Identification of meaningful customer segments.
- Comparison of K-Means and DBSCAN clustering.
- PCA and t-SNE visualizations.
- Customer cluster profiling.
- Data-driven marketing personas.
- Actionable recommendations for customer retention and engagement.

⚠️ Limitations

- Frequency is an estimate derived from purchase-channel counts, not exact transaction-level order frequency.
- DBSCAN performance depends on parameter selection.
- PCA and t-SNE are used for visualization and do not independently establish cluster quality.
- Marketing personas are rule-based interpretations and should be validated through real campaign experiments.

🚀 Future Improvements

- Use transaction-level e-commerce datasets for exact RFM calculations.
- Optimize DBSCAN parameters.
- Develop an interactive customer segmentation dashboard.
- Evaluate marketing strategies using A/B testing.
- Track customer retention and revenue improvements.

👨‍💻 Author

Utsav Rai

B.Tech CSE (AI & ML)

---

⭐ If you find this project useful, consider giving this repository a star!
