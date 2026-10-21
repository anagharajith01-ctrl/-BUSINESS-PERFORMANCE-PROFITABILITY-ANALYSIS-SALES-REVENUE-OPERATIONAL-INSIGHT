# -BUSINESS-PERFORMANCE-PROFITABILITY-ANALYSIS-SALES-REVENUE-OPERATIONAL-INSIGHT
Analyzing sales, revenue, profitability, and operational performance using Python, Pandas, NumPy, Matplotlib, Seaborn, and Plotly to generate actionable business insights.

PROJECT ABSTRACT
The project titled “business performance & profitability analysis: sales, revenue & operational insight” focuses on analysing sales performance, profitability and operational efficiency using python. The study uses a secondary sales dataset obtained from github to identify business trends and generate meaningful insights for decision-making.
The dataset was cleaned and prepared by handling missing values, removing duplicate records, standardising inconsistent categorical values and converting date columns into appropriate formats. Exploratory data analysis (eda) was performed using python libraries such as pandas, numpy, matplotlib, seaborn and plotly. The analysis examined total sales, profit, profit margins, product and category performance, regional sales, discount levels, delivery status and order cancellations. Correlation analysis was also used to examine relationships between sales and profit, as well as quantity sold and sales revenue.
The findings showed that the business generated approximately ₹36.53 crore in sales revenue and ₹9.23 crore in profit, with an overall profit margin of 25.27%. Technology was the highest-selling product category, while laptops were the top-selling individual product. The east region recorded the highest sales revenue and the highest cancellation rate. The analysis also identified differences in profitability across discount levels and product categories. A strong positive correlation was observed between sales and profit, whereas quantity sold and sales revenue showed a weak positive correlation.
Overall, the project demonstrates how python-based data cleaning, analysis and visualisation can transform raw sales data into useful business insights. The findings can support sales planning, profitability monitoring and operational improvement.


INTRODUCTION
1.1 INTRODUCTION
In today's competitive business environment, analysing sales and profitability is important for understanding business performance and making informed decisions. Businesses need to monitor sales revenue, profit margins, product performance, regional performance, and operational activities to identify strengths and areas that require improvement. Analysing sales data helps businesses understand performance patterns and identify opportunities to improve profitability and operational efficiency.
The project titled “Business Performance & Profitability Analysis: Sales, Revenue & Operational Insight” focuses on analysing sales transaction data to understand the overall performance of a business. The dataset was obtained from GitHub as secondary data and contains 10,500 records and 16 columns. Python was used to clean and prepare the data, perform exploratory data analysis (EDA), and create visualizations to present the results clearly.
The analysis examines total sales, total profit, profit margins, product and category performance, regional performance, monthly sales trends, the impact of discounts on profitability, and order delivery status. These areas help identify high-performing products and regions, understand changes in profitability, and examine patterns in order cancellations.
The project aims to convert raw sales data into meaningful business insights that can support better decision-making. The findings are used to identify areas of strong performance and suggest practical recommendations for improving profitability and operational efficiency.


1.1 BUSINESS CONTEXT
Sales and profitability analysis plays an important role in understanding business performance. Analysing sales transactions helps identify high-performing products, profitable categories, regional differences, and changes in performance over time. Examining discounts and order cancellations also helps businesses understand factors that may affect profitability and operational efficiency. This project uses sales transaction data to explore these areas and develop meaningful business insights.

1.2 PROBLEM STATEMENT
Raw sales data contains information about transactions, products, regions, discounts, profits, and order statuses. However, without systematic analysis, it can be difficult to identify performance patterns, compare profitability, and recognize operational issues. Therefore, this project aims to analyse the available sales data using Python to identify trends, evaluate business performance, examine profit margins and cancellation rates, and provide data-driven recommendations for better decision-making.

1.3 PROJECT OBJECTIVES
•	To analyse total sales, profit, and profit margins.
•	To evaluate sales and profitability across products, categories, and regions.
•	To identify monthly sales and profit margin trends.
•	To examine the impact of discounts on profitability.
•	To analyse order delivery statuses and cancellation rates.
•	To identify key business insights and provide recommendations for improving business performance.

1.4 PROJECT SCOPE
The scope of this project is to analyse sales transaction data to understand business performance, profitability, and operational trends. The analysis covers sales and profit by product, product category, and region, along with monthly sales trends, profit margins, discount impact, order delivery status, and cancellation rates. Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly are used for data preparation, exploratory data analysis, and visualization. The project focuses on identifying performance patterns and generating data-driven insights and recommendations to support business decision-making. The findings are limited to the dataset obtained from GitHub and may not represent the performance of an actual business in every situation.

1.5 DATASET DESCRIPTION
The dataset used in this project contains sales transaction records that were analysed to understand business performance, profitability, and operational trends. It was obtained from GitHub and used as secondary data. The dataset includes information about sales, products, profits, regions, discounts, and order delivery status.

