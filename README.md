# customer-segmentation-retailstore
---
## Project Overview

This project focuses on creating customer segments for an online retailer based in the UK. The retailer specializes in all-occasion gifts and serves both individual and wholesale customers. The main goal is to develop a data-driven approach to segment international customers based on their purchase patterns. These segments will help the retailer tailor its marketing strategies and improve service offerings.

## Key Components

1. **Data Cleaning and Aggregation**
   - **Transaction-Level Cleaning:** We cleaned the transaction-level data to ensure accuracy before aggregating it to the customer level.
   - **Intermediary Levels:** Created intermediary aggregation levels (e.g., cart-level) to calculate metrics like average cart value, before rolling up to customer-level data.

2. **Dimensionality Reduction Using PCA**
   - **The Curse of Dimensionality:** We addressed the challenge of high dimensionality in the dataset, which can make clustering difficult.
   - **Principal Component Analysis (PCA):** Applied PCA to reduce the number of features while retaining the maximum variance in the data. We reduced 2574 features down to 300 components, capturing almost 80% of the original variance.

3. **Customer Segmentation**
   - **Clustering:** The reduced features were used to cluster customers into distinct segments, which will be evaluated and compared against alternative clustering methods.

## Deliverables

- **Cleaned Dataset:** A cleaned and aggregated dataset at the customer level.
- **PCA Features:** A dataset with customer-level principal component features for clustering.
- **Clustering Results:** Analysis of customer segments based on PCA features.

## Tools and Technologies

- **Python:** Data processing, cleaning, and aggregation.
- **Pandas:** Handling and manipulating large datasets.
- **Scikit-learn:** Implementing PCA and clustering algorithms.
- **Matplotlib:** Visualization of PCA and clustering results.

## Conclusion

This project demonstrates the power of dimensionality reduction and clustering in identifying meaningful customer segments. The insights derived from these segments will enable the retailer to enhance its marketing efforts and provide more personalized services to international customers.

---
