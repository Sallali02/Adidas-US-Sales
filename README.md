# Adidas US Sales Analysis 📈
Analyzed Adidas US sales data to uncover trends, optimize marketing strategies, and identify underperforming products. Utilized Excel for dynamic pivot tables and charts, enabling clear insights into regional and retailer performance, as well as future sales forecasting. 

# About the Dataset
The Adidas US Sales dataset is a detailed collection of sales transaction data from 2020 to 2021, offering a deep dive into the performance of Adidas products across the United States. This dataset includes key metrics such as total sales revenue, units sold, operating profit, and operating margins. Additionally, it provides granular details on retailer performance, product categories, and sales methods, allowing for a thorough analysis of the factors influencing sales.

The data captures information on various regions, states, and cities, enabling the examination of regional sales trends and the effectiveness of different pricing strategies. With insights into product-specific sales, retailer contributions, and regional preferences, this dataset is a valuable resource for exploratory data analysis, predictive modeling, and strategy development.

This dataset can be used to uncover patterns in consumer behavior, identify high-performing products and regions, and evaluate the success of sales methods and marketing campaigns. Whether you're looking to refine business strategies, enhance forecasting accuracy, or develop new marketing initiatives, this dataset offers a robust foundation for data-driven decision-making.

# Dataset Description
**Retailer:** Represents the business or individual that sells Adidas products directly to consumers.

**Retailer ID:** A unique identifier assigned to each retailer in the dataset.

**Invoice Date:** The date when a particular invoice or sales transaction took place.

**Region:** Refers to a specific geographical area or district where the sales activity or retail operations occur.

**State:** Represents a specific administrative division or territory within a country.

**City:** Refers to an urban area or municipality where the sales activity or retail operations are conducted.

**Product:** Represents the classification or grouping of Adidas products.

**Price per Unit:** The cost or price associated with a single unit of a product.

**Units Sold:** The quantity or number of units of a particular product sold during a specific sales transaction.

**Total Sales:** The overall revenue generated from the sales transactions.

**Operating Profit:** The profit earned by the retailer from its normal business operations.

**Sales Method:** The approach or channel used by the retailer to sell its products or services.

# ❓ Some Questions For Analysis

### 💸Sales Performance Analysis
   
**Q:** Which regions and states have the highest and lowest sales? <br />
**A:** The West region has the highest total sales, substantially ahead of other regions, while the Midwest has the lowest sales. This disparity suggests regional differences in consumer behavior or market saturation that may warrant targeted strategies for each region.

**Q:** What are the top-performing cities in terms of total sales?<br />
**A:** Charleston and New York lead in total sales, with Charleston slightly outperforming New York. These two cities, along with San Francisco, account for a significant portion of the total sales, indicating strong market presence and demand in these urban areas.

**Q:** What is the seasonality of sales? Do certain months or seasons show a spike in sales based on the invoice date? <br />
**A:** The line graph shows distinct seasonal patterns in sales. In both 2020 and 2021, there are significant spikes in sales around April and December. These peaks suggest that certain months, likely driven by events or seasonal promotions, experience higher sales volumes.  Comparing the two years, sales in 2021 generally surpass those in 2020. The beginning of 2021 starts strong, with a peak in April, followed by a slight dip over the summer months. The end of the year, particularly November and December, shows a resurgence in sales, indicating a growth trend or increased demand over time.  The observed seasonality suggests that sales are highest during the spring and winter months, likely due to seasonal factors like holidays or product launches. Understanding these patterns can help in better planning for inventory, marketing strategies, and resource allocation during these key periods. 

**Q:** Which products have the highest sales volumes or revenue?<br />
**A:** Men's Street Footwear is the top-selling product category, generating the highest total sales, followed by Women's Apparel. Both categories significantly outperform others, indicating strong consumer preference for these types of products, while Women's Athletic Footwear ranks lowest in total sales among the listed categories.

**Q:** What is the year-over-year growth of total sales?<br />
**A:** The data shows substantial year-on-year growth across all product categories, with Men's Street Footwear experiencing the highest growth at 352.11%. Women's Apparel also saw significant growth at 308.77%, indicating a strong upward trend in sales for these products from 2020 to 2021. Overall, all categories demonstrated robust growth, reflecting a positive market trend.

### 🏷️Product and Price Insights
   
**Q:** How do units sold and total sales vary by product? What is the average price per unit for the top-selling products?<br />
**A:** Highest Average Sales Per Unit: Women's Apparel has the highest average sales per unit at $412.70.
Lowest Average Sales Per Unit: Women's Street Footwear has the lowest average sales per unit at $326.31.
Highest Total Sales: Men's Street Footwear leads with the highest total sales at $208,826,244.
Lowest Total Sales: Women's Athletic Footwear has the lowest total sales at $106,631,896.

**Q:** Are there any relationships between price and units sold? Do lower-priced products sell more units, or is the opposite true for premium products?<br />
**A:** There doesn't seem to be a clear, consistent pattern between the price and the number of units sold in this dataset. For instance, Women's Street Footwear and Women's Athletic Footwear are lower-priced but have similar or higher sales figures compared to some higher-priced products. Conversely, Men's Apparel is higher-priced but has comparable sales figures to some lower-priced items. The data shows that both lower-priced and higher-priced products have similar sales figures. This suggests that while price might influence sales, other factors like product type, brand, or market demand could also play significant roles. 