1.5.1 DATA SOURCE
The dataset was obtained from GitHub, an online platform for sharing and managing datasets and code. It was used as the source of sales transaction data for this project.

1.5.2 TYPE OF DATA
This project uses secondary data, as the data was obtained from an existing source rather than collected directly by the researcher.

1.5.3 DATASET SIZE
The dataset consists of 10,500 records and 16 columns. Each record represents a sales transaction, while the columns contain details about the transaction, product, sales amount, profit, and other business-related information.

1.5.4 STUDY PERIOD AND PROJECT DURATION
The project was carried out from September to October. During this period, the dataset was prepared, cleaned, analysed, and visualised to identify business performance patterns.

1.5.5 DESCRIPTION OF IMPORTANT COLUMNS
COLUMN NAME	DESCRIPTION
Order ID	Unique identification number assigned to each order
Customer ID	Unique identification number assigned to each customer
Customer Name	Name of the customer who placed the order
Order Date	Date on which the order was recorded
Region	Geographical region associated with the order
State	State associated with the order
Product Category	Category to which the product belongs
Product Name	Name of the product sold
Quantity Sold	Number of units sold
Unit Price	Price per unit of the product
Sales Amount	Total sales value of the transaction
Discount %	Discount applied to the transaction
Profit Amount	Profit earned from the transaction
Sales Representative	Name of the representative responsible for the sale
Payment Method	Method used to make the payment
Delivery Status	Current status of the order, such as delivered, shipped, pending, or cancelled

1.6 METHODOLOGY, TOOLS AND TECHNOLOGIES

1.6.1 PROJECT METHODOLOGY
The project followed a systematic data analysis approach to evaluate business performance and profitability. Secondary sales data obtained from GitHub was examined, cleaned, and prepared for analysis. Exploratory data analysis and visualization were then performed to identify trends, patterns, and insights related to sales, profit, product performance, regional performance, discounts, and order cancellations.

1.6.2 DATA CLEANING AND PREPARATION
Data cleaning and preparation were carried out to improve data quality and ensure the dataset was suitable for analysis. The process included checking for duplicate records, identifying and handling missing values, correcting inconsistent entries, converting data types, and preparing relevant columns for analysis. Additional columns, such as profit margin and date-related fields, were used where required for further analysis.

1.6.3 TOOLS AND TECHNOLOGIES USED
The following tools and technologies were used in the project:
•	Python: Used as the programming language for data analysis.
•	Pandas: Used for data cleaning, data manipulation, grouping, and summarization.
•	NumPy: Used for numerical calculations and descriptive statistical analysis, including mean, median, percentiles, and standard deviation.
•	Matplotlib: Used to create basic charts and visualizations.
•	Seaborn: Used to visualize data patterns and relationships.
•	Plotly: Used to create interactive charts for exploring business performance.

1.6.4 DATA ANALYSIS PROCESS
The data analysis process involved the following steps:
•	Obtaining the secondary dataset from GitHub.
•	Inspecting the dataset structure and column information.
•	Cleaning and preparing the data for analysis.
•	Performing exploratory data analysis to examine sales, profit, and other business metrics.
•	Creating visualizations to compare product, category, regional, and monthly performance.
•	Interpreting the results to identify key business insights.
•	Developing recommendations based on the findings to support business decision-making.

EXPLORATORY DATA ANALYSIS (EDA)

2.1 EXPLORATORY DATA ANALYSIS (EDA)
Exploratory Data Analysis (EDA) is the process of examining a dataset to understand its structure, identify missing values and duplicate records, summarize important statistics, and discover patterns and relationships in the data. In this project, EDA is used to understand sales performance, profitability, product categories, regional performance, discounts, and order statuses before drawing business insights.

2.1.1 DATASET OVERVIEW
The dataset used for this project consists of sales transaction records obtained from a GitHub repository. The original dataset contains 106,575 records and 16 columns, providing information about customers, orders, products, sales, profitability, and delivery operations. The columns include Order ID, Customer ID, Customer Name, Order Date, Region, State, Product Category, Product Name, Quantity Sold, Unit Price, Sales Amount, Discount %, Profit Amount, Sales Representative, Payment Method, and Delivery Status. The dataset contains both categorical and numerical variables. Categorical variables, such as Region, Product Category, Payment Method, and Delivery Status, describe the characteristics of transactions, while numerical variables, such as Quantity Sold, Unit Price, Sales Amount, Discount %, and Profit Amount, support quantitative analysis. Initially, 11 columns were stored as the object data type and five columns were stored as float64. The Order Date column was also initially stored as an object rather than a datetime data type. An initial examination of the dataset was conducted using Python and Pandas to understand its structure, data types, and completeness before performing data cleaning and exploratory data analysis.
Source: Raw Sales Dataset

