
# Pizza Sales Dashboard

### Dashboard Link : https://svvvindore-my.sharepoint.com/:u:/g/personal/20100btit07703_svvvindore_onmicrosoft_com/EX87DRXM1lFOjzNyzFTE3ycBKXl8Ny8tw5E9O14xwKdr5A?e=MBt3bC

### Problem Statement for Pizza Sales Dashboard

This dashboard provides a comprehensive overview of the pizza chain's performance, helping the management team understand key aspects of their business. It focuses on critical metrics such as total revenue, average order value, total pizzas sold, total orders, and average pizzas per order. These metrics are essential for identifying areas of success and opportunities for improvement.

Through the analysis of daily and monthly trends in total orders, the dashboard reveals patterns in customer demand, enabling the chain to optimize staffing and inventory. By categorizing sales by pizza type and size, the dashboard highlights which categories are most popular, guiding marketing and product development efforts.

Additionally, the dashboard identifies the top and bottom 5 pizzas by revenue and order quantity, providing insights into customer preferences and potential areas for menu adjustments. This information is crucial for tailoring marketing strategies and improving customer satisfaction.

In summary, this dashboard is an invaluable tool for the pizza chain to enhance its operational efficiency, product offerings, and overall customer experience.


### Steps Followed for Pizza Sales Dashboard

#### Step 1: Data Cleaning, Modeling, and Calculations in SQL
1. **Data Cleaning:** Executed SQL queries to clean the data, addressing missing values, correcting inconsistencies, and standardizing formats.
2. **Data Modeling:** Structured the data to facilitate analysis.
3. **KPI Calculations:**
   - **Total Revenue:** Calculated as the sum of revenue from all orders.
   - **Average Order Value:** Derived by dividing Total Revenue by Total Orders.
   - **Total Pizzas Sold:** Counted the total number of pizzas sold.
   - **Total Orders:** Counted the total number of orders.
   - **Average Pizzas per Order:** Calculated by dividing Total Pizzas Sold by Total Orders.
4. **Chart Requirements Calculations:**
   - **Daily and Monthly Trends:** Prepared data to visualize trends in total orders.
   - **Sales Distribution:** Organized data to show the percentage of sales by pizza category and pizza size.
   - **Top and Bottom Performers:** Identified the top 5 and bottom 5 pizzas by revenue and order quantity.

#### Step 2: Importing Data into Power BI
1. **Data Import:** Imported the cleaned and modeled data from the SQL database into Power BI.

#### Step 3: Power Query Editor
1. **Data Profiling:** Enabled "Column Distribution," "Column Quality," and "Column Profile" to evaluate data quality and distribution.
2. **Complete Data Profiling:** Selected "Column profiling based on entire dataset" for thorough analysis.

#### Step 4: Creating Visualizations in Power BI
1. **Daily and Monthly Trends:**
   - **Line Charts:** Created line charts to depict daily and monthly trends in total orders.
   
2. **Sales Breakdown:**
   - **Pie Charts and Bar Charts:** Displayed the percentage of sales by pizza category and size, illustrating the distribution of sales.

3. **Top and Bottom Performers:**
   - **Bar Charts:** Showcased the top 5 pizzas by revenue and quantity of total orders, as well as the bottom 5 pizzas by the same metrics.

4. **Slicers and Filters:**
   - **Visual Filters:** Added slicers for various categories like pizza type and size, enabling interactive data filtering and insights.

#### Step 5: Dashboard Design and Presentation
1. **Themes and Formatting:** Applied consistent themes and formatting for visual appeal.
2. **Text Boxes and Branding:** Included text boxes for titles, labels, and company branding, such as logos and taglines.
3. **Shapes and Images:** Incorporated shapes for highlighting sections and added images for enhanced visual appeal.

#### Step 6: Final Review and Publishing
1. **Review:** Conducted a thorough review to ensure the dashboard's accuracy and completeness.
2. **Publish:** Published the dashboard to Power BI Service for stakeholder access and collaboration. 
 
 
![Publish_Message](https://github.com/user-attachments/assets/4ad1b2fe-4bc6-405a-88fc-7954525073a5)


# Snapshot of Dashboard (Power BI Service)


![dashboard_snapo](https://github.com/user-attachments/assets/b0642a13-ac21-4ee8-adf6-6af3b89441ec)

![dashboard_snapo](https://github.com/user-attachments/assets/d9d8eec9-fd2b-4e22-8cb0-6ff4a5bb0e40)


# Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/user-attachments/assets/905b4caf-c203-4c03-9fcc-0f304798304f)

![Dashboard_upload](https://github.com/user-attachments/assets/f4a7d32a-08e2-4efd-9201-d6cad8f0a750)




### Pizza Sales Dashboard Insights

A single-page report was created using Power BI Desktop and published to Power BI Service, revealing the following insights:

#### 1. Busiest Days and Times
- **Days:** The highest number of orders occurs on weekends, especially on Friday and Saturday evenings. This pattern suggests that customers prefer to order pizzas during weekends, possibly for social gatherings or family dinners.
- **Monthly:** Peak order periods are observed in July and January. These months likely coincide with holidays, vacations, and special events, driving up demand for pizzas.

#### 2. Sales Performance
- **Category:** The Classic category is the top performer, contributing the most to total sales and orders. This indicates a strong customer preference for traditional pizza varieties.
- **Size:** Large-sized pizzas generate the highest sales, suggesting that customers favor larger portions, possibly for group settings or to maximize value.

#### 3. Best Sellers
- **Revenue:** The Thai Chicken pizza generates the highest revenue, indicating its popularity and potential profitability.
- **Quantity:** The Classic Deluxe pizza leads in total quantities sold, highlighting its widespread appeal among customers.
- **Total Orders:** The Classic Deluxe pizza also ranks highest in total orders, confirming its status as a customer favorite.

#### 4. Worst Sellers
- **Revenue:** The Brie Carre pizza contributes the least to revenue, suggesting limited customer interest or niche appeal.
- **Quantity:** Similarly, the Brie Carre pizza has the lowest quantity sold, indicating low demand.
- **Total Orders:** The Brie Carre pizza also has the fewest total orders, reflecting its lower popularity compared to other menu items.

These insights can help the pizza chain optimize its menu, pricing, and marketing strategies, as well as improve inventory management and customer satisfaction.
