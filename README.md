

# Task-02: Track & Visualize Ad Performance Like a Pro
### 📊 Social Media Campaign Performance Tracker Dashboard

## 🎯 Project Objective

The goal of this project is to analyze digital advertising campaign data to evaluate performance, track engagement, and measure return on investment (ROI). By transforming raw ad data into an interactive dashboard, this project provides actionable insights for marketing teams to optimize future campaigns, understand audience behavior, and maximize their advertising spend.

---

## 🛠️ Tools and Technologies

* **Power BI / Google Looker Studio**: Used for creating the interactive dashboard, data modeling, and visualization.
* **Microsoft Excel / Google Sheets**: Used for initial data inspection, cleaning, and preparation before importing into the BI tool.
* **DAX (Data Analysis Expressions)**: Used within Power BI to create custom measures for key marketing metrics.

---

## 🔄 Project Workflow

1.  **Data Preparation**: The raw CSV data from a simulated ad campaign was loaded into Power Query. Data cleaning steps included handling missing values and ensuring correct data types for metrics like Clicks, Impressions, and Spend.

2.  **Metric Calculation**: New columns and measures were created to calculate essential marketing KPIs that were not present in the original dataset. Key calculated metrics include:
    * **Click-Through Rate (CTR)**: `(Total Clicks / Total Impressions)`
    * **Cost Per Click (CPC)**: `(Total Spend / Total Clicks)`
    * **Return on Investment (ROI)**: `( (Revenue - Spend) / Spend )`

3.  **Dashboard Design**: An interactive dashboard was designed to answer key business questions at a glance. The layout was structured to provide a clear narrative, from a high-level overview down to granular details.

4.  **Visualization**: A variety of visuals were used to represent the data effectively:
    * **KPI Cards** for at-a-glance metrics like Total Spend, CTR, and ROI.
    * **Bar Charts** to compare performance across different ad posts or campaigns.
    * **Line Charts** to track performance trends over time.
    * **Tables** to show detailed breakdowns of performance by audience demographics (age, gender, region).

5.  **Interactivity**: Slicers and filters were added to allow users to dynamically filter the dashboard by date, campaign, audience demographics, and device, enabling deep-dive analysis.

---

## 💡 Key Insights & Recommendations

This dashboard helps answer critical business questions such as:

* **Overall Performance**: How effective was the ad campaign in terms of reach, engagement, and cost?
* **Top Performers**: Which specific ads or posts generated the highest engagement and click-through rates?
* **Audience Insights**: Which age group or region responded best to the campaign?
* **Actionable Recommendations**: Based on the data, the dashboard provides clear recommendations, such as reallocating budget to top-performing ads or targeting specific demographics in future campaigns.

---

## 🖼️ Dashboard Preview

<img width="1801" height="1016" alt="Screenshot 2025-08-15 062414" src="https://github.com/user-attachments/assets/faed0bcf-f85e-4196-bf67-351b2d519aca" />


