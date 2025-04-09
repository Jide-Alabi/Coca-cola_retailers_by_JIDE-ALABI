# Coca-Cola Retailer Sales Report Analysis (2022-2023)

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis EDA](#exploratory-data-analysis-eda)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

The objective of this project was to analyze and generate insights from Coca-Cola retailer sales data in the USA for the years 2022 and 2023. The analysis aimed to evaluate the performance of various Coca-Cola products across different regions, states, and cities, focusing on key sales metrics such as Total Sales, Units Sold, Operating Profit, and Operating Profit Margin (which is a column I added to the dataset by dividing Operating Profit by total sales= (Profit/Sales)*100). The final goal was to provide actionable insights for the sales and marketing teams to optimize strategies based on the data.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "Coca-cola_sales.CSV" file, containing detailed information about the Coca-cola products sales made by six (6) different retailers.

Dataset: The dataset used for this analysis contains the following key columns:
•	Retailer: The name of the retailer.
•	Retailer ID: Unique identifier for each retailer.
•	Invoice Date: The date of each sales transaction.
•	Region: The geographic region in which the retailer operates.
•	State: The state of the retailer's location.
•	City: The city where the retailer is based.
•	Beverage Brand: The specific Coca-Cola product sold.
•	Price per Unit: The selling price of each unit.
•	Units Sold: The number of units sold per transaction.
•	Total Sales: The total revenue generated from the sales (Price per Unit x Units Sold).
•	Operating Profit: The profit generated after accounting for costs.
•	Operating Profit Margin: The ratio of operating profit to total sales.


### Tools

Microsoft Excel- Data cleaning, Data analysis, Data visualization (Reports and dashboards). [Download here](https://microsoft.com)

### Data Cleaning and Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Removing duplicate values.
4. Data cleaning and formatting.
5. Various columns were transformed to ensure consistency.
6. New metrics were calculated, such as quarterly sales trends and profit margins.

### Exploratory Data Analysis EDA

1. What is the overall Retailers sales performance?

![retailers sales performance chart](https://github.com/user-attachments/assets/fb457557-293d-484a-8c2b-b891efaa9415)

2. Which product brand is the top seller?

![No of unit sold by brand](https://github.com/user-attachments/assets/dc65b81d-b6d4-4227-a2c0-bd9d795034c3)

3. What are the peak sales period?

![Screenshot 2025-04-08 125926](https://github.com/user-attachments/assets/33dee5eb-1821-4586-8f8b-12b3cb3cbce9)

4. What are the sales performance across different regions and states?

![Profit margin by region](https://github.com/user-attachments/assets/545d2110-94e5-4a69-a04d-30ad76583dfc)

![Profit by states](https://github.com/user-attachments/assets/1377c9af-2979-4d53-a18b-d8a8b1a82798)




### Data Analysis

1. Descriptive statistics were used to explore overall sales trends and performance across different time periods, regions, and product types.
2. Comparative analysis was performed on key metrics, such as the change in operating profit margin from 2022 to 2023.
3. Pivot tables and aggregations were employed to summarize data by different groupings (e.g., by region, state, and city).

![Screenshot 2025-04-03 010158](https://github.com/user-attachments/assets/5a853128-87a7-4f65-bba9-05948d94b31e)


### Results and Findings

1. Sales revenue increased rapidly in year 2023 compared to 2022.
2. Coca-cola is the preffered beverage brand across all states and region compared to the other Coca-cola brand.
3. West Soda who appears as the overall best selling retailer only dominated the market share at the West region which is the best selling region.
4. New York is the overall top selling state and it is in the Northeast region.
5. Retailers coverage are absent in some States resulting to overall low sales. 

### Recommendations

Based on the analysis, i recommend the following actions:
1. Invest in marketing and promotions during peak sales seasons like the festivals and the holiday seasons (Quarter 3 & 4) to maximize revenue.
2. Focus on expanding inventory budget to promote Coca-cola beverage brand as the top selling brand.
3. Retailers should invest in extending their reach and precense to new populated States and cities to multiply revenue.

### Limitations

- More robust dataset that span across longer period of years would have increased the accuracy of my conclusions from the analysis.
- Information like sales channel added to our dataset would have given a deeper insight to understand customers buying behavior to implement customer segregation strategy for sales optimization.

### References

How to document data analysis project the right way. [Click here](https://www.youtube.com/watch?v=0N9xekdKCwk&list=PPSV)






