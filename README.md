# Customer Segmentation — RFM & Category Behaviour

## Overview
K-means clustering model to segment ShopNow's customer base 
using RFM (Recency, Frequency, Monetary) metrics and category 
concentration, enabling targeted marketing actions.

## Models
- **Baseline:** K-means on RFM features (k=4)
- **Enhanced:** K-means on RFM + category concentration (k=4)

## Key Techniques
- Winsorization for outlier handling
- Log transformation + Scaling (using standardscaler) for feature prep
- Elbow method for cluster selection
- Shannon Entropy for category behaviour feature engineering

## Segment Profiles
| Segment | Behaviour |
|---|---|
| Recent High Spenders (VIPs) | High spend, moderate frequency |
| Loyal Customers | High frequency, mid basket size |
| Inactive / At-Risk | Low frequency, long since last purchase |
| Category Specialists | Focused category buyers, mid value |

## Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Google Colab

## Dataset
Synthetic retail dataset with RFM, demographic, 
and category-level purchase data.
