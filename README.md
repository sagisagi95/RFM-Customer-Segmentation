# [Power BI] IFood Customer Segmentation Analysis

## 📝 Project Summary
This project focuses on **exploratory data analysis (EDA)** and **RFM segmentation** of IFood's customer data to identify high-value segments and assess their interest in a newly proposed **food delivery service**. Insights derived can be utilized for **targeted marketing strategies and channel optimization** for service rollout.



## I. Business Context
- IFood is a retail food company with over **200,000 registered customers** in database and **1 million consumers annually**.
- A new **delivery service** is being considered.
- A survey was conducted with 2,200 randomly selected customers throughout 6 campaigns.

## 📌 Business Question
- Determine **which customers to target for the new delivery service** based on demographic and behavioral data.



## 📊 Dataset Overview
The dataset comprises three separate Excel files, each representing a key component of customer information at IFood. 
- Source: https://drive.google.com/drive/folders/1FE0PvORXBru-XYkd1oi55zEvKOExAnAn?usp=drive_link 
- Scope: Analyze **demographics**, **RFM scores**, and **shopping behavior** to segment customers
- Toolset: Power BI



## 👤 Customer Segmentation Logic

1. **About RFM Framework**
RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value. RFM is used to identify and categorize customers based on their purchasing behavior, how recently and frequently they have made purchases, and the total money spent on those purchases.
- Recency: measures how recently a customer has made a purchase.
- Frequency: measures how often a customer has made purchases.
- Monetary Value: measures the total amount of money a customer has spent on purchases.


2. **RFM Calculation**
In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores
- **RFM Score = (R_Score + F_Score + M_Score)/3**
- Within this project, RFM scores are combined to create 3 segments:
  - High (RFM > 25)
  - Middle (20 ≤ RFM ≤ 25)
  - Low (RFM < 20)

| RFM Segment | % of Total Customers | % of Accepted Group | % of Revenue |
|-------------|----------------------|---------------------|--------------|
| High        | 21.8%                | 34%                 | 55.2%        |
| Middle      | 35%                  | 38.2%               | 41.1%        |
| Low         | 43.3%                | 27.8%               | <4%          |

---

## II. Data Visualization with Power BI
See detailed analysis in [EDA_RFM Segmentation.pdf](docs/EDA_RFM%20Segmentation.pdf) here

<img width="1389" alt="image" src="https://github.com/user-attachments/assets/3c33ceec-8308-48ae-a2d4-56a5052c87eb" />
<img width="1387" alt="image" src="https://github.com/user-attachments/assets/9f7749f1-8cbf-46a4-ab26-e12bc05bf341" />
<img width="1385" alt="image" src="https://github.com/user-attachments/assets/1f121e80-6964-4e5b-8ac1-23a6237834a5" />

## 🔎 Key Insights

### 1. Demographics of Potential Users
- **31%** of surveyed customers are interested in the new delivery service
- These users are mostly: Aged 35–45, highly educated, married with at least one child, have middle to high income

### 2. Behavioral Traits
- Loyal customers made **13–15 orders**, highly contributed to company's revenue (>92%)
- Prefer **Store** (43%) and **Website** (32%) over other channels
- Less sensitive to promotions (compared to customers who are uninterested in the new service)


## 🎯 Recommendations for Marketing team

- **Target middle to high - RFM segments** for new service trials
- **Promote via Store & Website** channels where engagement is highest
- **Introduce trial offers** (e.g., free delivery on $50+ orders) for better conversion
- Consider **Personalized promotions** and **Cross-sell bundles** with wine/meat with delivery service to increase trials

---

