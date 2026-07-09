Pizza Place Sales Analysis

Overview
A year's worth of sales data (2015) from a fictitious pizza place, analyzed to uncover revenue trends, peak sales hours, bestselling pizzas, and menu performance. The raw data was split across four CSV files — orders, order details, pizzas, and pizza types — which were joined into a single data frame before analysis.

Files in this repo
Faith Chepkemoi Task3.ipynb — full analysis notebook (code + outputs)
Pizza_Place_Sales_Summary.md — written summary of findings

Dataset
orders.csv — order ID, date, and time
order_details.csv — order ID, pizza ID, and quantity ordered
pizzas.csv — pizza ID, pizza type, size, and price
pizza_types.csv — pizza type ID, name, category, and ingredients

Tools used
Python
pandas
matplotlib
Jupyter Notebook

Analysis questions answered
Total revenue/sales
Total quantity sold
Total orders
Number of pizza types sold
Average price of pizzas
Peak hours of sales
Sales by day of week
Top 5 bestselling pizzas
Sales by month and seasonal trends
Underperforming pizza types


Key findings
Total revenue: $817,860.05 across 21,350 orders and 49,574 pizzas sold
Average order value: $38.31 (average of 2.3 pizzas per order)
Peak sales hours: 12–1pm (lunch) and 5–7pm (dinner), with a lull in the mid-afternoon
Busiest day: Friday ($136,073.90); slowest day: Sunday ($99,203.50)
Bestselling pizza (by quantity): The Classic Deluxe Pizza (2,453 units)
Top earner (by revenue): The Thai Chicken Pizza ($43,434.25)
Weakest performer: The Brie Carre Pizza (490 units, $11,588.50) — a clear candidate for a menu review
Seasonality: Revenue stays fairly stable month to month ($64k–$73k), with no strong seasonal trend; July is the strongest month


How to run
Clone this repo
bash   git clone https://github.com/your-username/pizza-place-sales-analysis.git
Install dependencies
bash   pip install pandas matplotlib
Open Faith Chepkemoi Task3.ipynb in Jupyter Notebook or JupyterLab and run all cells (Kernel → Restart Kernel and Run All Cells)
