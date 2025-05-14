# Power-Bi-Project-Blink-it-Data-Analysis-

 Overview
The Blinkit Analytics Dashboard is a comprehensive Power BI solution designed to visualize and analyze sales performance, customer satisfaction metrics, and store distribution for Blinkit, India's Last Minute App. This dashboard provides stakeholders with actionable insights to drive strategic decision-making and optimize business operations.
 Features

Sales Analytics

Total sales performance tracking ($1M)
Average transaction value monitoring ($141)
Historical sales trends visualization (2010-2020)
Comparative analysis across store types and tiers


Customer Satisfaction Metrics

Overall rating analysis (4.0/5.0 average)
9K ratings distribution visualization
Rating breakdown by product categories and store types


Store Performance Analysis

Tier-based performance tracking (Tier 1, 2, and 3)
Store type comparison (Supermarket Types 1-3, Grocery Stores)
Outlet size and establishment year correlation


Product Analytics

Item categorization by fat content (Low Fat vs Regular)
Product category performance metrics
Item visibility impact analysis



 Interactive Filtering Capabilities
The dashboard features robust filtering options to slice data by:

Outlet Location Type
Outlet Size
Item Type
Fat Content

 Key Insights

Supermarket Type1 generates the highest revenue ($7.87M)
Sales peaked around 2018-2019 (~205K) before stabilizing
Consistent 4-star ratings across product categories
Tier 3 stores contribute approximately 39% of total revenue

 Technical Details
Built With

Microsoft Power BI
Data modeling with DAX
Custom visualizations

Data Sources

Blinkit transaction database
Customer reviews system
Store management database

 Installation & Setup

Clone this repository

bashgit clone https://github.com/yourusername/blinkit-analytics-dashboard.git

Open the .pbix file with Power BI Desktop

Blinkit_Dashboard.pbix

Connect to your data source by configuring the parameters in the Power Query Editor
Refresh the data and publish to your Power BI workspace

 Usage Guidelines

Filtering Data: Use the slicers on the left panel to filter by outlet type, size, and item categories
Drilling Down: Click on any chart element to drill down into detailed information
Exporting Reports: Use Power BI's export functionality to extract reports in various formats

 Updating Data
The dashboard is configured to refresh data:

Automatically once per day (configurable)
Manually through the "Refresh" button