2.2 MISSING VALUES AND DUPLICATE ANALYSIS
Data cleaning and preparation were performed to improve the quality, consistency, and reliability of the sales dataset before conducting exploratory data analysis. The original dataset contained 106,575 records and 16 columns. During the initial examination, missing values, duplicate records, inconsistent category labels, inconsistent region names, invalid date values, and negative numerical values were investigated. These issues were addressed using appropriate data-cleaning techniques to prepare the dataset for sales, profitability, and operational analysis.

2.2.1 IDENTIFICATION AND REMOVAL OF DUPLICATE RECORDS
Duplicate records were identified in the original dataset to prevent repeated entries from affecting the analysis. A total of 1,575 duplicate records were identified and removed, reducing the dataset from 106,575 to 105,000 records. The cleaned dataset retained all 16 original columns at this stage.

Table 2.1: Summary of Duplicate Analysis
Data quality check	Result
Original records	106,575
Original columns	16
Duplicate records removed	1,575
Records after duplicate removal	105,000

2.2.2 IDENTIFICATION OF MISSING VALUES
The missing-value analysis was conducted after duplicate removal. The results showed that four columns contained missing values: Customer Name, Quantity Sold, Discount %, and Payment Method. The remaining 12 original columns contained no missing values.

Table 2.2: Missing Values After Duplicate Removal
Column	Missing values	Percentage
Customer Name	1,529	1.46%
Quantity Sold	1,563	1.49%
Discount %	2,089	1.99%
Payment Method	2,191	2.09%
The missing values were handled according to the nature of each column. Missing Customer Name values were replaced with “Unknown” to retain the corresponding records without inventing customer names. Missing Quantity Sold values were filled using the median of the available values because the median is less affected by extreme values than the mean. Missing Discount % values were also filled using the median. Missing Payment Method values were replaced with “Unknown” because the actual payment method could not be determined from the available data.
West	26,224
South	26,071
Total	105,000

2.2.3 CONVERSION OF ORDER DATE AND CREATION OF DATE-BASED COLUMNS
The Order Date column was initially stored as an object data type. It was converted into the datetime64[ns] data type to support date-based calculations and time-series analysis. During conversion, invalid date values were investigated, and any values that could not be interpreted as valid dates needed to be checked before being treated as missing.
Three additional columns were created from Order Date to support the analysis:
•	Order Year: Extracted the year from each order date. This column supports yearly sales and profit comparisons.
•	Order Month: Extracted the month name, such as January or February. This column supports monthly sales and profit trend analysis.
•	Order YearMonth: Created a year-month period, such as 2025-01. This column supports chronological monthly grouping and helps distinguish the same month across different years.
These columns were derived from the original Order Date column and did not replace it. They provided additional time-based fields for analysing sales trends and changes in business performance.

2.2.4 IDENTIFICATION AND HANDLING OF INCONSISTENCIES
Inconsistencies were examined in both numerical and categorical columns of the dataset. In the Unit Price column, 117 negative values were identified, and the displayed records were associated with the Cancelled delivery status. In the Sales Amount column, 346 negative values were found, and all 346 records were associated with cancelled transactions. The absolute values of the original Sales Amount were also compared with the corresponding values in the cleaned dataset after rounding. The validation showed 78,669 matching records and zero mismatches among the records examined. The Quantity Sold and Profit Amount columns were also examined for negative values and potential inconsistencies, since these values can affect sales and profitability analysis. However, negative values were not automatically assumed to be errors because they may represent returns, refunds, or financial adjustments. Missing values were handled separately: missing values in Customer Name were replaced with “Unknown”, missing values in Quantity Sold and Discount % were filled using their respective median values, and missing values in Payment Method were replaced with “Unknown”. In the categorical columns, Product Category contained variations in spelling, capitalization, and abbreviations, such as “Furniture”, “Furnitures”, “furni”, “Technology”, “Tech”, “techno”, “Office Supplies”, and “Off. Supplies”. These labels were standardized into three categories: Furniture, Technology, and Office Supplies. Similarly, inconsistent labels in the Region column, including “North”, “NORTH”, “north”, and “N. Region”, were standardized into North, East, West, and South. These corrections helped improve data consistency and enabled more reliable comparisons across products, regions, sales, and profitability.

