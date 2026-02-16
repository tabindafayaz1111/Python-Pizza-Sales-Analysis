# Pizza Sales Analysis

## Overview
This project undertakes a comprehensive analysis of pizza sales data to derive actionable business insights. The analysis computes key performance indicators (KPIs) including:
- **Total Revenue**: the aggregate sales value generated.
- **Total Pizzas Sold**: the overall quantity of pizzas sold during the period.
- **Total Orders**: the number of distinct transactions processed.
- **Average Order Value**: the mean revenue per order, indicating customer spending behavior.
- **Average Pizzas per Order**: the average number of pizzas purchased in each transaction.
- **Ingredient Usage Counts**: detailed tallies of specific ingredients such as garlic count, tomato count, etc., reflecting ingredient popularity and inventory requirements.

The analytical workflow incorporates multiple visualizations to elucidate sales patterns:
1. **Bar graph of Total Orders by Day of Week**: displays weekly order distribution to identify peak ordering days.
2. **Bar graph of Total Revenue by Day of Week**: shows revenue fluctuations across weekdays.
3. **Bar graph of Total Orders by Hour of Day (24‑hour format)**: highlights intraday order peaks for operational planning.
4. **Bar graph of Total Revenue by Hour of Day**: reveals hourly revenue performance for pricing or promotion strategies.
5. **Filled area graph of Total Orders by Month**: illustrates monthly order trends and seasonality.
6. **Pie chart of Percentage of Sales by Pizza Category**: depicts the proportional contribution of each pizza category to overall sales.
7. **Pivot table for Pizza Category with sales percentage**: summarizes category‑wise sales distribution in tabular form.
8. **Heatmap of Percentage of Sales by Pizza Category and Sales**: visualizes the intensity of sales performance across categories.
9. **Bar graph of Top & Bottom Pizzas Sold by Pizza Category**: identifies best‑ and worst‑selling pizzas within each category.
10. **Bar graph of Top & Bottom Pizzas by Revenue**: highlights high‑ and low‑revenue generating pizzas for marketing focus.

The insights derived from these analyses enable data‑driven decisions regarding inventory management, promotional targeting, and menu optimization.

## Data Description
- **Dataset**: A CSV file named 'pizza_sales.csv' containing transactional data  with fields:'pizza_id', 'order_id', 'pizza_name_id', 'quantity', 'order_date' 'order_time', 'unit_price', 'total_price', 'pizza_size', 'pizza_category', 'pizza_ingredients', 'pizza_name'.
- **Key metrics**: total revenue, total pizzas sold, total orders, average order value, average pizzas per order and ingredient usage counts(e.g., garlic, tomato).

## Analysis Steps
1. Data cleaning & preprocessing.
2. Exploratory data analysis (EDA).
3. Visualization of sales trends (e.g., the bar chart you showed).
4. Insights & recommendations.

## Tools Used
- Python (pandas, numpy)
- Jupyter Notebook / Python script
- Visualization: matplotlib / seaborn

## Results
### Key Performance Indicators (KPIs)
- **Total Revenue**: $817860.0499999999
- **Total Pizzas Sold**: 49574
- **Total Orders**: 21350
- **Average Order Value**: $38.30726229508196
- **Average Pizzas per Order**: 2.321967213114754
- **Ingredient Usage**:
  - Garlic : 27422
  - Tomatoes : 26601
  - Red Onions : 19547
  - Red Peppers : 16284
  - Mozzarella Cheese : 10333
  - Pepperoni : 10300
  - Spinach : 10012
  - Mushrooms :  9624

### Sales Trends
- **Total Orders by Day of Week**: Thursday and Fridays see the highest number of orders.
- **Total Revenue by Day of Week**: Revenue peaks on Thursday and Fridays.
- **Total Orders by Hour of Day**: Peak times are lunch (12-1 PM) and evening (5-6 PM).
- **Total Revenue by Hour of Day**: Revenue mirrors order patterns.
- **Total Orders by Month**: Orders ranges between ~ 1,600 and ~1,900 per month.

### Pizza Category Analysis
- **Percentage of Sales by Pizza Category**: Classic pizzas dominate sales.

### Top & Bottom Pizzas
- **Top/Bottom Pizzas Sold**: "The Classical Deluxe Pizza" is a top seller and "The Brie Carre Pizza" is the least selling pizza.
- **Top/Bottom Pizzas by Revenue**: "The Thai Chicken Pizza" generates the highest revenue and "The Brie Carre Pizza" generates the least revenue.

### Recommendations
- Focus promotions on peak days/times.
- Highlight popular pizzas like "The Classical Deluxe Pizza","The Thai Chicken Pizza".
- Review less popular pizzas for adjustments.

### Conclusion
This analysis provides insights into sales trends and pizza popularity to help improve sales and optimize menu offerings.

## How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the notebook/script: `python pizza sales analysis.ipynb`.

## Contributors
- Tabinda Fayaz Lone
