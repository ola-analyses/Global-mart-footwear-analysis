 # Global-mart-footwear-analysis

## **Executive Summary:**
Using Power Query, DAX, and Power BI, I transformed raw sales data into an interactive dashboard to analyze sales performance and profitability for Global Mart Footwear.

The reported results show **$344K in total sales across 3,905 units sold, $158K in profit, a 46% profit margin, and an average order value (AOV) of $711.73**. The analysis identified Clarks as the leading brand by sales, generating approximately $124K, while Derby shoes recorded the highest reported profit margin at 50%. The USA was identified as the leading market by sales volume.

The dashboard provides an overview of business performance and enables users to compare results across brands, footwear categories, and geographic markets.

## **Business Problem**
Global Mart Footwear operates across multiple markets and sells a variety of footwear products under different brands. 
The business needs a clearer understanding of which brands and product styles contribute most to sales and profit, how performance differs across countries, and where profitability requires further investigation.
Key business questions:
1. Which brands contribute the most to total sales?
2. Which footwear styles generate the highest profit margins?
3. How do sales and profitability vary across geographic markets?
4. How do sales trends change over time?
5. Which products and markets should management investigate to improve profitability?

## **About the Data**
The dataset consists of retail transaction records detailing sales performance across geographic regions, product categories, brands, colors, Quantity and payment methods.

 **Order Metrics:** Order Date, Sales Amount, Quantity, Cost, Profit, Profit Margin 
 
 **Product Categorization:** Brand (Clarks, Zara, Steve Madden, Timberland), Category (Boots, Oxfords, Loafers, Derby, Monk Straps, Slippers), Color.

**Geographics:** Country (USA, UK, Ghana, Zimbabwe, India, Kenya, Cyprus, Uganda)

**Customer Transaction Channel:** Payment Type (Card, Cash, Bank Transfer, Mobile)

## **📊 Dashboard Preview**
 ### **Executive Overview**
![Executive Overview](https://github.com/ola-analyses/Global-mart-footwear-analysis/blob/main/overview_page.png)


## **Product Analysis**
![Product Analysis](https://github.com/ola-analyses/Global-mart-footwear-analysis/blob/main/product_analysis.png)

## **Methodology**

1. Used Power Query to extract, clean, and transform raw Excel/CSV data. Handled missing values, validated numeric data types, and standardized product and geographic fields.

2. Developed DAX measures to track key performance indicators (KPI), including Total Sales, Units Sold, Total Profit, and Profit Margin.

3. Built an interactive, two-page Power BI dashboard (*Executive Overview* and *Product Analysis*) to visualize business performance and compare sales and profitability across brands, product categories, and geographic markets.
   
 ## **🛠️ Tool & SKill**
 Power Bi: DAX, Writing functions, ETL, Calculated Column, Data Visualization, Data Modeling 

 Microsoft Excel

 Power Query

## **Results**

Creating an executive dashboard provides leadership with real-time visibility into sales performance and profit drivers. By democratizing this data, regional managers can self-serve insights, saving the analytics team hours of ad-hoc reporting requests each week.

Our analysis revealed that while volume is driven by popular brands like Clarks (~$124K total sales) and categories like Boots and Oxfords, high profit margins are heavily concentrated in styles like Derby (50% profit margin). Additionally, the USA and UK remain primary core markets, while emerging regions like Ghana demonstrate significant untapped potential.

## **Business Recommendations**

1. Focus on high-profit products rather than relying only on sales volume.

2. Monitor discount levels to protect profit margins.

3. Strengthen sales strategies in lower-performing regions and months.

4. Promote products that combine high demand with strong profitability.

5.  Use regional and product-level insights to support more targeted business decisions.
