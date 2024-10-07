
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
  - Average price dropped from 2018-2019 is 58% ($980 to 408)
  - Average price dropped 23.9% from 2019-2020 ($408 to $310)
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

#Recommendation Supported by Data
1. **Price Optimization Strategy**
   - **Data**: The 23.9% price reduction led to a 99.2% increase in units sold and 51.5% revenue growth
   - **Recommendation**: 
     - Fine-tune pricing by market: Each region shows different price sensitivity
     - Consider targeted price reductions in European markets to stimulate growth, as these markets currently show lower penetration
     - Maintain premium pricing in Australia while exploring volume growth opportunities

2. **Category Balance Optimization**
   - **Data**: 
     - Bikes generate 84.71% of profit but have the lowest margin (58.9%)
     - Clothing and accessories have margins over 70% but contribute minimally to total profit
   - **Recommendation**:
     - Develop bundling strategies: Pair high-margin accessories/clothing with bike purchases
     - Create premium bike lines to improve category margins while maintaining volume
     - Focus marketing on high-margin categories during non-peak bike sales periods

3. **Geographical Expansion Strategy**
   - **Data**:
     - U.S. dominates with 57.37% of revenue and 154K units
     - European markets each sell less than 20K units despite developed economies
     - Canada succeeds with a volume strategy (49K units, lower prices)
   - **Recommendation**:
     - Replicate U.S. success factors in European markets
     - Adapt Canada's volume strategy for similar markets
     - Maintain premium positioning in Australia while seeking efficiency improvements

4. **Seasonal Optimization**
   - **Data**: Consistent sales peaks in May, August, and November across years
   - **Recommendation**:
     - Align inventory management with seasonal patterns
     - Develop marketing campaigns for off-peak months
     - Consider region-specific seasonal strategies, as patterns may vary by market

5. **Digital Channel Enhancement**
   - **Data**: 
     - "Not Applicable" business type (internet sales) generated $29.36M with 64,398 units
     - This channel operates at 41.1% margin, lower than other business types
   - **Recommendation**:
     - Improve digital channel efficiency to boost margins
     - Expand e-commerce in markets with low physical presence
     - Develop strategies to complement existing business types

6. **Business Type Optimization** 
   - **Data**: 
     - Warehouse (71% margin) and Value Added Reseller (65.1% margin) significantly outperform Specialty Bike Shops (51.3% margin)
     - Specialty Bike Shops contribute only $3M in profit
   - **Recommendation**:
     - Evaluate and potentially restructure the Specialty Bike Shop model
     - Consider converting underperforming Specialty Bike Shops to the Warehouse or Value Added Reseller model
     - Develop specific support and improvement programs for Specialty Bike Shops

7. **Profit Margin Management** 
   - **Data**: 
     - Overall profit margin decreased from 65.3% in 2019 to 58.8% in 2020
     - This was offset by volume increases, but represents a potential area for improvement
   - **Recommendation**:
     - Identify and replicate high-margin success factors from 2019
     - Develop strategies to gradually increase margins while maintaining volume
     - Focus on operational efficiency to improve margins without raising prices


![image](https://github.com/user-attachments/assets/a539cc21-2ae0-445e-9ba8-aa9c17f68a16)

![image](https://github.com/user-attachments/assets/3aa02f7a-6905-433b-99d0-73a32f123258)

![image](https://github.com/user-attachments/assets/aa9f1558-30d9-4625-b663-31ace1c22f2a)






