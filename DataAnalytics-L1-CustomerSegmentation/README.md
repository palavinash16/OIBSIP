# 🎯 Customer Segmentation Analysis (RFM + K-Means Clustering)

**Oasis Infobyte Internship (OIBSIP)**  
**Track**: Data Analytics  
**Level / Task**: Level 1 - Task 2 (`OIBSIP/DataAnalytics-L1-CustomerSegmentation`)  
**Author**: Data Analytics Intern  

---

## 📌 Project Overview
Customer Segmentation is an essential data-driven technique used by leading e-commerce and retail platforms to divide their customer base into distinct, behavioral cohorts. This project leverages **Recency, Frequency, and Monetary (RFM) feature engineering** combined with **K-Means Machine Learning Clustering** to profile customer personas and develop targeted, high-ROI marketing strategies.

---

## 📊 Feature Checklist Compliance

| Checklist Item | Requirement Status | Implementation Details |
| :--- | :---: | :--- |
| **Data Inspection & Quality Audit** | ✅ Complete | Inspected raw dataset, identified missing CustomerIDs and negative quantities |
| **Data Preprocessing & Cleaning** | ✅ Complete | Filtered 4,475 clean transaction records across 950 unique active customers |
| **Descriptive Statistics** | ✅ Complete | Computed mean, median, max, and std dev for transaction spend & customer CLV |
| **RFM Feature Engineering** | ✅ Complete | Calculated **Recency** (days), **Frequency** (order count), and **Monetary** (spend) |
| **Data Scaling & Standardization** | ✅ Complete | Log transformation (`np.log1p`) + `StandardScaler` normalization |
| **K-Means & Optimal $K$ Selection** | ✅ Complete | Evaluated Elbow Method (WCSS) & Silhouette Scores to select optimal $K = 4$ |
| **Cluster Scatter Visualizations** | ✅ Complete | 2D/3D Scatter plots (`Recency vs Monetary`, `Frequency vs Monetary`) |
| **Customer Persona Profiling** | ✅ Complete | Identified 4 personas: *Champions*, *Loyal Customers*, *At-Risk*, and *Lost* |
| **Customer Distribution Bar Chart** | ✅ Complete | Visualized customer count distribution across segments |
| **Actionable Marketing Strategies** | ✅ Complete | Formulated segment-specific marketing strategy matrix |

---

## 🛠️ Tech Stack & Libraries
- **Language**: Python 3.x
- **Data Manipulation**: `pandas`, `numpy`
- **Machine Learning**: `scikit-learn` (`KMeans`, `StandardScaler`, `silhouette_score`)
- **Data Visualization**: `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook / Anaconda

---

## 🔑 Key Customer Persona Profiles

| Persona Segment | Average Recency | Average Order Frequency | Average Total Spend | Persona Description |
| :--- | :---: | :---: | :---: | :--- |
| **🏆 Champions (VIP)** | ~18 Days | ~8.2 Orders | ~$1,450.00 | Most recent, highly frequent, top-spending customers. |
| **⭐ Loyal Customers** | ~45 Days | ~5.1 Orders | ~$720.00 | Consistent buyers with strong overall lifetime value. |
| **⚠️ At-Risk / Hibernating**| ~160 Days | ~3.1 Orders | ~$380.00 | Previously active buyers showing signs of churn. |
| **📉 Lost / Low-Value** | ~270 Days | ~1.5 Orders | ~$110.00 | Highly dormant customers with low engagement. |

---

## 🚀 Segment-Specific Marketing Strategies

1. **Champions (VIP)**: Offer exclusive VIP perks, dedicated support, early access to new collections, and referral incentive rewards.
2. **Loyal Customers**: Deploy cross-selling & upselling product recommendations based on purchase history to upgrade them into Champions.
3. **At-Risk Customers**: Launch personalized "We Miss You" win-back email drip campaigns with time-limited 20% discount vouchers to reactivate interest.
4. **Lost / Low-Value**: Include in automated, low-cost newsletter updates highlighting seasonal bestsellers; avoid heavy ad spend.

---

## 📂 Project Repository Structure

```text
OIBSIP/DataAnalytics-L1-CustomerSegmentation/
├── Customer_Segmentation_Data.csv    # E-commerce customer transaction dataset
├── main.ipynb                        # Fully executed Jupyter Notebook with RFM & K-Means clustering
└── README.md                         # Detailed project documentation & task checklist compliance
```

---

## 📽️ Demo Video Instructions for Submission
When recording the screen walkthrough for LinkedIn & task submission:
1. **Title Card (First 2 Seconds)**: Display a static frame with:
   - Full Name
   - Track: Data Analytics
   - Task Title: Level 1 Task 2 - Customer Segmentation Analysis
2. **Walkthrough**: Narrate through the executed notebook, highlighting the RFM histograms, Elbow Curve, Silhouette Plot, 2D Cluster Scatter plots, and the Marketing Strategy Matrix.
3. **LinkedIn Post**: Tag **Oasis Infobyte** with `#oasisinfobyte #dataanalytics #customersegmentation #kmeans #rfm`.
