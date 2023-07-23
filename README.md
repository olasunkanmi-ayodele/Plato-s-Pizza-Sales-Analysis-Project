# Plato-s-Pizza-Sales-Analysis-Project

This is a fictional data that was provided by Maven Analytics. The main objective of the analysis is to help the restaurant use data to improve operations and find opportunities to drive more sales and work more efficiently.

Microsoft Excel was the only tool used for this Analysis and Visualization.

The dataset contained 4 tables in CSV format; the “Orders” table contained the date & time that all table orders were placed. The “Order Details” table contained the different pizzas served with each order in the Orders table, and their quantities. The “Pizzas” table contained the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type, and the “Pizza Types” table contained details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients.
After loading the CSV files into Microsoft Excel worksheet, I merged the orders, pizza types and pizza table to order details table using the VLOOKUP function in Excel. A total of 48625 rows and 12 columns namely date, time, pizza_id, pizza_type_id, name, size, category, ingredients, price, order_details_id, order_id, quantity. I added a new column (revenue) to ascertain the total sales. I extracted day from date in order to see a breakdown of sales/orders per day using the WEEKDAY function in Excel.

Next thing I did was to create six different pivot tables to quickly summarize and analyze the data in detail.
# Insights.
1.KPIs
There is a total number of 21,350 Orders, the total Revenue generated is $817,860, the average order value is $38.31 and the total number of pizzas sold is 49,574.
Plato Pizza has more Large(L), Medium(M) and Small(S) size pizza orders than the Xtra-large(XL) and Xtra-xtra-large(XXL) size order. Classic pizza category has high number of orders than supreme, veggie and chicken.
2. What days and times do we tend to be busiest?
In order to fully understand the days Plato pizza is the busiest I created a line chart that shows the quantity of Pizzas sold each day of the week and a column chart that shows the time in hour. This would help stakeholders to clearly see the times and days sales are most. Plato Pizza tends to be most busiest on Friday, Saturday and Thursday and always busy with high number of orders around 12 to 1pm and 5 to 6pm.

A total of 23,817 pizzas are made during peak periods with 13,189 pizzas around 12 to 1pm and 10,628 pizzas around 5 to 6pm.
3. What are our best and worst selling pizzas?
I created a Bar chart that shows the five best selling pizzas by the quantity sold and another Bar chart that shows the five worse selling pizzas by the quantity sold. This would help stakeholders to clearly understand the particular pizzas to look out for which could aid effective decision making. The top five best selling pizzas are the Classic deluxe pizza, Barbecue chicken pizza, Hawaiian pizza, Pepperoni pizza and, Thai pizza.
# Recommendations
Increase the amount of staff during peak periods and reduce them during low periods to increase efficiency and reduce costs.
Introduce Sales and Discounts during low periods.
