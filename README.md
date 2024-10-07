
# Adventure Works Bike Shop

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMWY2ODYxODktZTM2OC00YzZiLTg2YTEtMzMzNmE2NDI3ODQzIiwidCI6IjUwMzZkODQ1LWEzMTQtNDBhMi04YWQzLTM3YTlmMjUwMTQ2OSIsImMiOjEwfQ%3D%3D

## Problem Statement

![Problem](https://github.com/user-attachments/assets/8d316019-7434-44b6-9808-b6f1fc13bac5)


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Clean rows with null values and duplicates.
- Step 5 : Create data model for data sets. ![Data model](https://github.com/user-attachments/assets/9f3f88a6-4f4a-4a64-bb21-c8ea0045ca17) 
- Step 6 : Create measures for all kpi needed.
- Step 7 : Layout for visual and notes the metrics needed.
- Step 8 : Answering the objective/action  of the data "analyze the data to discover pattern and trends".


-YEAR-
Compare revenue growth rates across different year.
ASP per year to monitor price trends.
Volume trends over time.
Total profit by year to assess financial performance
Profit margin per year to understand overall profitability.

-BUSINESSS TYPE & CATEGORY-
Compare revenue across different product categories
Number of units sold within each category and business type
Profit margins across different and business types.
ASP across different categories and business types.

-COUNTRY-
Analyze revenue by country to identify top-performing regions.
ASP comparison by country to understand pricing strategies.
Profit contribution by country.
Country-specific profit margins to identify where margins are higher or lower.


# Insights Overview

## 1. Explosive Growth with Price Strategy Shift
- **Remarkable Growth**: 2020 saw a 51.5% revenue increase and 99.2% surge in units sold
- **Strategic Price Reduction**: 
  - Average price dropped 23.9% from previous year ($408 to $310)
  - This price reduction strategy proved highly effective:
    - Lowest quarter in 2020 ($12M) exceeded 2019's peak ($10M)
    - First quarter 2020 hit record $14M revenue

### Price Elasticity Impact
- Clear inverse relationship between price and volume:
  - 2018: High prices (~$980) = Lower volume
  - 2020: Reduced prices (~$310) = Significantly higher volume
- This suggests high price elasticity in the market

## 2. Profitability Dynamics
- **Overall Performance**: $65.8M total profit, 60% average margin
- **Efficiency vs. Volume Trade-off**:
  - 2019: Highest margins (65.3%) but lower volume
  - 2020: Lower margins (58.8%) but much higher volume and total profit
- **Business Model Efficiency**:
  1. Warehouses: Best performer (71% margin, $28M profit)
  2. Value Added Resellers: Strong second (65.1% margin, $23M profit)
  3. Specialty Bike Shops: Struggling (51.3% margin, only $3M profit)

## 3. Product Category Analysis
### The Bikes Paradox
- Dominate total profit ($56M, 84.71% of total)
- Lowest margin category (58.9%)
- Highest average price (>$1,000 in 2018, declining thereafter)

### Hidden Gems
- Clothing: Highest margin at 76.5%
- Accessories: Second-highest margin at 73.8%
These categories contribute less to total profit but are highly efficient

## 4. Geographical Insights
### United States Dominance
- 57.37% of revenue ($63M)
- 154K units sold
- Balanced strategy: moderate price ($408.8) with high volume

### Market-Specific Strategies
1. **Australia**: Premium Market
   - Highest average price ($582.5)
   - Lower volume (18K units)
   - Opportunity for margin improvement

2. **Canada**: Volume Play
   - Second-highest volume (49K units)
   - Lower average price ($331.2)
   - Strong margins suggest room for growth

3. **European Markets**: Untapped Potential
   - UK, France, Germany all under 20K units
   - Lower prices and revenues
   - Clear growth opportunity

## 5. Seasonal Patterns
Consistent peak sales in:
- May
- August
- November

This suggests potential for targeted seasonal strategies

## 6. Internet Sales Significance
"Not Applicable" business type:
- $29.36M in sales
- 64,398 units sold exclusively through internet channel
- Represents a significant digital presence


# Report

## Revenue and Growth Analysis
The company has demonstrated strong revenue performance with a total of $109.8 million generated. The year 2020 stands out as the most successful, contributing $52 million. This period saw consistent revenue growth.
##Impact of Pricing on Revenue
The average product price is $399.60. Interestingly, a lower average price correlates with higher revenue, as seen in 2020 when the price dropped to $310.50, leading to increased sales. This suggests that the market is price-sensitive, where reducing prices can drive higher demand. From 2018 to 2020, both Canada and the US maintained an average price below $900, making them the top revenue-generating regions. 

## Units Sold and Market Demand
The company sold a total of 274.8k units, with 2020 being the peak year, accounting for 60.81% of all orders. This spike in demand highlights the company’s ability to capitalize on market trends.

## Profit and Margin Performance
The company generated a profit of $65.8 million, with an impressive overall profit margin of 60%. Profit growth has been consistent year over year, with 2019 recording the highest margin at 65.3%. This shows strong operational efficiency and cost management.

## Product Performance and Key Drivers of Revenue
The top revenue-generating products are the Mountain 200 Black, 38, Mountain 200 Black, 42, and Mountain 200 Silver, 38, each contributing between $3.7 million and $4.4 million in revenue. The success of these models suggests a strong brand reputation and alignment with customer preferences.

## Sales Channels and Order Volume
Bikes dominate order volumes, driven primarily by value-added resellers (35k orders), warehouses (33k orders), and specialty bike shops (7k orders). Warehouses also excel across multiple product categories, including clothing, components, and accessories. High order volume and profit margin performance suggest the warehouse is a key sale channel.

## Market and Pricing Strategy
Bikes continue to lead in both average price and sales volume, positioning them as the flagship product category. Seasonal peaks in February, May, August, and November indicate key selling periods. Australia has a much higher average price of $582.50, yet it does not rank among the top revenue-generating countries. This indicates that simply maintaining higher prices isn’t enough to guarantee higher revenue.

## Regional Revenue Contribution
The United States remains the dominant market, contributing $63 million from 2018 to 2019 and $26 million in 2020, totaling $89 million. The sustained high performance in the US underscores its importance as the core revenue driver. Additionally, Canada, the US, and France have consistently maintained profit margins of 60% or higher, demonstrating their profitability as key markets.

## Customer Preferences and Trends
Color trends reveal that black and yellow are the top-selling options. Understanding these preferences allows for better inventory planning and targeted marketing efforts, ensuring the availability of popular colors.The top revenue-generating products are the Mountain 200 Black, 38, Mountain 200 Black, 42, and Mountain 200 Silver, 38, each contributing between $3.7 million and $4.4 million in revenue. The success of these models suggests a strong brand reputation and alignment with customer preferences.

![image](https://github.com/user-attachments/assets/a539cc21-2ae0-445e-9ba8-aa9c17f68a16)

![image](https://github.com/user-attachments/assets/3aa02f7a-6905-433b-99d0-73a32f123258)

![image](https://github.com/user-attachments/assets/aa9f1558-30d9-4625-b663-31ace1c22f2a)






