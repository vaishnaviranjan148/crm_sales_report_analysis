# CRM Sales Report Analysis
## Project Summary
This project focuses on analyzing CRM sales pipeline data for a B2B company that sells computer hardware. The goal of the project is to understand overall sales performance, identify top and low performing sales agents, analyze quarter-over-quarter trends, and evaluate product performance using data visualization.

The project uses sales opportunity data to track revenue, deal outcomes (won vs lost), win rates, and the average time taken to close deals. Two interactive Power BI dashboards were created: one for Sales Performance and another for Team & Product Performance. These dashboards help compare performance across quarters, regions, managers, sales agents, and products.

Through this project, key insights were derived related to seasonal sales trends, conversion efficiency, sales agent contribution, and product effectiveness. The project demonstrates the practical use of Excel and Power BI for cleaning data, creating KPIs, and building business-friendly dashboards to support data-driven decision making.

[Click here to view Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTVmMWY3YmUtOWJiZS00ZWZjLThiYTYtN2QzNDJjNjQ1YjRmIiwidCI6IjNmZmZmN2I2LTdlZjQtNGZhNC04ZmVhLTc5OGFiMDQ1NTcxNCJ9)

## Table of content
1. [About the company](#about-the-company)
2. [Client Requirements & Objective](#client-requirements--objective)
3. [Primary Goals of the Analysis](#primary-goals-of-the-analysis)
4. [Datasets used for this Project](#datasets-used-for-this-project)
5. [Tools and Techniques Used](#tools-and-techniques-used)
6. [Sales Performance](#sales-performance)
7. [Team Performance](#team--product-performance)

## About the company
B2B sales pipeline data from a Maven company that sells computer hardware, including information on accounts, products, sales teams, and sales opportunities. 

## Client Requirements & Objective
The Chief of Maven company, has tasked the Data analytics team with conducting a detailed sales pipeline. The lead data analyst, is responsible for analyzing key metrics, answering critical business questions and providing strategic recommendations. 

## Primary Goals of the Analysis
-	Sales performance: Analyze sales agent performance compared to the rest and any sales agent lagging behind.
-	Team & product performance: Analyze quarter-over-quarter trends and any products have better win rates.

[Home](#table-of-content)

## Datasets used for this Project:
This project is based on sales pipeline data collected from 2016 to 2017. The dataset consists of three separate spreadsheets:
1.	Products: 
-	This sheet contains products details. It includes details such as product name, product series and product price. 
2.	Sales pipeline: 
-	This sheet contains opportunities data by sales agent and their manager. It includes opportunities, sales agent names, manager names, regional office, product names, account details, deal stage (won, lost, engaging, prospecting), engage date (when deal started), close date (when deal closed), close value (price sold).
3.	Sales teams: 
-	This sheet captures sales agents details their name, their manager, regional office (which region there are working).
The dataset helps analyze key trends in Sales pipeline, region wise, and sales agent performance, forming the foundation for insights.

[Home](#table-of-content)


## Tools and Techniques Used:
### Tools: 
1.	Microsoft Excel: 
-	Used for initial data checking, formatting, and value matching.
-	Performed data cleaning and basic analysis before importing into Power BI.
2.	Power BI:
-	Used to create a well- structed, interactive, and visually appealing report.
-	Enabled real- time insights with dynamic filtering, trend analysis, and KPI tracking.
### Techniques:
1.	Data Preparation: Cleaning, transforming, and structuring raw data for better analysis.
2.	DAX writing: Creating calculated measures and columns for deeper insights.
3.	Data Modeling: Establishing relationships between datasets to enhance report functionality.
4.	Dynamic visuals: Designing interactive charts and graphs for better data storytelling. 
5.	Bookmarks & Navigation: Improving user experience with seamless report navigation.

[Home](#table-of-content)

## Sales Performance:
The Sales Performance dashboard provides an overall view of how the business is performing over time. It focuses on key sales metrics such as total revenue, number of deals closed, win rate, and average time taken to close deals. The dashboard helps track quarter-over-quarter trends and highlights changes in sales activity, efficiency, and conversion rates. It allows stakeholders to quickly understand whether sales performance is improving or declining across different quarters.

![Sales Performance](screenshots/01_Sales_Performance.png)

[Home](#table-of-content)


## Key insights:
### 1.	Sales Performance varies significantly across quarters:
The analysis shows that Q2 and Q3 recorded the highest revenue and deal closure activity, while Q1 consistently underperformed. This indicated possible seasonality or a weaker sales pipeline at the beginning of the year.
### 2.	Deal closure volume increased after Q1:
The number of deals closed rose sharply from Q1 to Q2 and remained relatively stable Q3 and Q4. This suggests improved sales engagement and better pipeline movement after the first quarter.
### 3.	Win rate declines slightly over time:
Although deal volume increased, the win rate showed a gradual decline from Q1 to Q4. This indicates the while more deals are being pursed, a slightly lower percentage is being successfully closed.
### 4.	Average time to close deals improved across quarters:
The average number of days required to close a deal decreased from Q1 to later quarters. This suggests better sales efficiency, improved follow-ups, or stronger qualification of opportunities.
### 5.	Deal loss remain significant in high-activity quarters:
Even during strong quarter like Q2 and Q3, deal losses are still noticeable. This highlights the need to improve conversion strategies and focus on deal quality, not just deal quantity.
## Conclusion:
Overall, sales performance shows positive momentum after Q1, with higher revenue and deal activity in later quarters. However, the declining win rate indicates that the sales team focus on improving conversion efficiency while maintaining deal volume. Faster deal closures are a positive sign of operational improvement.

[Home](#table-of-content)


## Team & Product Performance:
The Team & Product Performance dashboard focuses on identifying who is driving sales results and which products perform better. It compares sales performance across managers, regions, and sales agents, helping to identify top performers as well as underperforming areas. The dashboard also analyses product-level revenue and win rates to understand product effectiveness. This view supports data-driven decisions related to team performance improvement and product sales strategy.

![Team Performance](screenshots/02_Team_Performance.png)

[Home](#table-of-content)


## Key insights:
### 1.	Sales performance is uneven across managers and regions.
Some managers consistently generate higher revenue compared to others, indicating differences in team effectiveness or regional market strength. Certain regions contribute more strongly to overall revenue.
### 2.	A small group of sales agents drives most of the results.
The analysis shows that top-performing sales agents contribute a large share of total deals and revenue, while several agents lag behind. This highlights a performance gap within the sales team.
### 3.	High deal count does not always mean higher revenue.
Some sales agents close more deals but generate lower revenue, while others close fewer deals with higher deal values. This suggests differences in deal size and product mix across agents.
### 4.	Product performance varies clearly across the portfolio.
A few products generate the majority of revenue, while others contribute relatively little. This indicates that certain products have stronger market demand or better pricing power.
### 5.	Products with higher revenue do not always have the best win rate.
Some products show strong revenue performance but average win rates, while others have higher win rates but lower revenue. This suggests opportunities to optimize pricing, positioning, or sales focus for specific products.

## Conclusion:
The team and product analysis highlights clear performance differences across managers, sales agents, and products. While a few individuals and products drive most of the success, there is an opportunity to uplift overall performance by addressing underperforming agents and optimizing product sales strategies. Focusing on training, balanced product promotion, and targeted regional strategies could improve results.
[Home](#table-of-content)








