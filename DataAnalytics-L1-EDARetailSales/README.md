# 🛒 Retail Sales Data - Exploratory Data Analysis (EDA)

**Oasis Infobyte Internship (OIBSIP)**  
**Track**: Data Analytics  
**Level / Task**: Level 1 - Task 1 (`OIBSIP/DataAnalytics-L1-EDARetailSales`)  
**Author**: Data Analytics Intern  

---

## 📌 Project Overview
This project delivers a comprehensive **Exploratory Data Analysis (EDA)** on a retail sales dataset containing **2,000 transaction records**. The primary objective is to uncover underlying purchasing patterns, analyze customer demographics, evaluate product category revenue and profitability, and track temporal sales trends to provide actionable business recommendations.

---

## 📊 Feature Checklist Compliance

| Checklist Item | Requirement Status | Implementation Details |
| :--- | :---: | :--- |
| **Data Inspection & Quality Report** | ✅ Complete | Initial inspection (`shape`, `dtypes`, null value count, summary statistics) |
| **Data Preprocessing & Cleaning** | ✅ Complete | Typo renaming (`quantiy` ➔ `quantity`), datetime conversion, median imputation |
| **Descriptive Statistics** | ✅ Complete | Computed Mean, Median, Mode, and Std Dev for all numerical columns |
| **Time Series Analysis** | ✅ Complete | Plotted Monthly & Quarterly sales revenue line charts and bar plots |
| **Customer Demographics Analysis** | ✅ Complete | Analyzed Age group distribution (`<25`, `25-39`, `40-59`, `60+`) and Gender breakdown |
| **Product Category Analysis** | ✅ Complete | Evaluated Total Revenue, COGS, Net Profit, and Profit Margins across Categories |
| **Correlation Matrix Heatmap** | ✅ Complete | Computed and visualized Seaborn heatmap of numerical feature correlations |
| **Additional Non-Obvious Insights** | ✅ Complete | Analyzed Peak Shopping Hours (08:00–11:00 AM) & Gender x Category Heatmap |
| **Markdown Observations** | ✅ Complete | Detailed narrative observations placed after every chart in the notebook |
| **Conclusion & Business Recommendations** | ✅ Complete | Formulated 4 data-driven actionable strategic recommendations |

---

## 🛠️ Tech Stack & Tools Used
- **Language**: Python 3.x
- **Data Manipulation**: `pandas`, `numpy`
- **Data Visualization**: `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook / Anaconda

---

## 🔑 Key Analytical Insights

1. **Revenue Drivers**:
   - **Total Sales Revenue**: **~$912,800** generated across 2,000 transactions.
   - **Top Category**: **Electronics** ($311k revenue) closely followed by **Clothing** ($310k) and **Beauty** ($291k).
   - **Profit Margin**: Consistent profit margins of **~79-80%** maintained across all categories.

2. **Customer Profile**:
   - **Gender Breakdown**: Balanced mix (**51% Female**, **49% Male**).
   - **Core Demographic**: Customers aged **40–59 (Middle-Aged)** form the largest revenue-generating cohort.

3. **Temporal Patterns & Peak Hours**:
   - **Peak Transaction Times**: Morning hours between **08:00 AM and 11:00 AM** experience the highest traffic and transaction volumes.
   - **Seasonality**: Strong sales surges in spring (March/May) and late Q4 (October–December holiday period).

---

## 🚀 Actionable Business Recommendations

1. 🎯 **Demographic Marketing**: Focus targeted marketing campaigns on middle-aged female shoppers who drive high basket value in Beauty and Clothing.
2. ⏰ **Store Operations & Staffing**: Increase floor staff and checkout register availability during morning peak hours (08:00 AM – 11:00 AM) to optimize checkout velocity.
3. 📦 **High-Value Product Bundling**: Leverage the strong correlation between item unit price and total revenue by creating multi-product bundles to raise Average Order Value (AOV).
4. 🛍️ **Q4 Inventory Preparation**: Scale up stock levels in September/October to handle early Q4 demand spikes without stockouts.

---

## 📂 Project Repository Structure

```text
OIBSIP/DataAnalytics-L1-EDARetailSales/
├── main.ipynb            # Fully executed Jupyter Notebook with code, charts, and markdown narrative
├── README.md             # Detailed project documentation & summary
└── Retail_Sales.csv      # Source dataset (2,000 transaction records)
```

---

## 📽️ Demo Video Instructions for Submission
When recording the demo walkthrough video for LinkedIn/submission:
1. **Title Card (First 2 Seconds)**: Display a static frame with:
   - Full Name
   - Track: Data Analytics
   - Task Title: Level 1 Task 1 - EDA on Retail Sales Data
2. **Walkthrough**: Narrate through the executed notebook, highlighting key plots, correlation heatmap, demographic breakdown, and final recommendations.
3. **LinkedIn Post**: Tag **Oasis Infobyte** with `#oasisinfobyte #dataanalytics #internship`.
