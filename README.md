<img src="https://github.com/user-attachments/assets/80c36de8-74e9-4210-8cc4-8dd7d5c5ed0b" width="200" height="200" align="right" />
 
# Improvado Marketing Analytics Dashboard Homework
[Looker Studio Improvado Dashboard Homework](https://lookerstudio.google.com/reporting/d2de74be-fada-46f7-b32b-85b8cfc8afdb)

<img width="1000" height="800" alt="Improvado Dashboard" src="https://github.com/user-attachments/assets/1852a314-4687-4f91-86bb-056b2553b518" />

## Homework Overview

This Looker Studio dashboard provides a comprehensive analysis of marketing performance for August 2024. The solution transforms raw marketing data into an interactive executive summary dashboard that delivers actionable insights across channel performance, ROI analysis, and campaign effectiveness to support data-driven marketing decisions.

## Business Tasks

The analysis aimed to:
1. Recreate the Executive Summary page from Improvado's reference dashboard
2. Integrate multiple data sources (spend, revenue, acquisition, web analytics)
3. Calculate key marketing efficiency metrics (ROAS, CAC, Conversion Rate)
4. Analyze channel performance and identify optimization opportunities
5. Build an interactive dashboard with proper data blending and filtering

## Data Sources

The analysis uses five primary datasets for August 2024:
1. **Marketing Spend Data**: Daily channel spend, impressions, clicks, conversions
2. **Revenue Data**: Daily revenue by product category with units sold
3. **Customer Acquisition Data**: New customers and lifetime value by channel
4. **Campaign Performance Data**: Campaign-level metrics and ROAS
5. **Website Analytics Data**: Sessions, pageviews, bounce rates, goal completions

## Data Architecture

I implemented a **blended data model** in Looker Studio for cross-source analysis:

* **Primary Tables**: Marketing Spend Data, Revenue Data, Customer Acquisition Data
* **Blend Keys**: Date (primary), Channel (secondary)
* **Calculated Fields**: ROAS, CAC, Conversion Rate, Marketing Efficiency
* **Data Relationships**: Time-series alignment across all datasets

## Key Metrics & Analysis

### Core Marketing KPIs
* Total Revenue: $2.85M | Total Spend: $198K
* ROAS: 14.3x | Conversion Rate: 3.8%
* Customer Acquisition Cost: $28.45
* Total Conversions: 42,180

### Channel Performance Analysis
1. **ROAS by Channel**:
   * Email Marketing: 8.7x (Highest efficiency)
   * LinkedIn Ads: 5.1x 
   * Google Ads: 4.8x
   * Facebook Ads: 3.2x
   * Twitter Ads: 2.1x

2. **Spend Distribution**:
   * Google Ads: 42% of total spend
   * Facebook Ads: 28% of total spend
   * Multi-channel attribution analysis

3. **Conversion Efficiency**:
   * Channel-specific conversion rates
   * Cost per conversion analysis
   * Click-through rate optimization

## Dashboard Features

### Visual Components
* **Executive Scorecards**: Key metrics with month-over-month comparisons
* **Revenue vs Spend Trend**: Dual-axis time series analysis
* **Channel Performance**: Stacked bar charts for spend, revenue, conversions
* **ROAS Analysis**: Comparative visualization across channels
* **Conversion Trends**: Daily performance tracking

### Interactive Elements
* **Date Range Control**: August 1-31, 2024 timeframe
* **Channel Filter**: Multi-select channel comparison
* **Responsive Design**: Mobile-optimized layout
* **Conditional Formatting**: Performance indicators

### Tools & Technologies
* **Looker Studio**: Data visualization, blending, and dashboard design
* **Google Sheets**: Data storage and management
* **Data Blending**: Multi-source integration techniques
* **Custom Formulas**: ROAS, CAC, efficiency calculations

## How to Use

1. **Access the Dashboard**: [Live Looker Studio Link]
2. **Interact with Filters**:
   * Adjust date range for different periods
   * Select specific channels for focused analysis
   * Hover over charts for detailed metrics
3. **Key Interactions**:
   * Click scorecards for detailed breakdowns
   * Use channel filters for comparative analysis
   * Export data for further analysis

## Insights & Recommendations

### Performance Optimization
1. **Channel Efficiency**:
   * Increase investment in Email Marketing (highest ROAS)
   * Optimize Twitter Ads spending or improve targeting
   * Balance Google Ads volume with Facebook Ads efficiency

2. **Budget Allocation**:
   * Reallocate budget from lower-performing channels
   * Test incremental spending on high-ROAS channels
   * Implement bid strategies based on conversion value

3. **Campaign Strategy**:
   * Scale successful campaign patterns
   * Develop channel-specific creative strategies
   * Implement cross-channel attribution modeling

### Technical Implementation
1. **Data Pipeline**:
   * Automated data ingestion from source systems
   * Validation rules for data quality
   * Scheduled refreshes for real-time insights

2. **Dashboard Enhancements**:
   * Add cohort analysis for customer retention
   * Implement forecasting models
   * Create drill-down pages for detailed analysis

## Project Structure
```
Improvado-Marketing-Dashboard/
│
├── Data/
│   ├── marketing_spend_data.csv
│   ├── revenue_data.csv
│   ├── customer_acquisition_data.csv
│   ├── campaign_performance_data.csv
│   └── website_analytics_data.csv
│
├── Documentation/
│   ├── dashboard_requirements.md
│   ├── data_dictionary.pdf
│   └── implementation_guide.pdf
│
├── Screenshots/
│   ├── executive_summary.png
│   └── mobile_view.png
│
├── Looker-Studio-Link.txt
└── README.md
```

## Business Impact

This dashboard enables:
* **Real-time Performance Monitoring**: Daily tracking of marketing efficiency
* **Data-Driven Decisions**: Objective channel optimization based on ROAS
* **Budget Optimization**: Strategic allocation based on performance data
* **Stakeholder Communication**: Clear visualization of marketing effectiveness

## Author

**Mahmoud Abdallah**

**Mahmoud_abdallah20@outlook.com**

---

*This Homework was completed as part of the Junior Analyst position application process for Improvado, demonstrating capabilities in marketing analytics, data visualization, and business intelligence implementation.*
