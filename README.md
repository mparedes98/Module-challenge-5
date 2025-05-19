# Athletic Sales Analysis

## Overview
This project analyzes sales data for athletic wear across multiple retailers in the United States over a two-year period (2020-2021). The analysis focuses on identifying top-performing regions, cities, retailers, and products, with special attention to women's athletic footwear sales trends.

## Project Structure
- `athletic_sales_analysis.ipynb`: Jupyter notebook containing all the data analysis
- `Resources/athletic_sales_2020.csv`: Sales data for 2020
- `Resources/athletic_sales_2021.csv`: Sales data for 2021

## Analysis Performed
The following analyses were conducted using Python with pandas:

1. **Data Preparation**
   - Combined sales data from 2020 and 2021
   - Converted date strings to datetime format
   - Verified data integrity and checked for null values

2. **Regional Performance Analysis**
   - Identified regions that sold the most products
   - Determined regions with the highest total sales

3. **Retailer Analysis**
   - Ranked retailers by total sales across all product categories
   - Identified the top retailers for women's athletic footwear specifically

4. **Time-Based Analysis**
   - Determined the days with the highest women's athletic footwear sales
   - Identified the weeks with the highest women's athletic footwear sales

## Key Findings

### Top Regions by Products Sold
1. Northeast (New York, New York): 111,954 units
2. South (Texas, Houston): 90,322 units
3. West (California, San Francisco): 85,478 units

### Top Regions by Total Sales
1. Northeast (New York, New York): $39,801,235
2. West (California, San Francisco): $33,973,228
3. Southeast (Florida, Miami): $31,600,863

### Top Retailers by Total Sales
1. West Gear (West, California, San Francisco): $32,794,405
2. Kohl's (West, California, Los Angeles): $25,127,160
3. Foot Locker (Northeast, New York, New York): $25,008,568

### Top Retailers for Women's Athletic Footwear
1. West Gear (West, California, San Francisco): 12,107 units
2. Foot Locker (Northeast, New York, New York): 10,996 units
3. Kohl's (West, California, Los Angeles): 10,826 units

### Time Analysis for Women's Athletic Footwear Sales
- **Top Sales Day**: July 16, 2021 ($1,521,825)
- **Top Sales Week**: Week ending December 19, 2021 ($3,098,970)

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Conclusion
The analysis reveals that the Northeast region, particularly New York City, leads in both total products sold and sales revenue. West Gear emerged as the top retailer overall and specifically for women's athletic footwear. The highest sales for women's athletic footwear occurred in mid-July 2021, with the strongest weekly performance in December 2021, likely due to holiday shopping.
