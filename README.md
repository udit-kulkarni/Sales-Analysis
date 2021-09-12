#Sales for the year 2017
SELECT SUM(sales.transactions.sales_amount) FROM sales.transactions INNER JOIN sales.date ON sales.transactions.order_date=sales.date.date where sales.date.year=2017;
![2017](https://user-images.githubusercontent.com/84023687/132974471-8d1168ec-dd47-465d-8e5a-1edcae949256.PNG)

