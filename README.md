# Project Case Study: Nigeria Food Price Inflation Dashboard

## Executive Summary
This project is an end-to-end data solution built entirely in Power BI. It takes raw, messy economic data and transforms it into an interactive dashboard that tracks food prices and inflation in Nigeria from May 2025 to May 2026. The dashboard helps business owners and food suppliers instantly see which states and food items are becoming more expensive.

## Problem Statement
*   **Situation:** Food prices change very quickly in Nigeria, making up a massive part of daily household spending.
*   **Complication:** Inflation data is usually stuck in long, confusing spreadsheet files. Because the data starts out messy and unorganized, it is hard for businesses to know where prices are rising fastest and when to buy stock.
*   **Core Question:** How can we use a single tool to clean raw inflation numbers, build a working data model, and create a clear visual tool that shows exact price trends by state and food type?

##  Tools & Skills Used
This project was built 100% end-to-end using Microsoft Power BI, demonstrating full competency in data transformation, modeling, analytical calculations, and visual design within a single tool.

*   **Power Query (ETL - Extract, Transform, Load):** 
    *   Cleaned raw, unformatted data by removing duplicates and handling missing values.
    *   Transformed text columns and standardized currency formats for the Nigerian Naira (₦).
    *   Grouped individual states into their proper geopolitical regions using custom conditional columns.
*   **Data Modeling:** 
    *   Designed a star-schema relationship model to connect the primary inflation metrics with time and location tables, ensuring fast dashboard performance.
*   **DAX (Data Analysis Expressions):** 
    *   Wrote custom analytical calculations to generate summary metrics like Average Food Price, Average Food Inflation, and Average Headline Inflation.
*   **Data Visualization & UI Design:** 
    *   Built an interactive canvas utilizing key performance indicators (KPIs), bar charts, line graphs, and ribbon charts.

## How the Dashboard Was Built
1.  **Data Clean-up (Power Query):** Imported the raw data, removed duplicates, fixed missing numbers, and sorted the states into their proper geopolitical regions.
2.  **Calculations (DAX):** Created custom formulas to calculate the summary cards at the top, such as the Average Food Price of ₦3K and the Headline Inflation of 17.74%.
3.  **Dashboard Design:** Placed easy-to-read "KPI cards" across the top for quick facts and added interactive drop-down filters (Month, Year, Food Category, State) so users can click to filter the charts instantly.
4. **Interactive Slicers:** Implemented global cross-filtering page controls (**Month, Year, Food Category, and State**) to allow stakeholders to drill down dynamically into specific variables.
<img width="1520" height="736" alt="Screenshot 2026-09-24 152842" src="https://github.com/user-attachments/assets/47d06fff-bd7a-49d4-8462-cfac45a4c54d" />

##  Key Findings
*   **Meat and Seafood Cost the Most:** Meat, Fish/Seafood, and Poultry are significantly more expensive than other food groups, with average prices sitting between ₦5K and ₦7K.
*   **The South is More Expensive:** The South East and South South regions have the highest average food prices in the country, while the North West and North East have the lowest.
*   **Ogun State is an Inflation Hotspot:** Looking at individual states, Ogun State recorded the highest food inflation rate, followed closely by Abuja and Oyo.
*   **Prices Peak in July:** The line chart shows a massive price spike in July 2025, a drop during the end-of-year harvest season, and a steady climb back up by May 2026.

##  Recommendations
1.  **Focus on Protein Supply Chains:** Because meat and seafood drive the highest costs, businesses should focus on finding cheaper transport routes for these specific categories.
2.  **Sourcing Goods Wisely:** Retailers should look into sourcing more agricultural products from northern regions where baseline prices are lower, then shipping them to higher-cost southern markets.
3.  **Prepare for Seasonal Spikes:** Food buyers should stock up on inventory before the predictable mid-year price surge hits in June and July.
