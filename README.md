# Projects
All the hands on projects ( Data Science , Data Analysis and SQL ) 
This analysis explores a Superstore dataset, revealing insights into sales, profit, quantity, and discount across different regions and product categories.

### Data Overview

The dataset contains 9994 rows and 21 columns. There are no missing values. Key numerical columns include:

* **Sales:** Ranging from \$0.44 to \$22638.48, with an average of \$229.86.
* **Quantity:** Ranging from 1 to 14, with an average of 3.79.
* **Discount:** Ranging from 0.00 to 0.80, with an average of 0.16.
* **Profit:** Ranging from -\$6599.98 to \$8399.98, with an average of \$28.66. The presence of negative profit and high maximum profit indicates significant outliers.

### Key Findings

#### 1. Outliers in Profit and Sales
The wide range in 'Profit' (from -\\$6599.98 to \\$8399.98) and 'Sales' (from \\$0.44 to \\$22638.48) suggests the presence of outliers. Further investigation into these extreme values could reveal important business insights, such as highly profitable products or significant loss-making transactions.

#### 2. Regional Distribution
The sales are distributed across four main regions:
* **West:** 32.0% (3203 orders)
* **East:** 28.5% (2848 orders)
* **Central:** 23.2% (2323 orders)
* **South:** 16.2% (1620 orders)

The West and East regions account for the largest portions of the sales, indicating stronger market presence or higher demand in these areas.

#### 3. Product Categories
The dataset includes three primary product categories:
* **Office Supplies:** 6026 orders
* **Furniture:** 2121 orders
* **Technology:** 1847 orders

Office Supplies represent the largest category by count, suggesting it's the most frequently purchased type of product.

#### 4. Total Discount and Profit
The total discount given across all transactions is \\$1561.09, while the total profit generated is \\$286397.02. This indicates that despite some transactions incurring losses (as seen in the minimum profit), the overall business is profitable.

#### 5. Sales Trends Over Time
An initial look at the daily sales trend shows a significant boost in sales around 2014, while 2018 appears to be a slower year. A more detailed time-series analysis could pinpoint specific periods of high and low performance and identify contributing factors.

#### 6. Relationships Between Key Metrics

* **Sales vs. Discount:** The average sales are significantly higher than the average discount, which is expected.
* **Sales vs. Quantity:** Average sales are much higher than average quantity, as sales represent the total revenue from multiple units.
* **Quantity vs. Profit:** There is a notable difference between average quantity and average profit. High quantity does not always translate to high profit, especially if discounts are substantial.
* **Discount vs. Profit:** A clear inverse relationship is observed: as discount increases, profit tends to decrease. This highlights the impact of discounting strategies on profitability.

### Visualizations

The analysis includes various visualizations to illustrate these findings:

* **Pie Chart of Region Distribution:** Shows the percentage of sales originating from each region.
* **Count Plot of Region:** Displays the number of orders per region.
* **Count Plot of Category:** Shows the frequency of orders across different product categories.
* **Bar Charts:** Comparing average values of Sales vs. Discount, Sales vs. Quantity, Quantity vs. Profit, Quantity vs. Discount, Sales vs. Profit, and Discount vs. Profit. These plots visually confirm the relationships and disparities between these metrics.
* **Scatter Plot of Sales vs. Profit:** Illustrates the correlation between sales and profit, highlighting the spread and potential outliers.
* **Daily Sales Trend:** A line plot showing total sales over time, revealing annual patterns.

### Conclusion

The Superstore dataset provides a rich basis for understanding business performance. While overall profitability is positive, the presence of significant negative profits indicates areas for improvement, potentially related to discounting strategies or specific product lines. The regional and categorical breakdowns offer insights into market strengths and product popularity. Further in-depth analysis of outliers, time-series patterns, and the impact of discounts on specific products or regions could lead to actionable business strategies.

### Future Work

* **Outlier Analysis:** Investigate the specific transactions with high discounts or negative profits to understand the underlying causes.
* **Profitability by Sub-Category:** Analyze profit margins at a more granular product level.
* **Customer Segmentation:** Group customers based on their purchasing behavior to tailor marketing strategies.
* **Shipping Mode Impact:** Examine the influence of different shipping modes on delivery times and customer satisfaction.
* **Geospatial Analysis:** Visualize sales and profit data on a map to identify high-performing and underperforming cities/states.
