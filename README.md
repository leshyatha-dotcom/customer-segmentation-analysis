# Customer Segmentation Analysis

K-Means clustering project that segments mall customers based on annual income and spending behavior. Built as part of the **Tata Data Visualisation Forage Virtual Experience Program**.

## Objective
Segment customers based on behavior and demographics to enable targeted marketing strategies.

## Dataset
Mall customer dataset with the following features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Tools & Libraries
- Python
- Pandas
- Scikit-learn (K-Means)
- Matplotlib

## Approach
1. Loaded and explored the dataset
2. Selected Annual Income and Spending Score as clustering features
3. Scaled features using StandardScaler
4. Used the Elbow Method to determine the optimal number of clusters (k=5)
5. Applied K-Means clustering
6. Visualized customer segments
7. Derived business insights for each segment

## Key Insights
- **Cluster 0:** Low income, low spending — budget-conscious customers
- **Cluster 1:** High income, high spending — premium target customers
- **Cluster 2:** Low income, high spending — impulsive buyers
- **Cluster 3:** High income, low spending — price-sensitive despite wealth
- **Cluster 4:** Average income, average spending — typical customers

## Outcome
Gained hands-on experience in customer analytics, segmentation, and translating clustering results into actionable, targeted business insights.

## Author
Karuturi Leshyatha
