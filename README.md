# AI-Powered Sales Forecasting Dashboard

## Problem Statement
Retail businesses struggle to predict future sales accurately, leading to inventory issues and revenue loss.

## Solution
Built a time-series forecasting system using Prophet to predict store-level sales and visualize insights in Power BI.

## Tech Stack
- Python (Pandas, Prophet, Matplotlib)
- Power BI
- Google Colab

## Key Features
- Store-level forecasting
- Promotion-aware predictions
- Actual vs forecast comparison
- Business-ready dashboard

## Business Impact
Improves inventory planning, staffing, and promotional strategy.

## Business Insights & Recommendations
Key Insights

1️) Sales Trend & Forecast

-Historical sales show strong seasonality, with consistent peaks during promotional and holiday periods.
-The forecasting model predicts a stable upward trend, with higher volatility during peak months.
-Confidence intervals highlight periods of higher uncertainty, helping decision-makers plan inventory buffers.

2️) Holiday Impact

-Sales during holidays outperform non-holiday periods, confirming a positive holiday sales lift.
-The Holiday Impact KPI quantifies this uplift, enabling data-driven campaign planning.
-Not all holidays perform equally, indicating opportunities for targeted promotions.

3️) Promotion Effectiveness
-Promotional periods contribute significantly to total revenue.
-However, some promotions deliver diminishing returns, suggesting a need for optimization rather than blanket discounting.

4️) Store & Store Type Performance
-Certain store types consistently outperform others, showing clear location and format dependency.
-Underperforming stores may benefit from tailored promotions or inventory reallocation.

5️) Seasonality & Demand Patterns
-Monthly sales patterns reveal clear peak and low-demand seasons.
-Low seasons present opportunities for:
-Clearance sales
-Inventory reduction

Maintenance and operational optimization

## Business Recommendations

* Inventory Planning
Increase inventory levels ahead of forecasted peak months using forecast upper bounds to avoid stock-outs.

* Smarter Promotions
Focus promotions on high-impact periods rather than uniform discounting across all months.

* Holiday Strategy Optimization
Prioritize high-performing holidays and reassess low-impact ones to maximize ROI.

* Store-Level Decision Making
Allocate resources and marketing budgets based on store and store-type performance.

* Risk-Aware Forecasting
Use confidence intervals to prepare contingency plans during volatile demand periods.
