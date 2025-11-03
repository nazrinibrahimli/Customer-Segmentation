# Customer-Segmentation
In the Customer Segmentation project, I implemented K-Means clustering on the Telco dataset to segment customers, achieving 3 distinct groups based on tenure, charges, and contract types. Visualization and silhouette scoring (peak ~0.3) confirmed the segmentation, supporting targeted marketing or retention strategies. Computed cluster means for numeric features (tenure, MonthlyCharges, TotalCharges) to profile customer segments, resolving data type errors with selective aggregation.

Features: Uses tenure, MonthlyCharges, TotalCharges, Contract, and PaymentMethod to segment customers.
Preprocessing: Scales numerical data and one-hot encodes categorical data for K-Means.
K-Means: Clusters data into groups; silhouette score helps pick the best number of clusters.
Visualization: Plots show clusters based on tenure and MonthlyCharges, with a silhouette score graph to justify cluster choice.


<img width="800" height="600" alt="cluster_plot" src="https://github.com/user-attachments/assets/b37a29f8-8dd2-4d1f-8387-f7c9900c868f" />
<img width="1000" height="800" alt="3d_cluster_plot" src="https://github.com/user-attachments/assets/920726ba-1df1-418e-a011-149119bf4657" />
<img width="600" height="400" alt="silhouette_plot" src="https://github.com/user-attachments/assets/42d2da6f-8b6f-4828-9606-3d0472f92560" />


Insights:
Cluster 0: Moderate tenure, Low Charges. Tenure 28.60 months, MonthlyCharges 27.85$, TotalCharges 801.74$. Business use: Focus on retention to prevent customers from switching to competitor companies. 
Cluster 1: High Tenure, High Charges. Tenure 58.82 months, MonthlyCharges 89.67$, TotalCharges 5269.54$. Business use: Offer premium offers or discounts to retain high-value , loyal customers. 
Cluster 2: Low Tenure, High Charges. Tenure 13.59 months, MonthlyCharges 75.99$, TotalCharges 1068.80$. Business use: Cause could be early dissatisfaction, use retention campaigns ex: discounts to reduce churn risk. 
