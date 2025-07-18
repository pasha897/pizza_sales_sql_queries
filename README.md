# pizza_sales_sql_queries
Basic:

1) Retrieve the total number of orders placed.
2) Calculate the total revenue generated from pizza sales.
3) Identify the highest-priced pizza.
4) Identify the most common pizza size ordered.
5) List the top 5 most ordered pizza types along with their quantities.


Intermediate:

1) Join the necessary tables to find the total quantity of each pizza category ordered.
2) Determine the distribution of orders by hour of the day.
3) Join relevant tables to find the category-wise distribution of pizzas.
4) Group the orders by date and calculate the average number of pizzas ordered per day.
5) Determine the top 3 most ordered pizza types based on revenue.

Advanced:

1) Calculate the percentage contribution of each pizza type to total revenue.
2) Analyze the cumulative revenue generated over time.
3) Determine the top 3 most ordered pizza types based on revenue for each pizza category.

dataset comprises four main tables:

1) orders – includes order_id, date, time
2) order_details – links orders to pizzas with quantity
3) pizzas – defines pizza_id, size, price, pizza_type_id
4) pizza_types – maps types to name, category

   It starts with essential KPIs—total orders, total revenue, highest-priced pizza, most common size, and top types by order count.
   Then it delves deeper to reveal insights by category, hour-of-day patterns, daily averages, revenue-driven rankings, and each category’s share of total revenue.
   Advanced window functions are used to calculate cumulative revenue over time and identify the top performers within categories.
   This layered approach—from basic counts and sums to sophisticated time-series and partitioned rankings—mirrors best practices in data analysis, structuring insights for strategic decision-making
