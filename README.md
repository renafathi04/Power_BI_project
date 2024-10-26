# Electric Vehicle Market Analysis

![Electric Vehicle Market Analysis Dashboard](images/dashboard_sample.png)

## Project Overview
This project focuses on the electric vehicle (EV) market analysis for the Indian market. The objective is to provide insights for a US-based automotive company planning to introduce their electric vehicles in India. Using Power BI, this analysis highlights key market trends, consumer preferences, and the competitive landscape, offering actionable insights to guide the company's market entry strategy.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Sources](#data-sources)
- [Power BI Analysis](#power-bi-analysis)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [License](#license)

## Objectives
1. **Market Trends**: Identify current trends in the Indian electric vehicle market, including growth rates and projections.
2. **Competitor Analysis**: Analyze the performance of existing EV companies in India, including market share, pricing, and distribution.
3. **Recommendations**: Provide strategic recommendations for the company's market entry and competitive positioning.

## Data Sources
This document provides comprehensive metadata descriptions for the columns in the CSV files related to electric vehicle sales data. These datasets include sales by state, sales by maker, and a date dimension table useful for time-series analysis.


*******************************************
electric_vehicle_sales_by_state.csv

- date: The date on which the data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- state: The name of the state where the sales data is recorded. This indicates the geographical location within India.
- vehicle_category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- electric_vehicles_sold: The number of electric vehicles sold in the specified state and category on the given date.
- total_vehicles_sold: The total number of vehicles (including both electric and non-electric) sold in the specified state and category on the given date.

*******************************************
electric_vehicle_sales_by_makers.csv

- date: The date on which the sales data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- vehicle_category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- maker: The name of the manufacturer or brand of the electric vehicle.
- electric_vehicles_sold: The number of electric vehicles sold by the specified maker in the given category on the given date.

*******************************************
dim_date.csv

- date: The specific date for which the data is relevant. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- fiscal_year: The fiscal year to which the date belongs. This is useful for financial and business analysis.
- quarter: The fiscal quarter to which the date belongs. Fiscal quarters are typically divided as Q1, Q2, Q3, and Q4.


## Power BI Analysis
This project uses Power BI to visualize and interpret data, offering a comprehensive view of the Indian EV market:
- **Sales Trend Dashboard**: Visualizes the historical and projected sales growth of EVs in India.
- **Competitor Analysis Dashboard**: Shows a comparative analysis of existing EV companies in terms of market share, sales volume, and pricing.
  
## Key Findings
1. **High Growth Potential**: The Indian EV market shows significant growth potential due to rising fuel costs and supportive government policies.
2. **Urban Focus**: EV adoption is more prominent in urban areas, especially among environmentally conscious consumers with higher disposable incomes.
3. **Competitive Pricing Essential**: Competitors are offering various models across different price segments, so competitive pricing will be crucial for market penetration.
4. **Policy Incentives**: Government incentives have a substantial impact on adoption rates, particularly in high-demand states.

## Technologies Used
- **Power BI**: For data visualization and interactive dashboards.
- **Data Sources**: CSV and Excel files, along with public databases on automotive sales and demographics.
.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
