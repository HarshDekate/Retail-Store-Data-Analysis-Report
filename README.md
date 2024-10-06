# Retail Store Data Analysis Report

## Introduction

This project undertakes a comprehensive data analysis of a sample super store to understand its operational intricacies. By examining key metrics and trends, the study aims to derive actionable insights for business optimization. Using a blend of statistical tools and data visualization techniques, we will evaluate the store's sales, profitability, and customer behavior patterns. The findings from this analysis can offer valuable perspectives for stakeholders, aiding in informed decision-making and strategy formulation for the store's future.

## Data Set Information

- **Row ID**: A unique identifier for each row.
- **Order ID**: The sales order number.
- **Order/Ship Date**: The dates the order was placed and shipped.
- **Ship Mode**: The shipping method.
- **Customer ID/Name**: The buyer's unique ID and name.
- **Segment**: Customer type.
- **City/State/Country/Region/Market**: Location details of the customer.
- **Product ID/Name/Category/Sub-Category**: Information about the purchased product.
- **Sales/Quantity/Discount/Profit/Shipping Cost**: Transactional details including the sales amount, number of items sold, discounts, profit earned, and shipping fees.
- **Order Priority**: The urgency of the order.
- **Column1**: An additional, unspecified column.

## Data Preparation

We have three tables: Orders, Returns, and People, all connected using common keys like Order ID and Customer ID. The data preparation phase involved:

- Cleaning up the data by ensuring all columns were properly labeled and formatted.
- Replacing blank values with 'Not Available'.
- Sorting and filtering the data to focus on relevant parts.
- Adding new columns for calculations, like shipping duration.
- Applying conditional formatting to highlight important trends and outliers, making the data ready for clear and effective analysis.

During this phase, anomalies such as 'Order Date' being later than 'Ship Date' were identified and flagged for correction to ensure data accuracy.

## Quick Insights

Using conditional formatting, filters, custom filters, and sorts, we obtained the following insights:

- Orders with negative profits were highlighted in red.
- Orders with significant discounts (greater than 0.5) were highlighted in yellow.
- Color scales were applied to the Sales column to visualize high and low sales values.
- Top 10 highest and lowest sales and profit values were highlighted.
- Best-selling products and valuable customers were identified.
- Orders with high shipping costs negatively impacting profitability were highlighted in red.
- Products generating negative profits were highlighted in blue.
- Shipping durations exceeding 7 days were highlighted in yellow.
- Australia is the top-performing country with sales of ₹574,597.65.

## Detailed Insights

### Product Categories

- **Technology**: Contributed almost 50% of the business.
- **Shipping Costs vs. Sales**: Orders with shipping costs over 45% of sales were highlighted in red, indicating areas where shipping methods or rates need adjustment.

### Top Contributors

- **Top 5 Countries**: Australia, France, China, India, and Germany made significant contributions to total sales.
- **Product Categories**: Identified which product categories (Technology, Furniture) and subcategories (Phones, Tables, Bookcases) generate the highest sales.

### Order Priorities and Returns

- **Order Priorities**: Critical and High priorities had higher return rates.
- **Regional Sales Performance**: Analyzed sales performance across different regions and markets.

### Discount Impact

- **Discounts**: Analyzed how different discount levels (0.3, 0.5, 0.6, etc.) affect sales and profit.
- **Returned Products**: Identified the impact of returned products on overall sales and which products or categories were returned the most.

### Profitability by Ship Mode

- **Shipping Modes**: Analyzed which shipping modes (Standard Class, First Class, Second Class) were most profitable.

### Sales and Profit by Product

- **Best Performers**: Identified the best-performing products in terms of sales and profitability.
- **Worst Performers**: Identified the worst-performing products in terms of sales and profitability.

### Shipping Duration by Region

- **Shipping Duration**: Analyzed average shipping durations by region to identify areas for improvement.

## Action Steps

- **Diversification**: Look for diversification opportunities to minimize the impact of a recession on the business.
- **Cost Analysis**: Analyze the costs of products with high sales but no profit to find ways to cut expenses without reducing quality.
- **Pricing Strategy**: Adjust prices or create bundles for consistently unprofitable products to increase their profit margins.
- **Product Review**: Review products with very low sales that lose money and consider discontinuing them.
- **Marketing Focus**: Focus marketing efforts on products with good sales and profit to boost their visibility and grow sales.
- **Inventory Management**: Manage inventory by adjusting stock based on past sales and better forecasting demand.
- **Supplier Negotiation**: Negotiate better deals with suppliers or find cheaper alternatives for products that are losing money.
- **Upselling and Cross-selling**: Improve upselling and cross-selling for low-margin products by offering premium services or related products.
- **Product Audits**: Regularly audit all product lines to spot trends and quickly fix underperforming items.
- **Dynamic Pricing**: Use dynamic pricing to maximize profit on high-volume orders while staying competitive.
- **Discount and Promotion Review**: Reevaluate discount and promotion strategies, especially where aggressive pricing is hurting profit.
- **Market Expansion**: Expand and market products in the Technology and Furniture categories, as they perform well across different regions.
- **Logistics Improvement**: Invest in logistics improvements in successful regions like Asia Pacific and Europe to reduce costs and speed up delivery.
- **Regional Strategies**: Create regional strategies, especially in growing markets like Latin America and Africa, to attract new customers.
- **Customer Preferences**: Use data analytics to understand customer preferences in different regions and tailor products and marketing.

## Shipping Improvements

- **Feedback System**: Set up a feedback system for high-priority orders to measure satisfaction and find areas for improvement.
- **Shipping Issues**: Investigate unusual shipping problems in Canada, Central Asia, and South America to fix data or logistical issues.
- **Shipping Times**: Focus on improving shipping times in slow regions like Central US, Oceania, and Western Asia.
- **Shipping Practices**: Study shipping practices in Southern and Northern Europe and apply their successful methods in other regions.
- **Logistics Improvement**: Improve logistics in North America to balance shipping times between Eastern US, Western US, and Canada.
- **Africa Logistics**: Upgrade shipping infrastructure in Africa to reduce delivery time differences between regions.
- **Asia Logistics**: Simplify shipping processes in Asia, particularly in Western and Central Asia, by adopting successful practices from Southeastern Asia.
- **European Shipping**: Fix inconsistencies in European shipping by standardizing practices across the continent.
- **Caribbean and Central America**: Develop strategies to reduce shipping times in the Caribbean and Central America.
- **Global Shipping**: Review global shipping partnerships and routes to reduce the average shipping duration.
- **Local Warehouses**: Invest in local warehouses or partners in regions with slow shipping to speed up deliveries and cut costs.
- **Advanced Tracking**: Use advanced tracking systems to monitor shipments in real-time and prevent delays.
- **Shipping Data Analysis**: Regularly analyze shipping data to spot trends and adjust resources and strategies as needed.
- **New Transportation Methods**: Explore new transportation methods or routes in regions with difficult geography or infrastructure.
- **Shipping Goals**: Set specific shipping goals for each region and measure performance to continuously improve.
- **Continuous Improvement**: Encourage a mindset of continuous improvement and innovation in all areas of the business, from products to logistics.

