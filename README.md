Supply Chain Performance Analytics Dashboard
Overview

This project delivers an executive level analytics dashboard built in Power BI to evaluate supply chain performance across order volume, revenue, profitability, and delivery reliability. The goal is to give decision makers a clear view of operational health and highlight tradeoffs between service level and cost.

Business Objective

Organizations often struggle to balance fast delivery with sustainable margins. This dashboard enables leaders to monitor demand trends, identify fulfillment inefficiencies, and understand how logistics decisions influence profitability.

Key Features

Executive KPI Summary
Centralized metrics for Orders, Revenue, Profit, Margin, On Time Delivery, Late Deliveries, and Average Delay.

Trend Analysis
Time based revenue and demand patterns to support forecasting and capacity planning.

Delivery Performance Insights
Visibility into service levels by shipping mode, showing where delays occur and how frequently.

Service vs Profit Tradeoff View
Analysis that highlights how faster shipping improves customer experience while impacting margins.

Interactive Exploration
Dynamic filters allow users to analyze performance by date, market, customer segment, and product dimensions.

Data Model

A dimensional model was designed to support scalable analytics and clean relationships.

Fact Table
Order level metrics including revenue, profit, and delivery performance.

Dimension Tables
Date for time intelligence
Customer for segmentation analysis
Product for category level insights

This structure enables fast aggregation, accurate KPI calculations, and flexible slicing of data.

KPIs Implemented

Total Orders
Total Revenue
Total Profit
Profit Margin Percentage
On Time Delivery Percentage
Late Delivery Rate
Average Delivery Delay

All measures were created using DAX to ensure consistent logic across the report.

Insights Enabled

Identify operational inefficiencies causing recurring short delays.

Evaluate which shipping methods drive service improvements versus cost increases.

Monitor profitability impact of fulfillment decisions.

Detect performance variation across customer segments and markets.

Support data driven supply chain optimization.

Skills Demonstrated

Data modeling using a star schema approach
Data transformation and cleansing
DAX based metric design
Interactive dashboard development
Business focused analytics storytelling

Use Case

This solution is designed for supply chain leaders, operations managers, and executives who need a concise but powerful view of logistics performance to guide strategic and tactical decisions.
