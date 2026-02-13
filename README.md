# swiftroute-logistics-analytics-dashboard
1️⃣ Headline
A dynamic and interactive Power BI dashboard built to analyze logistics operations — focusing on delivery performance, hub efficiency, driver productivity, fleet reliability, and customer satisfaction.

2️⃣ Purpose
The SwiftRoute Logistics Analytics Dashboard is a comprehensive Power BI report designed to monitor and optimize end-to-end logistics operations.<br>
This dashboard enables operational managers and business stakeholders to track KPIs such as on-time delivery rate, hub capacity utilization, driver performance, and vehicle breakdown trends to support data-driven decision-making.

3️⃣ Tech Stack
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

4️⃣ Data Source
Source: Simulated logistics operational dataset (Orders, Hubs, Drivers, Vehicles).<br>
The dataset consists of multiple relational tables:<br>
• Orders – Order details, delivery time, delay status, customer satisfaction<br>
• Hubs – Hub capacity and processing performance<br>
• Drivers – Experience, performance rating, employment type<br>
• Vehicles – Fleet details, breakdown count, maintenance history<br>
The data model enables cross-analysis between operational entities to generate meaningful business insights.<br>

5️⃣ Features
• Business Problem
Logistics companies often struggle with:<br>
Delivery delays impacting customer satisfaction<br>
Hubs operating beyond capacity<br>
Driver performance inconsistencies<br>
Vehicle breakdowns causing operational disruptions<br>
Lack of centralized KPI monitoring<br>
Raw operational data alone makes it difficult for management to quickly identify bottlenecks and inefficiencies.<br>
• Goal of the Dashboard<br>
To build an interactive business intelligence solution that:<br>
Provides centralized visibility into logistics KPIs<br>
Enables performance comparison across hubs and drivers<br>
Tracks delivery efficiency trends month-over-month<br>
Identifies operational risks related to fleet and capacity<br>
Supports strategic and operational decision-making<br>
• Walkthrough of Key Visuals
🔹 Key KPIs (Overview Dashboard)
Total Orders
Month-over-Month Growth (%)
On-Time Delivery Rate (%)
Customer Satisfaction Score (CSAT %)
Average Delivery Time (Hours)
Provides a high-level operational performance summary.
🔹 Hub Analysis
Total Number of Hubs
Orders Processed vs Hub Capacity (Clustered Column Chart)
Hub Performance Ranking (Bar Chart)
Hub Processing Time Matrix
Helps identify overloaded hubs and improve capacity planning.
🔹 Driver Performance Analysis
Total Active Drivers
Experience vs Rating (Scatter Plot)
Drivers with Most Delays (Bar Chart)
Driver Profile Summary (Hire Date, YOE, Rating, Monthly Deliveries)
Monthly Order Trend (Line Chart)
Enables workforce evaluation and targeted performance improvement.
🔹 Vehicle & Fleet Analytics
Total Vehicles & Active Vehicles (KPI & Donut Chart)
Orders by Vehicle Model (Bar Chart)
Vehicle Age vs Breakdown (Scatter Plot)
Breakdown by Vehicle Code & Model
Orders by Vehicle Type (Donut Chart)
Supports fleet optimization and proactive maintenance planning.
• Business Impact & Insights
Operational Efficiency: Identified delay patterns and delivery performance gaps.
Capacity Planning: Highlighted hubs operating above capacity limits.
Performance Optimization: Revealed correlation between driver experience and rating.
Fleet Risk Monitoring: Detected aging vehicles with higher breakdown frequency.
Customer Experience Tracking: Monitored CSAT trends to improve service quality.

6️⃣ Screenshots / Demo
![Overview Dashboard][(screenshots/overview.png)](https://github.com/ShubhamW1107/swiftroute-logistics-analytics-dashboard/blob/main/Screenshots/swiftroute-logistics-analytics-dashboard.jpg)
![Hub Analysis][(screenshots/hubs.png)](https://github.com/ShubhamW1107/swiftroute-logistics-analytics-dashboard/blob/main/Screenshots/swiftroute-logistics-hubs-analytics-.jpg)
![Driver Analysis][(screenshots/drivers.png)](https://github.com/ShubhamW1107/swiftroute-logistics-analytics-dashboard/blob/main/Screenshots/swiftroute-logistics-drivers-analytics-.jpg)
![Vehicle Analysis][(screenshots/vehicles.png)](https://github.com/ShubhamW1107/swiftroute-logistics-analytics-dashboard/blob/main/Screenshots/swiftroute-logistics-vehicles-analytics-.jpg)