2.3 SALES, REVENUE AND PROFITABILITY ANALYSIS
1. What are the total sales/revenue generated by the business?
Objective: To determine the total revenue generated by the business during the period covered by the dataset.
Analysis: The total sales revenue was calculated by summing all values in the Sales Amount column using Python.
Results: The total sales revenue was ₹365,268,912 (approximately ₹36.53 crore).
Interpretation: The business generated total sales revenue of approximately ₹36.53 crore. This provides an overall measure of the sales activity recorded in the dataset and serves as a baseline for evaluating profitability and operational performance.
2. What is the total profit?
Objective: To calculate the total profit generated by the business.
Analysis: The values in the Profit Amount column were summed using Python to obtain the total recorded profit.
Results: The total profit was ₹92,319,868 (approximately ₹9.23 crore).
Interpretation: The dataset recorded a total profit of approximately ₹9.23 crore. This represents the combined profit recorded across the transactions and helps assess the business's overall financial performance.
3. What is the overall profit margin?
Objective: To determine the percentage of sales revenue retained as profit.
Analysis: The overall profit margin was calculated by dividing total profit by total sales revenue and multiplying the result by 100.
Results: The overall profit margin was 25.27%.
Interpretation: The business recorded a profit margin of 25.27%, meaning that approximately ₹25.27 of profit was recorded for every ₹100 of sales revenue. This provides an overall indication of profitability, although it does not show differences between individual products or categories.
4. What are the average sales and profit per transaction?
Objective: To determine the average sales revenue and profit generated per transaction.
Analysis: The average Sales Amount and average Profit Amount were calculated using the mean of their respective columns.
Results:
Measure	Average amount
Average sales per transaction	₹3,478.75
Average profit per transaction	₹879.24
Interpretation: Each transaction generated an average sales amount of ₹3,478.75 and an average recorded profit of ₹879.24. These averages provide a general understanding of transaction value and profitability, although individual transactions may differ considerably.
5. How does sales/revenue change over time?
Objective: To identify monthly changes in sales revenue and determine periods of relatively high and low sales.
Analysis: The Order Date column was grouped by month and year, and the Sales Amount values were summed for each month.
Results: Monthly Sales Revenue
Month	Sales revenue
Jan 2025	₹1,93,03,689.34
Feb 2025	₹2,81,02,638.08
Mar 2025	₹1,97,44,696.54
Apr 2025	₹1,95,68,327.66
May 2025	₹2,05,69,578.80
Jun 2025	₹5,77,28,548.29
Jul 2025	₹1,71,41,895.26
Aug 2025	₹2,20,16,480.92
Sep 2025	₹1,77,04,999.66
Oct 2025	₹2,02,84,058.24
Nov 2025	₹1,98,38,339.26
Dec 2025	₹1,85,17,196.60
Jan 2026	₹2,04,41,355.89
Feb 2026	₹1,41,80,131.38
Mar 2026	₹2,06,15,161.86
Apr 2026	₹2,03,24,955.17
May 2026	₹91,86,859.47
Interpretation: Sales revenue fluctuated considerably across the observed months. June 2025 recorded the highest monthly sales revenue, at approximately ₹5.77 crore, while May 2026 recorded the lowest, at approximately ₹91.87 lakh. These variations suggest changes in monthly sales activity that could be investigated further using information about demand, product availability, promotions, and order patterns.
6. Which product categories generate the highest sales/revenue?
Objective: To compare sales revenue across product categories and identify the largest contributors.
Analysis: Sales Amount was grouped by Product Category and summed for each category.
Results:
Product category	Sales revenue
Technology	₹22,51,70,104
Furniture	₹12,78,35,946
Office Supplies	₹1,22,62,862
Interpretation: Technology generated the highest sales revenue, followed by Furniture and Office Supplies. Technology was the largest contributor to recorded revenue, indicating that it was the leading category by sales value.

7. Which products generate the highest sales/revenue?
Objective: To identify the products contributing the most sales revenue.
Analysis: Sales Amount was grouped by Product Name and summed, and the products were compared in descending order of revenue.
Results: Product Sales Revenue
Product	Sales revenue
Laptop	₹11,10,27,000
Smartphone	₹5,54,74,000
Sofa	₹4,97,36,090
Tablet	₹2,57,39,020
Desk	₹2,26,46,850
Office Chair	₹1,93,66,900
Monitor	₹1,91,49,600
Table	₹1,41,55,520
Bookshelf	₹1,22,07,930
Headphones	₹1,06,49,530
Filing Cabinet	₹97,22,650
Whiteboard	₹78,57,837
Keyboard	₹31,30,948
Calculator	₹17,98,425
Paper Pack	₹9,84,822.30
Stapler	₹7,87,768.10
Binder	₹5,24,332.20
Pens Set	₹3,09,677.10
Interpretation: Laptops generated the highest sales revenue, followed by Smartphones and Sofas. Pens Set generated the lowest revenue among the listed products. The results show that revenue was concentrated in a small number of high-value product groups, while several other products contributed comparatively smaller amounts.
8. Which regions generate the highest sales/revenue?
Objective: To compare sales revenue across geographical regions.
Analysis: Sales Amount was grouped by region and summed for each region.
Results:
Region	Sales revenue
East	₹12,46,10,100
West	₹8,38,21,370
North	₹8,07,80,890
South	₹7,60,56,570
Interpretation: The East region generated the highest sales revenue, at approximately ₹12.46 crore. The South region recorded the lowest revenue, at approximately ₹7.61 crore. This comparison identifies differences in regional sales performance and can help guide further investigation into regional demand and business opportunities.

