# Sales Analysis Project

## Project Overview
This Power BI Sales Analysis project provides comprehensive and fully interactive insights into the key trends and patterns in sales activities, such as top-performing and poor-performing products by product types, product categories, and product details. Also, to identify sales trends by store locations, and sales trends over months and time of the day. The dashboard offers detailed tracking of sales performance metrics for managers and stakeholders of KACYFOODS, enabling them to make informed data-driven decisions to increase their sales and meet the organization's target.

## Data Source
I downloaded the data from the popular data repository website, Kaggle

## Tools and Software Used
- Power BI: The primary tool used in this project was Power BI, which facilitated the creation of interactive visualizations and dashboards to extract and display insights from the data. 
- Power Query Editor: I used the Power Query Editor in Power BI for data cleaning and transformation. I used this tool to perform various operations such as removing duplicates, eliminating blank rows, formatting columns, extracting 'Month Names' from the 'Date' column, and replacing values across different columns. Also, I used the DAX formula in Power Query to multiply the 'Transaction Quantity' column with the 'Unit Price' Column using the SUMX DAX formula to get the Total Sales value.

- Microsoft Excel: Microsoft Excel played a crucial role at the beginning of the project. It helped me grasp a better understanding of the data structure and also played crucial role during the data-cleaning phase of the project. I used the Excel VLOOKUP formula to extract the 'Time of Day' from the "Time of Purchase" column, eliminate blank rows and fields in the data, format columns, remove duplicate values, replace values across different columns using the "Find and Replace" function, among others.

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
Which store made the highest sales?
Which store sold the highest quantity of products?
Which product generated the highest sales in the Product Category?

