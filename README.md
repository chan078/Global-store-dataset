# Global-store-dataset 

## Description
I used a global store dataset from kaggle and imported into Microsoft PowerBI query editor containing three tables namely orders, returns and people. The orders table consisted of columns such as Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Postal Code, City, State, Country, Region, Market, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, Shipping Cost and Order Priority. Returns table consisted of columns such as returned, orderID and Region. People table consisted of Person and Region columns. Then created four dimension tables namely customer, product, shipmode and order from the orders table. After this, linked the orders table to these dimension tables using foreign and surrogate keys, also linked returns table to the order dimension table and people table to the customer dimension table. Also did some data cleaning and data transformation like removing columns, renaming columns, promoting headers, changing the type, added custom column, added index, removed duplicates and so on. Lastly, created many measures and built visualisations using cards for kpi's, line and bar graphs for sales, profits and order trends, used table visuals for top and bottom performers and many more.

## Dashboard

![Dashboard](./img/dashboard.png)
