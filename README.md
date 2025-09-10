# 🍕Pizza Sales Analysis  | SQL · Excel · Power BI

## 📊Project Overview  
This project is an **end-to-end data analysis of pizza sales** aimed at uncovering key business insights and performance trends.  
The analysis focuses on tracking revenue, order behavior, and product performance to support data-driven decision-making.  

Key objectives of this project include:  
- Measuring overall sales performance through KPIs.  
- Identifying order patterns across time (daily, monthly, hourly).  
- Evaluating customer preferences by pizza size and category.  
- Highlighting best and worst-performing pizzas by revenue, quantity, and orders.  
- Recommending actionable strategies to improve sales and efficiency.

 ## 🗂️Preview
### 1. SQL Queries Report [ View ](https://github.com/ManishKukreja98/pizza-sales-analysis/blob/2ad8239afd73bdbf1fc479927e5cb78ae295609e/PIZZA%20SALES%20SQL%20QUERIES%20REPORT.pdf)
    
    ![Screenshot SQL report](https://github.com/ManishKukreja98/pizza-sales-analysis/blob/2ad8239afd73bdbf1fc479927e5cb78ae295609e/Assets/Screenshot%20SQL%20queries%20report.png)

### 2. Excel Dashboard [ View ](https://github.com/ManishKukreja98/pizza-sales-analysis/blob/2ad8239afd73bdbf1fc479927e5cb78ae295609e/Excel%20pizzasales%20dashboard%200complete.xlsx)

   ![Screenshot EXCEL](https://github.com/ManishKukreja98/pizza-sales-analysis/blob/2ad8239afd73bdbf1fc479927e5cb78ae295609e/Assets/Screenshot%20Excel%20dashboard.png)

### 3. PowerBI Dashboard [ View ](https://github.com/ManishKukreja98/pizza-sales-analysis/blob/2ad8239afd73bdbf1fc479927e5cb78ae295609e/pizza%20sales%20powerbi%20dashboard.pbix)

   ![Screenshot powerbi](https://github.com/ManishKukreja98/pizza-sales-analysis/blob/2ad8239afd73bdbf1fc479927e5cb78ae295609e/Assets/screenshot%20powerbi%20pizza%20sales%20dashboard.png)
   
   ![Screenshot powerbi](https://github.com/ManishKukreja98/pizza-sales-analysis/blob/2ad8239afd73bdbf1fc479927e5cb78ae295609e/Assets/screenshot%202%20powerbi%20ps%20dashboard.png)
   
## 📝Executive Summary  

The objective of this project was to analyze pizza sales data in order to measure business performance and uncover actionable insights. The analysis focused on addressing key business questions through defined problem statements, performance metrics, and visual reporting.  

### Problem Statements  
- How much total revenue did the business generate, and what was the average order value?  
- What is the total number of pizzas sold and how many orders were placed?  
- What are the trends in customer ordering behavior across days, months, and hours?  
- Which pizza categories and sizes contribute most to sales?  
- What are the best- and worst-performing pizzas in terms of revenue, orders, and quantity sold?  

### KPI Requirements  
To answer these questions, the following metrics were calculated:  
1. **Total Revenue** – The sum of the total price of all pizza orders.  
2. **Average Order Value** – The average amount spent per order, calculated by dividing the total revenue by the total number of orders.  
3. **Total Pizzas Sold** – The sum of the quantities of all pizzas sold.  
4. **Total Orders** – The total number of orders placed.  
5. **Average Pizzas Per Order** – The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.  

### Chart Requirements  
The following visualizations were created to better understand sales performance and trends:  
1. **Daily Trend for Total Orders** – Bar chart showing the daily trend of total orders over a specific time period.  
2. **Monthly/Hourly Trend for Total Orders** – Line chart illustrating the hourly trend of total orders throughout the day.  
3. **Percentage of Sales by Pizza Category** – Pie chart showing the distribution of sales across different pizza categories.  
4. **Percentage of Sales by Pizza Size** – Pie chart representing the percentage of sales attributed to different pizza sizes.  
5. **Total Pizzas Sold by Pizza Category** – Funnel chart displaying the total number of pizzas sold for each category.  
6. **Top 5 Best Sellers** – Bar chart highlighting the top 5 pizzas by revenue, quantity, and orders.  
7. **Bottom 5 Worst Sellers** – Bar chart showcasing the bottom 5 pizzas by revenue, quantity, and orders.  

### Approach  
- **SQL (MySQL):** Queries were written to extract, clean, and aggregate data, ensuring accuracy in KPI calculations.  
- **Excel:** Pivot tables and charts were used to validate SQL outputs and build preliminary dashboards.  
- **Power BI:** An interactive dashboard was developed with DAX measures and advanced visuals to present KPIs and trends in a clear format.  

### Impact  
This end-to-end analysis enables the business to:  
- Track overall sales performance with reliable KPIs.  
- Identify peak demand periods for better staffing and resource planning.  
- Understand customer preferences by category and size.  
- Recognize best sellers to maximize promotion strategies.  
- Detect underperforming pizzas to reassess product offerings.

 ## 🛠️Methodology  

The analysis was carried out using a combination of SQL, Excel, and Power BI. Each tool played a specific role in ensuring data accuracy, validation, and interactive reporting.  
  
### SQL (MySQL)  
- Queried the raw pizza sales dataset to calculate KPIs and trends.  
- Applied **aggregate functions** (e.g., SUM, COUNT) to compute revenue, orders, and sales volume.  
- Used **date functions** (e.g., STR_TO_DATE, MONTHNAME) to handle and format time-based analysis.  
- Implemented **GROUP BY** and filtering/sorting operations (ORDER BY, ORDER BY FIELD, OR) to structure and organize results.  


### Excel  
- Imported SQL outputs for cross-checking and validation.  
- Built **pivot tables** to quickly summarize revenue, orders, and sales volume.  
- Applied **calculated fields** for metrics such as Average Order Value.  
- Designed preliminary dashboards with pivot charts and slicers to ensure consistency before moving to Power BI.  

### Power BI  
- Loaded cleaned and validated data for final dashboard creation.  
- Created **DAX measures** for dynamic KPIs like revenue, order value, and pizzas per order.  
- Used **slicers and filters** to enable interactive exploration of sales data.  
- Built **custom visuals** (bar, line, pie, funnel charts) to meet business requirements.  
- Designed a structured dashboard layout for easy navigation and decision-making.  

## 📈Insights  

The analysis of pizza sales data revealed the following key insights:  

### Ordering Patterns  
- **Busiest Days:** Orders peak on **Thursday** and **Friday**.  
- **Busiest Hours:** Maximum orders occur between **12 PM – 2 PM** and again from **5 PM – 8 PM**.  
- **Monthly Trends:** Order volumes are highest in **January** and **July**.  

### Sales Performance  
- **By Category:** The **Classic** category contributes the highest share of sales and orders.  
- **By Size:** **Large** pizzas account for the maximum sales contribution.  

### Best Sellers  
- **Highest Revenue:** *Thai Chicken Pizza*  
- **Highest Quantity Sold:** *Classic Deluxe Pizza*  
- **Highest Orders Placed:** *Classic Deluxe Pizza*  

### Worst Sellers  
- *Brie Carre Pizza* records the **lowest revenue**, **lowest quantity sold**, and **lowest total orders**.  

## 🎯Recommendations  

Based on the insights from the sales data, here are key recommendations to improve overall business performance:  

1. **Optimize Peak Demand Periods (Thursdays, Fridays, 12–2 PM, 5–8 PM, January & July):**  
   - Avoid offering heavy discounts during these high-demand windows.  
   - Instead, focus on **operational efficiency**: ensure sufficient staff, ingredients, and delivery resources to handle the rush.  
   - Introduce **bundle offers or upselling strategies** (e.g., combo meals, add-on sides/drinks) to maximize average order value without hurting margins.  

2. **Boost Off-Peak Demand (Early weekdays, afternoon lulls, slower months):**  
   - Launch **targeted promotions and discounts** during low-demand times to stimulate sales.  
   - Examples: “Happy Hour Deals (3–5 PM),” “Monday Specials,” or monthly campaigns in historically weaker months.  
   - Use loyalty rewards or limited-time offers to attract repeat customers during these quieter periods.  

3. **Product Mix Strategy:**  
   - Since **Classic category** and **Large pizzas** dominate sales, maintain strong inventory and continue promoting these as core offerings.  
   - Highlight **best sellers** like Thai Chicken Pizza and Classic Deluxe Pizza in marketing campaigns, menu placements, and featured promotions.  

4. **Address Poor Performers:**  
   - The **Brie Carre Pizza** (lowest in revenue, orders, and quantity) should be reviewed. Options include:  
     - Redesigning the recipe to better match customer preferences.  
     - Repackaging it as part of a combo deal.  
     - Phasing it out if it consistently underperforms.  

5. **Seasonal and Event-Based Campaigns:**  
   - Leverage high-demand months (January & July) with **festival/event tie-ins** to further capitalize on natural sales peaks.  
   - Offer limited-time flavors or promotions during festivals/holidays to attract new customers.  

By implementing these strategies, the business can **increase revenue during strong demand periods, lift sales during weak periods, and refine the product mix** for long-term profitability.  
