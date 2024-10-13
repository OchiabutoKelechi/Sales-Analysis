# Sales Analysis Project

## Project Overview
This project presents a detailed analysis of a company's sales data between January 2021 and June 2023. It highlights key trends and patterns across various aspects of the company's sales activities, including the top-performing and under-performing products by product type, product category, and specific product details. Additionally, it examines sales trends across different store locations, monthly sales trends, and patterns based on the time of day. The primary objective of this project is to deliver actionable insights through the Power BI dashboard, which helps managers and stakeholders make informed, data-driven decisions to enhance sales performance and meet organizational targets.

## Data Source
The dataset was downloaded from the Kaggle repository platform. The columns contained in the dataset are:
- Transaction ID
- Transaction Date
- Transaction Quantity
- Transaction Time
- Store ID
- Store Location
- Product ID
- Product Category
- Product Type
- Product Detail

Click on the link to interact with the [Analysis Dashboard](https://app.powerbi.com/groups/me/reports/848f531b-6c9b-4cd3-9765-ebe6cc837cc7/ReportSection37bdf803105093a3eef2?experience=power-bi&clientSideAuth)

## Softwares Used
1) Microsoft Excel: Utilized for data cleaning and transformation
2) Power Query Editor: Utilized for further cleaning and transformation of the data.
3) Power BI: Used for creation of interactive visualizations and dashboards to extract and display insights from the data.

## Data Cleaning and Transformation

The data cleaning and transformation process was extensive, focusing on ensuring data consistency and integrity to ensure the accuracy of the insights drawn from the analysis.
#### Key transformations included:

- Table Creation: The Excel worksheet containing the data was converted into structured a table using Excel’s Ctrl-A and Ctrl-T functions. This ensured proper organization for easier analysis.

- Removal of Duplicates: Duplicate entries across multiple columns were eliminated using Excel’s “Remove Duplicates” function to ensure the dataset reflected only unique transactions.

- Column Trimming: Irrelevant columns were removed to streamline the analysis, ensuring accuracy of the analysis.

- Correction of Misspellings: Both Power Query and Excel’s “Find and Replace” function were used to correct misspellings in key fields like product types, categories, and location names, ensuring consistency across the dataset.

- Blank Rows Removal: Blank rows were removed to maintain data integrity, ensuring a clean and complete dataset.

- Text Formatting: Data consistency was further ensured by cleaning, trimming, and capitalizing key columns such as Product Types, Product Details, Categories, Time and Date fields.

- Time of Day: Using Excel’s VLOOKUP function, the time of day (Morning, Afternoon, or Evening) was extracted from the "Time of Purchase" column.

- Extraction of Months: Power Query Editor was used to extract the month names from the "Date" column for easier identification of sales trends by month.

- Header Promotion: In both Power BI and Excel, the first row of each column was promoted to header status to ensure clarity.

- Column Renaming: To enhance readability, columns were renamed based on their content, improving the user experience within the Power BI dashboard.

## Exploratory Data Analysis (EDA)

1) What are the Total Sales and Quantity Sold?
2) Which Store generated the highest Sales?
3) Which Product Category generated the highest revenue?
4) Which Product Type had the highest Sales?
5) What are the Sales Trends over time?
6) What Time of Day generated the highest Sales?
7) Which Product Detail had the highest Sales?
8) What are the Total Quantities sold in each category?

## Data Analysis
To facilitate the analysis, the visualizations were divided into six key dashboards, each focusing on different aspects of sales performance. Appropriate charts were chosen to deliver clarity, including bar charts, card visuals, column charts, line graphs, and pie charts. Slicers were also deployed for easy drilling of the analysis.

#### General key Insights from the data visualization are summarized below:

- Total Sales: The company generated a total revenue of $698,812 from selling 214,470 units of products across three store locations: Hell's Kitchen, Astoria, and Lower Manhattan.

- Sales by Store Location: Hell's Kitchen was the top-performing store, generating $236,511, which accounts for 33.8% of total sales. Astoria followed closely with $232,244 (33.3%) while Lower Manhattan contributed $230,057 (32.92%).

- Sales by Product Category: Coffee was the best-selling category, bringing in $269,952 (38.63% of total revenue). Tea and Bakery Products followed with $196,406 (28.2%) and $82,316 (11.8%), respectively.

- Sales by Time of Day: Morning sales accounted for $388,315 (55.57%). Afternoon sales generated $204,702, while Evening sales brought in $105,793. Coffee and Tea products consistently performed well across all times of the day.

- Sales Trend by Month: There was a steady upward trend in sales from January to June 2023. June topped the chart with $166,486 in sales.

- Sales by Product Type: Barista Espresso was the best-selling Product Type, generating $91,406 (13% ). Brewed Chai Tea and Hot Chocolate followed with $77,082 and $72,416, respectively.

- Sales by Product Details: The Sustainably Grown Organic Rg product led with $21,152 in sales. Dark Chocolate Lg and Latte Lg followed with $21,006 and $19,112, respectively.
 
## Recommendations

1) Since Morning sales account for the majority of revenue (55.57%), focus marketing efforts on attracting more Morning customers. This could include offering breakfast promotions for Morning purchases.

2) From the analysis, Coffee contributes 38.63% of total revenue, consider introducing new coffee flavors, sizes, or seasonal specialties to attract more customers. Also, consider merging Coffee with Bakery items to increase sales in both categories.

3) While Coffee dominates, Tea and Bakery Products contribute significantly to sales. Focus on promoting these items through limited-time offers or seasonal pairings with coffee to grow their share of revenue.

4) With Evening sales lagging behind Morning and Afternoon sales, offer Evening promotions or discount to draw in more customers during those hours.

5) Barista Espresso, Brewed Chai Tea, and Hot Chocolate are top-sellers. Ensure that these Product Types are always available.

6) Focus on upselling the top-performing premium products in the Product Detail category, such as Sustainably Grown Organic Rg, Dark Chocolate Lg, and Latte Lg. These items have strong sales and likely generate higher profit margins, making them ideal for promotions to maximize revenue.

7) Offer incentives such as discounts or complimentary items for the purchase of underperforming products to encourage more patronage. Also, invest in strategic marketing to boost the visibility of the underperforming products.

8) Implement inventory management systems that prioritize keeping top-selling products in stock at all times. This will ensure you meet customers demands, avoid missed sales opportunities, and generally increase revenue.

9) Leverage the interactive dashboards to monitor sales performance in real-time and continuously implement and tweak strategies to improve overall overall sales.

## Conclusion
Conclusively, this Sales Analysis has provided valuable insights into the company's overall sales performance, customers behavior, sales trends, products performances, and overall business performance between January 2021 - June 2023.
By leveraging these insights, the company can make informed decisions to optimize sales strategies, improve team performance, boost products’ visibility, and boost their revenue.
