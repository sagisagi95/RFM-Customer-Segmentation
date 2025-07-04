# 🗂️ Dataset Overview

- The dataset comprises three separate files, each representing a key component of customer information at IFood. These tables are joined via a unique `Customer_ID`.
- Link: https://drive.google.com/drive/folders/1FE0PvORXBru-XYkd1oi55zEvKOExAnAn?usp=drive_link
- Format: Excel (cleaned data)

## Table Schema

## 1. Customer Profile (`Customer profile.xlsx`)

| Column Name    | Data Type | Description                                           |
|----------------|-----------|-------------------------------------------------------|
| Customer_ID    | String    | Unique identifier for each customer                   |
| Age            | Integer   | Age of the customer                                   |
| Education      | String    | Education level (e.g., Graduation, Post-Graduation)   |
| Marital_Status | String    | Marital status (e.g., Married, Single)                |
| Income         | Integer   | Annual income in USD                                  |
| Kidhome        | Integer   | Number of kids in the household                       |
| Teenhome       | Integer   | Number of teenagers in the household                  |

## 2. Customer Behavior (`Customer behavior.xlsx`)

| Column Name         | Data Type | Description                                 |
|---------------------|-----------|---------------------------------------------|
| Customer_ID         | String    | Unique identifier for each customer         |
| Customer_Days       | Integer   | Number of days since the first order        |
| Recency             | Integer   | Number of days since the last order         |
| NumDealsPurchases   | Integer   | Purchases made with discount                |
| NumWebPurchases     | Integer   | Purchases made through website              |
| NumCatalogPurchases | Integer   | Purchases via catalog                       |
| NumStorePurchases   | Integer   | Purchases made directly in-store            |
| NumWebVisitsMonth   | Integer   | Website visits in the last month            |
| MntWines            | Integer   | Amount spent on wine                        |
| MntFruits           | Integer   | Amount spent on fruits                      |
| MntMeatProducts     | Integer   | Amount spent on meat                        |
| MntFishProducts     | Integer   | Amount spent on fish                        |
| MntSweetProducts    | Integer   | Amount spent on sweets                      |
| MntGoldProds        | Integer   | Amount spent on gold products               |
| MntTotal            | Integer   | Total amount spent on all products          |
| Complain            | Boolean   | Whether customer has complained (Yes or No) |

## 3. Campaign Acceptance (`Customer accept campaign.xlsx`)

| Column Name      | Data Type | Description                                                |
|------------------|-----------|------------------------------------------------------------|
| Customer_ID      | String    | Identifier for each customer who accepted (may duplicate)  |
| AcceptedCmp      | String    | Cmp1: Customer was surveyed in campaign 1                  |
|                  |           | Cmp2: Customer was surveyed in campaign 2                  |
|                  |           | Cmp3: Customer was surveyed in campaign 3                  |
|                  |           | Cmp4: Customer was surveyed in campaign 4                  |
|                  |           | Cmp5: Customer was surveyed in campaign 5                  |
|                  |           | Cmp6: Customer was surveyed in campaign 6                  |

---
