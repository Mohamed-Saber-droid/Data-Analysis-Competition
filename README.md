# 🏦 NovaTrust Bank - Marketing Campaign Performance Analysis

## 📌 Project Overview
This project provides a comprehensive data analysis and interactive Power BI dashboard for **NovaTrust Bank's** recent telemarketing campaign. The goal of the project is to evaluate the campaign's performance, understand customer behavior, and optimize the marketing budget to increase the overall subscription rate while minimizing the Cost Per Acquisition (CPA).

<img width="891" height="500" alt="image" src="https://github.com/user-attachments/assets/4cc53a6a-d448-4c41-957b-d13da4f027bd" />

## 🎯 Business Objectives
1. **Performance Tracking:** Monitor key metrics such as Total Calls, Total Cost, Total Subscriptions, and Conversion Rate.
2. **Customer Segmentation:** Identify which customer demographics (e.g., job type) yield the highest conversion rates.
3. **Budget Optimization:** Analyze the Cost Per Acquisition (CPA) across different segments to recommend cost-effective marketing strategies.

## 📊 Key Insights & Findings

### 1. Overall Performance & Seasonality
* The campaign generated **5K subscriptions** from **41K total calls**, resulting in an overall **Conversion Rate of 11.27%**.
* **Seasonality Insight:** While the month of **May** had the highest volume of calls, it had one of the lowest conversion rates. Conversely, months like **March, September, October, and December** showed significantly lower call volumes but exceptionally high conversion rates (surpassing 40%).

<img width="890" height="500" alt="image" src="https://github.com/user-attachments/assets/13befd28-bfa6-44ce-8451-e8a6db683c4d" />

### 2. Customer Segmentation (Job Titles)
* **High Performers:** **Students** (31.43%) and **Retired** individuals (25.26%) showed the highest conversion rates, indicating strong responsiveness to the bank's offers.
* **Volume vs. Efficiency:** **Admin** and **Blue-collar** jobs consumed the majority of the calls and budget but yielded much lower conversion rates (12.97% and 6.90%, respectively).
* **Contact Method:** The vast majority of successful conversions (**83.04%**) came through **Cellular** contacts rather than traditional telephones.

<img width="891" height="500" alt="image" src="https://github.com/user-attachments/assets/bdf522c1-f082-4e65-a30d-9b872280cd9b" />

### 3. Budget & Cost Analysis (CPA)
* The average **Cost Per Acquisition (CPA) is €53.26**.
* **Impact of Previous Campaigns:** Targeting customers who had a "success" outcome in previous campaigns drastically dropped the CPA to under **€10**. Reaching out to completely new customers ("nonexistent" outcome) was the most expensive, driving the CPA up to nearly **€70**.
* **Recommendation:** Shift budget focus away from mass-calling blue-collar/admin profiles during peak months like May. Instead, allocate more resources to re-targeting past successful leads, and focus on students and retired demographics to maximize ROI.

## 🛠️ Tech Stack & Skills Demonstrated
* **Tool:** Power BI Desktop
* **Data Processing:** Power Query (Data cleaning, handling missing values, standardizing formats).
* **Data Modeling:** Star Schema design, creating dimension tables (e.g., Date/Months table) to resolve circular dependencies.
* **DAX:** Creating robust measures for KPIs (CALCULATE, COUNTROWS, DIVIDE, SWITCH).
* **Data Visualization:** Interactive charts, scatter plots for budget analysis, and custom professional UI/UX design.

---
