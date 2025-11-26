🌱 Plant Co. Sales & Quantity Performance Dashboard

(Replace plant_co_screen.jpg with the actual path to your image in the repo)

📖 Project Overview

This Power BI project is a dynamic performance tracking tool designed for Plant Co. to analyze Year-to-Date (YTD) versus Previous Year-to-Date (PYTD) metrics. The dashboard focuses on Quantity, Sales, and Gross Profit (GP%), allowing stakeholders to identify regional bottlenecks, seasonal trends, and account profitability segments.

The goal was to move beyond static reporting and provide a drill-down capable view of where the company is gaining or losing volume compared to the previous year.

📊 Key Features & Visuals

Dynamic KPI Cards: Real-time tracking of YTD (555.66K), PYTD, and Variance (+17.05K), with conditional formatting to highlight growth.

Waterfall Analysis: A detailed breakdown of Quantity YTD vs PYTD by Month, Country, and Product to pinpoint exactly when and where drops occurred (e.g., the visible dip in February/March vs. the recovery in April).

Regional Performance (Bottom 10): A Treemap highlighting underperforming countries (e.g., China, Sweden, Japan) to prioritize sales interventions.

Account Segmentation (Scatter Plot): A strategic view combining GP% and Quantity to classify accounts into:

High Volume / Low Margin

Low Volume / High Margin (Opportunity accounts)

Monthly Trends: Clustered column charts comparing current vs. previous year performance across product categories (Indoor, Landscape, Outdoor).

🛠️ Tech Stack

Microsoft Power BI: Core visualization and interactivity.

DAX (Data Analysis Expressions): Used for time-intelligence calculations (YTD, PYTD, YoY Growth) and dynamic segmentation logic.

Power Query: ETL processing to clean and merge sales and product lookup tables.

Data Sources: (Mention here if you used SQL or Excel, e.g., SQL Server for transactional data, Excel for targets).

💡 Key Insights from Analysis

Overall Growth: Despite specific regional dips, the company is up by 17.05K units YTD compared to the previous year.

Seasonal Volatility: There was a significant negative variance in February and March, followed by a strong recovery in April (adding ~13K units).

Problem Areas: China and Sweden are the top contributors to volume loss, dragging down the overall YTD variance.

Profitability: The scatter plot reveals a cluster of high-volume accounts operating at lower GP% (below 40%), suggesting a need for pricing review.

🚀 How to Run

Download the .pbix file from this repository.

Open in Power BI Desktop.

(Optional) Update the data source settings to point to the provided sample dataset if paths have changed.

Created by Hasnat Lubaid | Data Analyst & Power BI Specialist