### 💰Profitability and Margins
   
**Q:** Which products or regions have the highest operating profit and operating margins? Are certain regions or products less profitable?<br />
**A:** The West region leads in profitability with an operating profit of $89,609,407, driven by strong performances across several categories, especially Men's Street Footwear, which also tops product profits at $82,802,261. The Northeast region further boosts this product's success with a profit of $21,356,317. However, the Midwest and Southeast regions need improvement, particularly in Women's Athletic and Street Footwear, where profits are notably lower. Targeted strategies in these areas could help enhance overall performance.

**Q:** Which sales methods contribute the most to profitability?<br />
**A:** Based on the pivot table, online sales contribute the most to profitability, with a total sum of $224,421 across all product categories. This is followed by outlet sales, which generate $126,889, and in-store sales at $84,940. Notably, Women's Apparel leads in online sales, contributing $42,842, while Men's Apparel also performs strongly online with $41,805. The data suggests that focusing on enhancing online sales strategies could further boost overall profitability.

### 📊Retailer and Sales Method Performance
   
**Q:** Which retailers consistently generate the most sales and profits?<br />
**A:** West Gear consistently generates the most sales and profits, leading all retailers with total sales of $242,964,333 and an operating profit of $85,667,873.18. Foot Locker follows as a strong performer, with total sales of $220,094,720 and an operating profit of $80,721,124.81. Amazon also contributes significantly, with an operating profit of $28,818,503.31, though its total sales are lower compared to other top retailers. This data highlights West Gear as the top player in driving overall sales and profitability.

### 👤Customer Behavior
    
**Q:** Do certain regions prefer specific products?<br />
**A:** certain regions do have preferences for specific products. The West region leads in sales across multiple categories, particularly excelling in Men's Street Footwear with 150,795 units sold and Men's Athletic Footwear with 127,724 units sold. The Northeast also shows a strong preference for Men's Street Footwear, with 134,252 units sold. In contrast, the Midwest and Southeast regions show lower sales across most categories, indicating less pronounced product preferences. Overall, Men's Street Footwear appears to be the most popular product across regions, especially in the West and Northeast.

**Q:** Are certain retailers more popular in specific cities or regions? Do certain regions or retailers have larger purchases on average?<br />
**A:** Certain retailers are indeed more popular in specific regions. Sports Direct is particularly dominant in the South, with 231,695 units sold, making it the most popular retailer in that region. Foot Locker leads in the Northeast, with 179,087 units sold, and also performs well in the West with 98,434 units sold. West Gear is notably strong in the West, selling 340,749 units, far surpassing other regions. Conversely, Amazon and Kohl's have more evenly distributed sales but don't dominate any specific region. This data highlights regional preferences for certain retailers, with Sports Direct, Foot Locker, and West Gear standing out in their respective areas. 

### 🎯Sales Optimization
    
**Q:** Are there any underperforming regions or products that could benefit from targeted marketing or discounts?<br />
**A:** the Midwest and Southeast regions appear to be underperforming across several product categories, with consistently lower units sold compared to other regions. For example, the Midwest shows lower sales in Men's Apparel and Women's Athletic Footwear, while the Southeast underperforms in categories like Women's Street Footwear. In terms of products, Women's Athletic Footwear and Women's Street Footwear generally have lower sales across most regions, particularly in the Midwest and Southeast. These regions and products could benefit from targeted marketing campaigns or discounts to boost sales. Focusing on promotions in these areas could help drive more engagement and improve overall profitability.

# 📌 Key General Findings
🔍 **Sales Performance Analysis:** The West region leads in total sales, significantly outperforming other regions, while the Midwest lags behind, indicating a need for targeted strategies to address regional disparities. Charleston and New York emerge as top-performing cities, with strong sales driven by urban demand. Seasonality plays a crucial role, with sales spiking in April and December, suggesting a need for strategic planning around these periods.

👟 **Product Performance:** Men's Street Footwear dominates in sales, followed by Women's Apparel, both showing strong consumer preferences. Despite higher average sales per unit for Women's Apparel, Women's Athletic Footwear lags behind in total sales, highlighting an opportunity for targeted marketing or product enhancements.

🌍 **Regional Insights:** The West and Northeast regions show strong preferences for Men's Street Footwear, while the Midwest and Southeast underperform across several categories. These regions, particularly in Women's Footwear categories, could benefit from targeted promotions to boost sales.

📊 **Retailer Popularity:** West Gear leads in both sales and profitability across regions, with Foot Locker and Amazon also performing well. Retailer performance varies by region, with Sports Direct dominating the South and Foot Locker leading in the Northeast.

💡 **Optimization Opportunities:** Underperforming regions like the Midwest and Southeast, particularly in categories like Women's Athletic and Street Footwear, could see improved sales with targeted marketing efforts. Additionally, enhancing online sales strategies could further boost overall profitability, given the strong performance of online sales methods.
