# 📊 Nova Global Community: Executive Financial & ROI Dashboard

## 📌 Project Overview
Managing a global tech community requires balancing user growth with financial sustainability. This project is a two-page, interactive Business Intelligence application built in Power BI to bridge the gap between community operations and financial Return on Investment (ROI). The dashboard transforms raw community telemetry and financial data into a cohesive, dark-mode executive presentation, proving the tangible value of community spend.

## 💼 Business Value Framework
This dashboard is designed to shift "Community Management" from an unpredictable cost center into a measurable value driver. It delivers business value across three core pillars:

### 1. Financial Efficiency & Cost Optimization
* **Prevents "Black Hole" Spending:** By directly correlating Total Financial Burn with Active User Growth, leadership can immediately identify if marketing and operational spend is actually yielding user retention.
* **Granular Cost Tracking:** Calculates the exact *Cost Per Active Member* and *Cost Per Project*, establishing a baseline for future budget forecasting and resource planning.

### 2. Strategic Resource Allocation
* **Geographic Optimization:** The regional engagement map reveals discrepancies between where capital is deployed versus where organic growth is occurring, allowing executives to reallocate funding to high-yield regions.
* **Platform Consolidation:** Identifies dominant communication channels (e.g., Discord vs. GitHub vs. Forums), empowering leadership to sunset underperforming platforms and recapture wasted operational bandwidth.

### 3. ROI & Output Verification
* **Proving Tangible Value:** Replaces vanity metrics (like page views) with concrete output metrics (Total Value Creation/Projects). This proves to stakeholders that the community is actively building assets for the organization, justifying continued investment.

## 🏗️ Dashboard Architecture

### Page 1: The Macro View (Executive Financial Summary)
Focuses on the global footprint and high-level trends.
* **North Star KPIs:** Total Financial Burn, Average Community Engagement, and Cost Per Active Member.
* **Macro Trend Analysis:** A custom Line and Stacked Column chart plotting monthly burn rate against community engagement.
* **Global Distribution:** A Shape Map visualizing the geographic distribution of spend and engagement across regions.

### Page 2: The Micro View (Platform Operations & ROI)
Drills down into platform efficiency and output generation.
* **Platform Dominance:** A Donut Chart visualizing the exact share of daily active users across Discord, GitHub, and the Community Forum.
* **Value Output vs. Cost Efficiency:** A Clustered Bar chart displaying the total monthly value creation (projects) with custom tooltips revealing the underlying cost-per-project efficiency.

## 🛠️ Technical Skills & Methodology
* **Data Processing & Cleaning**: Extracted raw community logs and financial data. Performed extensive cleaning, including removing duplicate entries, standardizing regional naming conventions, and handling null values in engagement metrics to ensure 100% data integrity.
* **Data Modeling**: Built a robust relational schema in Power BI. This involved creating a central Date Table for time-intelligence, and connecting Fact tables (Financials, Engagement) to Dimension tables (Geography, Platforms) for seamless filtering.
* **Analytical Logic (DAX)**: Developed complex DAX measures, including:
    * *Total Burn Rate*: Aggregated monthly operational expenses.
    * *Cost-per-Active-Member*: A calculated ratio to assess efficiency.
    * *Growth Trajectory*: Month-over-month percentage changes to track momentum.
* **UI/UX Design**: Applied a custom dark-mode aesthetic (`#141E1A`) to reduce eye strain, removed chart junk to prioritize executive readability, and utilized custom tooltips for deep-dive analysis.

## 🚀 How to Interact with this Project
1. Download the [COMMUNITY EXECUTIVE DASHBOARD.pbix](COMMUNITY%20EXECUTIVE%20DASHBOARD.pbix) file from this repository.
2. Open the file using Power BI Desktop.
3. Use the Slicer on the top right of Page 1 to filter the entire report by specific platforms.
4. Hover over the bars on the Page 2 clustered bar chart to view the custom Cost-Per-Project tooltips.

---
*Note: The data used in this dashboard is dummy data created strictly for portfolio demonstration purposes.*
