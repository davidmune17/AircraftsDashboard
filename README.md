# Aircraft Type P&L Dashboard - Power BI

<img width="2065" height="1164" alt="DashboardAircraftType" src="https://github.com/user-attachments/assets/4ee62f28-1df2-4318-b203-602983e5814d" />

## Project Description

Interactive dashboard developed in Power BI for financial analysis of Profit & Loss (P&L) segmented by commercial aircraft type. This project enables visualization and analysis of the financial performance of different aircraft models in operation, facilitating strategic decision-making in the aviation industry.

## Objectives

Analyze profitability by aircraft type (Airbus A320, A350-900, A380, Boeing 737-800, 777-300ER, 787-9)
Evaluate temporal trends of revenue, costs, and profits
Identify seasonality in business profitability
Calculate key financial metrics (Gross Profit%, MoM%)
Provide actionable insights for fleet management

## Key Metrics (KPIs)

The dashboard presents the following key metrics:
MetricValueDescriptionProfit$575.5MTotal net profit for the periodTotal Cost$1.80bnTotal operational costsTotal Revenue$2.37bnTotal revenue generatedGross Profit %6.19%Gross profit marginMoM %11.11%Month-over-Month growth

## Dashboard Components

### KPI Cards

Visualization of main metrics in card format with highlighted values.

### Temporal Trends Chart

Title: Profit, Cost and Revenue by Month
Type: Multi-series line chart
Variables:

Profit (lower line - dark)
Total Cost (middle line - white)
Total Revenue (upper line - light blue)


Period: January - December 2024
Insight: Identifies seasonality and monthly trends

### Profit by Season

Type: Donut chart
Segmentation:

Peak (high season): $220.78M (38.36%)
Low (low season): $218.76M (38.01%)
Shoulder (mid season): $84.11M (14.62%)
Normal: $51.83M (9.01%)


Purpose: Business seasonality analysis

### Aircraft Type Filter

Side panel with multiple selection of models:

Airbus A320
Airbus A350-900
Airbus A380
Boeing 737-800
Boeing 777-300ER
Boeing 787-9

### Detailed Table

Granular breakdown by day with columns:

Year, Month, Day
Sum of Total_Revenue
Sum of Total_Cost
Sum of Profit
Median of GrossProfitMargin% Measure

Cumulative totals shown:

Revenue: $2,371,756,240.42
Cost: $1,796,275,579.39
Profit: $575,480,660.99
Median Gross Profit Margin: 0.15 (15%)

## Technologies Used

Power BI Desktop - Dashboard development
DAX (Data Analysis Expressions) - Measure and metric calculations
Power Query - Data transformation and cleansing
Excel/CSV - Data source (input format)
