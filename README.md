# Adidas Sales Report

### Dashboard Link : https://springboardaccess-my.sharepoint.com/personal/aehnd_sbuser_onmicrosoft_com/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Faehnd%5Fsbuser%5Fonmicrosoft%5Fcom%2FDocuments%2FAdidas%20Sales%20Report%2Epbix&parent=%2Fpersonal%2Faehnd%5Fsbuser%5Fonmicrosoft%5Fcom%2FDocuments

## Problem Statement

This dashboard enables Adidas to understand its sales performance across the United States. It helps the company identify top-performing regions, states, and products, while also revealing areas for improvement. Through detailed metrics such as Total Sales ($899.9M), Total Profit ($332.13M), and Total Quantity Sold (2M units), the dashboard provides a comprehensive view of sales trends. It also highlights the performance of different sales channels, with in-store sales contributing 39.63%, online 32.85%, and outlet sales 27.52%.

The analysis reveals key opportunities for growth, such as targeting underperforming regions or optimizing product offerings based on profitability. For instance, Men’s Street Footwear leads in total sales, while other categories show potential for increased focus. By using this dashboard, Adidas can refine its sales strategies, optimize inventory management, and focus efforts on regions and products that maximize revenue and profitability.

### Steps followed

- Step 1: Loaded data into Power BI Desktop, with the dataset being an Excel file containing Adidas' sales data for the United States.

- Step 2: Opened Power Query Editor, and under the view tab, enabled "Column Distribution," "Column Quality," and "Column Profile" options to ensure a thorough assessment of data quality.

- Step 3: Adjusted the settings to "column profiling based on entire dataset" to capture accurate data patterns and identify any inconsistencies, as the default setting profiles only the first 1000 rows.

- Step 4: Reviewed the data for missing or erroneous values, addressing these using Power Query's transformation tools. For example, any columns with empty values were cleaned to ensure accurate analysis. 

        Although by default, blank values were ignored in calculations, further steps were taken to verify data integrity.

- Step 5: Transformed the data by renaming columns for clarity, changing data types as needed, and adding calculated columns. This ensured the data was ready for meaningful visualizations and analysis.

- Step 6: Selected a consistent theme in the report view under the View tab to maintain a professional and cohesive look across all visuals and charts.

- Step 7: Added a title text box "Adidas Sales Report" using the Insert tab, applied bold formatting, and adjusted alignment to make the report title stand out prominently.

- Step 8: Created visual slicers for "State," "Region," "Month," and "Year" to allow users to filter data dynamically. This enabled stakeholders to drill down into specific timeframes and regions for detailed analysis.

- Step 9: Added card visuals to display key metrics:

    (a) Total Sales ($899.9M)

    (b) Total Profit ($332.13M)

    (c) Total Quantity Sold (2M units)
    
    (d) Total Number of States (9,648)
    
    (e)Total Number of Cities (9,648)
- Step 10: Created a bar chart for "Total Sales by State" to enable a quick comparison between states like New York ($64M) and California ($60M), highlighting top-performing areas.

- Step 11: Used a line and clustered column chart to present "Total Sales and Operating Profit by Product," providing insights into which products generated the most revenue and profit, such as Men’s Street Footwear.

- Step 12: Added a pie chart to show "Total Sales by Region," offering a clear view of how each region contributed to overall sales, with the West region leading at $269.93M.

- Step 13: Used a donut chart to break down "Total Sales by Sales Method," displaying the distribution among In-store (39.63%), Online (32.85%), and Outlet (27.52%) sales channels.

- Step 14: Inserted a bar chart to highlight the "Top 5 Cities by Total Sales," featuring key markets like Charleston, New York, and San Francisco.

- Step 15: Customized all visuals by adding data labels, adjusting fonts, colors, and borders for improved readability, and ensuring consistency with the selected theme.

- Step 16: Included a map visualization to represent sales distribution across the United States, providing a geographic overview of Adidas' market presence.

