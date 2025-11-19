# Retail-Sales-Analysis
## Executive Summary
According to my analysis on retail sales dataset, the company successfully drive sales through targeted demographics and seasonal peaks, but our high costs and excessive discounting have resulted in low profitability. Key customer segments show distinct preferences: 25-34-year-olds for Clothing, 35-64-year-olds for Electronics, and 18-24-year-olds for Beauty. Revenue fluctuates by product categories: Electronics drive high revenue at mid-tier prices, Clothing generates high volume through lower prices, and Beauty commands a premium price with lower sales volume. Promotions in May and October drive revenue with higher average prices, but broad discounts, like those in September, erode margins. The core issue is that a revenue of $456K yields only a 25% profit margin ($115K). To maintain sustainable growth, we must shift from a discount-driven volume strategy to a margin-focused approach centered on cost reduction and strategic pricing.
## Problem Statment
We want to discover which customer, product, and seasonal factors most strongly influence purchasing behavior and profitability in order to guide better marketing, pricing, and operational decisions. 

**Breaking down the problem into smaller sections:**
 -How do customer demographics (age and gender) influence purchasing behavior?
 -Are there discernible patterns in sales across different time periods (month, day of week)?
 -Which product categories hold the highest appeal among customers?
 -What are the relationships between age, spending, and product preferences?
 -How do seasonal trends and promotions affect customer purchasing behavior?
 -What can be inferred from the distribution of product prices vs. units sold?
 -Is there a balance between cost and profit?


## Dashboard
This dashboard enables users to filter by Time, Product Category, Age Group and Gender. You can click <a href="https://github.com/vnhsinpar/Retail-Sales-Analysis/blob/main/Retail_Sales_Dashboard.pbix"> here </a> for the interactive Power BI dashboard. 


<img width="1562" height="838" alt="Retail_Sales_Dashboard_Image" src="https://github.com/user-attachments/assets/a1594b7d-77cb-4329-9267-45ec1f9461b6" />


## Insight Deep Dive
To investigate the retail sales performance, we focus on these dimensions and matric: Age group, Gender, Product Category, Time, Revenue and Profit, and profit margin.

#### Gender Behavior
* Females slightly outperform males in total revenue with 51%. Product trends show males lead in Electronics (80.2K vs 76.7K) while females prefer Clothing (81.3K vs 74.3K).

#### Time Patterns
* Sales spike in May (53K) and October (47K), lowest in September (24K) and January (0.15K for 2024) likely incomplete data.
* On October, beauty make the most revenue, and Electronic in May which align with promotion, festivals, or seasonal demand. In these peak months, the products with the highest revenue show a higher average price per unit compare to their annual average.  At the same time, other products also show reduced price in these two months. 
* The dip in September is caused by heavy discounting as the average product price for all categories dropped below the annual average.   

#### Product Category
* Across 3 different product categories, Electronics generated the highest revenue (157K, 34.41%), followed by Clothing (156K, 34.12%), and Beauty (144K, 31.47%).

#### Age
* Revenue contribution is relatively strong across 25–54 years, showing this group is the most active in shopping.

#### Age & Product Relationship
* 25–34 age group spends the most on Clothing (42K), 35–44 and 55–64 show higher spending on Electronics (36–38K) and 18–24 prefers Beauty (29K), though total spend is lower.

#### Price Distribution
* Beauty has (184) Average price per unit but fewer units sold.
* Electronics are mid-priced (181) with moderate units, making them steady performer. 
* Clothing is lower-priced (174) but sells in highest volumes.

#### Profitability 
* Despite generating 456K in revenue, profit if limited to 115K 25% margin) due to high cost per unit across the product categories. This indicates the need of structural sourcing, pricing strategy rather than promotional discounting. A strategy that prioritizes margins and cost optimization is necessary.

## Business Recommendations
#### Marketing Team
* Target females aged 25–54 with premium clothing line, as this group drives consistent revenue.
* Launch youth-oriented promotions (18–24) for Beauty products to grow early loyalty.
* Use value added promotions such as free gift with purchase, bundles in peak seasons instead of discounts to maintain or increase margin during high demand period.

#### Finance Team
* Launch a deep-dive analysis into the Cost of Goods Sold (COGS) for each product category to identify the primary drivers of high unit costs.
* Shift key performance indicators from revenue to profit margin to incentivize profitable growth.
* Try working with Product and Marketing to model the profit impact of a 1-5% price increase for Clothing (high volume) and Electronics (mid-price). Our data suggests customer demand may be more price-inelastic than assumed.

#### Product Team
* Introduce a premium SKU in Clothing and Electronics to capture higher willingness-to-pay, especially from our core age demographics (25-44). 
* Bundle Beauty products with Clothing to cross-sell effectively.
* Optimize sourcing, logistics to improve profitability. 

## Dataset Stats
The dataset is retrieved from publicly available kaggle platform. Click <a href="https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset/data"> retail-sales-dataset  </a>
* Obtain from Kaggle, contained 1000 records.
* Data ranges from January 2023 to January 2024.
* The dataset has fields such as: Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Total Revenue.
* To simulate a more realistic business dataset for analytics, I extend Cost Per Unit matric with with the help of modern tech.

## Methodolody
* Sanity checks the data with excel
* Dax, writing function, calculated columns, data visualization in power BI
* I use both descriptive analysis (what happened) and diagnostic insights (why it happened).

## Assumptions and Caveats
* January 2024 data is incomplete; insights for that month will not reflect true performance.
* Dataset reflects historical retail transactions but may not account for external factors (inflation, macroeconomic shifts, or competitor promotions).