9. Which product categories generate the highest profit?
Objective: To determine which product categories, contribute the most to total profit.
Analysis: Profit Amount was grouped by Product Category and summed for each category.
Results:
Product category	Total profit
Technology	₹6,35,12,360.06
Furniture	₹2,37,84,221.24
Office Supplies	₹50,23,286.66
Interpretation: Technology generated the highest total profit, followed by Furniture and Office Supplies. Technology was the leading category in both sales revenue and total profit, making it an important contributor to the business's recorded financial performance.
10. Which products generate the highest and lowest profit?
Objective: To identify the products contributing the highest and lowest total profit.
Analysis: Profit Amount was grouped by Product Name and summed, allowing products to be ranked by their total recorded profit.
Results: Product Profit
Product	Total profit
Laptop	₹3,36,82,985.59
Smartphone	₹1,41,53,740.78
Sofa	₹84,08,026.06
Tablet	₹68,24,142.93
Monitor	₹50,57,122.00
Desk	₹45,68,280.25
Office Chair	₹42,26,064.86
Whiteboard	₹31,47,313.09
Headphones	₹29,54,175.53
Table	₹27,13,472.89
Bookshelf	₹22,24,866.20
Filing Cabinet	₹16,43,510.98
Keyboard	₹8,40,193.23
Calculator	₹7,79,375.67
Paper Pack	₹4,20,623.97
Stapler	₹3,29,418.14
Binder	₹2,18,900.63
Pens Set	₹1,27,655.16
Interpretation: Laptops generated the highest total profit, followed by Smartphones. Pens Set generated the lowest total profit among the listed products. These results identify the products contributing most and least to total profit, but total profit alone does not indicate which products have the highest profit margin.
11. Which regions generate the highest profit?
Objective: To compare the total profit generated by each region.
Analysis: Profit Amount was grouped by region and summed for each region.
Results:
Region	Total profit
East	₹3,21,92,746
North	₹2,09,54,867
West	₹1,97,36,967
South	₹1,94,35,288
Interpretation: The East region generated the highest total profit, followed by North, West, and South. The East region was the leading region in both sales revenue and total profit, while the South region recorded the lowest values for both measures.
12. Which products or categories have high sales but relatively low profit?
Objective: To identify product categories with high sales revenue but comparatively low profitability.
Analysis: Sales Amount, Profit Amount, and Profit Margin were compared across Product Category. Profit margin was calculated by dividing profit by sales revenue and multiplying by 100.
Results:
Product category	Sales revenue	Total profit	Profit margin
Furniture	₹12,78,35,946	₹2,37,84,221	18.61%
Office Supplies	₹1,22,62,862	₹50,23,287	40.96%
Technology	₹22,51,70,104	₹6,35,12,360	28.21%
Interpretation: Technology generated the highest sales revenue and total profit, while Furniture recorded the lowest profit margin at 18.61%. Office Supplies generated lower revenue but had the highest profit margin at 40.96%. Therefore, Furniture is the category that warrants closer investigation into costs, discounts, and pricing, despite its substantial sales revenue.
13. Which sales representatives generate the highest sales and profit?
Objective: To compare sales revenue and total profit across sales representatives.
Analysis: Sales Amount and Profit Amount were grouped by Sales Representative and summed for each representative.
Results:
Sales representative	Sales revenue	Total profit
Charlie Brown	₹8,41,10,530.39	₹2,23,92,273.96
Frank Thomas	₹6,16,83,860.94	₹1,44,14,736.69
Emma Wilson	₹5,66,05,304.19	₹1,31,15,225.70
David Miller	₹5,59,53,777.16	₹1,44,68,826.80
Bob Jones	₹5,37,70,099.35	₹1,49,48,625.12
Alice Smith	₹5,31,45,340.39	₹1,29,80,179.69
Interpretation: Charlie Brown generated the highest sales revenue and total profit among the listed representatives. Alice Smith recorded the lowest sales revenue and Emma Wilson recorded the lowest total profit. These results compare overall contributions, while profit margin provides an additional measure of profitability relative to sales.
14. Which sales representatives have the highest profit margin?
Objective: To determine which sales representatives, generate the highest profit relative to their sales revenue.
Analysis: Profit margin was calculated for each representative by dividing Profit Amount by Sales Amount and multiplying by 100.
Results:
Sales representative	Sales revenue	Total profit	Profit margin
Bob Jones	₹5,37,70,099.35	₹1,49,48,625.12	27.80%
Charlie Brown	₹8,41,10,530.39	₹2,23,92,273.96	26.62%
David Miller	₹5,59,53,777.16	₹1,44,68,826.80	25.86%
Alice Smith	₹5,31,45,340.39	₹1,29,80,179.69	24.42%
Frank Thomas	₹6,16,83,860.94	₹1,44,14,736.69	23.37%
Emma Wilson	₹5,66,05,304.19	₹1,31,15,225.70	23.17%
Interpretation: Bob Jones recorded the highest profit margin at 27.80%, while Emma Wilson recorded the lowest at 23.17%. Although Charlie Brown generated the highest total sales and profit, Bob Jones retained a higher proportion of sales as profit. This demonstrates why total profit and profit margin should be evaluated separately.
15. Do higher sales generally correspond to higher profit across sales representatives?
Objective: To examine the relationship between sales revenue and profit across sales representatives.
Analysis: The Pearson correlation coefficient was calculated between sales revenue and profit for the sales representatives.
Results: The correlation coefficient was 0.98.
Interpretation: The coefficient indicates a very strong positive relationship between sales revenue and total profit across the representatives. In general, representatives with higher sales also recorded higher total profit. However, correlation does not establish causation, and differences in profit margins should also be considered.
16. Does higher quantity sold generally correspond to higher sales?
Objective: To examine whether transactions with higher quantities sold tend to have higher sales amounts.
Analysis: The Pearson correlation coefficient was calculated between Quantity Sold and Sales Amount.
Results: The correlation coefficient was 0.17.
Interpretation: The coefficient indicates a weak positive relationship between quantity sold and sales amount. Higher quantities did not consistently correspond to substantially higher sales revenue, possibly because unit prices, product types, and discounts varied across transactions. Therefore, quantity alone is not a strong predictor of sales amount in this dataset.
17. How does profit vary by discount level?
Objective: To compare total and average profit across different discount levels.
Analysis: Transactions were grouped by Discount %, and the number of transactions, total profit, and average profit were calculated for each discount level.
Results:
Discount	Transactions	Total profit	Average profit
0%	34,277	₹3,02,55,506.84	₹882.68
5%	17,153	₹1,35,72,672.55	₹791.27
10%	19,264	₹2,42,14,390.09	₹1,256.98
15%	17,255	₹1,21,03,927.70	₹701.47
20%	17,051	₹1,21,73,370.78	₹713.94
Interpretation: The 0% discount group generated the highest total profit, while the 10% discount group recorded the highest average profit per transaction. The 15% discount group had the lowest average profit. These differences suggest that profitability varied by discount level, but they do not prove that discounts alone caused the changes.
18. Does a higher discount appear to reduce profit margin?
Objective: To examine how profit margin changes across discount levels.
Analysis: Sales Amount and Profit Amount were grouped by Discount %, and profit margin was calculated for each group.
Results:
Discount	Sales revenue	Total profit	Profit margin
0%	₹11,65,44,200	₹3,02,55,506.84	25.96%
5%	₹5,22,07,970	₹1,35,72,672.55	26.00%
10%	₹9,20,89,460	₹2,42,14,390.09	26.29%
15%	₹5,10,58,460	₹1,21,03,927.70	23.71%
20%	₹5,33,68,860	₹1,21,73,370.78	22.81%
Interpretation: Profit margin increased slightly from 25.96% at no discount to 26.29% at a 10% discount. However, it declined to 23.71% at a 15% discount and 22.81% at a 20% discount. This pattern suggests that higher discount levels were associated with lower profit margins in the higher-discount groups, although other factors may also have influenced profitability.
19. What is the distribution of Delivered, Shipped, Pending, and Cancelled orders?
Objective: To understand the distribution of transactions across delivery statuses.
Analysis: The number of records in each Delivery Status category was counted using Python.
Results:
Delivery status	Number of records
Cancelled	26,331
Shipped	26,306
Delivered	26,206
Pending	26,157
Total	105,000
Interpretation: The four delivery-status categories had relatively similar record counts. Cancelled orders formed the largest group, with 26,331 records, while Pending orders formed the smallest group, with 26,157 records. The relatively even distribution indicates that all four statuses represent substantial portions of the dataset and should be considered in operational analysis.
20. Which regions have the highest cancellation rates?
Objective: To identify regional differences in order cancellation rates.
Analysis: Cancelled orders were counted for each region, and the cancellation rate was calculated as the number of cancelled orders divided by the total number of orders in that region, multiplied by 100.
Results:
Region	Cancelled orders	Cancellation rate
East	6,739	25.66%
North	6,558	24.80%
South	6,493	24.91%
West	6,541	24.94%
Interpretation: The East region had the highest cancellation rate at 25.66%, while the North region had the lowest at 24.80%. The difference between the regions was relatively small, but the East region may warrant further investigation to identify possible reasons for its higher cancellation rate.
21. Which product categories have the highest cancellation rates?
Objective: To compare cancellation rates across product categories.
Analysis: The cancellation rate was calculated separately for Furniture, Office Supplies, and Technology using the number of cancelled orders relative to the total orders in each category.
Results:
Product category	Cancellation rate
Office Supplies	25.23%
Furniture	25.11%
Technology	24.89%
Interpretation: Office Supplies had the highest cancellation rate at 25.23%, followed by Furniture at 25.11%. Technology recorded the lowest rate at 24.89%. The differences were small, indicating broadly similar cancellation rates across the three categories.
22. Are there regions/categories with both strong sales and poor delivery performance?
Objective: To examine whether regions with higher sales also experience higher cancellation rates.
Analysis: Sales revenue, total profit, transaction counts, cancellation rates, and profit margins were compared across regions.
Results:
Region	Sales revenue	Total profit	Transactions	Cancellation rate	Profit margin
East	₹12,46,10,100	₹3,21,92,745.93	26,258	25.66%	25.83%
North	₹8,07,80,890	₹2,09,54,867.25	26,447	24.80%	25.94%
South	₹7,60,56,570	₹1,94,35,287.79	26,071	24.91%	25.55%
West	₹8,38,21,370	₹1,97,36,966.99	26,224	24.94%	23.55%
Interpretation: The East region generated the highest sales and profit but also recorded the highest cancellation rate. The West region had the lowest profit margin at 23.55%, despite generating more sales revenue than North and South. These findings indicate that strong sales performance does not necessarily mean better delivery performance or higher profit margins.
23.Which sales representatives generate the highest sales and profit?
Objective: To identify the sales representatives who contribute the most to total sales revenue and profit.
Analysis: The Sales Amount and Profit Amount columns were grouped by Sales Representative, and the total sales revenue and profit were calculated for each representative using Python.
Results:
Sales Representative	Sales Revenue (₹)	Total Profit (₹)
Charlie Brown	8,41,10,530.39	2,23,92,273.96
Frank Thomas	6,16,83,860.94	1,44,14,736.69
Emma Wilson	5,66,05,304.19	1,31,15,225.70
David Miller	5,59,53,777.16	1,44,68,826.80
Bob Jones	5,37,70,099.35	1,49,48,625.12
Alice Smith	5,31,45,340.39	1,29,80,179.69
Interpretation: Charlie Brown generated the highest sales revenue and total profit among the six representatives. Alice Smith recorded the lowest sales revenue, while Emma Wilson recorded the lowest total profit. These results show differences in overall sales contribution and profitability among the representatives.
24. Which sales representatives have the highest profit margin?
Objective: To identify the sales representatives who generate the highest profit relative to their sales revenue.
Analysis: Profit margin was calculated for each sales representative by dividing total Profit Amount by total Sales Amount and multiplying by 100.
Results:
Sales Representative	Sales Amount (₹)	Profit Amount (₹)	Profit Margin (%)
Bob Jones	5,37,70,099.35	1,49,48,625.12	27.80
Charlie Brown	8,41,10,530.39	2,23,92,273.96	26.62
David Miller	5,59,53,777.16	1,44,68,826.80	25.86
Alice Smith	5,31,45,340.39	1,29,80,179.69	24.42
Frank Thomas	6,16,83,860.94	1,44,14,736.69	23.37
Emma Wilson	5,66,05,304.19	1,31,15,225.70	23.17
Interpretation: Bob Jones recorded the highest profit margin at 27.80%, while Emma Wilson recorded the lowest at 23.17%. Although Charlie Brown generated the highest total profit, Bob Jones retained a higher proportion of sales revenue as profit. This demonstrates that the representative with the highest total profit may not have the highest profit margin.

