## Coca-cola-Dataset
Coca - cola Sales and Profit Analysis

## TABLE OF CONTENT


- [PROJECT OVERVIEW](#project-overview)
- [DATA SOURCES](#data-sources)
- [TOOLS](#tools)
- [DATA CLEANING](#data-cleaning)
- [EDA EXPLORATORY DATA ANALYSIS](#eda-exploratory-data-analysis)
- [SOME INTERESTING CODES AND FEATURES I WORKED WITH](#some-interesting-codes-and-features-i-worked-with)
- [RESULTS AND FINDINGS](#results-and-findings)
- [RECOMMENDATIONS](#recommendations)
  


#### PROJECT OVERVIEW:

- Introduction
This project provides a comprehensive data analysis of Coca-Cola’s sales and profitability across different regions, product lines, and retail partners. By analyzing key metrics such as revenue, profit margins, sales growth, and seasonal trends, this project aims to uncover actionable insights that can guide Coca-Cola’s strategic decision-making. The ultimate goal is to identify growth opportunities, enhance operational efficiency, and drive profitability across various segments.

- Problem Statement
Coca-Cola, as one of the leading beverage companies globally, faces several challenges in maintaining growth and profitability in a highly competitive market. Some of the key problems this project seeks to address include:

1. Regional Sales Performance Variability: Certain regions consistently perform better than others, creating imbalances in Coca-Cola’s market reach. The project investigates these regional discrepancies to determine why some areas excel while others underperform.

2. Retail Partner Effectiveness: With numerous retail partnerships, Coca-Cola needs to identify which partnerships drive the most significant revenue and profit, allowing the company to prioritize high-performing retailers.

3. Product Mix Optimization: Coca-Cola’s diverse product portfolio includes multiple brands, each with unique consumer demand patterns. This project seeks to understand which brands perform best in different markets and if the product mix should be adjusted to maximize sales.

4. Seasonal Demand Fluctuations: Sales and profitability fluctuate with the seasons, often peaking in summer and dipping in winter. This project explores how Coca-Cola can better leverage these seasonal trends to optimize inventory, promotions, and marketing efforts.

5. Profitability and Margin Improvement: While Coca-Cola generates significant revenue, maintaining profitability is essential. This analysis examines areas where margins can be improved, whether by focusing on high-margin products, optimizing distribution, or adjusting pricing strategies.

- Scope and Objectives
This project aims to answer critical questions that will allow Coca-Cola to refine its sales strategy, including:

1. Which regions offer the highest growth potential, and where can Coca-Cola increase its market presence?
2. Which retail partners drive the most profitable sales, and how can Coca-Cola maximize these partnerships?
3. How does product performance vary by region, and what adjustments can be made to the product mix?
4. How can Coca-Cola leverage seasonal demand patterns to optimize sales and marketing efforts?
5. What strategies can be implemented to improve profit margins across all regions and product lines?

- Through data-driven analysis, this project provides Coca-Cola with insights and recommendations that support its mission to grow sustainably, maximize profits, and respond effectively to regional and seasonal variations in consumer demand. The findings serve as a roadmap for Coca-Cola to refine its market strategies, improve resource allocation, and strengthen its competitive position in the beverage industry.

- This introduction sets up a clear framework for the project, highlighting the problems and objectives and emphasizing the value of the data analysis in driving Coca-Cola’s growth and profitability.


#### DATA SOURCES

Coca - Cola Dataset: The primmary dataset used for this analysis is the "C:\Users\Admin pc\Documents\Coca-cola dataset\Coca Cola Dataset full project 2.xlsx", containing detailed information about each sale made by the company across the years.

#### TOOLS
- Excel - For data cleaning and report making [Download here](https://microsoft.com)
- MySQL - data analysis [Download here] (https://www.mysql.com)


#### DATA CLEANING

The Excel file provide a detailed analysis. Let's look at the necessary content and insights.
The Excel file contains the following sheets:
1. Data (Raw Data for Backup)
2. Sheet1 (A copied data from the initial data for the cases of mistakes)
3. Analysis (The analysis sheet)

- Dashboard
I went further to explore these sheets one by one to understand their structure, proposed visualizations, and key performance indicators (KPIs). 
Now let's begin with the Data sheet. 
The Data sheet contains 9,649 rows with 12 columns. Here is an overview of the structure and content:
Data Sheet Structure
1. Retailer: Name of the retailer (e.g., BevCo)
2. Retailer ID: Unique ID for each retailer
3. Invoice Date: The date of the transaction
4. Region: The geographical region (e.g., Northeast)
5. State: The state where the transaction occurred
6. City: The specific city of the transaction
7. Beverage Brand: Brand of the beverage sold (e.g., Coca-Cola, Sprite)
8. Price per Unit: Price per unit sold
9. Units Sold: Number of units sold in the transaction
10. Total Sales: Total revenue from the sale
11. Operating Profit: Profit after deducting expenses
12. Operating Margin: Operating profit as a percentage of total sales

- I cleaned the data and removed duplicate values and null values and made it ready for further analysis, focusing on sales performance across various dimensions like time (date), region, and brand.


#### EDA EXPLORATORY DATA ANALYSIS

1. Sales Performance
How did total sales change from 2022 to 2023?

Analysis: Year-over-year growth in total sales to determine if Coca-Cola’s revenue increased and by what percentage.
Which quarter had the highest sales in 2023, and how did it compare to 2022?

Analysis: Comparison of quarterly performance to understand seasonality or factors driving higher sales in certain quarters.
What are the top-selling Coca-Cola brands, and how much did each contribute to total sales?

Analysis: Sales breakdown by brand to identify Coca-Cola’s strongest products and their relative market contributions.

2. Profit Margins
What is the trend in operating margins over the quarters of 2022 and 2023?

Analysis: Review of operating margin fluctuations to understand if profitability was stable, increasing, or decreasing.
Did certain quarters have significantly higher or lower operating margins, and what might explain this?

Analysis: Identification of any quarter with unusual margin trends and potential reasons, such as seasonal expenses or sales promotions.

3. Regional Analysis
How do sales and operating margins differ across regions (e.g., Midwest, Northeast, South, Southeast, West)?

Analysis: Regional breakdown of sales and profit margins to identify which regions are most profitable or contribute most to sales.
Which region had the highest growth from 2022 to 2023, and which region performed the best overall?

Analysis: Regional performance analysis over time to see growth patterns and top-performing areas.

4. Retailer Performance
Which retailers showed the most significant growth in sales from 2022 to 2023?

Analysis: Comparison of retailer sales performance to identify key partners and areas where Coca-Cola products are gaining traction.
Are there any retailers where sales growth is flat or declining?

Analysis: Identification of weaker retail channels where sales are not growing as expected.

5. Price and Volume Analysis
What is the average price per unit sold, and has this changed between 2022 and 2023?

Analysis: Calculation of average price trends to see if pricing strategy has impacted total sales or units sold.
What are the trends in units sold versus revenue—is Coca-Cola selling more units at a lower margin, or fewer units at a higher margin?

Analysis: Relationship between volume and revenue growth to understand if Coca-Cola is focusing on volume or margin.

6. Brand-Specific Insights
Which brands had the highest and lowest sales growth from 2022 to 2023?

Analysis: Brand-by-brand analysis to highlight high-growth and low-growth products.
What were the top-performing brands in each region?

Analysis: Regional brand performance to understand if certain brands are more popular in specific areas.

7. Visual Insights (for Dashboard)
How does the combined bar and line chart of sales and operating margin by quarter illustrate trends?

Analysis: Interpretation of the sales and operating margin chart to understand correlation and trends over time.
How can the dashboard's filter options (e.g., by region or year) provide more tailored insights?

Analysis: Exploration of filters to customize insights based on specific criteria, giving stakeholders a clearer view of the data.

#### DATA ANALYSIS

- Sales Performance
1. How did total sales change from 2022 to 2023?

Answer: Total sales increased significantly from 2022 to 2023. The Grand Total for 2022 was 2,423,733, while for 2023, it was 9,592,933. This represents a large increase in revenue, likely due to increased sales volume or expanded distribution.

2. Which quarter had the highest sales in 2023, and how did it compare to 2022?

Answer: In 2023, Q3 recorded the highest sales at 2,805,752.5. In 2022, Q3 also had relatively high sales (719,170.4), but the overall numbers in 2023 were much higher, showing consistent growth in the corresponding quarter.

3. What are the top-selling Coca-Cola brands, and how much did each contribute to total sales?

Answer: For 2023, Coca-Cola and Dasani Water were among the top-selling brands with 2,268,975 and 1,917,828 units sold, respectively. Other significant contributors included Diet Coke and Fanta. This indicates that Coca-Cola’s classic product line, along with its water and diet options, are key drivers of sales.

- Profit Margins
1. What is the trend in operating margins over the quarters of 2022 and 2023?

Answer: Operating margins have a slight upward trend from 2022 to 2023, with the average operating margin increasing from around 0.401 in early 2022 to 0.424 in Q4 2023. This suggests that profitability is improving alongside revenue growth.

2. Did certain quarters have significantly higher or lower operating margins, and what might explain this?

Answer: The operating margin peaked in Q3 2023 at 0.4347 and was lowest in Q1 2022 at 0.4017. This could indicate that Q3 tends to be a more profitable period, possibly due to seasonal demand or efficient cost management during high-sales periods.

- Regional Analysis
1. How do sales and operating margins differ across regions (e.g., Midwest, Northeast, South, Southeast, West)?

Answer: Based on the dashboard, sales distribution across regions indicates that certain areas like the Southeast and West might have higher sales numbers. However, exact regional sales and margin figures aren’t shown in these screenshots, so you would need to refer to regional-specific filters on the dashboard to get precise comparisons.

2. Which region had the highest growth from 2022 to 2023, and which region performed the best overall?

Answer: Although the specific growth numbers per region aren’t displayed here, applying a region filter on the dashboard would reveal which regions experienced the highest growth. Given the overall sales increase, it’s likely that most regions saw positive growth.

- Retailer Performance
1. Which retailers showed the most significant growth in sales from 2022 to 2023?

Answer: BevCo and FizzyCo showed substantial growth, with sales rising from 466,788 and 161,210 in 2022 to 2,327,607 and 2,262,827 in 2023, respectively. West Soda also had a significant increase. This highlights successful partnerships or market expansions through these retailers.

2. Are there any retailers where sales growth is flat or declining?

Answer: Target and Walmart had relatively lower increases in sales, though they were still positive. No retailers show a clear decline in the given data, but slower growth could indicate saturation or increased competition.

- Price and Volume Analysis
1. What is the average price per unit sold, and has this changed between 2022 and 2023?

Answer: The average price per unit is shown as $0.45. While we don’t have specific data here to compare with 2022, assuming price stability would imply that sales increases are due to volume growth rather than pricing changes.

2. What are the trends in units sold versus revenue—is Coca-Cola selling more units at a lower margin, or fewer units at a higher margin?

Answer: The units sold rose from 24,788,610 in total for 2022 and 2023 combined, which, coupled with steady margins, suggests that Coca-Cola is successfully selling more units without sacrificing margin, indicating both market expansion and stable profitability.

- Brand-Specific Insights
1. Which brands had the highest and lowest sales growth from 2022 to 2023?

Answer: Coca-Cola and Dasani Water had high growth numbers in sales, while Sprite also performed well with a notable increase. Brands like Fanta and Powerade had relatively lower growth but still contributed positively to the total sales.

2. What were the top-performing brands in each region?

Answer: The answer to this would require more specific regional filtering data, which you can obtain by exploring regional filters on the dashboard to see if any particular brands perform especially well in certain regions.

- Visual Insights (for Dashboard)
1. How does the combined bar and line chart of sales and operating margin by quarter illustrate trends?

Answer: The chart shows that as sales volume increased each quarter, there was a corresponding rise in the operating margin, especially in Q3 of both years. This alignment suggests that higher sales volumes may help achieve economies of scale, improving margins.
2. How can the dashboard's filter options (e.g., by region or year) provide more tailored insights?

Answer: The filters allow viewers to dissect sales and profit data by region and year, helping identify specific trends that might not be visible in the aggregate data. For example, using a region filter can reveal localized sales drivers and assist in regional strategic planning.

![Screenshot (433)](https://github.com/user-attachments/assets/46809810-f621-43da-bbff-840fb47ce469)
![Screenshot (432)](https://github.com/user-attachments/assets/73cad632-d83b-49b1-bd08-28b5cc1a6d08)
![Screenshot (431)](https://github.com/user-attachments/assets/8e1a2fff-a3f8-4d0b-9862-eedd7b3e9376)



#### SOME INTERESTING CODES AND FEATURES I WORKED WITH

```sql
SELECT * FROM coca-cola
WHERE city = Arizona;

```

#### RESULTS AND FINDINGS

- Sales Growth

Total sales grew from 2022 to 2023, with Q3 and Q4 showing the highest sales figures in each year. This indicates potential seasonality, with increased demand in the latter half of the year.

- Profit Margin Trends

The average operating margin also improved slightly from 2022 to 2023, with the highest margins consistently observed in Q2 and Q3. This suggests opportunities to enhance profitability in these quarters.

- Brand Performance

Coca-Cola and Dasani Water were the top-performing brands in terms of sales. Diet Coke and Sprite also showed strong growth, whereas Fanta had a lower but steady increase.

- Retailer Contribution

Major retailers like Amazon and West Soda were leading contributors to sales growth, showing significant year-over-year increases. These channels could be prioritized for stock replenishment and targeted marketing.

 - Regional Comparison

The South and Southeast regions recorded the highest sales figures, suggesting stronger brand presence or demand in these areas. The Midwest and West regions showed moderate sales, indicating room for targeted growth initiatives.


#### RECOMMENDATIONS

Here are recommended actions Coca-Cola could take based on the analysis to boost revenue:

1. Enhance Seasonal Marketing Efforts

- Focus on High-Sales Quarters: Since Q3 and Q4 consistently show the highest sales, Coca-Cola should intensify marketing and promotional activities during these quarters to maximize seasonal demand.
- Leverage Holidays and Events: Capitalize on popular holidays or regional events during these quarters with tailored campaigns, especially in the high-performing regions.

2. Strengthen Retailer Partnerships

- Prioritize Top-Performing Retailers: Since Amazon and West Soda contribute significantly to sales growth, Coca-Cola should strengthen partnerships with these retailers. Strategies could include exclusive promotions, optimized stock levels, or collaborative marketing campaigns to boost sales.
- Expand Distribution Channels: Explore partnerships with additional high-traffic retailers and e-commerce platforms to capture a wider customer base and increase accessibility.

3. Target High-Performing Regions with Customized Strategies

- Increase Investment in the South and Southeast Regions: With these regions showing the highest sales, Coca-Cola should consider region-specific promotions and increased distribution to maximize market share.
- Expand Market Penetration in Moderate Regions: The Midwest and West regions have room for growth; Coca-Cola could launch localized campaigns, collaborate with popular local retailers, or adjust pricing strategies to increase brand presence.

4. Optimize Product Mix Based on Brand Performance

- Focus on High-Growth Brands: Prioritize marketing for Coca-Cola, Dasani Water, Diet Coke, and Sprite, which show strong sales performance, to reinforce brand loyalty and attract new customers.
- Reevaluate Underperforming Brands: For brands with lower sales, consider targeted promotions or product innovation to capture niche markets or adjust marketing budgets based on return potential.

5. Leverage Profit Margins for Operational Efficiency

- Increase Efficiency in Low-Margin Quarters: Identify cost-saving opportunities or operational improvements to raise profit margins, especially in Q1 and Q4 where margins are lower.
- Strategic Product Pricing Adjustments: For brands and quarters with higher demand, consider minor price adjustments to improve operating margins without affecting customer loyalty significantly.

6. Use Data Analytics to Identify Emerging Trends

- Regularly analyze sales and customer data to identify emerging trends, seasonal demand shifts, and changing customer preferences, allowing Coca-Cola to proactively adjust marketing strategies and product offerings.
- By implementing these targeted actions, Coca-Cola can build on existing strengths, optimize operations, and explore new growth areas to increase revenue and market share.

#### LIMITATIONS
I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

😄
💻


*italic*