- Step 17: Wrote DAX expressions to create calculated measures, such as:

        Total Sales = SUM(Sales Data[Total Sales])

        Total Profit = SUM(Sales Data[Operating Profit]) These measures helped in accurately displaying key figures in card visuals.
- Step 18: Set up a filter pane to enhance data exploration, allowing users to filter data by products, regions, and sales methods for a more customized view.

- Step 19: Added images and Adidas branding elements in the report view for a professional finish, using the Insert tab to place the logo and other visuals strategically.

- Step 20: Tested the interactivity of the dashboard, applying different slicers and filters to ensure smooth navigation and an optimal user experience.

- Step 21: Published the report to Power BI Service, enabling easy access for stakeholders via a web link, eliminating the need for any file downloads and making it accessible on any device.

# Snapshot of Dashboard (Power BI Service)
![Dashboard_upload](https://github.com/user-attachments/assets/6fd28c9c-2a5c-443e-ae39-31e004a05090)

# Insights
A single-page report was created in Power BI Desktop and published to Power BI Service.

The following inferences can be drawn from the dashboard:

### [1] Total Sales and Profit

    (a) Total Sales: $899.9M

    (b) Total Profit: $332.13M

    (c) Total Quantity Sold: 2M units

The dashboard revealed that Adidas achieved a substantial total sales figure of $899.9M, generating a profit of $332.13M across its product lines. The data indicates that a strong sales volume of 2 million units contributed significantly to this performance.

### [2] Top Performing States
    Top State by Sales: New York ($64M)
    Other High Performers:
    California: $60M
    Florida: $59M
    Texas: $46M

New York led in total sales among the states, followed closely by California and Florida. This suggests that Adidas should maintain a strong presence in these states, while potentially exploring ways to enhance market penetration in states like Texas.

### [3] Sales by Region
West Region: $269.93M (30% of total sales)
Northeast Region: $186.32M (20.7%)
South Region: $163.17M (18.13%)
Midwest Region: $144.66M (16.08%)
Southeast Region: $135.8M (15.09%)
The West region led sales, contributing approximately 30% to Adidas' overall revenue. This suggests that strategies focused on the West region could further boost sales, while the lower-performing regions may benefit from targeted marketing efforts.

[4] Sales by Product
    Top Product Category: Men's Street Footwear (0.21bn in total sales)
    
    Other Key Products:

        (a) Women's Apparel: 0.18bn
        (b) Men's Athletic Footwear: 0.15bn
Men’s Street Footwear was the top-selling category, indicating strong demand for this product line. It may be beneficial for Adidas to continue expanding its range in this category, while exploring growth opportunities for other products like Women’s Apparel and Men's Athletic Footwear.

### [5] Sales Channels
    1.1) In-Store Sales: 39.63% of total sales
    1.2) Online Sales: 32.85%
    1.3) Outlet Sales: 27.52%
The data showed that in-store sales remained the dominant channel, followed by online sales. This highlights the importance of maintaining a robust physical presence while continuing to invest in e-commerce to capture a growing segment of online shoppers.

### [6] Top 5 Cities by Sales
    Top City: Charleston ($30.55M)

Other Key Markets:

    New York: $30.5M
    San Francisco: $29.8M
    Miami: $31.6M
    Portland: $34.5M

Charleston and New York emerged as top-performing cities, indicating strong market engagement. These insights can guide Adidas' decisions about where to focus its marketing and promotional activities.

### [7] Profitability Insights
The most profitable product category was Men's Street Footwear, with a high margin relative to other products.

Women’s Apparel also contributed significantly to overall profitability, suggesting that expanding this line could further increase profit margins.

### [8] Interactive Filters Impact
The use of interactive filters, such as the ability to drill down by state, product category, or year, allows stakeholders to explore the data dynamically.

This interactivity enables quick adjustments to marketing and inventory strategies based on specific regional performance or seasonal sales patterns.

These insights provide a comprehensive overview of Adidas' sales performance across various regions, product lines, and channels, offering actionable recommendations for optimizing marketing strategies, inventory management, and resource allocation to maximize profitability.