DATA VISUALISATION AND INTERPRETATION
3.1 BUSINESS PERFORMANCE OVERVIEW

3.1.1 TOTAL SALES, TOTAL PROFIT, PROFIT MARGIN

<img width="913" height="738" alt="image" src="https://github.com/user-attachments/assets/b644b035-2daf-40aa-87cf-63d088b91150" />
The business generated total sales revenue of ₹36,52,68,912 (approximately ₹36.53 crore) and a total profit of ₹9,23,19,868 (approximately ₹9.23 crore). The overall profit margin was 25.27%, indicating that the business earned approximately ₹25.27 in profit for every ₹100 of sales revenue. The results provide an overview of the company's financial performance during the period analysed.

3.1.2 AVERAGE SALES AND PROFIT PER TRANSACTION

<img width="940" height="701" alt="image" src="https://github.com/user-attachments/assets/982bac18-7567-42e5-9ac6-2cb194a7d43d" />

 The analysis shows that the average sales revenue per transaction was ₹3,478.75, while the average profit was ₹879.24. This indicates that each transaction generated an average profit of ₹879.24. The comparison helps evaluate the average financial contribution of individual transactions and provides insight into the business's profitability.

3.1.2 SALES BY PRODUCT CATEGORY, PRODUCT AND REGION

