# pizza_sales_sql_queries
Basic:

   Retrieve the total number of orders placed.
   Calculate the total revenue generated from pizza sales.
   Identify the highest-priced pizza.
   Identify the most common pizza size ordered.
   List the top 5 most ordered pizza types along with their quantities.


Intermediate:

   Join the necessary tables to find the total quantity of each pizza category ordered.
   Determine the distribution of orders by hour of the day.
   Join relevant tables to find the category-wise distribution of pizzas.
   Group the orders by date and calculate the average number of pizzas ordered per day.
   Determine the top 3 most ordered pizza types based on revenue.

Advanced:

   Calculate the percentage contribution of each pizza type to total revenue.
   Analyze the cumulative revenue generated over time.
   Determine the top 3 most ordered pizza types based on revenue for each pizza category.

dataset comprises four main tables:

1) orders – includes order_id, date, time
2) order_details – links orders to pizzas with quantity
3) pizzas – defines pizza_id, size, price, pizza_type_id
4) pizza_types – maps types to name, category

   It starts with essential KPIs—total orders, total revenue, highest-priced pizza, most common size, and top types by order count.
   Then it delves deeper to reveal insights by category, hour-of-day patterns, daily averages, revenue-driven rankings, and each category’s share of total revenue.
   Advanced window functions are used to calculate cumulative revenue over time and identify the top performers within categories.
   This layered approach—from basic counts and sums to sophisticated time-series and partitioned rankings—mirrors best practices in data analysis, structuring insights for strategic decision-making
