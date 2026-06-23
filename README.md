## Retail-Sales-Analysis-Excel
An Excel based retail sales analysis project featuring data cleaning, data imputation, pivot tables, charts, and an interactive dashboard to generate business insights from sales data.
## Project Title
-  Retail Sales Data Analysis Using Star Schema Data Model.

## Objective
 - 	To analyze retail sales data using data analytics techniques.
 - 	To build a data model by Customer, Product, Store, Sales tables.
 - 	To create relationship using primary keys, and foreign keys.
 -	 To perform sales analysis using Pivot Tables.
 -	 To identify top customers, products, and store performance.
 -  To analyze profit, loss and discount impact on sales.

## Table Structure        
 ## Customer Table
| Column Name |	Column Description |	Data Type |
|-------------|--------------------|-----------|
| Customer_ID	| Unique ID for Each Customer	| Text|
| Customer_Name |	Name of the Customer	| Text|
| Age	| Age of the Customer	| Number|
| Gender | 	Gender of the Customer |	Text|
| City |	Name of the City where the Customer is located |	Text|
| State |	Name of the State where the Customer is located |	Text|
| Country |	Name of the Country where the Customer is located |	Text|
| Loyalty | Level	Indicates the Customer membership type |	Text|

## Store Table
| Column Name	| Column Description |	Data Type|
|-------------|--------------------|----------|
| Store_ID |	Unique Store Identifier |	Tex
| Store_Name |	Name of the Store |	Text|
| Region |	Represent the geographical region where Store is located |	Text|
| City |	Name of the City where the Store is located	 |Text|
| Store_Type |Indicates the which type od Store |	Text|

## Product Table
| Column Name |	Column Description |	Data Type|
|-------------|--------------------|----------|
| Product_ID |	Unique Product Identifier |	Text|
| Product_Name |	Name of the Product |	Text|
| Category |	Product Category |	Text|
| Sub_Category |	Product Sub_Category |	Text|
| Brand |	Name of the Product Brand |	Text|
| Cost |	Represent cost of goods sold for the Product|	Currency|
| Stock	| Represent the quantity of products available in inventory |	Number|

## Sales Table(Fact Table)
| Column Name |	Column Description |	Data Type |
|-------------|--------------------|-----------|
| Sales_ID |	Unique ID for each Sales	|Text|
| Order_Date|	Date when the order was placed	 |Date|
| Customer_ID |	Unique ID for Each Customer |	Text|
| Product_ID |	Unique Product Identifier |	Text|
| Store_ID	| Unique Store Identifier |	Text|
| Quantity |	Number of units sold |	Number|
| Unit_Price |	Price per Single Unit	 |Currency|
| Discount |	Discount percentage applied |	Percentage|
| Payment_Type|	Mode of Payment|	Text|
| Total_Amount |	Total Revenue after discount |	Currency |
| Gross_Profit |	Profit after subtracting cost	| Currency|
| Profit/Loss |	Indicate whether transaction is profit or loss |	Text

## Tools Used
 - Microsoft Excel
 - Power Query
 - Pivot Tables
 - Pivot Charts
 - Slicers
 - Conditional Formatting
 - Data Modeling
 - Functions(SUM(),	SUMIF(), AVERAGE(), AVERAGEIF(),
           - COUNT(),	COUNTIF(),IF(),	MAX (), MIN (),
           - MODE()	STDDEV())

## Dashboard
 - <img width="1352" height="544" alt="Screenshot 2026-06-23 223422" src="https://github.com/user-attachments/assets/85902b6a-d229-4f97-872a-91423c3e57b9" />.
 - <img width="1074" height="410" alt="Screenshot 2026-06-23 224024" src="https://github.com/user-attachments/assets/54903900-50bc-4827-9ee9-63c8cb98c51f" />.



## Key Insights
 ## Descriptive Analysis:
 - 	Female Customers have a higher order count and purchase quantity, which contributes to their total Sales.

 -  The North region shows strong Customers demand, with higher order count and quantity leading to the highest total sale

 -	 PayPal is the most preferred payment method used by a majority of customers.

 - 	Customers in the middle age group contributes the highest purchases compared to other age group.
 ## Diagnostic Analysis:
 -	The West region has lower sales due to significantly lower order quantity (593) compared to other regions (1400- 1550).

    Losses occur regardless of discount levels as the cost price exceeds the selling price indicating a pricing issue.
 ## Predictive Analysis
 -	Female customers are expected to contribute more to future sales due to their higher order count and purchase quantity.

 - The middle age group is likely to remain the key contributor to total sales.
 ## Prescriptive Analysis:
 -	Maintain a selling price above cost price and avoid excessive discounts to ensure profitability.

 - Focus marketing efforts on the West region to increase customer engagement.

## Skills Demonstrated
 - Data Cleaning
 - Data Analysis
 - Data Visualization
 - Dahboard Creation
 - Business Insights Generation

 ## Conclusion
  - The analysis highlights key sales drivers and problem areas. By improving pricing strategies, controlling discounts and focusing on high performing segments the business can enhance both sales and profitability.


- Stock |	Represent the quantity of products available in inventory |	Number

