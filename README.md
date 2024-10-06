# Sales Analysis Project

## Project Overview
This Power BI Sales Analysis project provides comprehensive and fully interactive insights into the key trends and patterns in sales activities, such as top-performing and poor-performing products by product types, product categories, and product details of the company between January 2021 - June 2023. Also, to identify sales trends by store locations, and sales trends over months and time of the day. The dashboard offers detailed tracking of sales performance metrics for managers and stakeholders of KACYFOODS, enabling them to make informed data-driven decisions to increase their sales and meet the organization's target.

## Data Source
I downloaded the data from the popular data repository website, Kaggle

## Tools and Software Used
- Power BI: The primary tool used in this project was Power BI, which facilitated the creation of interactive visualizations and dashboards to extract and display insights from the data. 
- Power Query Editor: I used the Power Query Editor in Power BI for data cleaning and transformation. I used this tool to perform various operations such as removing duplicates, eliminating blank rows, formatting columns, extracting 'Month Names' from the 'Date' column, and replacing values across different columns. Also, I used the DAX formula in Power Query to multiply the 'Transaction Quantity' column with the 'Unit Price' Column using the SUMX DAX formula to get the Total Sales value.

- Microsoft Excel: Microsoft Excel played a crucial role at the beginning of the project. It helped me understand the data structure better and played a crucial role during the data-cleaning phase of the project. I used the Excel VLOOKUP formula to extract the 'Time of Day' from the "Time of Purchase" column, eliminate blank rows and fields in the data, format columns, remove duplicate values, replace values across different columns using the "Find and Replace" function, among others.

## Data Cleaning and Transformation
Key transformations included:

1) Creating Tables: Data on each worksheet was transformed into a table using the Cntr-A followed by Cntr-T functions.
2) Removal of Duplicates: I ensured the uniqueness of entries across all columns using the "Remove Duplicates" function in Excel.
3) Column Trimming: Unnecessary columns were removed to streamline the analysis. This ensured the focus was on relevant data.
4) Correction of Misspellings: I used the "Find and Replace" function in Excel and Power Query to correct wrongly spelt entries in the data such as product types,  product categories, product details, and location names.
5) Blank Rows Removal: Blank rows were removed to maintain data integrity.
6) Text Formatting: Columns such as Product Types, Product Details, Product Categories, Date, and Time columns were cleaned, trimmed, and capitalized to ensure consistency.
7) New Column Creation: I created two new columns called "Time of Day" and "Month" respectively. Therein, I extracted the Time of Day i.e. Morning, Afternoon, and Evening from the "Time of Purchase" column using the VLOOKUP formula in Excel and input it in the newly created "Time of Day" column. Also, I extracted 'Month Names' from the "Date Column" using Power Query Editor.
8) Header Promotion: I ensured that the first row of each column was promoted to header status for clarity.
9) Column Renaming: Columns were renamed for better readability.

## Exploratory Data Analysis (EDA)
- What's the Total Sales and Quantity Sold?
- Which store made the highest sales?
- Which Product Category generated the highest revenue?
- Which Product Type generated the highest sales?
- What is the Sales trend?
- Which time of the day generated the highest sales?
- Which Product Detail generated the highest Sales?
- What are the total quantities sold in each category?

## Data Analysis
To ensure easy navigation and adequate understanding of this analysis, I divided the visualizations into 6 dashboards, utilizing various and appropriate visualization charts to convey clarity and knowledge of the insights.

#### General key Insights from the data visualization are summarized below:

- Total Sales: Total revenue of $698,812 was generated, selling 214,470 Quantity of products across the three store locations; Hell's Kitchen, Astoria, and Lower Manhattan.

- Sales by Store Location: Hell's Kitchen store generated the highest revenue among the three (3) store locations, with a total revenue of $236,511, representing 33.8% of the total revenue. Astoria is next on the list with an income of $232,244 (33.3%) and Lower Manhattan with a total revenue of $230,057 (32.92%).
  
- Sales by Product Categories: Coffee generated the highest sales, with a total revenue of $269,952, representing 38.63%. Tea and Bakery products are next on the list, with a total sales of $196,406(28.2%) and $82,316(11.8%) respectively.
  
- Sales by Time Of Day: The highest sales were made in the Morning hours, with a total revenue of $388,315, representing 55.57% of the total sales. Afternoon and Evening hours generated $204,702, and $105, 793 revenue respectively. Coffee and Tea products categories generated the highest Sales throughout the Times of the day.
  
- Sales Trend by Month: The Sales Trend by Month has been in a progressive upward trajectory from January - June 2023, with June topping the chart with a total revenue of $166, 486.
  
- Sales by Product Types: Barista Espresso generated the highest sales among the twenty-nine (29) different Product Types, with a total revenue of $91, 406, representing 13% of the total revenue. Brewed Chai Tea and Hot Chocolate made it to the top of the list with a revenue of $77,082, and $72,416 respectively.
  
- Sales by Product Details: Sustainably Grown Organic Rg product generated the highest Sales in this category with a total revenue of $21,152. Dark Chocolate Lg and Latte Lg are next on the list with $21,006 and $19,112 sales respectively.