<img width="940" height="1003" alt="image" src="https://github.com/user-attachments/assets/bf9cb884-8044-458b-b2df-512e966e6765" />

 Technology generated the highest sales revenue at ₹22.52 crore, followed by Furniture at ₹12.78 crore and Office Supplies at ₹1.23 crore. Among individual products, Laptops led with ₹11.10 crore, followed by Smartphones at ₹5.55 crore and Sofas at ₹4.97 crore. Regionally, East recorded the highest sales at ₹12.46 crore, while South recorded the lowest at ₹7.61 crore. These findings identify the strongest product category, top-selling products and best-performing region, supporting better sales planning and resource allocation

 3.1.3 MONTHLY SALES AND REVENUE TREND
<img width="940" height="323" alt="image" src="https://github.com/user-attachments/assets/fc250d7c-2b67-4fe6-99f6-62a2592973cf" />
 
The monthly sales analysis shows fluctuations in revenue over time, with sales peaking in June 2025 at ₹5.77 crore. The lowest sales were recorded in May 2026 at ₹0.92 crore. These variations highlight changes in monthly sales performance and can help identify peak and low-sales periods for better business planning.
3.1.4 MONTHLY PROFIT MARGIN TREND
 <img width="940" height="332" alt="image" src="https://github.com/user-attachments/assets/bc134e19-04f4-4241-b505-3d875bab9474" />

