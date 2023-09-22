# Sprocket Central Pty Ltd Marketing Analysis

I am thrilled to share my enriching experience as a Data Analyst Intern with KPMG International Limited. Allow me to capture the highlights of this invaluable journey. 
I was tasked with analyzing customer data for Sprocket Central Pty Ltd, where I focused on the following key responsibilities:
1. Data Quality Assessment
2. Data Insights
3. Data Insights and Presentation

![image](https://github.com/yahayakayode/Sprocket-Central-Ltd-Marketing-Analysis/assets/40303292/bbb215a6-b613-48ca-8b2a-701ff3a3e79b)

![image](https://github.com/yahayakayode/Sprocket-Central-Ltd-Marketing-Analysis/assets/40303292/e91b151a-26a3-4274-be05-9f3c4bdcf59e)


# An Overview 
Sprocket Central Pty Ltd is a mid-sized company that specializes in providing top-tier bicycles and readily accessible cycling accessories to riders. Sprocket Central Pty Ltd, a prominent organization, is encountering a familiar obstacle prevalent in the business world. They are focused on efficiently analyzing customer data to optimize their marketing strategies. However, the company's team is currently grappling with the task of transforming and cleaning the dataset to ensure its suitability for analysis. With a substantial dataset at their disposal, they seek expert guidance on how to effectively preprocess and refine the data for accurate analysis. 
To tackle this obstacle, Sprocket Central Pty Ltd has procured a fresh dataset comprising 1000 prospective customers, encompassing their demographic information and other attributes. Despite these customers lacking prior transactional engagement with the company, the marketing team holds a firm belief that through diligent analysis, valuable customer insights can be unveiled. These insights will empower them to optimize resource allocation, allowing for a more targeted approach toward high-value customers. 
The company provided four essential datasets: 
- Transactions
- Customer Demographic
- Customer Address
- New Customer List

# The Business Questions 
Some of the business questions the analysis addressed are. 
1.	What are the trends in the underlying data? 
2.	Which customer segment has the highest customer value? 
3.	What do you propose should be Sprocket Central Pty Ltd’s marketing and growth strategy? 

# Tool Used
  Power BI

# Data Exploration & Cleaning
I explored the four datasets using Power Query, where I meticulously identified data quality issues necessitating cleaning and transformation. This thorough process was essential to guarantee the accuracy, consistency, and reliability of the customer data for subsequent analysis and decision-making.
The original customer Demographic dataset contained 4,000 rows and 13 columns, the number of rows was reduced after data cleaning, and the number of columns was increased to 15 after feature engineering. There are 20,000 distinct transactions (rows) and 13 columns, this number of rows and columns was not affected after data cleaning.

# Feature Engineering
To address some of the business questions and to also get better insights from the data, feature engineering was performed to create the following new columns in the customer dataset.
- Age
- Age in years
- Age group
DAX formula was also used to calculate the profit and profit margin.

# Data modeling 
After performing data cleaning on the dataset, I went further to establish relationships between the tables. This enabled the creation of a cohesive data model where the tables were connected using customer_ids as the primary key.
<img width="706" alt="Screenshot 2023-09-22 at 19 17 12" src="https://github.com/yahayakayode/Sprocket-Central-Ltd-Marketing-Analysis/assets/40303292/aa5181dc-2bdf-4ad6-9dea-5fffa58e1994">

# Data Analysis & Visualisation
Two interactive reports were created to answer the business questions for the marketing team.
## 1. Revenue Analysis
<img width="840" alt="Revenue Analysis" src="https://github.com/yahayakayode/Sprocket-Central-Ltd-Marketing-Analysis/assets/40303292/a63ed4b9-c27e-4b36-84e3-acde8e4e3e6a">

## 2. Customers Analysis
<img width="843" alt="Customer Analysis" src="https://github.com/yahayakayode/Sprocket-Central-Ltd-Marketing-Analysis/assets/40303292/699fb40d-fae3-4a30-b74a-bf2a86ba2aaa">

# Recommendations
Below are some of the recommendations for marketing strategies 
1. To enhance their campaigns and marketing efforts, Sprocket Central Pty Ltd should prioritize targeting customers within the age range of 41-51 years. This age group dominates their customer base, making it a strategic focus for reaching and engaging with potential customers. By tailoring their campaigns to resonate with this demographic, Sprocket Central can effectively capture the attention and interest of their target audience.
2. The analysis highlighted that the Mass customers' wealth segment holds the highest value among customers. Therefore, it is recommended to target this segment for marketing efforts. Additionally, exploring strategies to increase patronage from other wealth segments should be considered to expand the customer base and maximize overall profitability. 
3.	To maximize revenue, the company should primarily target customers from the NSW State, as they contribute nearly 50% of the total revenue. Additionally, efforts should be made to strengthen marketing and promotion towards customers from VIC and QLD States, as they individually generate a significant portion of revenue, almost equal to that of NSW. By focusing on these key regions, the company can effectively allocate resources and potentially increase overall profitability. 
4.	The major contributors to the total revenue were customers from Manufacturing, Financial Services, and Health sectors, followed by customers from Retail, Property, and IT. Therefore, it is advisable to prioritize targeting these customer segments for marketing efforts. By focusing on these sectors, the company can capitalize on their potential and maximize marketing outcomes. 
5.	When considering brands to prioritize for marketing and campaigns, it is recommended to focus on Solex, WeareA2B, and Giant Bicycles. These brands have shown a significant level of success and customer preference, making them the top priority for targeted marketing efforts. By directing resources toward promoting these brands, the company can maximize its marketing impact and potentially attract a larger customer base. 
6.	To maximize revenue, Sprocket Central Pty Ltd should intensify its marketing and campaign efforts during specific months. The analysis revealed that January, May, July, August, and October were the months with the highest recorded revenue. By strategically focusing on these months, the company can capitalize on the existing market trends and customer preferences to drive increased sales and profitability.  


Thank you for reading 🤝
