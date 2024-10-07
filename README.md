

# Adventure Works Bike Shop

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMWY2ODYxODktZTM2OC00YzZiLTg2YTEtMzMzNmE2NDI3ODQzIiwidCI6IjUwMzZkODQ1LWEzMTQtNDBhMi04YWQzLTM3YTlmMjUwMTQ2OSIsImMiOjEwfQ%3D%3D

## Problem Statement

![Problem](https://github.com/user-attachments/assets/8d316019-7434-44b6-9808-b6f1fc13bac5)


# Power BI Data Analysis Project

## Overview
This project demonstrates the process of importing, cleaning, transforming, modeling, and visualizing data using Power BI Desktop. The objective is to create a comprehensive and interactive data model to derive insights and key metrics from the provided datasets.

## Table of Contents
- [About the Project](#about-the-project)
- [Actions](#actions)
- [Tools & Technologies](#tools--technologies)
- [Project Goals](#project-goals)
- [License](#license)

## About the Project
The project leverages Power BI Desktop to work with datasets in CSV format. The aim is to build a comprehensive data model that provides actionable insights through clean data, efficient relationships, and accurate calculations.

## Actions

### 1. Utilize Power BI Desktop
- **Import Datasets**: Load CSV files into Power BI.
- **Data Transformation**: Use Power Query to clean, transform, and integrate data.
- **Build Relationships**: Establish connections between tables within the data model.
- **DAX Calculations**: Use DAX (Data Analysis Expressions) to create necessary calculations and visualizations.

### 2. Prepare the Data
- **Clean and Standardize**: Ensure data consistency and prepare it for analysis.
- **Remove Duplicates**: Use Power Query to identify and remove duplicate entries.
- **Modify Table Names**: Prefix table names with 'd' for dimension tables and 'f' for fact tables (e.g., `dCustomer` and `fSales_Data`).
- **Create New Dimensions and Measures**: Generate additional dimensions and measures as needed for the analysis.

### 3. Model the Data
- **Design Data Model**: Create a suitable structure for the data to support comprehensive analysis.
- **Establish Relationships**: Define connections between entities (tables).
- **Create Hierarchies and Dimensions**: Organize data for easy drill-down and analysis.

### 4. Necessary Calculations
- **Perform Exploratory Data Analysis (EDA)**: Examine data distribution, quality, and consistency.
- **Data Quality Checks**: Verify correct data types for each column and analyze value distribution for accuracy.
  
#### Key Metrics Calculations
The following DAX calculations were used to derive key metrics:

- **2020 Revenue**: Analyze performance in FY2020.
  ```DAX
  
  Avg. Price =
  DIVIDE(
      [Revenue], [Units Sold]
  )
  
  Profit = 
  [Revenue] - SUM(fSales_Data[Product Standard Cost])

  Profit = 
  [Revenue] - SUM(fSales_Data[Product Standard Cost])

  Profit Margin =
  DIVIDE(
      [Profit], [Revenue], ""
  )
  
  Revenue =
  SUM(
      fSales_Data[Sales Amount]
  )

  Units Sold =
  SUM(
      fSales_Data[Order Quantity]
  )

  
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