The monthly profit margin analysis shows how profitability varied over time. The trend helps identify months with higher and lower average profit margins, providing insights into changes in business profitability and supporting better pricing, discount and cost-management decisions.

3.1.5 PROFIT BY PRODUCT CATEGORY, REGION AND PRODUCT
 <img width="940" height="967" alt="image" src="https://github.com/user-attachments/assets/f70803e2-4143-4685-9b68-c1ee470bf959" />

The monthly profit margin analysis shows how profitability varied over time. The trend helps identify months with higher and lower average profit margins, providing insights into changes in business profitability and supporting better pricing, discount and cost-management decisions.

3.1.6AVERAGE PROFIT BY DISCOUNT LEVEL
 <img width="940" height="437" alt="image" src="https://github.com/user-attachments/assets/70e9fabd-52ea-4db7-9231-3949731e0ec0" />

The analysis shows that the average profit varied across discount levels. The 10% discount level recorded the highest average profit of ₹1,256.98, while the 15% discount level recorded the lowest at ₹701.47. This suggests that moderate discounts may support higher average profits, whereas larger discounts do not necessarily increase profitability.
3.1.7 IMPACT OF DISCOUNT ON PROFIT MARGIN
 <img width="940" height="403" alt="image" src="https://github.com/user-attachments/assets/33139202-f361-48d4-88db-e56527816d3a" />

The analysis shows that profit margins varied across discount levels. The highest profit margin was recorded at the 10% discount level (26.29%), while the lowest was observed at the 20% discount level (22.81%). This suggests that higher discounts may reduce profitability, highlighting the importance of balancing discounts with profit margins.

3.1.8 DISTRIBUTION OF ORDERS BY DELIVERY STATUS
 <img width="940" height="692" alt="image" src="https://github.com/user-attachments/assets/b0d692d1-e9be-4640-8e77-d9dcfdcc41ed" />

The analysis shows that orders were distributed almost equally across the four delivery statuses: Cancelled (26,331), Shipped (26,306), Delivered (26,206) and Pending (26,157). Cancelled orders were slightly higher than the other categories, highlighting the need to investigate cancellation reasons and improve order fulfilment.





3.1.9 CANCELLATION RATE BY REGION AND PRODUCT CATEGORY
 <img width="940" height="940" alt="image" src="https://github.com/user-attachments/assets/87a397dd-0a75-453a-8ea4-dc36a38c21b3" />

The analysis shows that the East region had the highest cancellation rate at 25.66%, while the North region had the lowest at 24.80%. Across product categories, Office Supplies recorded the highest cancellation rate at 25.23%, followed by Furniture at 25.11% and Technology at 24.89%. These findings suggest that cancellations were relatively similar across regions and categories, but further investigation into cancellation reasons could help improve order fulfilment.

3.1.10 REGIONAL SALES VS. CANCELLATION RATE
 <img width="940" height="337" alt="image" src="https://github.com/user-attachments/assets/e70d813b-70a1-4b87-8033-bc94c789b1b2" />

The analysis compares regional sales with cancellation rates. The East region recorded the highest sales of ₹12.46 crore and the highest cancellation rate of 25.66%, while the South region had the lowest sales of ₹7.61 crore and a cancellation rate of 24.91%. This indicates that higher sales do not necessarily correspond to lower cancellation rates, highlighting the need to improve order fulfilment across regions.

3.1.11 CORRELATION BETWEEN SALES AND PROFIT
 <img width="796" height="479" alt="image" src="https://github.com/user-attachments/assets/5bac50f3-b099-44b7-a3b8-3320a617556b" />

Sales and profit have a very strong positive correlation of 0.98, indicating that higher sales are generally associated with higher profits.

3.1.12 CORRELATION BETWEEN QUANTITY SOLD AND SALES
 <img width="719" height="483" alt="image" src="https://github.com/user-attachments/assets/1a500d59-8584-4c6e-ae9d-b2f2a94667ba" />

Quantity Sold and Sales Amount have a weak positive correlation of 0.17, indicating that selling more units does not necessarily lead to proportionally higher sales revenue.

